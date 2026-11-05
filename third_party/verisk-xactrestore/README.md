# Verisk XactRestore

BoldCreate plugin that connects agents to Verisk XactRestore through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Natural-language estimating for XactRestore.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Verisk XactRestore**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Verisk XactRestore**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install verisk-xactrestore@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "verisk-xactrestore": {
      "type": "http",
      "url": "https://xactrestore-xactremodelserver-usw2-prod.propsol.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Verisk XactRestore in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Verisk XactRestore: https://verisk.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
