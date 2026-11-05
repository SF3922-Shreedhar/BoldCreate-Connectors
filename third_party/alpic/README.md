# Alpic

BoldCreate plugin that connects agents to Alpic through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage your MCP Servers and MCP Apps hosted on Alpic.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Alpic**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Alpic**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install alpic@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "alpic": {
      "type": "http",
      "url": "https://mcp.alpic.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Alpic in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Alpic: https://alpic.ai/

## Logo

Icon downloaded from the Claude connector directory listing for Alpic. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
