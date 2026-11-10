# Slack

BoldCreate plugin that connects agents to Slack through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search Slack, read channels and threads, send and schedule messages, and work with canvases, files, lists and reactions.

## Install

Install and sign in through **BoldCreate Connect**: open **Marketplace**, find **Slack**, and click **Install**.

Slack's MCP server has no dynamic client registration and accepts only a registered Slack app. BoldCreate Connect supplies that app and handles sign-in, so this plugin is supported through Connect only. The Cursor and Claude Code manifests in this repository carry no OAuth client and will not complete sign-in on their own.

## MCP

```json
{
  "mcpServers": {
    "slack": {
      "type": "http",
      "url": "https://mcp.slack.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Slack in the browser (OAuth with PKCE, user token). Tool calls run with that member's permissions. The vendor's own plugin hard-codes an OAuth client ID. This plugin does not; BoldCreate Connect supplies the client. No client secret is stored in this repository.

A Slack workspace admin must approve MCP access before members can sign in. Slack allows MCP only for apps published in the Slack Marketplace or internal apps.

## What it can do

Based on Slack's [MCP server documentation](https://docs.slack.dev/ai/slack-mcp-server/):

| Area | Operations |
| --- | --- |
| Search | Messages and files, users, public and private channels, custom emoji |
| Messages | Read channels and threads, send, schedule and draft messages, create a conversation, add and get reactions |
| Canvases | Create, update and read |
| Users | Read profiles, list channel members, list the channels a member belongs to |
| Files | Upload in two steps (`slack_get_file_upload_url`, then `slack_complete_file_upload`) |
| Lists | Create and read lists, update lists and records |

**This plugin can change data.** It can post and schedule messages, create channels and conversations, and write canvases, files and lists, all as the signed-in member. Review what the agent is about to do before approving writes.

## Skills and commands

Copied unchanged from the vendor's [Slack plugin](https://github.com/slackapi/slack-skills-plugin) (MIT, commit `99e027a`, v1.7.0).

Skills (loaded on demand): `slack-messaging`, `slack-search`, `slack-api`, `slack-docs`, `slack-cli`, `create-slack-app`, `test-slack-app`, `deploy-slack-app` and `block-kit`.

Commands:

- `/slack:summarize-channel <channel-name>`: summarize recent activity in a channel.
- `/slack:find-discussions <topic>`: find discussions about a topic across channels.
- `/slack:draft-announcement <topic>`: draft an announcement and save it as a draft.
- `/slack:standup`: generate a standup update from your recent Slack activity.
- `/slack:channel-digest <channel1, channel2, ...>`: digest of recent activity across channels.

The `slack-cli`, `create-slack-app`, `test-slack-app` and `deploy-slack-app` skills run the Slack CLI and, for deploys, the Heroku or Railway CLI on your machine.

## Permissions

Slack requests these user-token scopes:

| Purpose | Scopes |
| --- | --- |
| Search | `search:read.public`, `search:read.private`, `search:read.im`, `search:read.mpim`, `search:read.files`, `search:read.users` |
| Read messages | `channels:history`, `groups:history`, `im:history`, `mpim:history` |
| List channels | `channels:read`, `groups:read`, `im:read`, `mpim:read` |
| Write | `chat:write`, `channels:write`, `groups:write`, `im:write`, `mpim:write` |
| Canvases | `canvases:read`, `canvases:write` |
| Files | `files:read`, `files:write` |
| Lists | `lists:read`, `lists:write` |
| Reactions and emoji | `reactions:read`, `reactions:write`, `emoji:read` |
| Users | `users:read`, `users:read.email` |

See Slack's table of the scopes each tool needs in the [OAuth scopes section](https://docs.slack.dev/ai/slack-mcp-server/).

## Rate limits

Slack applies the same limits as its Web API, per tool.

| Tier | Tools |
| --- | --- |
| Tier 2 (20+ per minute) | Search users, channels and emoji; create conversation; create canvas; list user channels |
| Tier 3 (50+ per minute) | Schedule message; read channel; read thread; add and get reactions; update canvas |
| Tier 4 (100+ per minute) | Read files; read user profile; list channel members; upload file |
| Special | Search messages and files; send message (see Slack's method pages) |

## Security

- Slack warns against connecting other MCP servers at the same time without care. Other servers have their own security and stability, and an agent can pass Slack content to them.
- MCP activity appears in Slack's [audit logs](https://docs.slack.dev/reference/audit-logs-api/methods-actions-reference.md#mcp-server).
- If your app has an IP allowlist, MCP requests are subject to it.

## Docs

- Slack MCP server: https://docs.slack.dev/ai/slack-mcp-server/
- Slack skills plugin (vendor repository): https://github.com/slackapi/slack-skills-plugin

## Logo

Icon downloaded from the Claude connector directory listing for Slack. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
