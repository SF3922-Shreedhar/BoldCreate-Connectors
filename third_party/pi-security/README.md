# Pi Security

BoldCreate plugin that connects agents to Pi Security through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Agentic product security platform.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Pi Security**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Pi Security**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install pi-security@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "pi-security": {
      "type": "http",
      "url": "https://mcp.pi.security/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Pi Security in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Pi Security: https://pi.security/

## Logo

Neutral tile with the product's initials.

## License

MIT
