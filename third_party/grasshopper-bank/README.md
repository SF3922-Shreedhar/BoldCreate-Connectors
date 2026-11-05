# Grasshopper Bank

BoldCreate plugin that connects agents to Grasshopper Bank through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Query and analyze your financial data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Grasshopper Bank**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Grasshopper Bank**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install grasshopper-bank@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "grasshopper-bank": {
      "type": "http",
      "url": "https://grasshopper-mcp.prd.narmitech.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Grasshopper Bank in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Grasshopper Bank: https://www.grasshopper.bank/

## Logo

Icon downloaded from the Claude connector directory listing for Grasshopper Bank. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
