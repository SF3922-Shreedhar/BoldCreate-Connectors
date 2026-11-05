# Metal

BoldCreate plugin that connects agents to Metal through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Access your deal intelligence.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Metal**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Metal**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install metal@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "metal": {
      "type": "http",
      "url": "https://mcp.metal.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Metal in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Metal: https://www.metal.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
