# EasyPost

BoldCreate plugin that connects agents to EasyPost through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Make smarter shipping decisions, instantly.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **EasyPost**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **EasyPost**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install easypost@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "easypost": {
      "type": "http",
      "url": "https://app-api.easypost.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to EasyPost in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- EasyPost: https://www.easypost.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
