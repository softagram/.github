# Softagram

**Code intelligence for humans and AI agents — and the company that runs on it.**

Softagram Oy is a Finnish software company (Kempele, Oulu region, est. 2013). We build tools that give people *and* AI coding agents a structural understanding of large codebases, and we use the same technology to deliver managed [Odoo ERP](https://softagram.com/en/erp-system), [AI services](https://softagram.com/en/tekoalypalvelut) and [security testing](https://softagram.com/en/tietoturvapalvelut) to Finnish SMEs. Official Odoo partner since 2026.

## Open source

| Repository | What it is |
|---|---|
| [sgraph-mcp-server](https://github.com/softagram/sgraph-mcp-server) | Model Context Protocol server that gives Claude Code, Codex, Cursor and other AI agents architectural awareness of a codebase: dependencies, callers, change impact and structure in one call instead of file-by-file reading. Also listed on [glama.ai](https://glama.ai/mcp/servers/softagram/sgraph-mcp-server). |
| [sgraph](https://github.com/softagram/sgraph) | Python library for the sgraph model — a hierarchical graph of software structure with typed dependencies. The data model behind Softagram Analyzer. |
| [sgraph.js](https://github.com/softagram/sgraph.js) | TypeScript/JavaScript library for the same sgraph data structure. |
| [softagram-analyzer-mcp](https://github.com/softagram/softagram-analyzer-mcp) | Run Softagram code analysis in Docker and query the architectural intelligence over MCP — the self-hosted route to the same answers. |
| [goodreason-agents-setup](https://github.com/softagram/goodreason-agents-setup) | GoodReason agent topology for Claude Code: four subagents (Strategist, Architect, Implementer, Evolution) with scoped verdict authority, organised over the metaontology's eight anchors α–Ω. Installable via the plugin marketplace below. |
| [cc-search](https://github.com/softagram/cc-search) | Fast full-text search over Claude Code conversation history. |
| [claude-plugins-marketplace](https://github.com/softagram/claude-plugins-marketplace) | Softagram's plugin marketplace for Claude Code. |
| [opengrok-mcp](https://github.com/softagram/opengrok-mcp) | MCP server for querying an OpenGrok source-code index from AI agents. |

## Products and services

- **[Softagram Analyzer](https://softagram.com/en/softagram-analyzer)** — architecture visualisation and dependency/impact analysis for every pull request (GitHub, GitLab, Bitbucket, Azure DevOps, Gerrit). [On GitHub Marketplace](https://github.com/marketplace/softagram) · [Pricing](https://softagram.com/en/softagram-analyzer/pricing)
- **[MCP for AI agents](https://softagram.com/en/softagram-analyzer/mcp)** — how the analyzer feeds AI coding agents.
- **[Software audit / technical due diligence](https://softagram.com/en/software-audit)** — architecture, technical debt, security and maintainability for acquisitions and investors.
- **[Managed Odoo ERP](https://softagram.com/en/erp-system)** — implementation, custom modules, integrations, EU hosting and Finnish-language support; AI built in, security reviewed, every customisation dependency-analysed before it is written.
- **[SecureOdoo](https://softagram.com/en/secure-odoo)** — static security scanner for custom Odoo modules.
- **[Penetration testing](https://softagram.com/en/tietoturvapalvelut)** — gray-box testing by a team that reads the architecture, not only the surface.

## Why we exist

Proper change rests on thorough understanding — we organise that understanding, for people and for machines. Our founders spent years on million-line codebases at Nokia and F-Secure; the analyzer started as our own internal tooling.

🌐 [softagram.com](https://softagram.com) · ✉️ yes@softagram.com · 💼 [LinkedIn](https://www.linkedin.com/company/softagram) · 🤝 [Odoo partner profile](https://www.odoo.com/partners/softagram-oy-22963820) · 🤖 [llms.txt](https://softagram.com/llms.txt)
