# Darwinbox

BoldCreate plugin that connects agents to Darwinbox through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Apply leave, track attendance, manage hiring and onboarding, file expenses and more in Darwinbox with your existing Darwinbox permissions.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Darwinbox**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Darwinbox**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install darwinbox-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "darwinbox-mcp": {
      "type": "http",
      "url": "https://mcp.darwinbox.com/mcp/all"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Darwinbox in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Darwinbox: https://darwinbox.com/ (vendor homepage; the sandbox could not load it, so the link is not verified)

## Logo

Neutral tile with the product's initials.

## License

MIT
