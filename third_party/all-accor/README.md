# ALL Accor

BoldCreate plugin that connects agents to ALL Accor through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search and book Accor hotels.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **ALL Accor**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **ALL Accor**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install all-accor@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "all-accor": {
      "type": "http",
      "url": "https://mcp.dams.aws.accor.com/green/v1/mcp/apps"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- ALL Accor: https://all.accor.com/

## Logo

Icon downloaded from the Claude connector directory listing for ALL Accor. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
