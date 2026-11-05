# BoardWise

BoldCreate plugin that connects agents to BoardWise through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Calm board-defense guidance for licensed pros.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **BoardWise**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **BoardWise**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install boardwise@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "boardwise": {
      "type": "http",
      "url": "https://uakozrqrztgrgwoywxkx.supabase.co/functions/v1/mcp-server"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- BoardWise: https://boardwise.online/

## Logo

Icon downloaded from the Claude connector directory listing for BoardWise. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
