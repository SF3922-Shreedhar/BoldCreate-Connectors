# Pushwoosh ManyMoney

BoldCreate plugin that connects agents to Pushwoosh ManyMoney through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Drive your Pushwoosh project in natural language — build segments, presets, and customer journeys, diagnose delivery, and analyze campaign performance, right from your AI client.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Pushwoosh ManyMoney**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Pushwoosh ManyMoney**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install pushwoosh-manymoney@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "pushwoosh-manymoney": {
      "type": "http",
      "url": "https://manymoney.pushwoosh.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Pushwoosh ManyMoney in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Pushwoosh ManyMoney: https://www.pushwoosh.com/

## Logo

Icon downloaded from the Claude connector directory listing for Pushwoosh ManyMoney. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
