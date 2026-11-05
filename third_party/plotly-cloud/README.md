# Plotly Cloud

BoldCreate plugin that connects agents to Plotly Cloud through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Build and deploy Plotly Dash apps to Plotly Cloud from a conversation with Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Plotly Cloud**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Plotly Cloud**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install plotly-cloud@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "plotly-cloud": {
      "type": "http",
      "url": "https://cloud.plotly.com/_mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Plotly Cloud in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Plotly Cloud: https://plotly.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
