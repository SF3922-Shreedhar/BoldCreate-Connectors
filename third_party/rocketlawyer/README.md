# Rocket Lawyer

BoldCreate plugin that connects agents to Rocket Lawyer through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Attorney access for contract reviews & legal protection.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Rocket Lawyer**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Rocket Lawyer**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install rocketlawyer@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "rocketlawyer": {
      "type": "http",
      "url": "https://api.rocketlawyer.com/mcp-du/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Rocket Lawyer in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Rocket Lawyer: https://www.rocketlawyer.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
