# Breezing

BoldCreate plugin that connects agents to Breezing through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Crypto accounting for Xero, QuickBooks and Bexio Alternative: Categorize, reconcile and book crypto in your ledger.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Breezing**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Breezing**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install breezing@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "breezing": {
      "type": "http",
      "url": "https://mcp.breezing.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Breezing in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Breezing: https://breezing.io/

## Logo

Icon downloaded from the Claude connector directory listing for Breezing. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
