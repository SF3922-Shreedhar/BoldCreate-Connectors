# Voluum

BoldCreate plugin that connects agents to Voluum through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage and analyze your Voluum ad-tracking campaigns directly from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Voluum**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Voluum**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install voluum@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "voluum": {
      "type": "http",
      "url": "https://mcp.voluum.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Voluum in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Voluum: https://voluum.com/

## Logo

Icon taken from the vendor's website (Voluum). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
