# Whimsical

BoldCreate plugin that connects agents to Whimsical through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Create flowcharts, mindmaps, wireframes and diagrams.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Whimsical**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Whimsical**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install whimsical@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "whimsical": {
      "type": "http",
      "url": "https://mcp.whimsical.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Whimsical in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Whimsical: https://whimsical.com/

## Logo

Icon downloaded from the Claude connector directory listing for Whimsical. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
