# Meko

BoldCreate plugin that connects agents to Meko through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Shared context for agents that work and learn together.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Meko**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Meko**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install meko@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "meko": {
      "type": "http",
      "url": "https://mcp.mekodata.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Meko in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Meko: https://www.mekodata.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
