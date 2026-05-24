# Trading Nightly Research Brief — 2026-05-24

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
## Recent Activity (Last 7 Days)
* **Total Trades:** 23
* **Trades Last 7 Days:** 23
* **Top Symbols (7 Days):** INJ/USDC (7), DOGE/USDC (7), ZEC/USDC (5), BTC/USDC (4)
* **Side Breakdown (7 Days):** Sell (13), Buy (10)

This activity reflects a balanced approach, with concentrated trades in perpetual futures, meme coins, privacy coins, and Bitcoin. The portfolio leans long but includes many sell trades to manage risk.

## 1. Decoding the Academic Echoes: What's Emerging from arXiv

The arXiv repository often contains papers that can inform trading strategies:

* **Vector Policy Optimization for Diverse Environments:** This research aims to train AI models to handle unexpected market conditions.
* **Gesture-Aware Vision-Language-Action Models:** Improving AI's ability to understand complex scenes and act accordingly in dynamic environments.
* **Sensor2Sensor Data Conversion:** Combining data from different sources to create comprehensive datasets for training AI models.
* **Constraints on Physics and Standard Models:** Efforts to refine our understanding of market dynamics, highlighting the complexity behind unexpected shifts.
* **Quantum Geometric Dipole Excitons:** Emphasizing the need to anticipate hidden dynamics in seemingly stable systems.

## 2. The GitHub Ecosystem: Practical Tools for Implementation

GitHub offers tools that translate theoretical concepts into actionable strategies:

* **[Barrazar274/the-0050-project](https://github.com/Barrazar274/the-0050-project):** Compares custom machine learning strategies against a "buy and hold" approach.
* **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant):** A tool for trading Kalshi prediction markets, focusing on fee-aware position sizing and statistical arbitrage.
* **[ankit6868/autotrade-hub](https://github.com/ankit6868/autotrade-hub):** An AI-driven crypto trading automation bot with paper/live trading capabilities.
* **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance):** Simplifies backtesting and deployment of algorithmic trading strategies.

## 3. Synthesizing the Research: Concrete Trading Strategies

Here are some specific trading approaches:

### a) Crypto Momentum with Regime Filters
* **Core Idea:** Trade momentum only when market conditions support it.
* **Setup:**
    * **Universe:** BTC, ETH, SOL, and other liquid alts.
    * **Regime Filter:** Long positions if BTC is above its 200-day moving average, the 50-day moving average trends up, and volatility isn't spiking.
    * **Entry:** Buy when a coin closes above its 20-day high.
    * **Exit:** Stop-loss at 2 ATR below entry.
* **Position Sizing:** Risk 0.5-1% of your account per trade.

### b) Equity Pair Trading
* **Core Idea:** Profit from the convergence of temporarily diverging asset prices.
* **Setup:**
    * **Universe:** XLF vs KRE, XLK vs QQQ, SMH vs SOXX, or similar pairs.
    * **Signal:** Identify when the spread between two assets deviates significantly from its historical average.
    * **Position Sizing:** Manage risk carefully, especially with small accounts.

**Final Thought:**

The challenge isn't finding the perfect indicator or algorithm but developing adaptability and critical thinking skills to navigate market complexity.

**Your concrete takeaway:** Spend 30 minutes exploring one of the GitHub repositories mentioned above. Understand its core logic, enhancing your ability to interpret research and adapt to market changes.
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-05-24 via Conway's auto-publisher.*