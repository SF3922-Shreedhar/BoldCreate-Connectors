# Energy Aspects

BoldCreate plugin that connects agents to Energy Aspects through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Access Energy Aspects' energy market research and data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Energy Aspects**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Energy Aspects**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install energy-aspects@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "energy-aspects": {
      "type": "http",
      "url": "https://mcp.energyaspects.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Energy Aspects in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Energy Aspects: https://www.energyaspects.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
