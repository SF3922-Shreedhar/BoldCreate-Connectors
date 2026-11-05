# Merchkit

BoldCreate plugin that connects agents to Merchkit through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

AI-Native Product Catalog (PIM / PXM / Product Feed / Agentic Commerce Optimization).

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Merchkit**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Merchkit**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install merchkit@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "merchkit": {
      "type": "http",
      "url": "https://www.merchkit.com/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Merchkit in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Merchkit: https://merchkit.com/

## Logo

Icon taken from the vendor's website (Merchkit). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
