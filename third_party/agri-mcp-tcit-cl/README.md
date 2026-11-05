# agri-mcp.tcit.cl

BoldCreate plugin that connects agents to agri-mcp.tcit.cl through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage farm operations in AGRI: labor tasks, harvest, irrigation, inventory, purchasing and cost reports.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **agri-mcp.tcit.cl**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **agri-mcp.tcit.cl**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install agri-mcp-tcit-cl@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "agri-mcp-tcit-cl": {
      "type": "http",
      "url": "https://agri-mcp.tcit.cl/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to agri-mcp.tcit.cl in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- agri-mcp.tcit.cl: https://www.agri.so/

## Logo

Neutral tile with the product's initials.

## License

MIT
