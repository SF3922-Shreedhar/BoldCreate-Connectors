# BoldCreate Connectors

Connectors for BoldCreate Connect, Cursor and Claude Code. Each connector is a plugin under `third_party/` that connects agents to a vendor's remote [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

**Available connectors: 803**

## Install

- **BoldCreate Connect:** open **Marketplace**, find the connector, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install the connector.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install <name>@boldcreate-connectors`.

Secrets such as API keys are never stored in this repository. Each connector declares them as install-time variables, and you enter them when you install it. See each connector's README for setup.
