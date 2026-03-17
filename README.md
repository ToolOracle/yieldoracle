# YieldOracle — DeFi Yield Intelligence MCP Server

> Top yields, risk-adjusted APY, stablecoin safe havens, RWA yields, protocol comparison — powered by 19,000+ DeFi pools via DeFiLlama.

**Part of [ToolOracle](https://tooloracle.io) — AI-Native MCP Tools for Professionals**

## Connect in 30 seconds

```bash
npx -y mcp-remote https://tooloracle.io/yield/mcp/
```

**Claude Desktop**:
```json
{
  "mcpServers": {
    "yieldoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/yield/mcp/"]
    }
  }
}
```

## 8 Tools

| Tool | Credits | Description |
|------|---------|-------------|
| `top_yields` | 2 | Highest APY pools across all chains, filter by TVL/chain/stablecoin |
| `yield_scan` | 1 | Deep scan: APY breakdown (base+reward), TVL, risk, IL exposure |
| `stablecoin_yield` | 2 | Safe stablecoin yields ranked, filtered for sustainability |
| `rwa_yield` | 2 | Tokenized treasury & RWA yields (Ondo, BlackRock, Maple etc.) |
| `risk_adjusted` | 3 | APY minus risk = real expected return, ranked smart |
| `chain_yields` | 2 | Best yields on a specific chain with stats |
| `yield_compare` | 3 | Two protocols side by side: avg APY, TVL, pools |
| `health_check` | 0 | Server status, pool count, chain count |

## Data

- **19,000+ pools** across 100+ chains and 500+ protocols
- **Source**: DeFiLlama Yields API (free, no key required)
- **Updates**: Real-time with 5-minute cache
- **RWA tracking**: Ondo, BlackRock, Mountain Protocol, Maple, Centrifuge, Goldfinch, and more

## Risk-Adjusted Scoring

Every pool gets a risk score (0-100) based on:
- APY sustainability (>500% = critical, >100% = high)
- TVL depth (<$100K = warning, >$100M = strong)
- Impermanent loss exposure
- APY volatility (sigma)
- Stablecoin status (lower risk)

**Risk-adjusted APY** = Raw APY × (1 - risk_score/100)

## Pricing

Credits shared across all ToolOracle products: Free (50/mo) | Starter $49 (500) | Pro $149 (2K) | Agency $349 (6K)

## Links

- [ToolOracle Platform](https://tooloracle.io)
- [RankOracle (SEO)](https://github.com/ToolOracle/rankoracle)
- [ShopOracle (E-Commerce)](https://github.com/ToolOracle/shoporacle)
- [MemeOracle (Memecoin)](https://github.com/ToolOracle/memeoracle)
- [SmartMoneyOracle (Whale Flows)](https://github.com/ToolOracle/smartmoneyoracle)
