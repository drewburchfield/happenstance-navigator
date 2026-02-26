# happenstance-navigator

Research people and search your professional network using the [Happenstance](https://happenstance.ai) API. Bundles the MCP server.

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugin from the [not-my-job](https://github.com/drewburchfield/not-my-job) marketplace.

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

**Requires:** Happenstance account. `HAPPENSTANCE_API_KEY` for shell fallback only.

## Install

```
claude plugins install happenstance-navigator@not-my-job
```

## License

MIT
