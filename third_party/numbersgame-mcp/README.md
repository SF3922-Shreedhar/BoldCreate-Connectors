# NumbersGame MCP

BoldCreate plugin that connects agents to NumbersGame MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Query and update QuickBooks Online and Xero from Claude — invoices, bills, reports, and reconciliations.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **NumbersGame MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **NumbersGame MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install numbersgame-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "numbersgame-mcp": {
      "type": "http",
      "url": "https://mcp.numbersgame.xyz/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to NumbersGame MCP in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- NumbersGame MCP: https://numbersgame.xyz/

## Logo

Icon downloaded from the Claude connector directory listing for NumbersGame MCP. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
