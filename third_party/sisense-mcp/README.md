# Sisense MCP

BoldCreate plugin that connects agents to Sisense MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Ask your Sisense natural language questions, get visuals and insights.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Sisense MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Sisense MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install sisense-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "sisense-mcp": {
      "type": "http",
      "url": "https://mcp.sisense.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Sisense MCP in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Sisense MCP: https://sisense.com/

## Logo

Icon taken from the vendor's website (Sisense MCP). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
