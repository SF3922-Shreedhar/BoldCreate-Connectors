# CloudBees Unify MCP Server

BoldCreate plugin that connects agents to CloudBees Unify MCP Server through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Connect AI agents to CloudBees Unify: feature flags, CI/CD, release orchestration, and security.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **CloudBees Unify MCP Server**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **CloudBees Unify MCP Server**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install cloudbees-unify-mcp-server@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "cloudbees-unify-mcp-server": {
      "type": "http",
      "url": "https://mcp.cloudbees.io/v1/mcp?toolset=all"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to CloudBees Unify MCP Server in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- CloudBees Unify MCP Server: https://cloudbees.com/

## Logo

Icon downloaded from the Claude connector directory listing for CloudBees Unify MCP Server. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
