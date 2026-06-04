# Kalshi Nightly Research Brief — 2026-06-04

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-04T02:01:38, run time 77.3s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
## 3. GitHub Repos (Recently Updated)
- **[InTheNightRaider/KalshiTradingBot](https://github.com/InTheNightRaider/KalshiTradingBot)** ⭐ 0 · HTML _(updated 2026-06-04)_
  This is the public facing trading bot repo. 

- **[oleksandrbannick/Meridian](https://github.com/oleksandrbannick/Meridian)** ⭐ 1 · Python _(updated 2026-06-04)_
  kalshi automated trading bot with custom UI

- **[braedonsaunders/homerun](https://github.com/braedonsaunders/homerun)** ⭐ 78 · Python _(updated 2026-06-04)_
  Open-source prediction market trading platform for Polymarket & Kalshi. Write full Python strategies & data sources, backtest them, then paper or live trade. 25+ built-in strategies, copy trading, AI 

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-04)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-04)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[TexasCoding/kalshi-python-sdk](https://github.com/TexasCoding/kalshi-python-sdk)** ⭐ 0 · Python _(updated 2026-06-04)_
  Professional Python SDK for the Kalshi prediction markets API

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 0 · Python _(updated 2026-06-04)_
  Polymarket Trade Bot

- **[bit-nexusxtitmtdsuy/Polymarket_Bot](https://github.com/bit-nexusxtitmtdsuy/Polymarket_Bot)** ⭐ 32 · None _(updated 2026-06-04)_
  Polymarket Bot is a tool for interacting with Polymarket, a decentralized prediction market platform where users trade shares representing the probability of real-world events using cryptocurrency (pr

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 97 · Solidity _(updated 2026-06-04)_
  Easy setup and creation of a bot

- **[braedonsaunders/homerun](https://github.com/braedonsaunders/homerun)** ⭐ 78 · Python _(updated 2026-06-04)_
  Open-source prediction market trading platform for Polymarket & Kalshi. Write full Python strategies & data sources, backtest them, then paper or live trade. 25+ built-in strategies, copy trading, AI 

- **[irfndi/NeuraTrade](https://github.com/irfndi/NeuraTrade)** ⭐ 1 · Go _(updated 2026-06-04)_
  NeuraTrade is a high-performance, scalable platform designed for real-time cryptocurrency arbitrage detection, advanced technical analysis, and prediction market.

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-06-04)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

- **[Waike122333/Automated-Trading-Kalshi](https://github.com/Waike122333/Automated-Trading-Kalshi)** ⭐ 0 · None _(updated 2026-03-17)_
  An algorithmic trading bot for kalshi.com event contracts that automates trading strategies based on economic data, news events, weather patterns, and political markets in real-time.

- **[GitHubMaster07/Enterprise-Test-Strategy-Blueprint](https://github.com/GitHubMaster07/Enterprise-Test-Strategy-Blueprint)** ⭐ 0 · None _(updated 2026-01-17)_
  Enterprise‑grade QA Automation & Test Strategy Blueprint for UI, API, DB, Events, Contracts, CI/CD, and Non‑Functional Testing.

## 4. Perplexity Strategy Synthesis
The most actionable **2026 prediction-market strategies** for Kalshi and Polymarket are: **tail-decay harvesting**, **cross-venue arbitrage**, and **convergence plays** on events where the market price is likely to move toward a clearer consensus as the resolution date approaches. For **small accounts ($50–$500)**, the most realistic edge is usually *short-horizon, liquid, near-expiry mispricings* rather than broad statistical arbitrage, because the binding constraint is often liquidity, not signal quality.[2][3][4]

**1) Tail-decay harvesting**
- This is the practice of selling overpriced “long-shot” outcomes when the implied probability is too high relative to the market’s likely late-stage convergence, especially after hype fades or fresh information arrives.[2][3]
- The most usable version for small accounts is: enter only when a contract is still **30–120 days from resolution**, the price is in the **5–25¢** range, and there is a plausible path for sentiment or information flow to decay toward zero or a lower fair value.[2][3]
- A practical rule is to target contracts where your estimate is at least **3–5 cents** better than market price, because fees, spread, and slippage eat thin edges quickly on small bankrolls.[2][3]
- Position sizing for a $50–$500 account should usually stay at **2–8% of bankroll per trade** on these tails, with more size only on highly liquid contracts where you can exit cleanly.[2]
- The YouTube guide you surfaced explicitly recommends avoiding reckless sizing, tracking correctness over **20–30+ trades**, and using Kelly-style sizing only after a demonstrated edge.[2]

**2) Cross-venue arbitrage**
- The cleanest arbitrage is when the *same event* trades at meaningfully different prices on Kalshi and Polymarket after adjusting for fees, settlement frictions, and any differences in contract wording.[2][4][6]
- The useful threshold is usually a **2–4 cent gross spread** at minimum; for small accounts, you generally want **4–8 cents** because tiny spreads get consumed by fees and execution friction.[2][4]
- A simple approach is to buy the cheaper side and hedge the more expensive side only when you can execute both legs quickly; otherwise, the position becomes a directional bet, not an arbitrage.[2]
- The YouTube walkthrough mentions using tools that notify when arbitrage opens and sorting opportunities by **largest percent spread** and **available profit**, which is exactly the right workflow for cross-venue trading.[2]
- For small accounts, this works best in **fast-moving but not ultra-liquid** markets where competitors miss small stale quotes, especially around news releases, debate nights, CPI/Fed events, or sports outcomes with shared reference events.[2][6]

**3) Convergence plays**
- These are trades where the market is likely to become more efficient as resolution nears, so the edge comes from entering early and exiting when price converges, rather than holding to settlement.[2][3]
- Best candidates are markets with a clear eventual data source or binary resolution rule, where the early price is noisy but the final answer will be public and hard to dispute.[3][6]
- Time horizon: **days to weeks**, not months, unless the catalyst calendar is sparse.[2][3]
- Entry is most attractive when the contract is **10–25¢ off** from your base-case probability and there is an identifiable catalyst that should force repricing, such as an official report, court filing, earnings release, or regulatory announcement.[2][3]
- Exit is usually best at **50–80% of the way to expected convergence**, not at settlement, because that preserves capital turnover and reduces binary event risk.[2]

**4

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-04 via Conway's auto-publisher.*
