# Jus AI by Jus Mundi (Light Mode)

BoldCreate plugin that connects agents to Jus AI by Jus Mundi (Light Mode) through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

AI-powered global arbitration intelligence.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Jus AI by Jus Mundi (Light Mode)**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Jus AI by Jus Mundi (Light Mode)**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install jus-mundi@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "jus-mundi": {
      "type": "http",
      "url": "https://mcp.jusmundi.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Jus AI by Jus Mundi (Light Mode) in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Jus AI by Jus Mundi (Light Mode): https://jusmundi.com/ (vendor homepage; the sandbox could not load it, so the link is not verified)

## Logo

Neutral tile with the product's initials.

## License

MIT
