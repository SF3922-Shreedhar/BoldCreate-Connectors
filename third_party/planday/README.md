# Planday

BoldCreate plugin that connects agents to Planday through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage Planday scheduling (Early access).

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Planday**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Planday**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install planday@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "planday": {
      "type": "http",
      "url": "https://public-mcp-server.prod-westeurope.planday.cloud/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Planday in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Planday: https://planday.com/

## Logo

Icon downloaded from the Claude connector directory listing for Planday. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
