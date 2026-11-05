# Brightcove

BoldCreate plugin that connects agents to Brightcove through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage Brightcove videos, players, live streams, analytics and more from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Brightcove**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Brightcove**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install brightcove@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "brightcove": {
      "type": "http",
      "url": "https://mcp.brightcove.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Brightcove in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Brightcove: https://www.brightcove.com/

## Logo

Icon taken from the vendor's website (Brightcove). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
