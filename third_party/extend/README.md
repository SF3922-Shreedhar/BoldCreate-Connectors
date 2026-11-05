# Extend

BoldCreate plugin that connects agents to Extend through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Turn documents into structured data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Extend**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Extend**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install extend@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "extend": {
      "type": "http",
      "url": "https://mcp.extend.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Extend in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Extend: https://www.extend.ai/

## Logo

Icon downloaded from the Claude connector directory listing for Extend. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
