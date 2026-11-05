# Terminal49

BoldCreate plugin that connects agents to Terminal49 through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Track ocean shipments and containers.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Terminal49**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Terminal49**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install terminal49@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "terminal49": {
      "type": "http",
      "url": "https://mcp.terminal49.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Terminal49 in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Terminal49: https://terminal49.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
