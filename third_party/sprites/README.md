# Sprites

BoldCreate plugin that connects agents to Sprites through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Let Claude manage your Sprites.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Sprites**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Sprites**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install sprites@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "sprites": {
      "type": "http",
      "url": "https://sprites.dev/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Sprites in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Sprites: https://fly.io/sprites

## Logo

Icon taken from the vendor's website (Sprites). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
