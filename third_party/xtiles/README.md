# xTiles

BoldCreate plugin that connects agents to xTiles through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Projects that keep Claude in context.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **xTiles**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **xTiles**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install xtiles@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "xtiles": {
      "type": "http",
      "url": "https://mcp.xtiles.app/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to xTiles in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- xTiles: https://xtiles.app/

## Logo

Icon downloaded from the Claude connector directory listing for xTiles. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
