<div align="center">

# developerz.ai

**AI-native developer tools, built in public.**

[Website](https://developerz.ai) · [GitHub org](https://github.com/developerz-ai) · [wurk](https://github.com/developerz-ai/wurk)

</div>

---

## Who we are

We're a small team building the infrastructure layer that lets AI coding agents
safely do real work on real systems. Every agent-driven workflow we tried kept
hitting the same wall: agents either get **too much** access (raw DB credentials,
raw SSH, unrestricted browser control — terrifying) or **too little** (no useful
access at all, so a human has to babysit every step). So we're building the
missing middle — audited, scoped, revocable access for agents — plus the
orchestration layer that runs them end-to-end, plus the everyday tools (like a
faster Sidekiq) that make all of it practical to actually ship.

Everything below is open source. We build in public: real READMEs, real
installs, real issues open for anyone to file — including the early, messy
stuff.

## What we're shipping

| Project | What it does | Stack | Stars |
|---|---|---|---|
| ⭐ **[wurk](https://github.com/developerz-ai/wurk)** | Drop-in replacement for Sidekiq + Pro + Enterprise. 100% API-compatible, free forever, meaningfully faster. Mountable Rails engine. | Ruby | ![GitHub stars](https://img.shields.io/github/stars/developerz-ai/wurk?style=flat&label=) |
| **[db-mcp-gateway](https://github.com/developerz-ai/db-mcp-gateway)** | Self-hosted MCP gateway: AI agents get audited, SSO-gated, read-only database access without ever holding a DB credential. | Rust | ![GitHub stars](https://img.shields.io/github/stars/developerz-ai/db-mcp-gateway?style=flat&label=) |
| **[mcp-ssh](https://github.com/developerz-ai/mcp-ssh)** | Remote shell + file access for AI agents over authenticated MCP-HTTP — an SSH replacement you talk to over `/mcp`. Single Rust binary, OAuth 2.1 + Basic auth, auto-backgrounding jobs with paginated logs. | Rust | ![Gits.io/github/stars/developerz-ai/mcp-ssh?style=flat&label=) |
| **[ai-task-master](https://github.com/developerz-ai/ai-task-master)** | Autonomous task orchestrator. Goal in, merged PRs out. Planner/Worker/Reviewer loop on the Vercel AI SDK + OpenRouter. | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/developerz-ai/ai-t |
| **[claude-task-master](https://github.com/developerz-ai/claude-task-master)** | Autonomous task orchestration that keeps an agent working until the goal is actually achieved. | Python | ![GitHub
stars](https://img.shields.io/github/stars/developerz-ai/claude-task-master?style=f
| **[ui-debugger-mcp](https://github.com/developerz-ai/ui-debugger-mcp)** | Autonomous UI-debugging MCP server — a fast agent drives the browser/desktop, finds bugs and visual issues, and reports
back so a coding agent can fix them. | TypeScript | ![GitHub stars](https://img.shields.io/github/stars/developerz-ai/ui-debugger-mcp?style=flat&logo=github&label=stars&color=lightgrey) |

**wurk is the most mature of the set** — if you're running Sidekiq and curious
about a faster drop-in, that's the easiest one to try today.

## Why in public

db-mcp-gateway and mcp-ssh are still early (Phase-0) — we'd rather show the
messy middle than pretend everything launched finished. Star what's useful,
open an issue if something's broken or missing, or send a PR. If you're
building agent tooling and want to compare notes, we're around.

## Also exploring

Earlier-stage / adjacent projects, not the core pitch yet but public if you're
curious: [ai-designer](https://github.com/developerz-ai/ai-designer) (chat to
redesign a page in real time, ship the code via MCP),
[claude-and-conquer](https://github.com/developerz-ai/claude-and-conquer)
(command-and-control for a pool of VPSes running Claude at scale).

## Get in touch

- 🌐 [developerz.ai](https://developerz.ai)
- 💬 [Discord](https://developerz.ai) *(invite link — add once live)*
- 🦋 [Bluesky](https://bsky.app/profile/developerzai.bsky.social)
- ✍️ [dev.to](https://dev.to/developerzai)

</div>
