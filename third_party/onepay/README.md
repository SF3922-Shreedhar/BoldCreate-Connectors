# OnePay

BoldCreate plugin that connects agents to OnePay through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Get answers about your OnePay accounts from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **OnePay**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **OnePay**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install onepay@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "onepay": {
      "type": "http",
      "url": "https://mcp.onepay.com/anthropic"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to OnePay in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- OnePay: https://www.onepay.com/

## Logo

Icon downloaded from the Claude connector directory listing for OnePay. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
