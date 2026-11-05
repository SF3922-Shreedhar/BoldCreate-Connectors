# Dext

BoldCreate plugin that connects agents to Dext through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

For accounting and bookkeeping firms: ask Dext about client data health, VAT and CT positions, aged debt, workflow and team capacity - across one client or your whole portfolio. Read-only.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Dext**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Dext**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install dext@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "dext": {
      "type": "http",
      "url": "https://app.dext.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Dext in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Dext: https://dext.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
