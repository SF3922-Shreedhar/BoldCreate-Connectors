# Isometric

BoldCreate plugin that connects agents to Isometric through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Agentic certification for the industrial economy.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Isometric**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Isometric**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install isometric@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "isometric": {
      "type": "http",
      "url": "https://api.isometric.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Isometric in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Isometric: https://isometric.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
