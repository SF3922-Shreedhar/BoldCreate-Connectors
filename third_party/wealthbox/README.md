# Wealthbox

BoldCreate plugin that connects agents to Wealthbox through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search, update, and manage Wealthbox data from inside Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Wealthbox**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Wealthbox**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install wealthbox@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "wealthbox": {
      "type": "http",
      "url": "https://mcp.crmworkspace.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Wealthbox in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Wealthbox: https://www.wealthbox.com/

## Logo

Icon downloaded from the Claude connector directory listing for Wealthbox. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
