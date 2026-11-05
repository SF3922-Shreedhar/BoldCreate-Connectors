# Vibe AI

BoldCreate plugin that connects agents to Vibe AI through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Transcripts, summaries, action items, and memos from your Vibe Bot and Vibe Dot meetings.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Vibe AI**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Vibe AI**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install vibe-ai@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "vibe-ai": {
      "type": "http",
      "url": "https://mcp.vibe.us/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Vibe AI in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Vibe AI: https://vibe.us/

## Logo

Neutral tile with the product's initials.

## License

MIT
