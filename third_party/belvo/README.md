# Belvo MCP

BoldCreate plugin that connects agents to Belvo MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Understand your finances on your own terms.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Belvo MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Belvo MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install belvo@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "belvo": {
      "type": "http",
      "url": "https://panorama-mcp.belvo.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Belvo MCP in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Belvo MCP: https://belvo.com/

## Logo

Icon downloaded from the Claude connector directory listing for Belvo MCP. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
