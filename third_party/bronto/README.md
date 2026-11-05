# Bronto

BoldCreate plugin that connects agents to Bronto through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Query your Observability data in plain language, then turn what you find into monitors, saved searches, and Investigation Reports.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Bronto**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Bronto**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install bronto@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "bronto": {
      "type": "http",
      "url": "https://mcp.eu.bronto.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Bronto in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Bronto: https://bronto.io/

## Logo

Icon downloaded from the Claude connector directory listing for Bronto. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
