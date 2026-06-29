# Kalshi Nightly Research Brief — 2026-06-29

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-29T02:04:26, run time 196.5s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
## 3. GitHub Repos (Recently Updated)
- **[Masdunn4/North-Pointe-Capital-Kalshi](https://github.com/Masdunn4/North-Pointe-Capital-Kalshi)** ⭐ 1 · HTML _(updated 2026-06-29)_
  Kalshi Futures Trading Bot

- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1931 · TypeScript _(updated 2026-06-29)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[anglil/kalshi-ai-trading-bot](https://github.com/anglil/kalshi-ai-trading-bot)** ⭐ 6 · Python _(updated 2026-06-29)_
  AI-powered Kalshi prediction market trading bot using Gemini

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-29)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-29)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[TexasCoding/kalshi-python-sdk](https://github.com/TexasCoding/kalshi-python-sdk)** ⭐ 1 · Python _(updated 2026-06-28)_
  Professional Python SDK for the Kalshi prediction markets API

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 2 · Python _(updated 2026-06-29)_
  Polymarket Trade Bot

- **[Axiom-Projects/polymarket-dashboard](https://github.com/Axiom-Projects/polymarket-dashboard)** ⭐ 1 · HTML _(updated 2026-06-29)_
  Mobile P&L dashboard for Polymarket trading bots

- **[Casiniza/polymarket-bot](https://github.com/Casiniza/polymarket-bot)** ⭐ 2 · Python _(updated 2026-06-29)_
  Automated Polymarket trading bot with GitHub Actions

- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1931 · TypeScript _(updated 2026-06-29)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[baiqiefan/Python-Arbitrage](https://github.com/baiqiefan/Python-Arbitrage)** ⭐ 0 · Python _(updated 2026-06-29)_
  A small Python Arbitrage between prediction markets 

- **[Trum3it/polymarket-arbitrage-bot](https://github.com/Trum3it/polymarket-arbitrage-bot)** ⭐ 36 · TypeScript _(updated 2026-06-29)_
  Polymarket arbitrage bot - automated prediction market trading and opportunity detection. Work on crypto prediction markets. Subscribe BTC, ETH, SOL, XRP price tick and real time analyse. Make decisio

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-27)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[jhunter11/openclaw-kalshi-operator](https://github.com/jhunter11/openclaw-kalshi-operator)** ⭐ 0 · HTML _(updated 2026-06-26)_
  Autonomous AI agent operating an event-contract research & trading loop (Kalshi). Python research/orchestration harness + strategy gates + learning log.

- **[aasuper1/kalshi-alpha-strategies](https://github.com/aasuper1/kalshi-alpha-strategies)** ⭐ 0 · Python _(updated 2026-06-19)_
  Three independent Kalshi event-contract trading strategies: latency (sell-worthless), liquidity-incentive market making, and a cross-market/correlation engine.

## 4. Perplexity Strategy Synthesis
The most actionable strategies for small accounts ($50–$500) on Kalshi and Polymarket in 2026 center on **cross-venue arbitrage** on wide gaps (5¢+), **domain-expertise trading** in niche markets, and **copy/mirror trading** using on-chain transparency, rather than complex "tail decay harvesting" or "convergence plays" which typically require institutional capital[3].

### 1. Cross-Venue Arbitrage (Lowest Risk for Small Accounts)
This is the primary profit engine for small wallets, exploiting structural mispricing between the regulated (Kalshi) and non-custodial (Polymarket) platforms.
*   **Strategy Parameters:**
    *   **Time Horizon:** Intraday; execute only when major news creates immediate gaps[3].
    *   **Price Thresholds:** Target wide gaps of **≥5¢ (5%)** to ensure profits after fees on both legs[3].
    *   **Position Sizing:** Allocate **1–5%** of your bankroll per idea (e.g., $5–$25 on a $500 account) to manage "impossible event" risk[3].
    *   **Execution:** Buy "YES" on the lower-priced venue (e.g., Polymarket at 10.3¢) and simultaneously buy "NO" on the higher-priced venue (e.g., Kalshi at 14¢), locking in a net cost of ~96.8¢ for a $1 payout[2].
*   **Critical Checklist:** Verify real book depth behind headline prices, calculate fee math for both legs, and confirm identical resolution criteria before entering[3].

### 2. Domain-Expertise Trading (Highest Edge Source)
Small accounts can outperform algorithms by leveraging personal knowledge in niche categories where the crowd lacks depth.
*   **Strategy Parameters:**
    *   **Time Horizon:** Medium-term (weeks); requires 5–10 hours/week of research[3].
    *   **Starting Capital:** Works with **$50+**[3].
    *   **Edge Source:** You know a niche better than the crowd (e.g., specific crypto protocol outcomes, local sports, or regional politics)[3].
    *   **Method:** Size positions as a small fixed fraction of your bankroll; avoid over-leveraging on single ideas[3].

### 3. Copy / Mirror Trading (Low-Medium Risk)
Utilize on-chain transparency to replicate the trades of proven winners.
*   **Strategy Parameters:**
    *   **Time Horizon:** Short-to-medium; requires 2–4 hours/week[3].
    *   **Starting Capital:** **$100+**[3].
    *   **Edge Source:** On-chain transparency allows you to overlay a trader's exact entry/exit points and entry logic onto price charts[2][4].
    *   **Automation:** Optional; manual execution is often safer for beginners to avoid "racing" failures[3].

### 4. What to Avoid or Approach Carefully
*   **Tail Decay Harvesting & Convergence Plays:** These strategies often require "portfolio theory" and "Kelly formula" sizing, which are typically executed by pro traders with analyst teams and higher capital buffers to hedge with options[1]. Small accounts may lack the liquidity to absorb the volatility of these strategies.
*   **News & AI-Assisted Trading:** While viable, it requires 3–8 hours/week and carries "Information processing" risk; AI should be used to *structure* probability (base rates, resolution sources) but never as a direct trade trigger to avoid hallucination losses[3].

### Platform Context for 2026
*

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-29 via Conway's auto-publisher.*
