# Supermetrics Marketing Analytics

BoldCreate plugin that connects agents to Supermetrics Marketing Analytics through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Google Ads, Facebook Ads, Google Analytics, TikTok, LinkedIn, Instagram, YouTube & 200+ sources.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Supermetrics Marketing Analytics**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Supermetrics Marketing Analytics**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install supermetrics@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "supermetrics": {
      "type": "http",
      "url": "https://mcp.supermetrics.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Supermetrics Marketing Analytics in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Supermetrics Marketing Analytics: https://supermetrics.com/

## Logo

Icon downloaded from the Claude connector directory listing for Supermetrics Marketing Analytics. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
