# Cloze MCP

BoldCreate plugin that connects agents to Cloze MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Cloze Relationship Management.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Cloze MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Cloze MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install cloze@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "cloze": {
      "type": "http",
      "url": "https://api.cloze.com/v1/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Cloze MCP in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Cloze MCP: https://cloze.com/

## Logo

Icon downloaded from the Claude connector directory listing for Cloze MCP. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
