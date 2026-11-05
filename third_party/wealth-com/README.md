# Wealth.com

BoldCreate plugin that connects agents to Wealth.com through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Bring your clients' estate plans, tax returns, and documents into Claude — with instant snapshots, risk analysis, and advisor-ready summaries.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Wealth.com**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Wealth.com**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install wealth-com@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "wealth-com": {
      "type": "http",
      "url": "https://mcp.wealth.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Wealth.com in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Wealth.com: https://www.wealth.com/

## Logo

Icon downloaded from the Claude connector directory listing for Wealth.com. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
