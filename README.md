<div align="center">

# Egor Dushenko

**AI Engineer** · LLM integrations · automation · full-cycle product development

</div>

I build practical AI-powered products end-to-end — product logic, architecture, backend, LLM pipelines, payments, and deployment. I use LLMs as engineering tools to ship real products faster, not as decoration.

---

## Selected Projects

### [Alterega Platform](https://github.com/egordushenko/alterega-platform)

Architecture showcase for a commercial ecosystem of video-editing tools for Adobe Premiere Pro and After Effects, built and operated solo.

Three product lines across five builds (AEGACut plugin and desktop, AEGAPanel, AEGA Sync for Premiere and After Effects), a central licensing service, payment pipeline, storefront, and Telegram-based delivery. Actively operated in production.

Frontend case study: [Alterega Storefront](https://github.com/egordushenko/alterega-storefront) — public frontend-only showcase of the real commercial storefront, built with Next.js, React, TypeScript, Tailwind CSS, Framer Motion, Three.js / React Three Fiber, and next-intl.

**What it demonstrates:**

* full-cycle commercial product engineering as a single operator
* HWID-bound licensing core shared across five product builds
* Adobe CEP panel development with ExtendScript and Python sidecars
* Electron desktop packaging on Windows
* server-side payment confirmation pipeline (Robokassa) with Telegram and SMTP delivery
* frontend storefront architecture: multilingual catalog, product modals, SEO, motion, and 3D hero scene
* VPS operations: Nginx, systemd, PostgreSQL, GitHub Actions

**Stack:** Node.js, Fastify, Next.js, React, TypeScript, Tailwind CSS, Framer Motion, Three.js, Python, Electron, Adobe CEP, ExtendScript, PostgreSQL, ffmpeg, Linux VPS.

Website: [alterega.ru](https://alterega.ru)

---

### [Redmine AI Technical Planner](https://github.com/egordushenko/redmine-ai-technical-planner)

AI automation for engineering teams: reads a Redmine issue, resolves its Git repo, selects relevant files under a token budget, asks an LLM for an implementation plan, and posts it back. Repository-aware automation with safe handling of untrusted issue text and a Docker demo.

**Stack:** Python, Redmine REST API, OpenAI-compatible LLM API, SQLite, Docker, pytest, ruff.

---

### [goload](https://github.com/egordushenko/goload)

HTTP load-testing CLI in idiomatic Go — benchmarks a single endpoint or drives a full virtual-user flow (login, token chaining, in-flow parallel requests) with terminal/JSON/HTML reports. Concurrency by design: producer → worker pool → single-writer collector, `context`-driven cancellation, race-tested, cross-platform CI.

**Stack:** Go, Cobra, net/http, html/template, YAML, GitHub Actions.

---

### [CardBot](https://github.com/egordushenko/CardBot)

Telegram bot that generates marketplace product cards for Wildberries and Ozon sellers — SEO titles, descriptions, keywords, characteristics, and AI product images from ordinary photos plus a short prompt. Full product cycle with payments, trial logic, and a balance system; cost-optimized by combining multiple photos into one model input.

**Stack:** Python, Telegram Bot API, PostgreSQL, OpenRouter, DeepSeek, GPT Image, payment integration.

---

### [PAI Methodology](https://github.com/egordushenko/pai-methodology)

A typed knowledge-ops methodology for running a solo multi-product operation — the system that backs the Alterega platform. Typed separation between identity, applications, projects, research, stacks, and tasks; explicit source-of-truth boundaries; privacy auditing and context recovery for agent-assisted work. Operational maturity beyond product code.

**Stack:** agent-ready knowledge architecture (ISA, privacy zones, context search, instruction diet).

---

## Tech Stack

| Area | Tools |
|---|---|
| **Languages** | Go, Python, TypeScript, JavaScript |
| **AI / LLM** | OpenRouter, GPT / Claude / Gemini, GPT Image, structured output, LLM orchestration |
| **Backend** | Node.js, Fastify, Next.js, FastAPI, PostgreSQL, REST |
| **Infra** | Linux, Nginx, Docker, systemd, GitHub Actions, VPS |
| **Workflow** | Claude Code, Codex, MCP servers, agentic coding |

---

## Links

- Website — [alterega.ru](https://alterega.ru)
- Telegram — [@alterega](https://t.me/alterega)
