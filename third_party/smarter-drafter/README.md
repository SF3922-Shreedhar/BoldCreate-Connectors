# Smarter Drafter

BoldCreate plugin that connects agents to Smarter Drafter through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Draft client-ready legal documents from your firm's approved templates, inside Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Smarter Drafter**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Smarter Drafter**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install smarter-drafter@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "smarter-drafter": {
      "type": "http",
      "url": "https://mcp.smarterdrafter.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Smarter Drafter in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Smarter Drafter: https://tensis.com/

## Logo

Icon downloaded from the Claude connector directory listing for Smarter Drafter. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
