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
