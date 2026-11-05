# Questrade

BoldCreate plugin that connects agents to Questrade through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Connect Claude to your Questrade brokerage account to check your portfolio, get real-time market data, and explore trades.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Questrade**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Questrade**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install questrade@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "questrade": {
      "type": "http",
      "url": "https://mcp.questrade.com/v1/brokerage/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Questrade in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Questrade: https://www.questrade.com/

## Logo

Icon downloaded from the Claude connector directory listing for Questrade. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
