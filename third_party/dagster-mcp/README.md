# Dagster+ MCP

BoldCreate plugin that connects agents to Dagster+ MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Investigate issues and take action in your Dagster+ deployment from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Dagster+ MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Dagster+ MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install dagster-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "dagster-mcp": {
      "type": "http",
      "url": "https://mcp.agent.dagster.cloud/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Dagster+ MCP in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Dagster+ MCP: https://prefect.io/

## Logo

Icon downloaded from the Claude connector directory listing for Dagster+ MCP. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
