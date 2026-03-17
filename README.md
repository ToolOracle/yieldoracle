# YieldOracle — DeFi Yield Intelligence MCP Server

> Top yields, risk-adjusted APY, stablecoin safe havens, RWA yields, protocol comparison. 19,000+ pools, 100+ chains.

**Part of [ToolOracle](https://tooloracle.io) — Policy-enforced, tier-gated, usage-metered tool execution**

## Connect

```bash
npx -y mcp-remote https://tooloracle.io/yield/mcp/
```

## x402 Pay-per-call (autonomous agents)

```
POST https://tooloracle.io/x402/yield/mcp/
→ 402 with structured pricing → Send USDC on Base → Retry with X-PAYMENT header
```

## 8 Tools · 1 unit = $0.01

| Tool | Units | Price | Tier |
|------|-------|-------|------|
| `risk_adjusted` | 10 | $0.10 | Premium |
| `yield_compare` | 8 | $0.08 | Deep |
| `rwa_yield` | 5 | $0.05 | Deep |
| `top_yields` | 3 | $0.03 | Standard |
| `stablecoin_yield` | 3 | $0.03 | Standard |
| `chain_yields` | 3 | $0.03 | Standard |
| `yield_scan` | 2 | $0.02 | Standard |
| `health_check` | 0 | free | — |

## Risk-adjusted scoring

`risk_adjusted` calculates real expected return: APY × (1 - risk_score/100). Risk factors: APY sustainability, TVL depth, impermanent loss, APY volatility, stablecoin status.

## RWA tracking

`rwa_yield` tracks tokenized treasury and Real World Asset yields from Ondo, BlackRock, Mountain Protocol, Maple, Centrifuge, Goldfinch, and 10+ more.

## Tier gating

| Tier | Max/call | Blocked |
|------|----------|---------|
| Free ($0) | 3 units | risk_adjusted |
| Starter ($49/mo) | 8 units | — |
| Pro+ / x402 | 15 units | — |

## Data

19,000+ pools · 100+ chains · 500+ protocols · DeFiLlama Yields API (free, no key) · 5-min cache

## Links

- [ToolOracle](https://tooloracle.io) · [x402 Gateway](https://tooloracle.io/x402/)
- [RankOracle](https://github.com/ToolOracle/rankoracle) · [ShopOracle](https://github.com/ToolOracle/shoporacle) · [MemeOracle](https://github.com/ToolOracle/memeoracle) · [SmartMoneyOracle](https://github.com/ToolOracle/smartmoneyoracle)
