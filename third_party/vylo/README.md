# Vylo

BoldCreate plugin that connects agents to Vylo through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Your meeting memory.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Vylo**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Vylo**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install vylo@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "vylo": {
      "type": "http",
      "url": "https://mcp.vylo.one/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Vylo in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Vylo: https://vylo.one/

## Logo

Neutral tile with the product's initials.

## License

MIT
