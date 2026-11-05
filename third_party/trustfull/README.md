# Trustfull

BoldCreate plugin that connects agents to Trustfull through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Bring Trustfull fraud intelligence and risk assessments into Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Trustfull**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Trustfull**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install trustfull@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "trustfull": {
      "type": "http",
      "url": "https://mcp.trustfull.com/connector"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Trustfull in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Trustfull: https://www.trustfull.com/

## Logo

Icon taken from the vendor's website (Trustfull), because the Claude connector directory links to a web page instead of an image file. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
