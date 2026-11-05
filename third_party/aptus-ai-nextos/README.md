# Aptus.AI - NextOS

BoldCreate plugin that connects agents to Aptus.AI - NextOS through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Aptus.AI NextOS in your assistant: what a law, regulation or court ruling provides on your point, with quotations and links to the full text on Aptus.AI.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Aptus.AI - NextOS**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Aptus.AI - NextOS**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install aptus-ai-nextos@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "aptus-ai-nextos": {
      "type": "http",
      "url": "https://legalmcp.next.aptus.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Aptus.AI - NextOS in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Aptus.AI - NextOS: https://aptus.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
