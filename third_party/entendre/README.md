# Entendre

BoldCreate plugin that connects agents to Entendre through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage accounting and reporting with agents.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Entendre**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Entendre**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install entendre@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "entendre": {
      "type": "http",
      "url": "https://mcp.entendre.finance/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Entendre in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Entendre: https://entendre.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
