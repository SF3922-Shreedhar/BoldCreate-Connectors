# Spara

BoldCreate plugin that connects agents to Spara through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Build the agents that run your GTM.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Spara**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Spara**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install spara@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "spara": {
      "type": "http",
      "url": "https://app.spara.co/mcp/customer/stream"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Spara in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Spara: https://www.spara.com/

## Logo

Icon taken from the vendor's website (Spara). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
