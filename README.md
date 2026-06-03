<h1 align="center">Hi, I'm Elo Lin 👋</h1>

<p align="center">
  <b>Founder · Indie Developer · Building AI & Healthcare Products</b>
</p>

<p align="center">
  <i>I build local-first AI tooling in Rust, developer productivity extensions, and<br/>
  practical agent skills — shipped as single binaries with zero telemetry.</i>
</p>

<p align="center">
  <a href="https://develolin.github.io/EvoClawSite/"><img src="https://img.shields.io/badge/Website-EvoClaw-1f6feb?style=for-the-badge" alt="EvoClaw website"></a>
  <img src="https://img.shields.io/badge/Rust-orange?style=for-the-badge&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/data-stays_local-green?style=for-the-badge" alt="local-first">
</p>

---

## 🚀 Featured Project — EvoClaw

> **A local-first, self-evolving AI agent runtime that learns from every task and grows its own skill tree.**

[**EvoClaw**](https://github.com/DevEloLin/evoclaw) is a self-evolving personal AI assistant you run on **your own machine**. It plans, runs tools, observes results, and keeps going until the job is done — then distills what it learned into a **YAML Skill** on disk, so the next similar task is shorter, cheaper, and sharper. Written in Rust as **one binary** (`evoclaw` / `evo`), ~8K LOC core, **zero telemetry**.

| | |
|---|---|
| 🦀 **Single static binary** | Rust 1.80+, zero runtime deps, sub-100ms cold start, 153 tests passing |
| 🌳 **Self-evolving Skill Tree** | five-state EWMA lifecycle (Draft → Candidate → Active → Degraded → Deprecated) |
| 🔐 **Secret-redaction barrier** | named Vault + pattern catch-all, idempotent scrub at 6 runtime boundaries |
| 💰 **Token economy** | layered caching + compression → long-task spend ≈ ⅓ of naive cost |
| 🔌 **Standards interop** | 7 ACP agents · 7 MCP servers · 17 model vendors (国内 9 + 国际 8 + local 3) |
| 🗂 **Local-first by default** | every byte of state lives under `~/.evoclaw/` — vault, agents, logs, skills |

🌐 **[develolin.github.io/EvoClawSite](https://develolin.github.io/EvoClawSite/)** · 🇨🇳 中文文档 available

---

## 🧰 What I'm Building

### 🤖 AI Agent Runtime & Ecosystem
- **[evoclaw](https://github.com/DevEloLin/evoclaw)** — Self-evolving local-first AI agent runtime *(Rust)* ⭐
- **[evoclaw-plugin-wechat](https://github.com/DevEloLin/evoclaw-plugin-wechat)** — WeChat Official Account passive-reply bridge for EvoClaw *(Rust)*
- **[EvoClawSite](https://github.com/DevEloLin/EvoClawSite)** — Official website for EvoClaw *(HTML)*
- **[homebrew-tap](https://github.com/DevEloLin/homebrew-tap)** — Homebrew tap for installing EvoClaw *(Ruby)*

### 🧩 Atlassian / Jira Products
- **[atlassian-rovo-agent-mcp](https://github.com/DevEloLin/atlassian-rovo-agent-mcp)** — Local MCP facade for Atlassian Rovo agent workflows; validates Jira / Confluence / Bitbucket Cloud *(Python)* ⭐
- **[dashboards-rich-filters-site](https://github.com/DevEloLin/dashboards-rich-filters-site)** — Marketing site for *Dashboards Rich Filters*, a premium Jira Cloud dashboard gadget on the Atlassian Marketplace *(HTML)*

### ✍️ Agent Skills
- **[skill-xiaoshuo](https://github.com/DevEloLin/skill-xiaoshuo)** — A complete Chinese-novel writing skill: 40 capabilities covering worldbuilding, serialized pacing, continuity review, and de-AI styling *(Skill)* ⭐
- **[Work-assistant-skill](https://github.com/DevEloLin/Work-assistant-skill)** — Miren Work Assistant: automated morning briefs, task planning, and daily/weekly report generation for Claude Code & OpenClaw *(Shell)* ⭐

---

## 🧠 Tech & Focus

```text
Languages   ·  Rust  ·  Python  ·  TypeScript  ·  Shell  ·  HTML/CSS
Domains     ·  AI agents  ·  LLM tooling  ·  Developer productivity  ·  Healthcare products
Principles  ·  Local-first  ·  Single-binary  ·  Zero telemetry  ·  Standards-based (ACP / MCP)
```

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DevEloLin&show_icons=true&hide_border=true&theme=tokyonight" alt="GitHub stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DevEloLin&layout=compact&hide_border=true&theme=tokyonight" alt="Top languages" height="165">
</p>

<p align="center">
  📫 Reach me at <a href="mailto:dev.elolin@gmail.com">dev.elolin@gmail.com</a>
</p>
