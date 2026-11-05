# Schwab Advisor Services

BoldCreate plugin that connects agents to Schwab Advisor Services through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Less time searching. More time focused on your clients. For professional use only.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Schwab Advisor Services**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Schwab Advisor Services**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install schwab-advisor-services@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "schwab-advisor-services": {
      "type": "http",
      "url": "https://agent.schwabinstitutional.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Schwab Advisor Services in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Schwab Advisor Services: https://advisorservices.schwab.com/ (vendor homepage; the sandbox could not load it, so the link is not verified)

## Logo

Icon downloaded from the Claude connector directory listing for Schwab Advisor Services. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
