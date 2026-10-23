# Trong Tran (developzoneio)

> Fullstack .NET developer — building spec-driven AI workflows · [developzone.dev](https://developzone.dev)

---

### Stack

![C#](https://img.shields.io/badge/C%23-ASP.NET%20Core%208-512BD4?style=flat-square&logo=dotnet)
![React](https://img.shields.io/badge/React-TypeScript-61DAFB?style=flat-square&logo=react&logoColor=000)
![Claude Code](https://img.shields.io/badge/Claude%20Code-AI%20Workflows-635bff?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?style=flat-square&logo=docker&logoColor=fff)

`C#` · `ASP.NET Core 8` · `React + TypeScript` · `Docker` · `MSSQL` · `Redis` · `EF Core` · `MediatR` · `Clean Architecture` · `CQRS`

---

### Featured

**[specwright](https://github.com/developzoneio/specwright)** — Spec-driven development for AI coding agents

[![Release](https://img.shields.io/github/v/release/developzoneio/specwright?style=flat-square)](https://github.com/developzoneio/specwright/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://github.com/developzoneio/specwright/blob/main/LICENSE)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey?style=flat-square)

> **Claude Code cannot touch your code until a spec is approved.**

Transform AI-assisted development from:

```text
Prompt → Code
```

into:

```text
Specification → Approval → Implementation → Review
```

* 14 slash commands — 6 spec-producing workflows + 8 utilities
* 6 specialized subagents with minimal tool allowlists (the reviewer has no write tools)
* 7 cross-platform guard-rail hooks — `spec-gate` denies `Edit` / `Write` at the tool layer until a spec is approved
* 10 templates
* 11 reusable skills
* Durable project memory under `.specs/`
* Stack-agnostic (.NET, Node, Python, Go, Rust) · Windows / macOS / Linux

```text
/sd:feature   /sd:bug      /sd:refactor   /sd:perf      /sd:rca       /sd:port
/sd:spec      /sd:explore  /sd:review     /sd:setup     /sd:release   /sd:adr
/sd:verify    /sd:status
```

Next on the roadmap: Codex support · GitHub Issue auto-fetch

---

### Other projects

**[.NET Migration Assessor](https://github.com/developzoneio/dotnet-migration-assessor)** — Ranked, explained migration plan from .NET Framework / .NET 8 to .NET 10

![Status: pre-alpha](https://img.shields.io/badge/status-pre--alpha-orange?style=flat-square)
![.NET 10](https://img.shields.io/badge/target-.NET%2010-512BD4?style=flat-square)
![License: Apache-2.0](https://img.shields.io/badge/license-Apache--2.0-blue?style=flat-square)

```text
your .sln  →  Roslyn code graph · facts  →  LLM · reasoning  →  ranked migration plan
```

* Facts before reasoning — every recommendation traces back to a concrete fact in the code
* Code stays local by default — only structured findings go to the model
* Leaf-first migration order, per-project blockers, effort & risk estimate
* Clean Architecture, pluggable `IMigrationReasoner`, Markdown + JSON reports
* Planned as a `dotnet` global tool: `dotnet assess ./MySolution.sln`

**[GitSwitch](https://github.com/developzoneio/GitSwitch)** — Switch Git identities (user, email, SSH key) in one command

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)

* `gsw add` / `gsw switch` profiles per repo — SSH or HTTPS, remote URLs converted automatically
* Manages one isolated block in `~/.ssh/config`, leaves the rest untouched
* Repo pattern matching + shell hook auto-detection (Bash, Zsh, PowerShell, Fish)

**[Claude Code Statusline for Windows](https://github.com/developzoneio/claude-code-statusline-windows)** — Native PowerShell statusline for Claude Code

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)

```text
admin@MY-PC D:/projects/my-app | Sonnet | Context: 25% | 5h: 50% | Weekly: 70%
```

* Model, context usage, working directory and 5h / weekly rate limits
* No `jq`, no dependencies — PowerShell parses the JSON natively

---

### What I build

- Backend APIs & microservices on ASP.NET Core with CQRS + Clean Architecture
- React frontends talking to ML/AI services via API Gateway layer
- AI-augmented dev tooling — spec systems, subagents, Claude Code workflows
- Cross-platform hook systems for enforcing code quality gates before edits

---

### Architecture principles

```
Domain → Application → Infrastructure → Presentation
  (no frameworks)   (use cases)   (EF/Redis/ext)   (API/controllers)
```

Dependency rule always points inward. Business logic never touches databases or HTTP.

---

### Connect

- Website: [developzone.dev](https://developzone.dev)
- GitHub: [@developzoneio](https://github.com/developzoneio)
- Tooling: Claude Code + MCP (Atlassian, Context7, GitNexus, Sequential Thinking)

---

<sub>Built with spec-first discipline · <a href="https://github.com/developzoneio/specwright">specwright</a></sub>
