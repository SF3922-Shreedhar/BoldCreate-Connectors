# Lumonic

BoldCreate plugin that connects agents to Lumonic through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Analyze portfolio data and reporting in Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Lumonic**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Lumonic**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install lumonic@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "lumonic": {
      "type": "http",
      "url": "https://mcp.lumonic.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Lumonic in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Lumonic: https://www.lumonic.com/

## Logo

Icon taken from the vendor's website (Lumonic). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
