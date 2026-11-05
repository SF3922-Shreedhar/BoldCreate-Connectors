# Vertiso Memory

BoldCreate plugin that connects agents to Vertiso Memory through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Portable, durable memory for every AI agent you use.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Vertiso Memory**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Vertiso Memory**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install vertiso-memory@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "vertiso-memory": {
      "type": "http",
      "url": "https://memory.vertiso.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Vertiso Memory in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Vertiso Memory: https://www.vertiso.com/

## Logo

Icon downloaded from the Claude connector directory listing for Vertiso Memory. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
