# Vasara

BoldCreate plugin that connects agents to Vasara through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search case law and legislation across Lithuania and the EU, with verifiable citations.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Vasara**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Vasara**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install vasara@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "vasara": {
      "type": "http",
      "url": "https://mcp.vasara.ai/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Vasara in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Vasara: https://vasara.ai/

## Logo

Icon taken from the vendor's website (Vasara). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
