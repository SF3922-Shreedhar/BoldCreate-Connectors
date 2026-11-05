# Notra

BoldCreate plugin that connects agents to Notra through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Track AI search visibility.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Notra**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Notra**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install notra@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "notra": {
      "type": "http",
      "url": "https://mcp.usenotra.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Notra in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Notra: https://www.usenotra.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
