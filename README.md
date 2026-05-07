<div align="center">

# Yandu

Sci-Researching. Redefined.

[![npm version](https://img.shields.io/npm/v/@yandu/yandu.svg)](https://www.npmjs.com/package/@yandu/yandu)
[![npm downloads](https://img.shields.io/npm/dm/@yandu/yandu)](https://www.npmjs.com/package/@yandu/yandu)
[![platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey)](https://github.com/yandu-app/yandu/releases)
[![stage](https://img.shields.io/badge/stage-early%20access-orange)](https://github.com/yandu-app/yandu)

</div>

---

Desktop app for reading and managing academic papers, with an integrated agent that can run experiments in sandboxed environments.

> **Early access.** Things will break. Use at your own risk.

## Install

```bash
npm install -g @yandu/yandu
yandu
```

CLI for headless / agent-driven access:

```bash
npx @yandu/cli
```

Prebuilt binaries for macOS, Windows, and Linux are on the [Releases](https://github.com/yandu-app/yandu/releases) page.

## What it does

- Papers are automatically converted to readable Markdown — tables, formulas, figures, and structure preserved (powered by [MinerU](https://github.com/opendatalab/MinerU) and [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR))
- Ask an agent questions about any paper in your library
- Agent can connect to sandboxed environments to run and iterate on experiments
- Works with OpenAI, Anthropic, Google, DeepSeek, Alibaba (Qwen), Zhipu (GLM), Moonshot (Kimi), MiniMax, Ollama, and many more via [models.dev](https://models.dev)
- Subscribe to arXiv, RSS, DBLP, Semantic Scholar feeds
- Import from Zotero
- Local-first with optional self-hosted sync
