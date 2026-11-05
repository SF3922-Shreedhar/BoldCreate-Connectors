# Paybooc

BoldCreate plugin that connects agents to Paybooc through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Paybooc Shopping Rewards links and reward rates for partner online stores.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Paybooc**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Paybooc**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install paybooc-shopping-rewards@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "paybooc-shopping-rewards": {
      "type": "http",
      "url": "https://open.paybooc.co.kr/pybc/api/mcp/shopping/claude"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Paybooc: https://www.bccard.com/app/card/MainActn.do

## Logo

Icon downloaded from the Claude connector directory listing for Paybooc. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
