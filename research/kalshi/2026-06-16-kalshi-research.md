# Kalshi Nightly Research Brief — 2026-06-16

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-16T02:03:03, run time 119.8s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
## 3. GitHub Repos (Recently Updated)
- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 1 · None _(updated 2026-06-16)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[oleksandrbannick/Meridian](https://github.com/oleksandrbannick/Meridian)** ⭐ 2 · Python _(updated 2026-06-16)_
  kalshi automated trading bot with custom UI

- **[dcamco/kalshi-snapshots](https://github.com/dcamco/kalshi-snapshots)** ⭐ 0 · HTML _(updated 2026-06-16)_
  Public read-only snapshots of the Kalshi paper-trading dashboard (main repo private)

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 1 · None _(updated 2026-06-16)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-16)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[TexasCoding/kalshi-python-sdk](https://github.com/TexasCoding/kalshi-python-sdk)** ⭐ 0 · Python _(updated 2026-06-15)_
  Professional Python SDK for the Kalshi prediction markets API

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 1 · None _(updated 2026-06-16)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 1 · Python _(updated 2026-06-16)_
  Polymarket Trade Bot

- **[bit-nexusxtitmtdsuy/Polymarket_Bot](https://github.com/bit-nexusxtitmtdsuy/Polymarket_Bot)** ⭐ 32 · None _(updated 2026-06-16)_
  Polymarket Bot is a tool for interacting with Polymarket, a decentralized prediction market platform where users trade shares representing the probability of real-world events using cryptocurrency (pr

- **[pjmerica/pred-arbitrage](https://github.com/pjmerica/pred-arbitrage)** ⭐ 0 · Python _(updated 2026-06-16)_
  Cross-market prediction market arbitrage scanner — Kalshi, Polymarket, PredictIt

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-06-16)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant)** ⭐ 2 · Python _(updated 2026-06-16)_
  Trade Kalshi prediction markets with a quantitative system designed for fee-aware position sizing and statistical arbitrage.

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-12)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[talirabban/prediction-markets-thesis](https://github.com/talirabban/prediction-markets-thesis)** ⭐ 0 · Python _(updated 2026-06-10)_
  Quantitative analysis of Polymarket event contracts: calibration, ML-based pricing-error prediction, and out-of-sample strategy backtesting.

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

## 4. Perplexity Strategy Synthesis
For **small accounts**, the most actionable edges in Kalshi and Polymarket are usually **time-decay “sell the close” trades, simple cross-venue arbitrage when spreads exceed fees, and convergence trades in stale or thin markets**. The best opportunities tend to be in the final hours of liquid markets, where Polymarket often leads on price discovery and Kalshi can lag or temporarily overreact in the opposite direction.[1]

- **Tail decay harvesting**: sell overpriced **Yes** or **No** contracts into the last phase of a market when the remaining time value collapses faster than the true event risk.
- **Cross-venue arbitrage**: buy the cheaper venue and sell the richer one when the same event trades at a gap large enough to cover fees, spreads, and fill risk.
- **Convergence plays**: enter when a price is clearly stale versus a more informative reference market and exit as the lagging venue converges.
- **Small-account edges**: target markets where a $50–500 bankroll can still get filled, usually through fractional sizing, one-leg directional trades, or very small arb baskets rather than capital-intensive full-book arbitrage.[1][4]

## 1) Tail decay harvesting

The practical idea is to **sell overpriced tails late** rather than try to predict the event perfectly. QuantPedia notes that prediction markets can exhibit systematic inefficiencies and that **Polymarket generally leads Kalshi due to higher liquidity, especially in the last hours**, which is exactly where decay trades are most actionable.[1]

**How to trade it**
- Focus on contracts with **24 hours to 2 hours remaining**.
- Look for markets where the price is still **above 5–10 cents** but the remaining path to resolution is mostly binary and information flow is slowing.
- Prefer **No-side decay** in “favorite likely to fail” markets and **Yes-side decay** in “overhyped longshots,” depending on the direction of the overreaction.
- Take profits mechanically once the price decays by **20–40% of the remaining premium** rather than waiting for full expiry.

**Concrete parameter guide**
- **Time horizon:** enter at **T-48h to T-2h**, scale out into the final **6–12h**.
- **Price threshold:** best candidates are usually in the **0.10–0.35** range; above that, the market still has meaningful event risk, below that, the edge can get too small after fees.
- **Position sizing:** on a $50–500 bankroll, risk **1–3% of bankroll per trade**, which usually means **$0.50–$15** per ticket or a few small tickets across correlated contracts.[4]

**Why it works**
- The final hours often compress probability into the most informative venue.
- When the market’s implied probability is still too high relative to your own estimate, the decay from time passing alone can be harvested if the event does not materially change.[1]

## 2) Cross-venue arbitrage

QuantPedia explicitly describes **inter-market arbitrage** as trading the same contract across platforms when the sum of the implied probabilities is less than **1 minus transaction costs**, or when a buy-all basket is cheaper than the guaranteed payout.[1]

**Best use case**
- The same or effectively equivalent event trades on both venues.
- One venue is clearly leading price discovery.
- The other venue lags enough that the spread exceeds fees, slippage, and transfer friction.[1]

**Concrete setup**
- If Polymarket implies **62%** and Kalshi implies **55%** for effectively the same outcome, you have an **7-point spread**.
- Only act if the spread is large enough to survive:
  - taker fees,
  - bid/ask spread,
  - fill uncertainty,
  - settlement difference

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-16 via Conway's auto-publisher.*
