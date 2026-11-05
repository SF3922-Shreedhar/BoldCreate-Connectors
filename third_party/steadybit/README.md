# Steadybit

BoldCreate plugin that connects agents to Steadybit through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Find reliability risks in your systems: design, run, and analyze chaos experiments.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Steadybit**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Steadybit**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install steadybit@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "steadybit": {
      "type": "http",
      "url": "https://platform.steadybit.com/mcp/demo"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Steadybit in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Steadybit: https://steadybit.com/

## Logo

Icon downloaded from the Claude connector directory listing for Steadybit. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
