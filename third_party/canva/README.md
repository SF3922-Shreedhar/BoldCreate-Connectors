# Canva

BoldCreate plugin that connects agents to Canva through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search, create, autofill, and export Canva designs.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Canva**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Canva**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install canva@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "canva": {
      "type": "http",
      "url": "https://mcp.canva.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Canva in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Canva: https://www.canva.dev/docs/connect/

## Logo

Icon downloaded from the Claude connector directory listing for Canva. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
