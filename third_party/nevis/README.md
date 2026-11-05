# Nevis

BoldCreate plugin that connects agents to Nevis through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

The AI platform for wealth management.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Nevis**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Nevis**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install nevis@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "nevis": {
      "type": "http",
      "url": "https://app.neviswealth.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Nevis in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Nevis: https://www.neviswealth.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
