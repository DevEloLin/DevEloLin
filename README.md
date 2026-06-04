<h1 align="center">Hi, I'm Elo Lin 👋</h1>

<p align="center">
  <b>Founder · Indie Developer · I build tools because the existing ones let me down.</b>
</p>

<p align="center">
  <i>Every project here started the same way: a tool I relied on was slow, clunky, buggy,<br/>
  or quietly broke at the worst moment — so I rebuilt it the way it should have worked.<br/>
  Software that's fast, that just works, and that makes the day a little easier.</i>
</p>

<p align="center">
  <a href="https://develolin.github.io/EvoClawSite/"><img src="https://img.shields.io/badge/Website-EvoClaw-1f6feb?style=for-the-badge" alt="EvoClaw website"></a>
  <img src="https://img.shields.io/badge/Rust-orange?style=for-the-badge&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/data-stays_local-green?style=for-the-badge" alt="local-first">
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

## 🧠 Tech & Focus

```text
Languages   ·  Rust  ·  Python  ·  TypeScript  ·  Shell  ·  HTML/CSS
I care about ·  reliability  ·  speed  ·  ergonomics  ·  things that just work
Domains      ·  AI agents  ·  LLM tooling  ·  developer & life productivity  ·  healthcare
Principles   ·  local-first  ·  single-binary  ·  zero telemetry  ·  standards-based (ACP / MCP)
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
