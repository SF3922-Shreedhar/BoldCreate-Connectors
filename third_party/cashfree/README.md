# Cashfree

BoldCreate plugin that connects agents to Cashfree through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Your All in One AI Assistant.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Cashfree**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Cashfree**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install cashfree@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "cashfree": {
      "type": "http",
      "url": "https://mcp.cashfree.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Cashfree in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Cashfree: https://www.cashfree.com/

## Logo

Icon downloaded from the Claude connector directory listing for Cashfree. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
