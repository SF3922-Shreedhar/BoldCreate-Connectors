# Airfield Directory

BoldCreate plugin that connects agents to Airfield Directory through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Airfield Reports, fees and aviation data for GA Pilots.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Airfield Directory**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Airfield Directory**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install airfield-directory@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "airfield-directory": {
      "type": "http",
      "url": "https://airfield.directory/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Airfield Directory: https://airfield.directory/

## Logo

Icon downloaded from the Claude connector directory listing for Airfield Directory. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
