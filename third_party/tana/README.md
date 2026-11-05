# Tana

BoldCreate plugin that connects agents to Tana through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Your meetings, decisions, and docs as Claude context.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Tana**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Tana**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install tana@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "tana": {
      "type": "http",
      "url": "https://home.tana.inc/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Tana in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Tana: https://tana.inc/

## Logo

Icon downloaded from the Claude connector directory listing for Tana. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
