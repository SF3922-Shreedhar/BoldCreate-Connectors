# GIS Cloud

BoldCreate plugin that connects agents to GIS Cloud through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Run your entire GIS workflow in plain language: maps, data, analysis, field apps, and reports.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **GIS Cloud**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **GIS Cloud**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install giscloud@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "giscloud": {
      "type": "http",
      "url": "https://mcp.giscloud.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to GIS Cloud in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- GIS Cloud: https://www.giscloud.com/

## Logo

Icon taken from the vendor's website (GIS Cloud). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
