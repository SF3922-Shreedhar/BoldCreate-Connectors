# Productised

BoldCreate plugin that connects agents to Productised through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

AI-Powered Inbound for Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Productised**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Productised**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install productised@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "productised": {
      "type": "http",
      "url": "https://mcp.productised.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Productised in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Productised: https://www.productised.ai/

## Logo

Icon downloaded from the Claude connector directory listing for Productised. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
