# Revealed

BoldCreate plugin that connects agents to Revealed through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Always-on sales intelligence for healthcare.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Revealed**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Revealed**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install revealed@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "revealed": {
      "type": "http",
      "url": "https://mcp.revealed.ai/mcp/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Revealed in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Revealed: https://www.revealed.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
