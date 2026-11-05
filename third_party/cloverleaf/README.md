# Cloverleaf

BoldCreate plugin that connects agents to Cloverleaf through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Bring Cloverleaf's personality insights into Claude to understand how you and your colleagues work together, and get coaching grounded in real assessment data, not generic advice.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Cloverleaf**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Cloverleaf**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install cloverleaf@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "cloverleaf": {
      "type": "http",
      "url": "https://app.cloverleaf.me/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Cloverleaf in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Cloverleaf: https://cloverleaf.me/

## Logo

Icon taken from the vendor's website (Cloverleaf). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
