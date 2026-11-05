# Keel

BoldCreate plugin that connects agents to Keel through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Build & backtest Hyperliquid strategies.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Keel**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Keel**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install keel@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "keel": {
      "type": "http",
      "url": "https://mcp.usekeel.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Keel in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Keel: https://usekeel.io/

## Logo

Icon downloaded from the Claude connector directory listing for Keel. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
