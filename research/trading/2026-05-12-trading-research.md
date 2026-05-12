# Trading Nightly Research Brief — 2026-05-12

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options.*

---
**Recent Activity (Last 7 Days):**

- **Total Trades:** 24
- **Trades Last 7 Days:** 19
- **Top Symbols (7 Days):** ZEC/USDC (9), INJ/USDC (9), DOGE/USDC (5), BTC/USDC (2)
- **Side Breakdown (7 Days):** Sell (13), Buy (11)

This portfolio includes privacy coins, DeFi infrastructure, and meme assets.

## 1. Decoding the Academic Echoes

The academic papers on arXiv offer insights into future algorithmic trading trends:

- **HarmoWAM** ([https://arxiv.org/abs/2605.10942v1](https://arxiv.org/abs/2605.10942v1)): Highlights the increasing sophistication of AI agents in exploiting market inefficiencies.
- **Quantifying Concentration Phenomena** ([https://arxiv.org/abs/2605.10931v1](https://arxiv.org/abs/2605.10931v1)): Reveals predictable patterns in Transformer models, indicating mean reversion trends.

## 2. GitHub Gems

GitHub repositories provide practical tools for traders:

- **finquant** ([Yankeremerycloth537/finquant](https://github.com/Yankeremerycloth537/finquant)): Efficient backtesting and data logging.
- **autotrade-hub** ([ankit6868/autotrade-hub](https://github.com/ankit6868/autotrade-hub)) and **alpha-skills** ([Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)): Combining AI with automated trading systems.

## 3. Actionable Strategies

### Crypto Momentum with Regime Filters
- **Time Horizon**: Intraday to 1-3 days.
- **Entry Rules**:
  - Volatility regime via ATR(14) > 2x 20-day avg (high vol only).
  - BTC/ETH above 50-period EMA on 1H chart.
  - Fair Value Gap (FVG): High of candle N-2 < low of candle N; enter long on close above FVG high with volume >1.5x avg.
- **Exit Rules**:
  - Take Profit: 2:1 R:R at next resistance or 3% move.
  - Stop Loss: Below FVG low (risk 1% account).
- **Position Sizing**: 1-2% risk per trade.

### Equity Pair Trading
- **Time Horizon**: 1-5 days.
- **Entry Rules**:
  - Long SPY/short QQQ when z-score of spread > +2SD or < -2SD.
  - Regime Filter: VIX <25 (low vol regime).
  - Volume confirmation: Both > avg daily volume.

---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-05-12 via Conway's auto-publisher.*