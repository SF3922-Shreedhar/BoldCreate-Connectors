# Robutler

BoldCreate plugin that connects agents to Robutler through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Build, remix, and run apps with agents, together.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Robutler**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Robutler**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install robutler@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "robutler": {
      "type": "http",
      "url": "https://robutler.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Robutler in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Robutler: https://robutler.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
