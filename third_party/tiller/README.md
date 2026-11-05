# Tiller

BoldCreate plugin that connects agents to Tiller through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Connect to your transactions in your Tiller spreadsheet.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Tiller**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Tiller**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install tiller@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "tiller": {
      "type": "http",
      "url": "https://ai-tools.tillermoney.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Tiller in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Tiller: https://tiller.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
