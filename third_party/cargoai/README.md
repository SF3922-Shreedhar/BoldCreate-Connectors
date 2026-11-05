# CargoAi

BoldCreate plugin that connects agents to CargoAi through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Instant air cargo rates, quotes & tracking.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **CargoAi**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **CargoAi**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install cargoai@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "cargoai": {
      "type": "http",
      "url": "https://api.cargoai.co/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to CargoAi in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- CargoAi: https://www.cargoai.co/

## Logo

Icon downloaded from the Claude connector directory listing for CargoAi. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
