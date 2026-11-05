# Rhizome AI

BoldCreate plugin that connects agents to Rhizome AI through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Know what your regulator thinks.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Rhizome AI**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Rhizome AI**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install rhizome-ai@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "rhizome-ai": {
      "type": "http",
      "url": "https://rhizomeai.com/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Rhizome AI in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Rhizome AI: https://rhizomeai.com/

## Logo

Icon taken from the vendor's website (Rhizome AI). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
