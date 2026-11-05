# Saily

BoldCreate plugin that connects agents to Saily through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Browse and buy eSIM data plans for 190+ countries.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Saily**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Saily**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install saily@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "saily": {
      "type": "http",
      "url": "https://mcp.saily.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Saily in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Saily: https://nordsecurity.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
