# Scite

BoldCreate plugin that connects agents to Scite through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Evidence-based answers grounded in research.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Scite**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Scite**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install scite@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "scite": {
      "type": "http",
      "url": "https://api.scite.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Scite in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Scite: https://scite.ai/

## Logo

Icon downloaded from the Claude connector directory listing for Scite. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
