# Mojo — Pocket Capture

BoldCreate plugin that connects agents to Mojo — Pocket Capture through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Talk to your leads, funnel, and capture setup.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Mojo — Pocket Capture**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Mojo — Pocket Capture**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install pocket-capture@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "pocket-capture": {
      "type": "http",
      "url": "https://mcp.mojosystems.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Mojo — Pocket Capture in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Mojo — Pocket Capture: https://www.mojosystems.io/

## Logo

Neutral tile with the product's initials.

## License

MIT
