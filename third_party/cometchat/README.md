# CometChat

BoldCreate plugin that connects agents to CometChat through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Add real-time chat, voice, and video to your app.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **CometChat**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **CometChat**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install cometchat@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "cometchat": {
      "type": "http",
      "url": "https://mcp.cometchat.com/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- CometChat: https://www.cometchat.com/

## Logo

Icon taken from the vendor's website (CometChat). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
