# Oak National Academy

BoldCreate plugin that connects agents to Oak National Academy through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Free, national curriculum-aligned Oak teaching resources.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Oak National Academy**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Oak National Academy**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install oak-national-academy@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "oak-national-academy": {
      "type": "http",
      "url": "https://mcp.thenational.academy/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Oak National Academy in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Oak National Academy: https://www.thenational.academy/

## Logo

Neutral tile with the product's initials.

## License

MIT
