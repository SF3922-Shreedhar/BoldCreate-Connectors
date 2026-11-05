# MAIA

BoldCreate plugin that connects agents to MAIA through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

The geospatial research engine: get answers from the physical world, built as map and table datasets.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **MAIA**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **MAIA**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install maia@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "maia": {
      "type": "http",
      "url": "https://api.maia-analytics.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to MAIA in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- MAIA: https://www.maia-analytics.com/

## Logo

Icon taken from the vendor's website (MAIA). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
