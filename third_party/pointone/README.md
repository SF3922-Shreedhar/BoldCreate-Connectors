# PointOne

BoldCreate plugin that connects agents to PointOne through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Timekeeping and firm intelligence.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **PointOne**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **PointOne**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install pointone@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "pointone": {
      "type": "http",
      "url": "https://mcp.pointone.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to PointOne in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- PointOne: https://pointone.com/

## Logo

Icon downloaded from the Claude connector directory listing for PointOne. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
