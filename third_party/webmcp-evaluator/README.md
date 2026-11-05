# WebMCP Evaluator

BoldCreate plugin that connects agents to WebMCP Evaluator through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Get an actionable, detailed review and build plan for making any public page ready for AI agents, based on your content, not generalized advice.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **WebMCP Evaluator**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **WebMCP Evaluator**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install webmcp-evaluator@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "webmcp-evaluator": {
      "type": "http",
      "url": "https://mcp.webmcp-eval.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to WebMCP Evaluator in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- WebMCP Evaluator: https://www.sunbusinessgroup.com/

## Logo

Icon downloaded from the Claude connector directory listing for WebMCP Evaluator. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
