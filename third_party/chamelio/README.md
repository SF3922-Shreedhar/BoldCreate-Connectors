# Chamelio

BoldCreate plugin that connects agents to Chamelio through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search contracts, track and start legal workflows, and ask Chamelio's AI legal agent.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Chamelio**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Chamelio**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install chamelio@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "chamelio": {
      "type": "http",
      "url": "https://mcp.chamelio.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Chamelio in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Chamelio: https://chamelio.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
