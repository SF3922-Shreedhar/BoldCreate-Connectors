# Promptless

BoldCreate plugin that connects agents to Promptless through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search, read, and edit your documentation.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Promptless**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Promptless**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install promptless@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "promptless": {
      "type": "http",
      "url": "https://api.gopromptless.ai/mcp/with-direct-edits"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Promptless in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Promptless: https://promptless.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
