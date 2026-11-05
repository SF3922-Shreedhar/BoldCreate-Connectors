# Insight Timer

BoldCreate plugin that connects agents to Insight Timer through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Emotional health & sleep.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Insight Timer**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Insight Timer**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install insight-timer@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "insight-timer": {
      "type": "http",
      "url": "https://claude-connector-api.insighttimer-api.net/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Insight Timer: https://insighttimer.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
