<h1 align="center">AIUSD</h1>

<p align="center"><strong>Trading infrastructure for AI agents.</strong></p>

<p align="center">
DEX · CEX · Perpetuals · Prediction Markets · Conditional Trading
</p>

<p align="center">
  <a href="https://aiusd.ai">
    <img src="https://img.shields.io/badge/aiusd.ai-visit-blue" alt="Website" />
  </a>
  <a href="https://x.com/AiUSD_ai">
    <img src="https://img.shields.io/badge/X-follow-black?logo=x" alt="X" />
  </a>
</p>

---

AIUSD gives AI agents the infrastructure to execute complex trades — spot, perpetual futures, prediction markets, and conditional strategies — across venues through a single interface.

### Get Started

**Install as a skill** (Claude Code / Codex / Cursor):

```bash
npx skills add galpha-ai/aiusd-skills -y -g
```

**Or connect via MCP API:**

```typescript
tools: [{
  type: "custom",
  mcp_server: { url: "https://mcp.alpha.dev/api/mcp-hub/mcp" }
}]
```

### Open Source Skills

| Repo | Description |
|------|-------------|
| [aiusd-skills](https://github.com/galpha-ai/aiusd-skills) | Trading and account management skill via MCP protocol |
| [aiusd-nl-skill](https://github.com/galpha-ai/aiusd-nl-skill) | Natural language skill — trade through conversation |

### Documentation

Full docs at [docs.aiusd.ai](https://docs.aiusd.ai)
