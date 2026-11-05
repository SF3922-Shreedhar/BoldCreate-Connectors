# Flourish Financial

BoldCreate plugin that connects agents to Flourish Financial through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Securely access and analyze Flourish client data from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Flourish Financial**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Flourish Financial**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install flourish-financial@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "flourish-financial": {
      "type": "http",
      "url": "https://www.flourish.com/api/mcp/v2.0"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Flourish Financial in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Flourish Financial: https://www.flourish.com/

## Logo

Icon downloaded from the Claude connector directory listing for Flourish Financial. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
