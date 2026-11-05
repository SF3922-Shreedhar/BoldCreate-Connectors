# Daffy MCP

BoldCreate plugin that connects agents to Daffy MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Check your Daffy fund, donations and charities.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Daffy MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Daffy MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install daffy-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "daffy-mcp": {
      "type": "http",
      "url": "https://public.daffy.org/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Daffy MCP in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Daffy MCP: https://www.daffy.org/

## Logo

Neutral tile with the product's initials.

## License

MIT
