# BoldCreate Connectors

Connectors for BoldCreate Connect, Cursor and Claude Code. Each connector is a plugin under `third_party/` that connects agents to a vendor's remote [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

This repository is a staging copy. It holds the connectors moved out of [BoldCreate Plugins](https://github.com/syncfusion/BoldCreate-Plugins), with the same structure, manifests, scripts and checks. It will move to the Syncfusion organization after the connectors have been verified in the target environment.

## Install

- **BoldCreate Connect:** open **Marketplace**, find the connector, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install the connector.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install <name>@boldcreate-connectors`.

Secrets such as API keys are never stored in this repository. Each connector declares them as install-time variables, and you enter them when you install it. See each connector's README for setup.

## Connectors

| `name` | Connector | Category | `description` (from marketplace) |
|:-------|:-------|:---------|:-------------------------------------|
| `8am-mycase` | [8am MyCase](third_party/8am-mycase/) | Legal | Connect your MyCase practice data to Claude — look up matters, contacts, tasks, time, and billing without leaving your AI workspace. |
| `actively` | [Actively](third_party/actively/) | Marketing | 1:1 account agents for GTM teams. |
| `addepar` | [Addepar MCP](third_party/addepar/) | Analytics | Bring Addepar portfolio intelligence into Claude. |
| `addgene` | [Addgene](third_party/addgene/) | Science | Search Addgene's catalog of plasmids and viral preps. |
| `aiwyn-tax` | [Aiwyn Tax (formerly Column Tax)](third_party/aiwyn-tax/) | Finance | Estimate your federal & state taxes with Aiwyn's tax engine. |
| `all-accor` | [ALL Accor](third_party/all-accor/) | Travel | Search and book Accor hotels. |
| `atlar` | [Atlar](third_party/atlar/) | Finance | Query your live treasury data: accounts, balances, transactions, and forecasts—directly from Claude. |
| `atlasfindings` | [atlasFindings](third_party/atlasfindings/) | Analytics | Search, investigate, and act on Atlas data. |
| `attentive` | [Attentive](third_party/attentive/) | Communication | Attentive, inside the AI tools you already use. |
| `aurora` | [Aurora](third_party/aurora/) | Legal | Search your Consilio matters, docs, and more. |
| `bitrise-mcp` | [Bitrise MCP](third_party/bitrise-mcp/) | Developer Tools | Set up and manage mobile CI/CD on Bitrise: build, test, and distribute iOS, Android, Flutter, and React Native apps from your AI assistant. |
| `blackthorn-beacon-event-ma` | [Blackthorn Forge MCP for Native Salesforce Event Management](third_party/blackthorn-beacon-event-ma/) | Education | Blackthorn's MCP server for Salesforce events: create, query, and report on events, attendees, tickets, sessions, forms, and email campaigns, over 100 available tools, live against your org. |
| `cargoai` | [CargoAi](third_party/cargoai/) | Productivity | Instant air cargo rates, quotes & tracking. |
| `chariot` | [Chariot](third_party/chariot/) | Finance | Manage your nonprofit's DAF donations and deposits. |
| `checkatrade` | [Checkatrade](third_party/checkatrade/) | Commerce | Find trusted local tradespeople and book fixed-price jobs — without leaving Claude. |
| `civitatis` | [Civitatis](third_party/civitatis/) | Travel | Search, plan, and book tours and activities worldwide with Civitatis. |
| `clarity-ai` | [Clarity AI](third_party/clarity-ai/) | Finance | Simulate fund classifications under proposed SFDR 2.0. |
| `clarivate-compumark` | [Clarivate IPOne CompuMark Trademarks](third_party/clarivate-compumark/) | Analytics | Trusted Trademark Intelligence from Clarivate CompuMark. |
| `clearstreet` | [Clear Street](third_party/clearstreet/) | Analytics | Research and Analyze Stocks and Options. |
| `cloze` | [Cloze MCP](third_party/cloze/) | Productivity | Cloze Relationship Management. |
| `cna-mcp` | [中央社新聞 CNA TAIWAN NEWS](third_party/cna-mcp/) | Analytics | 把中央社可信新聞接進你的 AI｜Taiwan CNA news, sourced answers. |
| `cometchat` | [CometChat](third_party/cometchat/) | Developer Tools | Add real-time chat, voice, and video to your app. |
| `controlplane` | [Control Plane](third_party/controlplane/) | Developer Tools | Deploy, scale, and debug cloud apps from one platform. |
| `datacamp` | [DataCamp](third_party/datacamp/) | Education | DataCamp catalog and team admin for your AI assistant. |
| `db-fa-mcp` | [D&B Finance Analytics](third_party/db-fa-mcp/) | Analytics | Commercial credit decisioning and portfolio risk workflows for AI. |
| `definely` | [Definely](third_party/definely/) | Legal | Structured contract review tools for legal teams. |
| `dext` | [Dext](third_party/dext/) | Finance | For accounting and bookkeeping firms: ask Dext about client data health, VAT and CT positions, aged debt, workflow and team capacity - across one client or your whole portfolio. Read-only. |
| `diffit` | [Diffit](third_party/diffit/) | Education | Quality, classroom-ready resources for anything. |
| `embat` | [Embat](third_party/embat/) | Finance | Ask Embat about cash, debt, payments, and accounting. |
| `fitch-solutions` | [Fitch Solutions](third_party/fitch-solutions/) | Finance | Fitch credit intelligence, inside your AI workflow. |
| `giscloud` | [GIS Cloud](third_party/giscloud/) | Analytics | Run your entire GIS workflow in plain language: maps, data, analysis, field apps, and reports. |
| `grasp` | [Grasp](third_party/grasp/) | Finance | Find, screen and analyse private-market opportunities. |
| `grasshopper-bank` | [Grasshopper Bank](third_party/grasshopper-bank/) | Finance | Query and analyze your financial data. |
| `hubstaff` | [Hubstaff](third_party/hubstaff/) | Productivity | AI-ready workforce insights. |
| `infobip-message` | [Infobip Message](third_party/infobip-message/) | Communication | Send SMS, RCS, MMS, and Viber messages through Infobip in Claude. |
| `instrumentl` | [Instrumentl](third_party/instrumentl/) | Nonprofit | Find, evaluate, and manage your grants. |
| `isolved` | [isolved People Cloud](third_party/isolved/) | Productivity | Your isolved data, inside Claude. |
| `iubenda` | [iubenda: Privacy policy & cookie banner](third_party/iubenda/) | Developer Tools | GDPR and CCPA compliance: cookie consent, cookie scanner, and terms and conditions. |
| `jupiterone` | [JupiterOne](third_party/jupiterone/) | Analytics | Ask questions about your JupiterOne agentic security and it asset graph and manage alerts, rules, and dashboards — in natural language. |
| `jus-mundi` | [Jus AI by Jus Mundi (Light Mode)](third_party/jus-mundi/) | Legal | AI-powered global arbitration intelligence. |
| `ketryx` | [Ketryx](third_party/ketryx/) | Productivity | Search and explore regulated software lifecycle data. |
| `kpler` | [Kpler](third_party/kpler/) | Analytics | Explore Kpler's maritime and commodities intelligence. |
| `legal-brain-agent` | [Legal Brain Agent](third_party/legal-brain-agent/) | Legal | 日本最大級の法律データベースを基盤にした、法務特化AIエージェント. |
| `legora` | [Legora](third_party/legora/) | Legal | Ask legal questions and get grounded answers with citations. |
| `light` | [Light](third_party/light/) | Finance | Work with your Light finance data in Claude. |
| `lilt` | [LILT](third_party/lilt/) | Productivity | High-quality translation with human verification. |
| `loopio` | [Loopio](third_party/loopio/) | Legal | Search approved response content, answer entire RFPs, and manage projects effortlessly. |
| `lorikeet` | [Lorikeet](third_party/lorikeet/) | Productivity | A universal concierge for complex businesses. |
| `lumonic` | [Lumonic](third_party/lumonic/) | Finance | Analyze portfolio data and reporting in Claude. |
| `manufact` | [Manufact](third_party/manufact/) | Developer Tools | Deploy and monitor MCP servers. |
| `mdn` | [MDN](third_party/mdn/) | Developer Tools | Search & retrieval of MDN docs & browser compat data. |
| `meistertask` | [MeisterTask](third_party/meistertask/) | Productivity | Create, search, and update tasks, projects, and notes. |
| `mindmeister` | [MindMeister](third_party/mindmeister/) | Education | Build, search, and edit mind maps in Claude. |
| `mulesoft` | [MuleSoft](third_party/mulesoft/) | Analytics | Govern, manage, and observe your entire Agent ecosystem. |
| `myob` | [MYOB](third_party/myob/) | Finance | Understand your MYOB business finances with Claude. |
| `nutshell-crm` | [Nutshell CRM](third_party/nutshell-crm/) | Communication | Connect Claude to Nutshell CRM to search leads, contacts, and companies, pull sales reports, and review deal timelines - all without leaving chat. |
| `onfire` | [Onfire](third_party/onfire/) | Marketing | GTM intelligence, prospecting, and buying signals. |
| `origin` | [Origin](third_party/origin/) | Analytics | See what AI agents are doing across your endpoint fleet. |
| `orion-advisor-solutions` | [Orion](third_party/orion-advisor-solutions/) | Finance | Bring Orion Connect portfolio data and Redtail CRM together in Claude — prep for client meetings, capture follow-ups, prioritize your pipeline, and turn reports into talking points. |
| `paperoffice` | [PaperOffice](third_party/paperoffice/) | Analytics | Built for companies. Ready for AI agents. The headless DMS for Claude: search, read, extract, approve, send for signing and archive documents in your own account, with your permissions. |
| `patlytics` | [Patlytics](third_party/patlytics/) | Legal | Prior art, claims, and portfolio search. |
| `paytm-for-business` | [Paytm Payment Gateway](third_party/paytm-for-business/) | Finance | Make Claude your Paytm Payments assistant. |
| `pg-aiguide` | [pg-aiguide](third_party/pg-aiguide/) | Developer Tools | Search pg and Tiger docs, learn database skills. |
| `phished` | [Phished](third_party/phished/) | Developer Tools | Phished's entire ZIR app at your fingertips directly in Claude. |
| `planday` | [Planday](third_party/planday/) | Productivity | Manage Planday scheduling (Early access). |
| `privacy` | [Privacy.com](third_party/privacy/) | Finance | Manage virtual cards and track your spending patterns. |
| `salesflare` | [Salesflare](third_party/salesflare/) | Communication | Manage and explore your CRM in Claude. |
| `squarespace` | [Squarespace](third_party/squarespace/) | Commerce | Find a domain name for your next idea, and run your Squarespace store's orders, products and customers, all from Claude. |
| `superbooks` | [SuperBooks](third_party/superbooks/) | Analytics | Financial OS for small businesses. |
| `taxact` | [TaxAct](third_party/taxact/) | Finance | Estimate your refund, and check what documents you need. |
| `tiller` | [Tiller](third_party/tiller/) | Finance | Connect to your transactions in your Tiller spreadsheet. |
| `turquoise` | [Turquoise](third_party/turquoise/) | Health | Query Turquoise's proprietary healthcare pricing data. |
| `twinmind-app` | [TwinMind](third_party/twinmind-app/) | Productivity | AI notes & Memory. |
| `unify` | [Unify](third_party/unify/) | Marketing | Find, enrich, and sequence prospects from 40+ data sources. |
| `unthread` | [Unthread](third_party/unthread/) | Productivity | Manage and automate your support tickets. |
| `usafacts-connector` | [USAFacts Government Data Connector](third_party/usafacts-connector/) | Analytics | Give Claude a better source for government data. |
| `vani` | [Vani by Zoho](third_party/vani/) | Productivity | Create diagrams, visualize workflows, and manage Spaces in Vani. |
| `veltra-activities` | [Veltra Activities](third_party/veltra-activities/) | Travel | Design the genuine experiences of tomorrow. |
| `verisk-xactrestore` | [Verisk XactRestore](third_party/verisk-xactrestore/) | Finance | Natural-language estimating for XactRestore. |
| `vertiso-memory` | [Vertiso Memory](third_party/vertiso-memory/) | Developer Tools | Portable, durable memory for every AI agent you use. |
| `vianexus-vast` | [viaNexus vAST](third_party/vianexus-vast/) | Communication | Power AI workflows with viaNexus: a financial data marketplace delivering prices, news, fundamentals, and global macro economic data directly from trusted provider partners. |
| `vuetify-mcp` | [Vuetify MCP](third_party/vuetify-mcp/) | Developer Tools | Official Vuetify docs, APIs, and bins for AI agents. |
| `wealth-com` | [Wealth.com](third_party/wealth-com/) | Analytics | Bring your clients' estate plans, tax returns, and documents into Claude — with instant snapshots, risk analysis, and advisor-ready summaries. |
| `wealthbox` | [Wealthbox](third_party/wealthbox/) | Finance | Search, update, and manage Wealthbox data from inside Claude. |
| `webmcp-evaluator` | [WebMCP Evaluator](third_party/webmcp-evaluator/) | Analytics | Get an actionable, detailed review and build plan for making any public page ready for AI agents, based on your content, not generalized advice. |
| `wetransfer` | [WeTransfer](third_party/wetransfer/) | Communication | Send files from your chat via WeTransfer — get a shareable link or email them to recipients, using your own WeTransfer account. |
| `windmill-hr` | [Windmill HR](third_party/windmill-hr/) | Analytics | Draft performance reviews, manage 1:1s, send pulses, and collect feedback in Windmill, without ever leaving Claude. |
| `windsor-social-media` | [Windsor.ai for Social Media](third_party/windsor-social-media/) | Analytics | Analyze and post organic social content across Instagram, Facebook, TikTok, YouTube, LinkedIn, and Google Business Profile. |
| `xtiles` | [xTiles](third_party/xtiles/) | Productivity | Projects that keep Claude in context. |
| `zacks-data` | [Zacks Data](third_party/zacks-data/) | Analytics | Trusted Financial Data from Zacks Investment Research. |

## Repository structure

```text
.claude-plugin/marketplace.json      generated marketplace index for Claude Code
.cursor-plugin/marketplace.json      generated marketplace index for Cursor
.boldcreate-plugin/marketplace.json  generated marketplace index for BoldCreate Connect
third_party/<name>/                  one connector per folder
  .cursor-plugin/plugin.json         hand-written source manifest
  .claude-plugin/plugin.json         generated
  .boldcreate-plugin/plugin.json     generated
  boldcreate.json                    transport, auth, hosting and endpoint check
  mcp.json                           the remote MCP server
  README.md  CHANGELOG.md  LICENSE
  assets/logo.*
schemas/                             JSON schemas for every manifest
scripts/                             build.mjs, validate.mjs, check-kit.mjs
.github/workflows/validate.yml       CI
```

## Contributing

Edit `third_party/<name>/.cursor-plugin/plugin.json`, `mcp.json` and `boldcreate.json` by hand. Never edit the generated manifests or the three marketplace indexes. Run:

```bash
npm ci
npm run build
npm run validate
```

## License

Each connector is MIT licensed. The vendor's name and logo remain the property of the vendor.
