# Adobe Workfront

BoldCreate plugin that connects agents to Adobe Workfront through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage planning, projects, tasks, and approvals.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Adobe Workfront**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Adobe Workfront**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install adobe-workfront@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "adobe-workfront": {
      "type": "http",
      "url": "https://mcp.workfront.adobe.com/mcp/v1/workfront"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Adobe Workfront in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Adobe Workfront: https://business.adobe.com/

## Logo

Icon downloaded from the Claude connector directory listing for Adobe Workfront. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
