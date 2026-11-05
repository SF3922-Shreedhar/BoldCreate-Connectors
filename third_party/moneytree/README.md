# Moneytree

BoldCreate plugin that connects agents to Moneytree through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Explore your financial data through conversation.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Moneytree**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Moneytree**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install moneytree@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "moneytree": {
      "type": "http",
      "url": "https://mcp.getmoneytree.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Moneytree in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Moneytree: https://getmoneytree.com/

## Logo

Icon taken from the vendor's website (Moneytree). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
