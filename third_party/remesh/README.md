# Remesh

BoldCreate plugin that connects agents to Remesh through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Research conversations with real people at scale. Design studies, recruit audiences, launch conversations, and explore results without leaving your workflow.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Remesh**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Remesh**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install remesh@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "remesh": {
      "type": "http",
      "url": "https://live.remesh.chat/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Remesh in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Remesh: https://www.remesh.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
