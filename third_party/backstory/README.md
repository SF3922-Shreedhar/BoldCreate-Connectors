# Backstory

BoldCreate plugin that connects agents to Backstory through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Get answers on every deal.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Backstory**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Backstory**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install backstory@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "backstory": {
      "type": "http",
      "url": "https://mcp.backstory.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Backstory in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Backstory: https://www.backstory.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
