# PubMatic

BoldCreate plugin that connects agents to PubMatic through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage campaigns, deals, reporting, and inventory in PubMatic directly from Claude using natural language.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **PubMatic**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **PubMatic**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install pubmatic@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "pubmatic": {
      "type": "http",
      "url": "https://mcp.pubmatic.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to PubMatic in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- PubMatic: https://pubmatic.com/ (vendor homepage; the sandbox could not load it, so the link is not verified)

## Logo

Neutral tile with the product's initials.

## License

MIT
