<div align="center">

# 🧩 Awesome MCP by Vertical

**Production-grade [Model Context Protocol](https://modelcontextprotocol.io) servers, curated by industry — not by tech category.** Skip the 20,000-server noise; find the ones that matter for *your* use case.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Docs](https://img.shields.io/badge/docs-EN%20%2B%20ES-orange.svg)](es/README.md)

[English](README.md) · [Español](es/README.md)

</div>

---

## Why this list

Every other MCP directory sorts by *technical* category — "databases", "dev tools" — and lists everything, including thousands of abandoned toy servers. If you're building an agent for a **real business**, you think in verticals: *"I run a store, what do I connect?"*

This list answers that. Each vertical gives you the **mature, mostly official** servers worth connecting, with a link and a one-line description. `[official]` = maintained by the vendor or the MCP project; `[community]` = active third-party.

> ⚠️ Ecosystems move fast — verify a server's repo and permissions before wiring it into production. PRs to fix or add welcome.
>
> Maintained by [@JohnnyFerranteTech](https://github.com/JohnnyFerranteTech). Useful? A ⭐ helps other builders find it.

---

## Contents
- [💳 Fintech & Payments](#-fintech--payments)
- [🗄️ Data & Databases](#-data--databases)
- [🛠️ Dev & DevOps](#-dev--devops)
- [💬 Communication & Productivity](#-communication--productivity)
- [🔎 Search & Web](#-search--web)
- [🛒 Retail & E-commerce](#-retail--e-commerce)
- [📈 Marketing & CRM](#-marketing--crm)
- [☁️ Cloud & Infra](#-cloud--infra)

---

## 💳 Fintech & Payments

| Server | Source | | What it does |
|---|---|---|---|
| Stripe | [stripe/agent-toolkit](https://github.com/stripe/agent-toolkit) | `official` | Payments, payment links, customers, products (`mcp.stripe.com`) |
| PayPal | [paypal.ai MCP](https://www.paypal.ai/) | `official` | Create invoices, manage and complete payments |
| Plaid | [plaid.com](https://plaid.com/) | `official` | Connect bank accounts, fetch transactions and balances |
| QuickBooks | [Intuit](https://developer.intuit.com/) | `official` | Invoicing, bookkeeping, financial reports |
| Supabase | [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) | `official` | Postgres backend often used for fintech ledgers |

## 🗄️ Data & Databases

| Server | Source | | What it does |
|---|---|---|---|
| Postgres (Pro) | [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) | `community` | Configurable read/write + performance analysis |
| MongoDB | [mongodb-js/mongodb-mcp-server](https://github.com/mongodb-js/mongodb-mcp-server) | `official` | MongoDB + Atlas: CRUD and queries |
| Supabase | [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) | `official` | Query/write Postgres, manage tables and config |
| MySQL | [awslabs/mcp](https://github.com/awslabs/mcp) | `official` | Managed MySQL access (AWS Labs) |
| ClickHouse | [ClickHouse](https://github.com/ClickHouse) | `community` | OLAP analytical queries |
| Filesystem | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) | `official` | Safe local file operations with access controls |

## 🛠️ Dev & DevOps

| Server | Source | | What it does |
|---|---|---|---|
| Git | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers/tree/main/src/git) | `official` | Read, search and manipulate Git repositories |
| GitHub | [github/github-mcp-server](https://github.com/github/github-mcp-server) | `official` | Interact with the GitHub API |
| Sentry | [getsentry/sentry-mcp](https://github.com/getsentry/sentry-mcp) | `official` | Error tracking, issues, events (`mcp.sentry.dev`) |
| Kubernetes | [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) | `community` | Interact with Kubernetes / OpenShift clusters |
| DevOps toolkit | [rohitg00/awesome-devops-mcp-servers](https://github.com/rohitg00/awesome-devops-mcp-servers) | `community` | Curated DevOps-specific MCP list |

## 💬 Communication & Productivity

| Server | Source | | What it does |
|---|---|---|---|
| Notion | [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) | `official` | Docs, databases, blocks, comments, files |
| Slack | [Anthropic plugins](https://github.com/anthropics/claude-plugins-official) | `official` | Post, read, and manage Slack workspaces |
| Linear | [linear.app](https://linear.app/docs/mcp) | `official` | Issues, projects, milestones (`mcp.linear.app`) |
| Google Workspace | [Google](https://developers.google.com/workspace) | `official` | Gmail, Calendar, Drive, Docs in one server |

## 🔎 Search & Web

| Server | Source | | What it does |
|---|---|---|---|
| Brave Search | [brave/brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server) | `official` | Web, local, image, video and news search |
| Playwright | [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) | `official` | Browser automation via accessibility snapshots |
| Fetch | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) | `official` | Fetch a URL and convert it to Markdown |
| Tavily | [tavily.com](https://tavily.com/) | `official` | Search API optimized for research + citations |
| Exa | [exa.ai](https://exa.ai/) | `official` | Semantic, AI-first web search |

## 🛒 Retail & E-commerce

| Server | Source | | What it does |
|---|---|---|---|
| Shopify Storefront | [Shopify](https://shopify.dev/docs/api/storefront) | `official` | GraphQL Storefront: products, cart, search, policies |
| Shopify Admin | [GeLi2001/shopify-mcp](https://github.com/GeLi2001/shopify-mcp) | `community` | Full Shopify Admin API access |
| Shopify Dev | [Shopify](https://shopify.dev/) | `official` | Shopify API docs and dev resources |

## 📈 Marketing & CRM

| Server | Source | | What it does |
|---|---|---|---|
| FirstSales MCP | [FirstSales](https://developer.firstsales.io/agents/mcp-server) | `official` | Read CRM contacts, deals, lists and workflows; create contacts via hosted OAuth MCP (eligible paid plan) |
| HubSpot | [HubSpot](https://developers.hubspot.com/) | `official` | CRM read/write: contacts, deals, tickets, analytics |
| Salesforce | [Salesforce](https://www.salesforce.com/) | `official` | Create/update/delete CRM records |
| Jira | [Atlassian](https://www.atlassian.com/) | `official` | Project management, issues, sprints |
| Google Analytics 4 | [Google](https://developers.google.com/analytics) | `community` | GA4 reporting and analytics data |
| Google Ads | [Google](https://developers.google.com/google-ads/api) | `community` | Campaign management and performance data |

## ☁️ Cloud & Infra

| Server | Source | | What it does |
|---|---|---|---|
| AWS | [awslabs/mcp](https://github.com/awslabs/mcp) | `official` | Official AWS suite: CloudWatch, IAM, Serverless, Aurora, more |
| Cloudflare | [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) | `official` | Workers, DNS, Radar, Observability, Security |
| Azure | [microsoft/mcp](https://github.com/microsoft/mcp) | `official` | Manage Azure resources |
| Vercel | [vercel.com](https://vercel.com/docs/mcp) | `official` | Deploy and manage Vercel / Next.js projects |

---

## How to use this list

1. Find your vertical.
2. Prefer `official` servers; treat `community` ones as "verify before trusting."
3. Before production: check the repo is active, read what **permissions/scopes** the server asks for, and apply least privilege.
4. Building the agent that *uses* these? See the [Claude Agents Cookbook](https://github.com/JohnnyFerranteTech/claude-agents-cookbook) for ready recipes, and [LLM Security Payloads](https://github.com/JohnnyFerranteTech/llm-security-payloads) to harden them.

## Contributing

Add a real, maintained server to the right vertical — one line, with a working link and an
honest `official`/`community` tag. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT](LICENSE).
