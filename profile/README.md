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

AIUSD gives AI agents the infrastructure to execute complex trades — spot, perpetual futures, prediction markets, and conditional strategies — in one unified layer.

### Get Started

**AIUSD Core** — structured CLI tools, no platform inference cost:

```bash
npx skills add galpha-ai/aiusd-core -y -g
```

**AIUSD Pro** — managed AI agent with built-in reasoning:

```bash
npx skills add galpha-ai/aiusd-pro -y -g
```

**Or connect via MCP API:**

```typescript
tools: [{
  type: "custom",
  mcp_server: { url: "https://mcp.alpha.dev/api/mcp-hub/mcp" }
}]
```

### Open Source

| Repo | Description |
|------|-------------|
| [aiusd-core](https://github.com/galpha-ai/aiusd-core) | Trading tools and account management for AI agents |
| [aiusd-pro](https://github.com/galpha-ai/aiusd-pro) | AI-powered trading agent with built-in reasoning |

### Documentation

Full docs at [docs.aiusd.ai](https://docs.aiusd.ai)
