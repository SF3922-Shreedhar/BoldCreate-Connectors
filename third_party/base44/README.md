# Base44

BoldCreate plugin that connects agents to Base44 through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Build and manage Base44 apps.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Base44**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Base44**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install base44@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "base44": {
      "type": "http",
      "url": "https://app.base44.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Base44 in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Base44: https://base44.com/

## Logo

Icon downloaded from the Claude connector directory listing for Base44. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
