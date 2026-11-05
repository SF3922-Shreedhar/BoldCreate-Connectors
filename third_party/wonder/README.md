# Wonder

BoldCreate plugin that connects agents to Wonder through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Create and edit designs with Claude on a canvas where every design is real code.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Wonder**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Wonder**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install wonder@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "wonder": {
      "type": "http",
      "url": "https://mcp.wonder.so/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Wonder in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Wonder: https://wonder.design/

## Logo

Neutral tile with the product's initials.

## License

MIT
