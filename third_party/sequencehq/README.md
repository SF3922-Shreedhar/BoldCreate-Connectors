# Sequence

BoldCreate plugin that connects agents to Sequence through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Billing, invoicing, and revenue data tools for Sequence.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Sequence**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Sequence**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install sequencehq@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "sequencehq": {
      "type": "http",
      "url": "https://eu.sequencehq.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Sequence in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Sequence: https://www.sequencehq.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
