# Sendcloud

BoldCreate plugin that connects agents to Sendcloud through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage your shipping without leaving the chat.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Sendcloud**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Sendcloud**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install sendcloud-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "sendcloud-mcp": {
      "type": "http",
      "url": "https://mcp.sendcloud.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Sendcloud in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Sendcloud: https://sendcloud.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
