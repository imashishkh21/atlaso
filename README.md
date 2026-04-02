<p align="center">
  <img src="https://github.com/imashishkh21/atlaso/blob/main/.github/icon.png?raw=true" width="128" height="128" alt="Atlaso">
</p>

<h1 align="center">Atlaso</h1>

<p align="center">
  <strong>Your AI assistant for everything.</strong><br>
  Writing, research, analysis, brainstorming, coding — one app, every task.
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

---

## What is Atlaso?

Atlaso is a desktop AI assistant built by [Emergence Labs](https://atlaso.ai). It connects to the best AI models and gives you a private, powerful workspace for:

- **Writing** — drafts, emails, documents, summaries
- **Research** — web search, analysis, fact-checking
- **Coding** — write, edit, debug code with file system access
- **Brainstorming** — ideas, outlines, mind maps
- **Analysis** — data interpretation, comparisons, recommendations

Atlaso runs locally on your machine and connects to AI models through your own API keys (BYOK) or through built-in providers.

## Download

| Platform | Download |
|----------|----------|
| **macOS** (Apple Silicon + Intel) | [Download DMG](https://github.com/imashishkh21/atlaso/releases/latest) |
| **Windows** | Coming soon |
| **Linux** | Coming soon |

> **Note:** macOS builds are currently unsigned. On first launch, right-click the app and select "Open", then click "Open" in the dialog.

## Features

- **Multi-model support** — use Claude, GPT, Gemini, and more through Vercel AI Gateway or OpenRouter
- **Pulses** — rich content blocks (documents, code, diagrams, tables, canvases) that live alongside your conversations
- **File system access** — read, write, edit files and run commands in your local workspace
- **MCP support** — connect external tools via Model Context Protocol
- **Tabs and sessions** — organize your work across multiple contexts
- **Memory** — Atlaso remembers your preferences and project context across sessions
- **Web search** — built-in web search and content fetching
- **Privacy first** — your data stays on your machine, API keys stored in OS keychain

## How It Works

Atlaso is a lightweight desktop app (built with [Tauri](https://tauri.app)) that connects to the Atlaso Engine — our AI orchestration server. The engine handles model routing, multi-agent coordination, and tool execution.

```
┌─────────────────┐         ┌─────────────────┐
│  Atlaso Desktop  │ ──wss──▶│  Atlaso Engine   │──▶ AI Models
│  (your machine)  │◀────────│  (cloud server)  │──▶ Web Search
└─────────────────┘         └─────────────────┘
```

Your conversations, files, and preferences stay local. The engine only sees what you send in each message.

## Feedback & Issues

- **Bug reports:** [Open an issue](https://github.com/imashishkh21/atlaso/issues/new?template=bug_report.yml)
- **Feature requests:** [Open an issue](https://github.com/imashishkh21/atlaso/issues/new?template=feature_request.yml)
- **General feedback:** Use the feedback button in the app (bottom-left)

## Built by Emergence Labs

Atlaso is built by [Emergence Labs](https://atlaso.ai) — a research-driven company exploring adaptive AI coordination.

Our core discovery: **coordination timing matters more than coordination itself.** Agents that explore independently first, then coordinate once real information exists, consistently outperform both always-coordinated and never-coordinated approaches.

This "warm start" principle is baked into Atlaso's multi-agent architecture.

---

<p align="center">
  <sub>Made with care by Emergence Labs</sub>
</p>
