# ADITUS Evo

BoldCreate plugin that connects agents to ADITUS Evo through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

ADITUS Evo translates the complexity of modern events into clear insights and makes data-driven decisions easier than ever.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **ADITUS Evo**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **ADITUS Evo**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install aditus-evo@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "aditus-evo": {
      "type": "http",
      "url": "https://mcp.aditus.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to ADITUS Evo in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- ADITUS Evo: https://www.aditus.com/

## Logo

Icon taken from the vendor's website (ADITUS Evo). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
