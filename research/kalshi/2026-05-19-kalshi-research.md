# Kalshi Nightly Research Brief — 2026-05-19

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-05-19T02:04:39, run time 168.8s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
## 3. GitHub Repos (Recently Updated)
- **[oleksandrbannick/Meridian](https://github.com/oleksandrbannick/Meridian)** ⭐ 1 · Python _(updated 2026-05-19)_
  kalshi automated trading bot with custom UI

- **[dexpoly1/polymarket-kalshi-crossplatform-arbitrage-bot](https://github.com/dexpoly1/polymarket-kalshi-crossplatform-arbitrage-bot)** ⭐ 0 · None _(updated 2026-05-19)_
  polymarket kalshi arbitrage bot polymarket kalshi arbitrage bot polymarket kalshi arbitrage bot polymarket kalshi arbitrage bot polymarket kalshi arbitrage bot polymarket kalshi arbitrage bot polymark

- **[anglil/kalshi-ai-trading-bot](https://github.com/anglil/kalshi-ai-trading-bot)** ⭐ 2 · Python _(updated 2026-05-19)_
  AI-powered Kalshi prediction market trading bot using Gemini

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-05-19)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-05-19)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[TexasCoding/kalshi-python-sdk](https://github.com/TexasCoding/kalshi-python-sdk)** ⭐ 0 · Python _(updated 2026-05-19)_
  Professional Python SDK for the Kalshi prediction markets API

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 0 · Python _(updated 2026-05-19)_
  Polymarket Trade Bot

- **[dexpoly1/polymarket-kalshi-crossplatform-arbitrage-bot](https://github.com/dexpoly1/polymarket-kalshi-crossplatform-arbitrage-bot)** ⭐ 0 · None _(updated 2026-05-19)_
  polymarket kalshi arbitrage bot polymarket kalshi arbitrage bot polymarket kalshi arbitrage bot polymarket kalshi arbitrage bot polymarket kalshi arbitrage bot polymarket kalshi arbitrage bot polymark

- **[RiekertQuant/polymarket-weather-bot-poc](https://github.com/RiekertQuant/polymarket-weather-bot-poc)** ⭐ 21 · Python _(updated 2026-05-19)_
  Paper trading bot for Polymarket weather temperature markets (POC)

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-05-19)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant)** ⭐ 1 · Python _(updated 2026-05-19)_
  Trade Kalshi prediction markets with a quantitative system designed for fee-aware position sizing and statistical arbitrage.

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-05-19)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

- **[Waike122333/Automated-Trading-Kalshi](https://github.com/Waike122333/Automated-Trading-Kalshi)** ⭐ 0 · None _(updated 2026-03-17)_
  An algorithmic trading bot for kalshi.com event contracts that automates trading strategies based on economic data, news events, weather patterns, and political markets in real-time.

- **[GitHubMaster07/Enterprise-Test-Strategy-Blueprint](https://github.com/GitHubMaster07/Enterprise-Test-Strategy-Blueprint)** ⭐ 0 · None _(updated 2026-01-17)_
  Enterprise‑grade QA Automation & Test Strategy Blueprint for UI, API, DB, Events, Contracts, CI/CD, and Non‑Functional Testing.

## 4. Perplexity Strategy Synthesis
Here’s a practical 2026-focused playbook for **Kalshi + Polymarket**. I’ll keep this centered on the four things you asked for:

1. **tail decay harvesting**
2. **cross-venue arbitrage**
3. **convergence plays**
4. **small-account edge cases ($50–$500)**

I’ll also cite the recent sources you surfaced and note where the “actionable” edge tends to come from.

---

## 1) Tail decay harvesting

This is one of the few strategies that can still work for small accounts because it relies on **time decay + overreaction**, not huge capital.

### What it is
You sell expensive “noisy tail” contracts after the market has overpaid for a low-probability outcome, then let the premium decay as the event window passes and new information doesn’t confirm the scare.

### Best settings
- **Time horizon:** 1–14 days for most event markets; sometimes 30+ days for policy or macro.
- **Best targets:** contracts in the **5–25 cent** range that got there from narrative spikes, not fundamentals.
- **Avoid:** binary outcomes with imminent hard catalysts where information can gap violently.

### Practical entry rules
Look for:
- **A fast move to the upside on weak evidence**
- **No follow-through in the real-world data**
- **Thinly justified “headline premium”**
- **Repeated failure to break through a price level**

A useful heuristic:
- If a contract trades from, say, **12c → 24c** on a headline, and the underlying event hasn’t actually improved for the “yes” side, the rerate often partially decays within hours or days.

### How to size it
For small accounts:
- Risk **1–3% of bankroll per idea**
- If account is **$100**, you can often only deploy **$5–$15** per trade after leaving room for fees/slippage.
- Prefer **multiple small positions** over one large one.

### When it works best
- Fed / CPI / jobs / GDP markets after a noisy headline
- Political or regulatory event markets where the first move is narrative-driven
- Sports-adjacent or media-driven markets with transient hype

### Important caveat
This is **not** “sell every high contract.”  
Tail decay works when:
- the market overprices a tail
- the tail probability is not being reinforced by new evidence
- you are not too close to resolution

If you’re too close to the event, decay can vanish and jump risk dominates.

### Sources that support the environment
- Trade Ideas notes that by 2026, trading opportunities include **Federal Reserve decisions, inflation, GDP, politics, weather, AI, and crypto regulations**, and that traders increasingly use **advanced strategies** like event correlation and Kelly sizing. That’s the kind of environment where tail-decay setups are most common. [1]
- Quicknode’s 2026 analytics overview emphasizes **real-time aggregation, whale tracking, and AI signal generation**, which is exactly what you need to identify overextended tail premiums. [2]

---

## 2) Cross-venue arbitrage

This is probably the most concrete “edge” if you can watch both venues and move quickly.

### Core idea
If Kalshi and Polymarket are pricing the same or economically similar event differently, you buy the cheaper side and/or sell the richer side.

### Example
If the same event is:
- **Kalshi YES = 38c**
- **Polymarket YES = 42c**

You can potentially:
- buy YES on Kalshi
- buy NO / or short the richer equivalent on Polymarket if the structure allows

The point is not just “same market” arbitrage. It also includes **near-equivalents**:
- same macro event phrased differently
- same

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-05-19 via Conway's auto-publisher.*
