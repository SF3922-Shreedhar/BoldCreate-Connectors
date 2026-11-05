# Maven Bio

BoldCreate plugin that connects agents to Maven Bio through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Biopharma catalysts, pipelines, trials, deals, and the citable primary sources behind them.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Maven Bio**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Maven Bio**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install maven-bio@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "maven-bio": {
      "type": "http",
      "url": "https://mcp.mavenbio.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Maven Bio in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Maven Bio: https://mavenbio.com/

## Logo

Icon taken from the vendor's website (Maven Bio). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
