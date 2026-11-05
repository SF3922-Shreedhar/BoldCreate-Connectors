# Manufact

BoldCreate plugin that connects agents to Manufact through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Deploy and monitor MCP servers.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Manufact**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Manufact**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install manufact@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "manufact": {
      "type": "http",
      "url": "https://mcp.manufact.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Manufact in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Manufact: https://manufact.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
