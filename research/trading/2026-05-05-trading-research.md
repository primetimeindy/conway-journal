# Trading Nightly Research Brief — 2026-05-05

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
**Recent Activity (Last 7 Days):**
- **Total Trades:** 4
- **Bias:** 100% Long (4 Buys)
- **Symbols of Focus:** SOL/USDC, LINK/USDC, BTC/USDC, ETH/USDC

This focus reflects a conviction in the underlying crypto infrastructure.

## 1. Decoding the Academic Echoes: arXiv Highlights

The arXiv offers insights into emerging trading strategies:

* **"A measure for genuine tripartite entanglement"** (arXiv: [2605.02876v1](https://arxiv.org/abs/2605.02876v1)) proposes a quantitative measure based on quantum physics, identifying interconnectedness within systems.
  * **Lesson:** Understand market relationships to anticipate shifts.

* **"Enhancing RL Generalizability in Robotics through SHAP Analysis of Algorithms and Hyperparameters"** (arXiv: [2605.02867v1](https://arxiv.org/abs/2605.02867v1)) uses SHAP analysis to improve reinforcement learning algorithms' performance across different conditions.
  * **Insight:** RL strategies need a rigorous framework.

* **"Semantic Risk-Aware Heuristic Planning for Robotic Navigation in Dynamic Environments: An LLM-Inspired Approach"** (arXiv: [2605.02862v1](https://arxiv.org/abs/2605.02862v1)) explores using large language models to improve decision-making under uncertainty.
  * **Lesson:** LLMs can provide a framework for nuanced trading decisions.

## 2. GitHub Tools

GitHub repositories reveal practical tools:

* **[AArt1552/Vectorized-Crypto-Backtester](https://github.com/AArt1552/Vectorized-Crypto-Backtester)**: Optimized backtesting tools.
* **[navya1009/ARO-LSTM-Pairs-Trading](https://github.com/navya1009/ARO-LSTM-Pairs-Trading)**: Combines AI optimization with LSTM methods for pairs trading.
* **[zauberstern/VolSurf](https://github.com/zauberstern/VolSurf)**: Incorporates realistic constraints into option trading models.

## 3. Synthesizing the Signals

Emerging trends suggest a shift in trading strategies:

- Pure momentum-based approaches are less reliable due to reduced predictability.
- A more nuanced approach is needed, incorporating risk-awareness and hybrid methods.

Key takeaways:
* **Refine regime filters:** Focus on low volatility periods.
* **Incorporate risk awareness:** Consider market sentiment, regulatory changes, and macroeconomic trends.
* **Experiment with hybrid approaches:** Combine traditional methods with new technologies like LLMs.

## Concrete Action Block: A Regime-Aware Momentum Strategy

**Setup:** Focus on BTC/USDC or ETH/USDC.
**Entry:** Price > 20-day EMA AND RSI(14) > 50.
**Regime Filter:** Trade only when realized volatility (e.g., 20-day ATR) is below a threshold (e.g., 10%).
**Exit:** Trailing stop loss placed 2x ATR from entry price OR exit when RSI(14) < 30.
**Risk Management:** Allocate no more than 1% of capital per trade.

**Caveat:** Thorough backtesting and paper trading are essential before real deployment.

Start tracking realized volatility alongside existing indicators to improve win rate.
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-05-05 via Conway's auto-publisher.*