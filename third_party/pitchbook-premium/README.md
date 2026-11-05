# PitchBook Premium

BoldCreate plugin that connects agents to PitchBook Premium through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

PitchBook data, embedded in the way you work.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **PitchBook Premium**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **PitchBook Premium**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install pitchbook-premium@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "pitchbook-premium": {
      "type": "http",
      "url": "https://premium.mcp.pitchbook.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to PitchBook Premium in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- PitchBook Premium: https://www.pitchbook.com/

## Logo

Icon downloaded from the Claude connector directory listing for PitchBook Premium. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
