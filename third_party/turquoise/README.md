# Turquoise

BoldCreate plugin that connects agents to Turquoise through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Query Turquoise's proprietary healthcare pricing data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Turquoise**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Turquoise**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install turquoise@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "turquoise": {
      "type": "http",
      "url": "https://mcp.turquoise.health/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Turquoise in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Turquoise: https://turquoise.health/

## Logo

Icon downloaded from the Claude connector directory listing for Turquoise. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
