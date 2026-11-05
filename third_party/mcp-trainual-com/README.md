# Trainual

BoldCreate plugin that connects agents to Trainual through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search your training, operations, and performance data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Trainual**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Trainual**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install mcp-trainual-com@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "mcp-trainual-com": {
      "type": "http",
      "url": "https://mcp.trainual.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Trainual in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Trainual: https://trainual.com/

## Logo

Icon downloaded from the Claude connector directory listing for Trainual. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
