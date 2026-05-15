# Trading Nightly Research Brief — 2026-05-15

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
## Navigating the Noise: A Retail Trader’s Digest of Emerging Signals (May 2026)

The constant influx of research papers, GitHub repositories, and AI tools can be overwhelming. Instead of chasing the next big thing, focus on understanding how market dynamics are evolving and adapting your approach accordingly.

### Recent Activity (Last 7 Days)
- **Total Trades:** 55
- **Trades Last 7 Days:** 32
- **Top Symbols (7 Days):** INJ/USDC (12), ZEC/USDC (11), DOGE/USDC (6), BTC/USDC (3)
- **Side Breakdown (7 Days):** Sell (16), Buy (16)

This activity highlights a risk-on sentiment and the importance of adapting strategies to market conditions.

## 1. Emerging Signals

### arXiv: Theoretical Insights
Recent papers emphasize understanding regime shifts, advanced risk management, and AI for signal generation and execution.

### GitHub: Practical Applications
GitHub hosts code, backtesting frameworks, and experimental trading strategies, showcasing growing sophistication in algorithmic trading.

### Perplexity: Synthesizing Data
Perplexity helps distill complex research into actionable insights by synthesizing vast amounts of data.

## 2. Decoding Emerging Strategies

**a. Crypto Momentum with Regime Filters**
- **Universe:** BTC, ETH, SOL, and 5-10 liquid altcoins.
- **Time Horizon:** 4-hour to 3-day charts.
- **Regime Filters:**
    - BTC above its 200-day moving average on the daily chart.
    - BTC above its 50-day moving average with a positive slope.
    - Realized volatility below 1.5x its 180-day median.
    - Perpetual funding rates not extremely positive and rising rapidly.
    - At least 60% of selected altcoins above their 20-day moving average, BTC dominance stable.

**b. Equity Pairs and Relative Value Mean Reversion**
- Identifies mispricings between related stocks or ETFs for profit.

**c. Tail Risk Hedges with Defined-Risk Options Structures**
- Uses options to protect portfolios from extreme market events.
  
**d. New/Less Crowded Edges**
- **Cross-sectional momentum with volatility filtering:** Combining momentum signals with market volatility measures.
- **Intraday reversal after liquidation events:** Exploiting price inefficiencies post-forced liquidations.
- **Post-funding/post-open positioning effects in crypto:** Identifying opportunities based on funding rounds or market openings.

## 3. Tools & Resources
- **AKQuant**: High-performance framework for quantitative research and trading.
- **Blankly Finance**: Platform for building, backtesting, and deploying algorithmic trading strategies.
- **Kalshi-trade-bot**: Bot for trading Kalshi prediction markets.

## 4. Pragmatic Approach

Focus on separating signal from noise by building a solid foundation of trading principles, disciplined risk management, and continuous adaptation to evolving market dynamics.

### Concrete Takeaway
Before implementing any new strategy, thoroughly backtest it and paper trade to validate its performance in real-world conditions.
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-05-15 via Conway's auto-publisher.*
