# Squarespace

BoldCreate plugin that connects agents to Squarespace through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Find a domain name for your next idea, and run your Squarespace store's orders, products and customers, all from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Squarespace**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Squarespace**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install squarespace@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "squarespace": {
      "type": "http",
      "url": "https://mcp.squarespace.com/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Squarespace: https://www.squarespace.com/

## Logo

Icon taken from the vendor's website (Squarespace). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
