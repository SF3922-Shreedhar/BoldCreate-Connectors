# Breezy HR MCP

BoldCreate plugin that connects agents to Breezy HR MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Turn a conversation with Claude into actual work. Connect to Breezy to manage your hiring workflow, from job creation to reporting on hiring activity.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Breezy HR MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Breezy HR MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install breezy-hr-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "breezy-hr-mcp": {
      "type": "http",
      "url": "https://mcp.breezy.hr/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Breezy HR MCP in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Breezy HR MCP: https://breezy.hr/

## Logo

Icon downloaded from the Claude connector directory listing for Breezy HR MCP. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
