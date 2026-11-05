# Clerq MCP

BoldCreate plugin that connects agents to Clerq MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

AI-powered patent retrieval and analysis capabilities.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Clerq MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Clerq MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install clerq-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "clerq-mcp": {
      "type": "http",
      "url": "https://mcp.us.clerq-ip.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Clerq MCP in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Clerq MCP: https://www.clerq-ip.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
