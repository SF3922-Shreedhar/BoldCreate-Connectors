# Trimble SketchUp

BoldCreate plugin that connects agents to Trimble SketchUp through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Create and iterate 3D models for use in SketchUp.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Trimble SketchUp**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Trimble SketchUp**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install trimble-sketchup@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "trimble-sketchup": {
      "type": "http",
      "url": "https://api.sketchup.com/mcp/v1/sketchup/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Trimble SketchUp in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Trimble SketchUp: https://sketchup.trimble.com/

## Logo

Icon downloaded from the Claude connector directory listing for Trimble SketchUp. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
