# Kick

BoldCreate plugin that connects agents to Kick through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search, categorize, edit, and report in Kick.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Kick**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Kick**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install kick-co@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "kick-co": {
      "type": "http",
      "url": "https://use.kick.co/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Kick in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Kick: https://kick.co/

## Logo

Icon taken from the vendor's website (Kick). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
