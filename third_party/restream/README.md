# Restream

BoldCreate plugin that connects agents to Restream through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Create and manage live streams on 30+ destinations.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Restream**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Restream**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install restream@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "restream": {
      "type": "http",
      "url": "https://mcp.restream.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Restream in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Restream: https://restream.io/

## Logo

Neutral tile with the product's initials.

## License

MIT
