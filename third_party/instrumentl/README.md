# Instrumentl

BoldCreate plugin that connects agents to Instrumentl through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Find, evaluate, and manage your grants.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Instrumentl**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Instrumentl**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install instrumentl@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "instrumentl": {
      "type": "http",
      "url": "https://mcp.instrumentl.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Instrumentl in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Instrumentl: https://www.instrumentl.com/

## Logo

Icon downloaded from the Claude connector directory listing for Instrumentl. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
