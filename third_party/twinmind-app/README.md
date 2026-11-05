# TwinMind

BoldCreate plugin that connects agents to TwinMind through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

AI notes & Memory.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **TwinMind**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **TwinMind**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install twinmind-app@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "twinmind-app": {
      "type": "http",
      "url": "https://api.twinmind.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to TwinMind in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- TwinMind: https://twinmind.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
