# Grasp

BoldCreate plugin that connects agents to Grasp through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Find, screen and analyse private-market opportunities.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Grasp**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Grasp**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install grasp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "grasp": {
      "type": "http",
      "url": "https://app.grasp-ai.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Grasp in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Grasp: https://grasp-ai.com/

## Logo

Icon downloaded from the Claude connector directory listing for Grasp. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
