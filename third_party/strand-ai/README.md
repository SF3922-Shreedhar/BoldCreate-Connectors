# Strand AI

BoldCreate plugin that connects agents to Strand AI through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Predict spatial proteomics from H&E histology slides.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Strand AI**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Strand AI**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install strand-ai@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "strand-ai": {
      "type": "http",
      "url": "https://mcp.strandai.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Strand AI in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Strand AI: https://strandai.com/

## Logo

Icon downloaded from the Claude connector directory listing for Strand AI. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
