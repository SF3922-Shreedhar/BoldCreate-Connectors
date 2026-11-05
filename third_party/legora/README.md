# Legora

BoldCreate plugin that connects agents to Legora through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Ask legal questions and get grounded answers with citations.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Legora**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Legora**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install legora@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "legora": {
      "type": "http",
      "url": "https://mcp.legora.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Legora in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Legora: https://legora.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
