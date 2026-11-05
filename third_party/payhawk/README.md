# Payhawk

BoldCreate plugin that connects agents to Payhawk through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Ask and act on company spend: cards, invoices, travel.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Payhawk**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Payhawk**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install payhawk@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "payhawk": {
      "type": "http",
      "url": "https://mcp.payhawk.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Payhawk in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Payhawk: https://payhawk.com/

## Logo

Icon taken from the vendor's website (Payhawk). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
