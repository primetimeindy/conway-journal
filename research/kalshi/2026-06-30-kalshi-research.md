# Kalshi Nightly Research Brief — 2026-06-30

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-30T02:02:55, run time 117.1s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **One-Step Gradient Delay is Not a Barrier for Large-Scale Asynchronous Pipeline Parallel LLM Pretraining** _(binary option pricing convergence)_
  [2026-06-29](https://arxiv.org/abs/2606.30634v1)
  Modern large-scale LLM pretraining benefits from utilizing Pipeline Parallelism; however, synchronous implementations leave GPUs idle during pipeline bubbles, wasting computational resources. Asynchronous Pipeline Parallelism eliminates these bubbles, maximizing throughput at the cost of gradient staleness. Among asynchronous schedules, PipeDream-2BW is particularly appealing: unlike the original 

- **Prescriptions for the stochasticity effect on the integrated X-ray luminosity of star-forming galaxies:Implications for selecting star-forming galaxies and AGN in X-ray surveys** _(binary option pricing convergence)_
  [2026-06-29](https://arxiv.org/abs/2606.30624v1)
  (abridged) The integrated X-ray luminosity (Lx) of star-forming galaxies is dominated by high-mass X-ray binary (HMXB) populations. The discrete nature of these populations introduces stochastic sampling effects that distort the X-ray Luminosity Function (XLF) and bias observed scaling relations. We investigate how stochastic sampling of the HMXB XLF affects the predicted integrated Lx across a wi

- **When and Which Sensor to Observe? Timely Tracking of a Joint Markov Source** _(binary option pricing convergence)_
  [2026-06-29](https://arxiv.org/abs/2606.30623v1)
  We investigate the problem of remote estimation (at a monitor) of a discrete-time joint Markov process with individual components which can be observed with dedicated sensors. At a given time slot, the monitor has the option of staying idle or sending a pull request to one of the sensors to obtain a partial state value, while the sensors are assumed to have heterogeneous sampling costs. Our goal i

## 3. GitHub Repos (Recently Updated)
- **[oleksandrbannick/Meridian](https://github.com/oleksandrbannick/Meridian)** ⭐ 2 · Python _(updated 2026-06-30)_
  kalshi automated trading bot with custom UI

- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1935 · TypeScript _(updated 2026-06-30)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[dcamco/kalshi-snapshots](https://github.com/dcamco/kalshi-snapshots)** ⭐ 0 · HTML _(updated 2026-06-30)_
  Public read-only snapshots of the Kalshi paper-trading dashboard (main repo private)

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-30)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-30)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[rockmundada/kalshi-weather-bot](https://github.com/rockmundada/kalshi-weather-bot)** ⭐ 0 · Python _(updated 2026-06-29)_
  Automated weather derivatives trading system for Kalshi — 5 API integrations, 10-chart analytics dashboard, data-driven strategy from 339 analyzed trades

- **[rexlau-prog/pm-crypto-trend-dashboard](https://github.com/rexlau-prog/pm-crypto-trend-dashboard)** ⭐ 0 · HTML _(updated 2026-06-30)_
  Report dashboard for the pm_crypto_trend Polymarket 5-min trading bot

- **[Casiniza/polymarket-bot](https://github.com/Casiniza/polymarket-bot)** ⭐ 2 · Python _(updated 2026-06-30)_
  Automated Polymarket trading bot with GitHub Actions

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 98 · Solidity _(updated 2026-06-30)_
  Easy setup and creation of a bot

- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1935 · TypeScript _(updated 2026-06-30)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[DanielTabakman/Probability-prediction-engine](https://github.com/DanielTabakman/Probability-prediction-engine)** ⭐ 0 · Python _(updated 2026-06-30)_
  Probability prediction engine. used to understand what the market is saying using calls and puts to understand the probability distribution of future prices. will eventually cross reference with predi

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-06-30)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-27)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[jhunter11/openclaw-kalshi-operator](https://github.com/jhunter11/openclaw-kalshi-operator)** ⭐ 0 · HTML _(updated 2026-06-26)_
  Autonomous AI agent operating an event-contract research & trading loop (Kalshi). Python research/orchestration harness + strategy gates + learning log.

- **[aasuper1/kalshi-alpha-strategies](https://github.com/aasuper1/kalshi-alpha-strategies)** ⭐ 0 · Python _(updated 2026-06-19)_
  Three independent Kalshi event-contract trading strategies: latency (sell-worthless), liquidity-incentive market making, and a cross-market/correlation engine.

## 4. Perplexity Strategy Synthesis
For small accounts ($50–$500) on Kalshi and Polymarket in 2026, the most actionable strategies are **cross-platform arbitrage on wide gaps (5¢+)**, **domain-expertise trading in niche markets**, and **"reverse bonding" (betting 1¢ on edge cases)** to harvest tail decay, executed with strict position sizing of **1–5% per idea** and short time horizons (under 3 months) to ensure capital recycling [2][1].

### 1. Cross-Venue Arbitrage (The "Beginner Playbook")
This is the most reliable way for small accounts to generate low-risk alpha by exploiting structural mispricing between Kalshi and Polymarket.
*   **Strategy Parameters:**
    *   **Time Horizon:** Immediate execution; gaps often close within minutes on major events [1].
    *   **Price Thresholds:** Target **5¢+ (5%)** gaps on slower markets to offset fees and ensure net profit after spread depth checks [2].
    *   **Position Sizing:** Split capital across venues; use **1–5%** of bankroll per arbitrage leg [2].
    *   **Execution Checklist:** Before placing orders, verify (1) real book depth behind headline prices, (2) fee math on both legs (Polymarket fees up to 1.8%), and (3) matching resolution criteria [2][5].
*   **Why it works for small accounts:** 2–5% price gaps exist on major events, and the structural mispricing is arbitraged without predicting the outcome [1].

### 2. Tail Decay Harvesting via "Reverse Bonding"
This strategy exploits the market's tendency to overprice "impossible" or low-probability events (tail decay), allowing small accounts to buy cheap 1¢ tokens that likely won't hit but offer high leverage if the premise fails.
*   **Strategy Parameters:**
    *   **Time Horizon:** Short-to-medium (weeks to months) to limit capital lock-up [2].
    *   **Price Thresholds:** Place limit orders at **1¢** (reverse bonding) on edge cases where the market implies a 10–20% chance but the true probability is <1% [6].
    *   **Position Sizing:** Very small (**1%** of bankroll) due to the binary "all or nothing" risk of these edge cases [6].
    *   **Risk Management:** Do not "revenge trade" if these fail; treat them as a diversified portfolio of low-probability bets [6].
*   **Mechanism:** By betting 1¢ instead of 99¢, you limit downside while capturing the "tail decay" if the event is proven impossible [6].

### 3. Convergence Plays & Domain-Expertise Trading
For small accounts, the best "edge" is personal knowledge in a niche, allowing you to spot mispriced convergence plays before the crowd corrects them.
*   **Strategy Parameters:**
    *   **Time Horizon:** 3–8 hours of research/week; hold until resolution or convergence (short windows first) [2].
    *   **Starting Capital:** **$50+** is sufficient for niche domain trading [2].
    *   **Edge Source:** "You know a niche better than the crowd" (e.g., specific crypto protocols, local weather, or obscure sports stats) [2].
    *   **AI Integration:** Use AI models to *structure* your probability (base rates, resolution sources) before looking at prices, then verify against primary sources to avoid hallucinated details [2].
*   **Expert Upgrade:** Treat trades as a portfolio with a "velocity target" (turn

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-30 via Conway's auto-publisher.*
