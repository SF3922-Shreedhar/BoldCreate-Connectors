# Optilogic

BoldCreate plugin that connects agents to Optilogic through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

AI-driven supply chain design and decision intelligence.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Optilogic**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Optilogic**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install optilogic@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "optilogic": {
      "type": "http",
      "url": "https://mcp.optilogic.app/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Optilogic in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Optilogic: https://optilogic.com/

## Logo

Icon downloaded from the Claude connector directory listing for Optilogic. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
