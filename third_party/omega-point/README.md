# Omega Point

BoldCreate plugin that connects agents to Omega Point through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Turn market, index, and portfolio data into decisions: institutional risk, performance, and factor analytics in one place.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Omega Point**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Omega Point**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install omega-point@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "omega-point": {
      "type": "http",
      "url": "https://mcp.ompnt.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Omega Point in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Omega Point: https://omegapoint.ai/?ref=claude-directory

## Logo

Neutral tile with the product's initials.

## License

MIT
