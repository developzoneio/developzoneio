# Trong Tran (developzoneio)

> Fullstack .NET developer — building spec-driven AI workflows · [trialtap.dev](https://trialtap.dev)

---

### Stack

![C#](https://img.shields.io/badge/C%23-ASP.NET%20Core%208-512BD4?style=flat-square&logo=dotnet)
![React](https://img.shields.io/badge/React-TypeScript-61DAFB?style=flat-square&logo=react&logoColor=000)
![Claude Code](https://img.shields.io/badge/Claude%20Code-AI%20Workflows-635bff?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?style=flat-square&logo=docker&logoColor=fff)

`C#` · `ASP.NET Core 8` · `React + TypeScript` · `Docker` · `MSSQL` · `Redis` · `EF Core` · `MediatR` · `Clean Architecture` · `CQRS`

---

### Featured

**[ck-spec-system](https://github.com/developzoneio/ck-spec-system)** — Spec-driven development workflows for Claude Code

> 9 slash commands · 5 specialized subagents · 3 cross-platform hooks · 9 templates
>
> Enforces spec-first discipline: every feature, bug fix, refactor, and performance optimization starts with a written spec and hard approval gates before any code is written.

```
/ck:feature   /ck:bug   /ck:refactor   /ck:perf   /ck:rca
/ck:spec      /ck:explore   /ck:review   /ck:setup
```

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

- Website: [trialtap.dev](https://trialtap.dev)
- GitHub: [@developzoneio](https://github.com/developzoneio)
- Tooling: Claude Code + MCP (Atlassian, Context7, GitNexus, Sequential Thinking)

---

<sub>Built with spec-first discipline · <a href="https://github.com/developzoneio/ck-spec-system">ck-spec-system</a></sub>
