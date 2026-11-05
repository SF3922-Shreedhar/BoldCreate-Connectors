# Flipsnack

BoldCreate plugin that connects agents to Flipsnack through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Find, create, update, share, embed, and get analytics for the flipbooks in your Flipsnack account.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Flipsnack**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Flipsnack**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install flipsnack@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "flipsnack": {
      "type": "http",
      "url": "https://mcp.flipsnack.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Flipsnack in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Flipsnack: https://www.flipsnack.com/

## Logo

Icon taken from the vendor's website (Flipsnack). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
