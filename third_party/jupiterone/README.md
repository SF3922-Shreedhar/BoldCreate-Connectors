# JupiterOne

BoldCreate plugin that connects agents to JupiterOne through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Ask questions about your JupiterOne agentic security and it asset graph and manage alerts, rules, and dashboards — in natural language.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **JupiterOne**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **JupiterOne**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install jupiterone@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "jupiterone": {
      "type": "http",
      "url": "https://mcp.us.jupiterone.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to JupiterOne in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- JupiterOne: https://www.jupiterone.com/

## Logo

Icon downloaded from the Claude connector directory listing for JupiterOne. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
