# Checkout.com

BoldCreate plugin that connects agents to Checkout.com through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Investigate, troubleshoot, and understand payment operations.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Checkout.com**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Checkout.com**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install checkout-com@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "checkout-com": {
      "type": "http",
      "url": "https://mcp.checkout.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Checkout.com in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Checkout.com: https://www.checkout.com/

## Logo

Icon downloaded from the Claude connector directory listing for Checkout.com. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
