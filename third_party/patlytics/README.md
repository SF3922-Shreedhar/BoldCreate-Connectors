# Patlytics

BoldCreate plugin that connects agents to Patlytics through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Prior art, claims, and portfolio search.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Patlytics**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Patlytics**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install patlytics@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "patlytics": {
      "type": "http",
      "url": "https://mcp.patlytics.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Patlytics in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Patlytics: https://www.patlytics.ai/

## Logo

Icon taken from the vendor's website (Patlytics). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
