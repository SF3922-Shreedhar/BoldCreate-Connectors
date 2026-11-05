# AWS Knowledge

BoldCreate plugin that connects agents to AWS Knowledge through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search AWS documentation, API references, and regional availability.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **AWS Knowledge**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **AWS Knowledge**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install aws-knowledge@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "aws-knowledge": {
      "type": "http",
      "url": "https://knowledge-mcp.global.api.aws"
    }
  }
}
```

## Setup

No settings.

This server needs no account or key.

## Docs

- AWS Knowledge MCP server: https://awslabs.github.io/mcp/servers/aws-knowledge-mcp-server

## Logo

Neutral tile with the product's initials.

## License

MIT
