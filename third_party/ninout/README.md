# Ninout

BoldCreate plugin that connects agents to Ninout through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Design, publish, and analyze forms entirely in chat.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Ninout**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Ninout**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install ninout@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "ninout": {
      "type": "http",
      "url": "https://mcp.svy.ooo/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Ninout in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Ninout: https://www.ninout.ai/

## Logo

Icon taken from the vendor's website (Ninout). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
