# Addepar MCP

BoldCreate plugin that connects agents to Addepar MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Bring Addepar portfolio intelligence into Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Addepar MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Addepar MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install addepar@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "addepar": {
      "type": "http",
      "url": "https://mcp.addepar.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Addepar MCP in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Addepar MCP: https://addepar.com/

## Logo

Icon downloaded from the Claude connector directory listing for Addepar MCP. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
