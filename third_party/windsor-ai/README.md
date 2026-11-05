# Windsor.ai

BoldCreate plugin that connects agents to Windsor.ai through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Connect Meta Ads, Google Ads, TikTok Ads, LinkedIn Ads + 320 more.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Windsor.ai**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Windsor.ai**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install windsor-ai@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "windsor-ai": {
      "type": "http",
      "url": "https://mcp.windsor.ai/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Windsor.ai in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Windsor.ai: https://windsor.ai/

## Logo

Icon downloaded from the Claude connector directory listing for Windsor.ai. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
