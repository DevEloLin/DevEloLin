<h1 align="center">Hey, I'm Elo Lin 👋</h1>

<p align="center">
  <b>Solo full-stack developer — I ship small, sharp products. Fast, cheap, and end-to-end.</b>
</p>

<p align="center">
  <a href="https://elolin.com">🌐 elolin.com</a> &nbsp;·&nbsp;
  <a href="mailto:dev.elolin@gmail.com">📫 dev.elolin@gmail.com</a>
</p>

---

Over the last couple of months I shipped **eight small products** — an AI photo app, a family health vault, a crowd-testing marketplace, a desktop design tool, a browser game platform, and a few developer tools — for **under ten dollars**, most of them quietly humming on **a Raspberry Pi in my living room**.

Here's the honest part: **building them was the easy part.** Getting people to care is the real work, and I'm still learning that one in public. So I build the boring foundation once — one account system, one billing spine, one database — and then move fast on top of it. Local-first, cheap to run, no team, no investors. I own every product from the first commit to pricing, launch, and the 2 a.m. bug report.

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare">
</p>

---

## 🏗 What I've shipped

Everything below is live, runs on one shared foundation, and is built + operated by me alone — under one login at [**elolin.com**](https://elolin.com).

| Product | What it does | Stack · Model |
|---|---|---|
| 🎨 **[PhotoAI](https://photoai.elolin.com)** | Upload a selfie → **ID photo, avatar, pet portrait or character art** in seconds, no prompt-writing. Photos are discarded the same day. | Next.js · self-hosted (Raspberry Pi) · credit packs + subscriptions |
| 🎮 **[EloGames](https://games.elolin.com)** | Instant-play web game platform, led by my self-published flagship **Lifeverse** — a life-simulator you replay across parallel worlds. | Next.js · Cloudflare · self-operated ads + cross-promo |
| 🩺 **[KinMate](https://kinmate.elolin.com)** | A private, **local-first family health vault** — keep lab reports, medical records & pet health on-device, with AI that explains them in plain language. | Flutter (iOS / Android) · on-device first |
| 🧪 **[TestHive](https://testhive.elolin.com)** | A **crowd-testing marketplace** — developers launch test campaigns, testers earn through an in-app credit economy, with shareable public reports. | Next.js · Supabase · in-app currency + commission |
| 🖥 **[Zivoe](https://zivoe.elolin.com)** | A desktop **AI industrial-design tool built to spark ideas** — turn a rough concept or reference image into product hero shots & three-view drawings. | Flutter + Rust core · offline licensing · Win / macOS |
| 🌐 **[EloLin Domains](https://domains.elolin.com)** | Claim a **free sub-domain** and manage its DNS yourself, from a simple dashboard. | Next.js · Cloudflare |
| 🔧 **[mv3migrate](https://mv3migrate.elolin.com)** | A CLI that drags Chrome extensions from **Manifest V2 → V3** — scans, applies codemods, and writes a migration report. | Node CLI · self-hosted docs |
| 🔌 **[Onrix AI](https://docs.getarriveready.com)** | An **OpenAI-compatible chat + image API** — point your existing OpenAI SDK at it and build. | Cloudflare · edge |
| 🔐 **[accounts.elolin.com](https://accounts.elolin.com)** | The **single sign-on** layer that ties the studio together — one login across every product. | Cloudflare · OAuth · session & device management |

---

## ⭐ EvoClaw — the one I open-sourced

> A local-first AI agent that **learns from every task and gets out of your way.**

Most AI assistants are amnesiacs — every session starts from zero and you re-explain the same things forever. That bugged me. [**EvoClaw**](https://github.com/DevEloLin/evoclaw) runs on your own machine, plans, runs tools, and keeps going until the job is done — then **distills what it learned into a reusable skill on disk**, so the next similar task is shorter and cheaper. One Rust binary, ~8K-LOC core, zero telemetry, everything under `~/.evoclaw/`.

<sub>🦀 single static binary · 🌳 skills that graduate through a five-state lifecycle · 🔐 secrets never leave the machine · 🔌 works across 7 ACP agents, 7 MCP servers & 17 model vendors</sub>

🌐 **[Website](https://develolin.github.io/EvoClawSite/)** · 中文文档 available · `brew install` via [homebrew-tap](https://github.com/DevEloLin/homebrew-tap)

**Also on GitHub:** [atlassian-rovo-agent-mcp](https://github.com/DevEloLin/atlassian-rovo-agent-mcp) (a sane local MCP over Atlassian Rovo) · [skill-xiaoshuo](https://github.com/DevEloLin/skill-xiaoshuo) (a 40-step Chinese-novel writing workflow) · [Work-assistant-skill](https://github.com/DevEloLin/Work-assistant-skill) (morning briefs & auto reports)

---

## 🛠 How I work

- **Fix it, don't route around it.** When a tool is slow or flaky, I'd rather rebuild it right than fight it forever. Reliability is a feature.
- **Fast & effortless.** Sub-second response, sane defaults, one command instead of ten. The best tool is the one you stop thinking about.
- **Local-first, cheap to run, no telemetry.** Your data stays on your machine; my infra bill stays near zero.
- **Ship, then listen.** Real users find the bugs I never would. I launch early and fix in public.

<sub><b>Stack</b> — Rust · Go · TypeScript · Python · Dart · SQL &nbsp;|&nbsp; Next.js · React · Tailwind · Flutter &nbsp;|&nbsp; Node · Hono · FastAPI · Axum · gRPC &nbsp;|&nbsp; Postgres · SQLite · Redis · Cloudflare D1 &nbsp;|&nbsp; Cloudflare · Docker · Linux · GitHub Actions &nbsp;|&nbsp; LLM agents · RAG · MCP / ACP</sub>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DevEloLin&show_icons=true&hide_border=true&theme=tokyonight" alt="GitHub stats" height="160">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DevEloLin&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages" height="160">
</p>

<p align="center">
  <i>Building is the easy part. If you've figured out the getting-people-to-care part — I'd love to hear how.</i><br/>
  📫 <a href="mailto:dev.elolin@gmail.com">dev.elolin@gmail.com</a>
</p>
