# Salesflare

BoldCreate plugin that connects agents to Salesflare through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage and explore your CRM in Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Salesflare**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Salesflare**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install salesflare@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "salesflare": {
      "type": "http",
      "url": "https://mcp.salesflare.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Salesflare in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Salesflare: https://salesflare.com/

## Logo

Icon taken from the vendor's website (Salesflare). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
