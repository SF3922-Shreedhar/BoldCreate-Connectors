# Ideals

BoldCreate plugin that connects agents to Ideals through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search, manage, and update your Ideals project from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Ideals**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Ideals**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install ideals@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "ideals": {
      "type": "http",
      "url": "https://gateway.idealsvdr.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Ideals in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Ideals: https://www.idealsvdr.com/

## Logo

Icon taken from the vendor's website (Ideals). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
