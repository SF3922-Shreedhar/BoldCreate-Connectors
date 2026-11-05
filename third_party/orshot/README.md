# Orshot

BoldCreate plugin that connects agents to Orshot through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Automate Videos, PDFs and Images from templates for marketing, post to social platforms, and track and grow engagement.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Orshot**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Orshot**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install orshot@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "orshot": {
      "type": "http",
      "url": "https://mcp.orshot.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Orshot in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Orshot: https://orshot.com/

## Logo

Icon taken from the vendor's website (Orshot). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
