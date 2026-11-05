# august

BoldCreate plugin that connects agents to august through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Understand your users with august Digital Twins.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **august**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **august**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install august-digital-twins@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "august-digital-twins": {
      "type": "http",
      "url": "https://mcp.getaugust.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to august in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- august: https://getaugust.ai/ (vendor homepage; the sandbox could not load it, so the link is not verified)

## Logo

Neutral tile with the product's initials.

## License

MIT
