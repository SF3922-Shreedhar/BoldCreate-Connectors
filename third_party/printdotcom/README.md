# Print.com

BoldCreate plugin that connects agents to Print.com through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Get inspired,configure and price print products from our full catalogue and manage Print.com orders without leaving Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Print.com**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Print.com**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install printdotcom@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "printdotcom": {
      "type": "http",
      "url": "https://mcp.print.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Print.com in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Print.com: https://www.print.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
