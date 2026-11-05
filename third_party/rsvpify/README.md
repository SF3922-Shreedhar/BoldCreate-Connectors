# RSVPify

BoldCreate plugin that connects agents to RSVPify through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Run your event operations in RSVPify, end-to-end.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **RSVPify**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **RSVPify**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install rsvpify@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "rsvpify": {
      "type": "http",
      "url": "https://mcp.rsvpify.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to RSVPify in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- RSVPify: https://rsvpify.com/ (vendor homepage; the sandbox could not load it, so the link is not verified)

## Logo

Neutral tile with the product's initials.

## License

MIT
