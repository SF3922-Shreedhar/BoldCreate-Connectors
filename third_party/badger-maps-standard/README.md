# Badger Maps (Standard)

BoldCreate plugin that connects agents to Badger Maps (Standard) through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Badger Maps is the #1 field sales platform.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Badger Maps (Standard)**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Badger Maps (Standard)**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install badger-maps-standard@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "badger-maps-standard": {
      "type": "http",
      "url": "https://mcp.badgermapping.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Badger Maps (Standard) in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Badger Maps (Standard): https://www.badgermapping.com/

## Logo

Icon taken from the vendor's website (Badger Maps (Standard)). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
