# Theysaid

BoldCreate plugin that connects agents to Theysaid through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Run AI-powered usability tests on any live app, prototype, or design and get actionable insights, all from your chat.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Theysaid**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Theysaid**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install theysaid@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "theysaid": {
      "type": "http",
      "url": "https://ai.theysaid.io/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Theysaid in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Theysaid: https://www.theysaid.io/

## Logo

Icon taken from the vendor's website (Theysaid). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
