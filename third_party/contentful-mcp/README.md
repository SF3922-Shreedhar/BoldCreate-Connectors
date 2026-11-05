# Contentful MCP

BoldCreate plugin that connects agents to Contentful MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage your content from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Contentful MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Contentful MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install contentful-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "contentful-mcp": {
      "type": "http",
      "url": "https://mcp.contentful.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Contentful MCP in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Contentful MCP: https://www.contentful.com/

## Logo

Neutral tile with the product's initials.}

## License

MIT
