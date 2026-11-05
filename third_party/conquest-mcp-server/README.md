# Conquest MCP Server

BoldCreate plugin that connects agents to Conquest MCP Server through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Conquest’s verifiable AI financial advice engine in Claude — create plans, review client goals, and apply SAM strategies right where you work.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Conquest MCP Server**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Conquest MCP Server**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install conquest-mcp-server@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "conquest-mcp-server": {
      "type": "http",
      "url": "https://api.conquest-cloud.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Conquest MCP Server in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Conquest MCP Server: https://conquestplanning.com/

## Logo

Icon downloaded from the Claude connector directory listing for Conquest MCP Server. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
