# Bonsai

BoldCreate plugin that connects agents to Bonsai through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage your CRM, client projects and invoices from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Bonsai**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Bonsai**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install bonsai@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "bonsai": {
      "type": "http",
      "url": "https://mcp.hellobonsai.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Bonsai in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Bonsai: https://hellobonsai.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
