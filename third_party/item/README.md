# item

BoldCreate plugin that connects agents to item through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search, analyze, and act on CRM data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **item**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **item**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install item@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "item": {
      "type": "http",
      "url": "https://mcp.item.app/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to item in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- item: https://item.app/

## Logo

Neutral tile with the product's initials.

## License

MIT
