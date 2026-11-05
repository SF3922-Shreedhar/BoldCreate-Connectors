# grtwo-docs

BoldCreate plugin that connects agents to grtwo-docs through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Publish -docs. from Claude and get a shareable link.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **grtwo-docs**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **grtwo-docs**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install grtwo-docs@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "grtwo-docs": {
      "type": "http",
      "url": "https://www.grtwo.app/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to grtwo-docs in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- grtwo-docs: https://grtwo.com/

## Logo

Icon downloaded from the Claude connector directory listing for grtwo-docs. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
