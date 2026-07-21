<h1 align="center">Hi, I'm Elo Lin 👋</h1>

<p align="center">
  <b>Full-Stack Engineer · Founder · Indie Developer — I build tools because the existing ones let me down.</b>
</p>

<p align="center">
  <i>Every project here started the same way: a tool I relied on was slow, clunky, buggy,<br/>
  or quietly broke at the worst moment — so I rebuilt it the way it should have worked.<br/>
  Software that's fast, that just works, and that makes the day a little easier.</i>
</p>

<p align="center">
  <a href="https://develolin.github.io/EvoClawSite/"><img src="https://img.shields.io/badge/Website-EvoClaw-1f6feb?style=for-the-badge" alt="EvoClaw website"></a>
  <img src="https://img.shields.io/badge/Full--Stack-5%2B_yrs-1f6feb?style=for-the-badge" alt="Full-Stack 5+ years">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/Rust-orange?style=for-the-badge&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
</p>

---

## 🧭 Why I build

I have a low tolerance for tools that fight back.

The app that takes five clicks for a one-second job. The CLI that crashes on the input it should obviously handle. The "smart" assistant that forgets everything the moment you close it. The dashboard that can't filter the one thing you actually need. These small frictions add up — they steal hours, and worse, they steal focus.

So I build the fix. My work lives at the intersection of three ideas:

- **🛠 Fix the broken workflow** — when a tool is unreliable or awkward, I'd rather rebuild it than route around it forever. Reliability is a feature.
- **⚡ Make it fast & effortless** — a tool should disappear into the task. Sub-second response, sane defaults, one command instead of ten.
- **🌱 Make daily life easier** — automate the repetitive, remember the tedious, hand back the time. The best tool is the one you stop thinking about.

The recurring principles: **local-first** (your data stays on your machine), **single-binary** (no setup tax), and **zero telemetry** (no one's watching). Tools should serve you — not the other way around.

---

## 🏢 elolin.com — my product studio

Open source is only half the story. [**elolin.com**](https://elolin.com) is the studio I run — a portfolio of shipped products across **gaming, health, SaaS, and desktop AI**, all sharing one account system ([accounts.elolin.com](https://accounts.elolin.com)). I own the whole loop: build it, price it, launch it, and keep it running.

| Product | What it does | Stack · Model |
|---|---|---|
| 🎨 **[PhotoAI](https://photoai.elolin.com)** | Upload a selfie → **ID photo, avatar, pet portrait or character art** in seconds, no prompt-writing. Photos are discarded the same day. | Next.js · self-hosted (Raspberry Pi) · credit packs + subscriptions |
| 🩺 **[KinMate](https://kinmate.elolin.com)** | A private, **local-first family health vault** — keep lab reports, medical records & pet health on-device, with AI that explains them in plain language. | Flutter (iOS / Android) · on-device first |
| 🧪 **[TestHive](https://testhive.elolin.com)** | A **crowd-testing marketplace** — developers launch test campaigns, testers earn through an in-app credit economy, with shareable public reports. | Next.js · Supabase · in-app currency + commission |
| 🖥 **[Zivoe](https://zivoe.elolin.com)** | A desktop **AI industrial-design tool built to spark ideas** — turn a rough concept or reference image into product hero shots & three-view drawings. | Flutter + Rust core · offline licensing · Win / macOS |
| 🌐 **[EloLin Domains](https://domains.elolin.com)** | Claim a **free sub-domain** and manage its DNS yourself, from a simple dashboard. | Next.js · Cloudflare |
| 🔧 **[mv3migrate](https://mv3migrate.elolin.com)** | A CLI that drags Chrome extensions from **Manifest V2 → V3** — scans, applies codemods, and writes a migration report. | Node CLI · self-hosted docs |
| 🔌 **[Onrix AI](https://docs.getarriveready.com)** | An **OpenAI-compatible chat + image API** — point your existing OpenAI SDK at it and build. | Cloudflare · edge |
| 🔐 **[accounts.elolin.com](https://accounts.elolin.com)** | The **single sign-on & identity layer** that ties the studio together — one login across every product. | Cloudflare · OAuth · session & device management |

<sub><i>Running the full loop end-to-end: product → engineering → pricing &amp; licensing → launch → growth &amp; retention.</i></sub>

---

## 🚀 Featured — EvoClaw

> **A local-first, self-evolving AI agent that learns from every task and gets out of your way.**

Most AI assistants are amnesiacs: every session starts from zero, and you re-explain the same things forever. That bugged me. [**EvoClaw**](https://github.com/DevEloLin/evoclaw) runs on **your own machine**, plans, runs tools, observes results, and keeps going until the job is done — then **distills what it learned into a reusable Skill on disk**, so the next similar task is shorter, cheaper, and sharper. One Rust binary (`evoclaw` / `evo`), ~8K LOC core, **zero telemetry**.

| | |
|---|---|
| 🦀 **Single static binary** | Rust 1.80+, zero runtime deps, sub-100ms cold start, 153 tests passing |
| 🌳 **Learns as it works** | five-state Skill lifecycle (Draft → Candidate → Active → Degraded → Deprecated) |
| 🔐 **Secrets never leave** | named Vault + pattern redaction, idempotent scrub at 6 runtime boundaries |
| 💰 **Costs ⅓ of naive** | layered caching + compression keeps long-running tasks cheap |
| 🔌 **Works with your stack** | 7 ACP agents · 7 MCP servers · 17 model vendors (国内 9 + 国际 8 + local 3) |
| 🗂 **Yours, locally** | all state lives under `~/.evoclaw/` — vault, agents, logs, learned skills |

🌐 **[develolin.github.io/EvoClawSite](https://develolin.github.io/EvoClawSite/)** · 🇨🇳 中文文档 available

---

## 🧰 What I'm Building

### 🤖 AI that remembers and gets out of the way
- **[evoclaw](https://github.com/DevEloLin/evoclaw)** — Self-evolving local-first AI agent runtime *(Rust)* ⭐
- **[evoclaw-plugin-wechat](https://github.com/DevEloLin/evoclaw-plugin-wechat)** — Talk to EvoClaw straight from a WeChat Official Account, passive-reply within WeChat's 5s deadline *(Rust)*
- **[EvoClawSite](https://github.com/DevEloLin/EvoClawSite)** — Official website for EvoClaw *(HTML)*
- **[homebrew-tap](https://github.com/DevEloLin/homebrew-tap)** — One-line install: `brew install` and you're running *(Ruby)*

### 🧩 Making clunky work tools bearable
- **[atlassian-rovo-agent-mcp](https://github.com/DevEloLin/atlassian-rovo-agent-mcp)** — A clean local MCP facade over Atlassian Rovo; validates Jira / Confluence / Bitbucket Cloud without the dashboard dance *(Python)* ⭐
- **[dashboards-rich-filters-site](https://github.com/DevEloLin/dashboards-rich-filters-site)** — *Dashboards Rich Filters*, a premium Jira Cloud gadget that finally lets you filter the thing you actually need *(Marketplace product)*

### ✍️ Skills that automate the tedious
- **[Work-assistant-skill](https://github.com/DevEloLin/Work-assistant-skill)** — Miren Work Assistant: automated morning briefs, task planning, and daily/weekly reports so you stop writing them by hand *(Claude Code & OpenClaw)* ⭐
- **[skill-xiaoshuo](https://github.com/DevEloLin/skill-xiaoshuo)** — A complete Chinese-novel writing workflow: 40 capabilities for worldbuilding, serialized pacing, continuity checks, and de-AI styling *(Skill)* ⭐

---

## 🛠 Tech Stack

<p align="center">
  <b>Full-stack engineer · 5+ years shipping production software end-to-end</b><br/>
  <i>Systems code, APIs, web, mobile &amp; desktop, data, and cloud infra — from a blank repo to a signed release.</i>
</p>

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend & APIs**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=flat-square&logo=go&logoColor=white)
![Axum](https://img.shields.io/badge/Axum-000000?style=flat-square&logo=rust&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-2B6CB0?style=flat-square)
![REST APIs](https://img.shields.io/badge/REST_APIs-02569B?style=flat-square)

**Mobile & Desktop**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-3B82F6?style=flat-square)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)

**Data & Storage**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Cloudflare D1](https://img.shields.io/badge/Cloudflare_D1-F38020?style=flat-square&logo=cloudflare&logoColor=white)

**Cloud & DevOps**

![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**AI / LLM**

![LLM Agents](https://img.shields.io/badge/LLM_Agents-6E56CF?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-0EA5E9?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![ACP](https://img.shields.io/badge/ACP-000000?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-10A37F?style=flat-square)

```text
Focus       ·  reliability · speed · ergonomics · things that just work
Domains     ·  AI agents · LLM tooling · developer & life productivity · healthcare
Principles  ·  local-first · single-binary · zero telemetry · standards-based (ACP / MCP)
```

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DevEloLin&show_icons=true&hide_border=true&theme=tokyonight" alt="GitHub stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DevEloLin&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages" height="165">
</p>

<p align="center">
  <i>If a tool wasted your time today, maybe I'll build the one that doesn't.</i><br/>
  📫 <a href="mailto:dev.elolin@gmail.com">dev.elolin@gmail.com</a>
</p>
