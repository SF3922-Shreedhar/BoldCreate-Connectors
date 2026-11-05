# Kepler

BoldCreate plugin that connects agents to Kepler through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Connect your Kepler account for sourced financial analysis and model building.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Kepler**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Kepler**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install kepler@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "kepler": {
      "type": "http",
      "url": "https://mcp.kepler.ai/api/mcp/v1"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Kepler in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Kepler: https://kepler.ai/

## Logo

Icon taken from the vendor's website (Kepler). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
