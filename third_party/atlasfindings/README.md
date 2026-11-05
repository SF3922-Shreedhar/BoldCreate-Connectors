# atlasFindings

BoldCreate plugin that connects agents to atlasFindings through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search, investigate, and act on Atlas data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **atlasFindings**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **atlasFindings**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install atlasfindings@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "atlasfindings": {
      "type": "http",
      "url": "https://api.esentire.com/mcp/rpc"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to atlasFindings in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- atlasFindings: https://www.esentire.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
