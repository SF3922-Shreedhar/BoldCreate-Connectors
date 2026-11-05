# LILT

BoldCreate plugin that connects agents to LILT through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

High-quality translation with human verification.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **LILT**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **LILT**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install lilt@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "lilt": {
      "type": "http",
      "url": "https://mcp.lilt.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to LILT in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- LILT: https://lilt.com/

## Logo

Icon downloaded from the Claude connector directory listing for LILT. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
