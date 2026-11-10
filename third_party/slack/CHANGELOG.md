# Changelog

All notable changes to this plugin will be documented here.

## 1.0.0 - 2026-11-10

- First stable release: Slack remote MCP server over streamable HTTP at `https://mcp.slack.com/mcp`.
- Checked against Slack's MCP documentation and the vendor plugin repository (`slackapi/slack-skills-plugin`, commit `99e027a`, v1.7.0). The endpoint answers with 401 `missing_authorization_header` when called without sign-in, as expected.
- Description now covers sending, scheduling, canvases, files, lists and reactions.
- README documents the write access, OAuth scopes, rate limits, admin approval and security notes.
- Adds the vendor's 9 skills and 5 commands, copied unchanged from `slackapi/slack-skills-plugin` at `99e027a`.
- Sign-in is handled by BoldCreate Connect. The vendor's OAuth client ID and callback port are not copied, and no client secret is stored here.
