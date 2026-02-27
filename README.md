<div align="center">

<img src="https://ghrb.waren.build/banner?header=happenstance-navigator%20%F0%9F%A4%9D&subheader=Network%20intelligence%20with%20bundled%20MCP%20server&bg=0a1628&secondaryBg=1e3a5f&color=e8f0fe&subheaderColor=7eb8da&headerFont=Inter&subheaderFont=Inter&support=false" alt="happenstance-navigator" width="100%">

<br><br>

**Network intelligence with bundled MCP server.**

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugin from the [not-my-job](https://github.com/drewburchfield/not-my-job) marketplace.

![License](https://img.shields.io/badge/license-MIT-blue)

</div>

<br>

## What it does

Research people and search your professional network using the [Happenstance](https://happenstance.ai) API. Run compound workflows like deep search, warm intros, meeting prep, network scanning, and batch prospecting. The MCP server bundles with the plugin and auto-starts.

## Commands

| Command | What it does | Credits |
|---------|-------------|---------|
| `/happenstance` | Research a person or search your network | 1-2 |
| `/deep-search` | Search + auto-research top matches | 2+N |
| `/warm-intro` | Find who can introduce you to people at a target company | 2+ |
| `/meeting-prep` | Pre-meeting briefing: background + mutual connections + talking points | 3 |
| `/network-scan` | Compare the same search across multiple groups | 2xG |
| `/batch-prospect` | Exhaustive search with pagination and CSV/markdown export | 2+ |

## Features

- MCP server (OAuth via Clerk, no API key needed) with 7 tools
- Shell script fallback for batch/automated operations
- Credit-aware workflows with balance checks and cost estimates
- Async polling with timeout protection

## Requirements

- [Happenstance](https://happenstance.ai) account
- `HAPPENSTANCE_API_KEY` for shell fallback only

## Install

```
claude plugins install happenstance-navigator@not-my-job
```

## License

MIT
