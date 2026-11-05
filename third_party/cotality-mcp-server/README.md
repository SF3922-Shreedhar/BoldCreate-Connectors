# Cotality

BoldCreate plugin that connects agents to Cotality through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Access Cotality’s property and location intelligence.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Cotality**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Cotality**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install cotality-mcp-server@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "cotality-mcp-server": {
      "type": "http",
      "url": "https://mcp.cotality.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Cotality in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Cotality: https://cotality.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
