# Chatbase

BoldCreate plugin that connects agents to Chatbase through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage Chatbase agents, sources, conversations, tickets.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Chatbase**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Chatbase**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install chatbase@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "chatbase": {
      "type": "http",
      "url": "https://mcp.chatbase.co/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Chatbase in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Chatbase: https://www.chatbase.co/

## Logo

Neutral tile with the product's initials.

## License

MIT
