<div align="center">

# Terraphim AI

<img src="https://raw.githubusercontent.com/terraphim/terraphim.ai/main/static/images/terraphim_logo_gray.png" alt="Terraphim AI" width="180" />

**United Kingdom** · Privacy-preserving AI assistant · Applied Knowledge Systems Ltd

![Rust](https://img.shields.io/badge/-Rust-2b2b2b?style=flat-square&logo=rust&logoColor=dea584)
![WebAssembly](https://img.shields.io/badge/-WebAssembly-2b2b2b?style=flat-square&logo=webassembly&logoColor=654FF0)
![Tauri](https://img.shields.io/badge/-Tauri-2b2b2b?style=flat-square&logo=tauri&logoColor=24C8D8)
![TypeScript](https://img.shields.io/badge/-TypeScript-2b2b2b?style=flat-square&logo=typescript&logoColor=3178C6)
![Claude](https://img.shields.io/badge/-Claude-2b2b2b?style=flat-square&logo=anthropic&logoColor=d4a27f)

*Local-first knowledge graph search engine in Rust and WebAssembly. Your data never leaves your machine.*

![Public Repos: 66](https://img.shields.io/static/v1?label=Public+Repos&message=66&color=2b2b2b&style=flat-square&logo=github&logoColor=white)
![Workspace Crates: 52+](https://img.shields.io/static/v1?label=Workspace+Crates&message=52%2B&color=2b2b2b&style=flat-square&logo=rust&logoColor=white)
![Search Latency: < 1 ms](https://img.shields.io/static/v1?label=Search+Latency&message=%3C+1+ms&color=2b2b2b&style=flat-square&logo=zap&logoColor=white)
![Telemetry: Zero](https://img.shields.io/static/v1?label=Telemetry&message=Zero&color=2b2b2b&style=flat-square&logo=shield&logoColor=white)
![Latest Release](https://img.shields.io/github/v/release/terraphim/terraphim-ai?style=flat-square&color=2b2b2b&logo=github&logoColor=white)

[![Website](https://img.shields.io/badge/terraphim.ai-2b2b2b?style=flat-square&logo=google-chrome&logoColor=white)](https://terraphim.ai)
[![Docs](https://img.shields.io/badge/docs.terraphim.ai-2b2b2b?style=flat-square&logo=readthedocs&logoColor=white)](https://docs.terraphim.ai)
[![Rust](https://img.shields.io/badge/terraphim.rs-2b2b2b?style=flat-square&logo=rust&logoColor=white)](https://terraphim.rs)
[![Discourse](https://img.shields.io/discourse/users?server=https%3A%2F%2Fterraphim.discourse.group&style=flat-square&logo=discourse&logoColor=white&label=Discourse)](https://terraphim.discourse.group)
[![Discord](https://img.shields.io/discord/852545081613615144?style=flat-square&label=Discord&logo=discord&logoColor=white&color=5865F2)](https://discord.gg/VPJXB6BGuY)
[![Reddit](https://img.shields.io/badge/r%2FTerraphimAI-2b2b2b?style=flat-square&logo=reddit&logoColor=FF4500)](https://www.reddit.com/r/TerraphimAI)

`Local-First Search` · `Knowledge Graphs` · `Rust + WASM` · `MCP Server` · `Privacy by Design` · `Agent Hooks`

</div>

<p align="center">
<a href="#what-is-terraphim">What is Terraphim</a> · <a href="#flagship-projects">Flagship</a> · <a href="#quick-install">Install</a> · <a href="#ecosystem">Ecosystem</a> · <a href="#community">Community</a> · <a href="#about">About</a> · <a href="#connect">Connect</a>
</p>

> [!NOTE]
> **Sub-millisecond search, zero telemetry, no account required.** Terraphim matches thousands of knowledge-graph patterns in a single pass using Aho-Corasick automata — on your hardware, never in our cloud.

---

## What is Terraphim?

**Terraphim** is a privacy-preserving AI assistant that works for you under your complete control. It starts as a local search engine over role-based knowledge graphs — personal notes (Obsidian, Logseq, Markdown), team systems (Jira, Confluence), code (grepapp), and email — and grows into an exocortex that runs entirely on your infrastructure.

- **Local-first architecture** — indexing, search, and graph traversal happen on-device. No cloud dependency, no exfiltration.
- **Knowledge graph engine** — role-configured thesauri with Aho-Corasick multi-pattern matching; every match traces back to a concept.
- **Graph embeddings** — deterministic, explainable ranking. No neural vectors, no GPUs.
- **MCP server** — first-class integration with Claude Code, Codex, and other AI coding assistants.
- **Hooks system** — deterministic context injection for agentic coding workflows.
- **Eight deployment targets** — CLI, desktop (Tauri), HTTP server, MCP server, browser extension (WASM), Node.js, Python, edge/embedded.

---

## Flagship Projects

| Project | Stars | Lang | Purpose |
|:--------|:-----:|:----:|:--------|
| [**terraphim-ai**](https://github.com/terraphim/terraphim-ai) | ![Stars](https://img.shields.io/github/stars/terraphim/terraphim-ai?style=flat-square&logo=github&logoColor=white) | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white) | The engine: deterministic AI assistant with local-first KG search, MCP server, CLI, and HTTP server — 52+ workspace crates |
| [**terraphim-ai-desktop**](https://github.com/terraphim/terraphim-ai-desktop) | ![Stars](https://img.shields.io/github/stars/terraphim/terraphim-ai-desktop?style=flat-square&logo=github&logoColor=white) | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white) | Privacy-first desktop application built with Tauri |
| [**md-book**](https://github.com/terraphim/md-book) | ![Stars](https://img.shields.io/github/stars/terraphim/md-book?style=flat-square&logo=github&logoColor=white) | ![HTML](https://img.shields.io/badge/-HTML-E34F26?style=flat-square&logo=html5&logoColor=white) | Rust documentation can be pretty — the engine behind docs.terraphim.ai |
| [**terraphim-liquid-glass-terminal**](https://github.com/terraphim/terraphim-liquid-glass-terminal) | ![Stars](https://img.shields.io/github/stars/terraphim/terraphim-liquid-glass-terminal?style=flat-square&logo=github&logoColor=white) | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white) | Terminal emulator with liquid glass design effects, Rust/Tauri |
| [**Terraphim Skills**](https://terraphim-skills.md) | — | — | Discover, install, and publish skills for any AI coding agent |
| [**terraphim-firecracker**](https://github.com/terraphim/terraphim-firecracker) | ![Stars](https://img.shields.io/github/stars/terraphim/terraphim-firecracker?style=flat-square&logo=github&logoColor=white) | ![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) | Firecracker VM tooling for the Terraphim Private Cloud |

### Quick Install

> [!TIP]
> ```bash
> # macOS / Linux
> brew tap terraphim/terraphim && brew install terraphim-grep terraphim-agent
> # or via Cargo
> cargo install terraphim_grep --locked
> cargo install terraphim_agent --locked
> # or one-liner
> curl -fsSL https://raw.githubusercontent.com/terraphim/terraphim-ai/main/scripts/install.sh | bash
> ```
> Full guide: [terraphim.ai/docs/installation](https://terraphim.ai/docs/installation)

---

## Ecosystem

| Project | What it is |
|:--------|:-----------|
| [**terraphim.ai**](https://github.com/terraphim/terraphim.ai) | Project website — [terraphim.ai](https://terraphim.ai) |
| [**VS Code extension**](https://github.com/terraphim/terraphim-ai/blob/main/vs-code-terraphim-it/README.md) | VS Code extension for Terraphim search, in terraphim-ai |
| [**zed-terraphim**](https://github.com/terraphim/zed-terraphim) | Zed editor extension |
| [**Browser extensions**](https://github.com/terraphim/terraphim-ai/blob/main/browser_extensions/INSTALL.md) | Browser extensions for Terraphim search, in terraphim-ai |
| [**terraphim-cursor-plugin**](https://github.com/terraphim/terraphim-cursor-plugin) | Cursor skills for Terraphim search, learning, and memory |
| [**INCOSE-Systems-Engineering-Handbook**](https://github.com/terraphim/INCOSE-Systems-Engineering-Handbook) | Semantic search over the systems engineering body of knowledge |

---

## Community

<p align="center">
<a href="https://terraphim.discourse.group"><img src="https://img.shields.io/discourse/users?server=https%3A%2F%2Fterraphim.discourse.group&style=flat-square&logo=discourse&logoColor=white&label=Discourse" alt="Discourse" /></a>
<a href="https://discord.gg/VPJXB6BGuY"><img src="https://img.shields.io/discord/852545081613615144?style=flat-square&label=Discord&logo=discord&logoColor=white&color=5865F2" alt="Discord" /></a>
<a href="https://www.reddit.com/r/TerraphimAI"><img src="https://img.shields.io/badge/r%2FTerraphimAI-2b2b2b?style=flat-square&logo=reddit&logoColor=FF4500" alt="Reddit" /></a>
</p>

Long-form discussion and integration guides on **[Discourse](https://terraphim.discourse.group)**, real-time chat on **[Discord](https://discord.gg/VPJXB6BGuY)**, news and showcases on **[Reddit](https://www.reddit.com/r/TerraphimAI)**.

---

## About

Terraphim is built by **Applied Knowledge Systems Ltd**:

- Terraphim's talent digital shadow functionality was funded by **Innovate UK** (project "ATOMIC", TSB Project No: 600594)
- **2021 Platinum winner** of the Redis "Build on Redis" Hackathon — real-time NLP over medical literature (The Pattern)
- Advanced operational digital twins of aircraft networks for **Boeing** and **Rolls-Royce**
- Sensor fusion from IoT devices: LiDAR, acoustic water-flow sensors
- More at [applied-knowledge.systems](https://applied-knowledge.systems/)

> [!NOTE]
> **Why "Terraphim"?** Alex Mikhalev was inspired by Vasiliy Golovachev's *Relict* science-fiction series, where a Terraphim is an artificial intelligence living inside a space suit — part of an exocortex.

---

## Connect

[![X](https://img.shields.io/badge/-@alex__mikhalev-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/alex_mikhalev)
[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/terraphim)
[![LinkedIn](https://img.shields.io/badge/-Alex_Mikhalev-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alexmikhalev)
[![Website](https://img.shields.io/badge/-terraphim.ai-FF5722?style=flat-square&logo=google-chrome&logoColor=white)](https://terraphim.ai)
[![Email](https://img.shields.io/badge/-alex@terraphim.ai-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:alex@terraphim.ai)
