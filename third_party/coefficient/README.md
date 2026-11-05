# Coefficient SuperAgent

BoldCreate plugin that connects agents to Coefficient SuperAgent through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

The data agent built for everyone. Ask about your company's data and get answers the way your data team would give them, with the lineage to prove it.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Coefficient SuperAgent**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Coefficient SuperAgent**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install coefficient@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "coefficient": {
      "type": "http",
      "url": "https://superagent.app.coefficient.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Coefficient SuperAgent in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Coefficient SuperAgent: https://coefficient.io/

## Logo

Neutral tile with the product's initials.

## License

MIT
