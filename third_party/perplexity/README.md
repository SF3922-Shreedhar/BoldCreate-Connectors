# Perplexity Docs

BoldCreate plugin that connects agents to Perplexity's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search Perplexity's official Sonar and API documentation.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Perplexity Docs**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Perplexity Docs**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install perplexity@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "perplexity": {
      "type": "http",
      "url": "https://docs.perplexity.ai/mcp"
    }
  }
}
```

## Setup

No settings.

This server needs no account or key.

## Docs

- Perplexity docs: https://docs.perplexity.ai

## Logo

Icon taken from the vendor's website (Perplexity Docs). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
