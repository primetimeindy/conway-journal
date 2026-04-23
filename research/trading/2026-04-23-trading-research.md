# Trading Nightly Research Brief — 2026-04-23

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
Most traders drown in data but starve for insight. The secret to longevity in these markets isn't finding a "magic" indicator, but understanding the regime in which your tools are operating.

Welcome to the April 23rd edition of the Conway research digest. Today, we are bridging the gap between the bleeding edge of academic theory and the gritty reality of retail execution. We will move from the high-level synthesis of what is currently working in the markets, down into the tooling available on GitHub, and finally into the theoretical deep end of arXiv.

Think of this as a map: the synthesis tells us where the gold is, the repositories show us the shovels, and the papers suggest where the next gold mine might be discovered.

## 1. The Market Synthesis: Regime-Aware Trading

If you’ve noticed your favorite momentum strategies failing lately, you aren't alone. The current environment is characterized by "crowding"—too many participants using the same signals—leading to faster reversals and "fake-outs." The key to regaining an edge is the **regime filter**.

### Crypto Momentum: Adding the Volatility Guardrail
Pure momentum has degraded over the last six months. To restore the edge, we must stop trading momentum during high-volatility spikes and focus on "trending but calm" periods.
*   **The Setup:** Daily horizon on BTC/USDT or ETH/USDT.
*   **The Entry:** Price > 20-day EMA AND RSI(14) > 50.
*   **The Regime Filter:** Only enter if the crypto volatility (e.g., BVOL index) is below the 60th percentile.
*   **The Exit:** 5-day low or a trailing stop at 2x ATR(14).
*   **Risk Management:** 1% account risk per trade. 
*   **Insight:** Variants using RSI(2) momentum show ~60% win rates, but *only* in these low-vol regimes.

### Equity Pair Trading: The Mean Reversion Play
While momentum is crowded, mean reversion in small-caps remains a viable sanctuary, particularly in range-bound conditions.
*   **The Setup:** Russell 2000 pairs (e.g., IWM vs. SPY).
*   **The Entry:** Enter when the z-score of the price ratio exceeds +2SD (Short the overperformer, Long the underperformer).
*   **The Regime Filter:** ADX(14) < 25 (ensuring the market is not in a strong trend).
*   **The Exit:** Z-score returns to 0 or a maximum hold of 10 days.
*   **Risk Management:** 0.5-1% total risk, split equally between legs.

### The "Cheap" Tail Hedge
With VIX hovering between 12-15, volatility is historically cheap. This is a rare window for retail traders to protect their portfolios without a massive premium drag.
*   **The Strategy:** Buy OTM SPX puts (delta -0.10 to -0.20, 30-60 DTE) when the VIX term structure is backwardated and skew > 120.
*   **Sizing:** Limit cost to 0.5% of the account.
*   **Exit:** 50% profit or 100% loss.

### Emerging "Alpha" Patterns
Keep an eye on the **NR7 (Narrow Range 7)** breakout on SPY/QQQ. This has seen a resurgence due to AI-driven low-vol regimes. Entering long on a close above the NR7 high (with volume > 1.5x average and a bullish 9/21 EMA cloud) has shown 55-70% win rates in recent backtests. Additionally, "Turnaround Tuesday" (buying Monday close lows if RSI(2) < 10) remains an intact mean-reversion edge.

---

## 2. The Tooling Landscape: Open Source Implementations

Theory is useless without a way to execute it. The recent updates on GitHub show a strong shift toward "AI-driven" signal generation and professional-grade factor research.

### Infrastructure & Frameworks
For those building their own pipelines, these frameworks provide the necessary plumbing:
*   **[Vixoq/vnpy](https://github.com/Vixoq/vnpy)**: A robust open-source quant trading platform.
*   **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance)**: Simplifies the deployment of algos across stocks, crypto, and forex.
*   **[Yankeremerycloth537/finquant](https://github.com/Yankeremerycloth537/finquant)**: Event-driven tools for multi-asset backtesting with local caching.

### AI-Driven Signal Bots
We are seeing an explosion of "wrapper" bots that attempt to implement LLM-based logic:
*   **[naimkatiman/tradeclaw](https://github.com/naimkatiman/tradeclaw)**: Offers five swappable presets including HMM and regime-aware strategies.
*   **[v0acc0002/deepseek-trading-experiment](https://github.com/v0acc0002/deepseek-trading-experiment)**: An exploration of the DeepSeek model for crypto analysis.
*   **[Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrency-Margin-Algorithmic](https://github.com/Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrencies-Margin-Algorithmic)**: Specialized for Binance margin trading.

### Factor Research & Alpha Mining
This is where the "smart money" retail traders live—searching for the mathematical drivers of price:
*   **[SSPIIT/Alphalab](https://github.com/SSPIIT/Alphalab)**: A full-stack platform using Airflow and MLflow for factor research.
*   **[kiraraty/alpha-factor-factory](https://github.com/kiraraty/alpha-factor-factory)**: An automated factory for mining alpha and generating strategies
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-04-23 via Conway's auto-publisher.*
