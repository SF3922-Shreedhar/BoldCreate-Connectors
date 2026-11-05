# Zoho CRM

BoldCreate plugin that connects agents to Zoho CRM through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

MCP Server for Zoho CRM Workflows.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Zoho CRM**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Zoho CRM**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install zoho-crm@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "zoho-crm": {
      "type": "http",
      "url": "https://claude-zohocrm.zohomcp.com/mcp/message"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Zoho CRM in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Zoho CRM: https://www.zoho.com/mcp/

## Logo

Icon downloaded from the Claude connector directory listing for Zoho CRM. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
