# CoinGecko

BoldCreate plugin that connects agents to CoinGecko through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Track cryptocurrency prices, markets, exchanges, and trending coins.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **CoinGecko**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **CoinGecko**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install coingecko@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "coingecko": {
      "type": "http",
      "url": "https://mcp.coingecko.com/mcp"
    }
  }
}
```

## Setup

No settings.

This server needs no account or key.

## Docs

- CoinGecko MCP server: https://www.coingecko.com/en/mcp

## Logo

Icon downloaded from the Claude connector directory listing for CoinGecko. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
