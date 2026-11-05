# Pliant

BoldCreate plugin that connects agents to Pliant through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Query and manage your Pliant corporate spend, cards, team, and accounting directly in Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Pliant**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Pliant**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install pliant@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "pliant": {
      "type": "http",
      "url": "https://mcp.getpliant.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Pliant in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Pliant: https://www.getpliant.com/

## Logo

Icon taken from the vendor's website (Pliant). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
