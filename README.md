<p align="center">
  <img src="https://github.com/imashishkh21/atlaso/blob/main/.github/icon.png?raw=true" width="128" height="128" alt="Atlaso">
</p>

<h1 align="center">Atlaso</h1>

<p align="center">
  <strong>We studied how AI agents coordinate. Then we built what we learned.</strong><br>
  More communication made AI agents worse. Knowing <em>when</em> to start made them the best.<br>
  The result is Atlaso — an AI assistant built on this principle.
</p>

<p align="center">
  <a href="https://github.com/imashishkh21/atlaso/releases/latest">
    <img src="https://img.shields.io/github/v/release/imashishkh21/atlaso?label=Download&style=flat-square" alt="Download">
  </a>
  <a href="https://github.com/imashishkh21/atlaso/releases/latest">
    <img src="https://img.shields.io/github/downloads/imashishkh21/atlaso/total?style=flat-square&label=Downloads" alt="Downloads">
  </a>
  <a href="https://github.com/imashishkh21/atlaso/issues">
    <img src="https://img.shields.io/github/issues/imashishkh21/atlaso?style=flat-square" alt="Issues">
  </a>
</p>

<p align="center">
  <a href="https://atlaso.ai">Website</a> · <a href="https://atlaso.ai/research">Research</a> · <a href="https://atlaso.ai/product">Product</a> · <a href="https://doi.org/10.5281/zenodo.19436476">Paper</a>
</p>

---

## What is Atlaso?

Atlaso is a general-purpose AI assistant — writing, research, analysis, brainstorming, coding, and everything in between. Built by [Emergence Labs](https://atlaso.ai) on adaptive coordination research.

**No account needed. No subscription. Your models, your keys, your machine.**

## Download

| Platform | Download |
|----------|----------|
| **macOS** (Apple Silicon + Intel) | [Download DMG](https://github.com/imashishkh21/atlaso/releases/latest) |
| **Windows** | [Download Installer](https://github.com/imashishkh21/atlaso/releases/latest) |
| **Linux** | [Download AppImage](https://github.com/imashishkh21/atlaso/releases/latest) |

## Features

- **Multi-model support** — use Claude, GPT, Gemini, and more
- **Pulses** — rich content blocks that turn conversations into deliverables:
  - **Documents** — markdown with full formatting, diagrams, and export
  - **Code** — multi-file editing with syntax highlighting across 50+ languages
  - **Tables** — interactive, sortable, filterable data views
  - **Diagrams** — flowcharts, sequence diagrams, state machines, architecture views
  - **Canvas** — live interactive HTML/CSS/JS visualizations and dashboards
- **File system access** — read, write, edit files and run commands in your local workspace
- **MCP support** — connect external tools via Model Context Protocol
- **Web search** — built-in web search and content fetching
- **Memory** — remembers your preferences and project context across sessions
- **Privacy first** — your data stays on your machine, API keys stored in OS keychain

Ask for a comparison — get an interactive table. Ask for architecture — get a diagram. Ask for a dashboard — get a live canvas.

## How It Works

Atlaso is a lightweight desktop app (built with [Tauri](https://tauri.app)) that connects to the Atlaso Engine — our AI orchestration server. The engine handles model routing, multi-agent coordination, and tool execution.

```
┌─────────────────┐         ┌─────────────────┐
│  Atlaso Desktop  │ ──wss──▶│  Atlaso Engine   │──▶ AI Models
│  (your machine)  │◀────────│  (cloud server)  │──▶ Web Search
└─────────────────┘         └─────────────────┘
```

Your conversations, files, and preferences stay local. The engine only sees what you send in each message.

## The Research

Atlaso is built on a discovery from multi-agent coordination research: shared communication channels can *harm* collective performance when activated too early. Agents read noise as signal, causing premature lock-in and degraded outcomes.

The solution is **adaptive stigmergy** — agents explore independently first, then coordinate only when real information exists.

**Key findings:**
- **+34%** improvement over always-on coordination
- **+19%** over no coordination at all
- Lowest variance across all conditions
- Validated across 481 LLM runs and 20 RL experiments

> *Don't coordinate until there is something worth coordinating about — and regulate how long the channel stays open, because errors propagate faster than corrections.*

Read the full paper: **[When to Start Communicating: Adaptive Stigmergy Gates Improve Multi-Agent RL Training Dynamics](https://doi.org/10.5281/zenodo.19436476)**

## Feedback & Issues

- **Bug reports:** [Open an issue](https://github.com/imashishkh21/atlaso/issues/new?template=bug_report.yml)
- **Feature requests:** [Open an issue](https://github.com/imashishkh21/atlaso/issues/new?template=feature_request.yml)
- **General feedback:** Use the feedback button in the app

## Built by Emergence Labs

[Emergence Labs](https://atlaso.ai) — independent AI research and engineering.

- Website: [atlaso.ai](https://atlaso.ai)
- Research: [atlaso.ai/research](https://atlaso.ai/research)
- Paper: [DOI 10.5281/zenodo.19436476](https://doi.org/10.5281/zenodo.19436476)
- Contact: [ashishkhandelwal054@gmail.com](mailto:ashishkhandelwal054@gmail.com)

---

<p align="center">
  <sub>Made with care by Emergence Labs</sub>
</p>
