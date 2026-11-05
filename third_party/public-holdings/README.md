# Public Holdings

BoldCreate plugin that connects agents to Public Holdings through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

View your Public portfolio, market data and preflight trades.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Public Holdings**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Public Holdings**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install public-holdings@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "public-holdings": {
      "type": "http",
      "url": "https://mcp.public.com/read-only/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Public Holdings in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Public Holdings: https://public.com/

## Logo

Icon taken from the vendor's website (Public Holdings). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
