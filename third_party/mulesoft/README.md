# MuleSoft

BoldCreate plugin that connects agents to MuleSoft through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Govern, manage, and observe your entire Agent ecosystem.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **MuleSoft**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **MuleSoft**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install mulesoft@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "mulesoft": {
      "type": "http",
      "url": "https://omni.mulesoft.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to MuleSoft in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- MuleSoft: https://www.mulesoft.com/ (vendor homepage; the sandbox could not load it, so the link is not verified)

## Logo

Neutral tile with the product's initials.

## License

MIT
