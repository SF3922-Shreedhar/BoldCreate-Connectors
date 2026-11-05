# RocketReach

BoldCreate plugin that connects agents to RocketReach through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Verified work emails and phones from 700M+ contacts.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **RocketReach**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **RocketReach**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install rocketreach@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "rocketreach": {
      "type": "http",
      "url": "https://mcp.rocketreach.co/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to RocketReach in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- RocketReach: https://rocketreach.co/

## Logo

Icon downloaded from the Claude connector directory listing for RocketReach. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
