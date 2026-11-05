# neimo.

BoldCreate plugin that connects agents to neimo. through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Answer any kids' privacy or age-assurance question for 200+ markets, with the law cited.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **neimo.**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **neimo.**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install neimo@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "neimo": {
      "type": "http",
      "url": "https://mcp.neimo.ai/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to neimo. in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- neimo.: https://k-id.com/

## Logo

Icon downloaded from the Claude connector directory listing for neimo.. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
