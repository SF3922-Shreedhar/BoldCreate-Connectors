# Civic IQ

BoldCreate plugin that connects agents to Civic IQ through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Sales intelligence for selling to US state and local government: open RFPs, pre-RFP meeting signals, agency contacts and vendor spend.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Civic IQ**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Civic IQ**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install civic-iq@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "civic-iq": {
      "type": "http",
      "url": "https://mcp.civiciq.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Civic IQ in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Civic IQ: https://civiciq.com/ (vendor homepage; the sandbox could not load it, so the link is not verified)

## Logo

Neutral tile with the product's initials.

## License

MIT
