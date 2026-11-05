# Mantic

BoldCreate plugin that connects agents to Mantic through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Explore judgemental forecasts.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Mantic**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Mantic**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install mantic@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "mantic": {
      "type": "http",
      "url": "https://api.mantic.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Mantic in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Mantic: https://www.mantic.com/

## Logo

Icon taken from the vendor's website (Mantic). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
