# Phished

BoldCreate plugin that connects agents to Phished through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Phished's entire ZIR app at your fingertips directly in Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Phished**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Phished**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install phished@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "phished": {
      "type": "http",
      "url": "https://mcp.phished.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Phished in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Phished: https://phished.io/

## Logo

Icon taken from the vendor's website (Phished). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
