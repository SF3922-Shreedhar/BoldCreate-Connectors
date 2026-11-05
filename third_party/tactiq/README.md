# Tactiq

BoldCreate plugin that connects agents to Tactiq through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search, summarise & find answers in meetings.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Tactiq**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Tactiq**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install tactiq@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "tactiq": {
      "type": "http",
      "url": "https://mcp.tactiq.io/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Tactiq in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Tactiq: https://tactiq.io/

## Logo

Icon taken from the vendor's website (Tactiq). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
