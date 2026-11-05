# Prefect

BoldCreate plugin that connects agents to Prefect through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Inspect Prefect workflows.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Prefect**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Prefect**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install prefect@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "prefect": {
      "type": "http",
      "url": "https://prefect.fastmcp.app/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Prefect in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Prefect: https://www.prefect.io/

## Logo

Icon downloaded from the Claude connector directory listing for Prefect. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
