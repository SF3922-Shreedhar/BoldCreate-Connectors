# Within

BoldCreate plugin that connects agents to Within through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Explore your org's processes.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Within**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Within**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install within@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "within": {
      "type": "http",
      "url": "https://api.within.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Within in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Within: https://www.within.ai/

## Logo

Icon downloaded from the Claude connector directory listing for Within. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
