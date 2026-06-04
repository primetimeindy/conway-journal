# Trading Nightly Research Brief — 2026-06-04

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-04T02:32:43, run time 67.9s._

## 1. Self-Analysis (Conway Trade Log)
```json
{
  "total_trades_logged": 130,
  "trades_last_7d": 33,
  "top_symbols_7d": [
    [
      "ZEC/USDC",
      12
    ],
    [
      "INJ/USDC",
      10
    ],
    [
      "BTC/USDC",
      6
    ],
    [
      "DOGE/USDC",
      5
    ]
  ],
  "side_breakdown_7d": {
    "buy": 16,
    "sell": 17
  }
}
```

## 2. arXiv Papers (Last 60 Days)
- **STRIDE: Training Data Attribution via Sparse Recovery from Subset Perturbations** _(reinforcement learning portfolio)_
  [2026-06-03](https://arxiv.org/abs/2606.05165v1)
  Training Data Attribution (TDA) seeks to trace a model's predictions back to its training data. The gold standard for TDA relies on causal interventions, observing how a model changes when data is added or removed, but repeated retraining is computationally challenging for Large Language Models (LLMs). Consequently, most approaches approximate this effect in the parameter space using gradients. Ho

- **X4Val: Learning Neural Surrogates for Variance-Reduced Policy Evaluation** _(reinforcement learning portfolio)_
  [2026-06-03](https://arxiv.org/abs/2606.05159v1)
  Rigorous evaluation of learning-based robotic systems is an essential prerequisite for deployment. However, real-world test data is expensive to gather; moreover, in a typical iterative development context, data gathered from the latest policy is necessarily limited in scale. This motivates evaluation methodologies that make use of heterogeneous data sources, including simulation, historical polic

- **Reinforcement Learning from Rich Feedback with Distributional DAgger** _(reinforcement learning portfolio)_
  [2026-06-03](https://arxiv.org/abs/2606.05152v1)
  Reasoning models have advanced rapidly, but the dominant reinforcement learning from verifiable rewards (RLVR) recipe remains surprisingly narrow: sample many responses and reward each with a single bit indicating whether the final answer is correct. Yet many settings provide rich feedback, including execution traces, tool outputs, expert corrections, and model self-evaluations. We study how to us

- **Mapping the star formation peak with LIGO A# and Next-Generation detectors** _(factor investing alpha)_
  [2026-06-03](https://arxiv.org/abs/2606.05151v1)
  Measuring the redshift evolution of star formation rate density is crucial in understanding the origin and evolution of galaxies and large scale structure in the universe. It is currently measured with electromagnetic probes, however, these probes often track luminosity, which is then converted to star formation rate (SFR) depending on various factors such as initial mass function, dust extinction

- **Early Multiwavelength Observations of AT 2026fgk: The Luminous Afterglow to Sub-luminous GRB 260310A, Identified Independently of a Gamma-ray Trigger** _(factor investing alpha)_
  [2026-06-03](https://arxiv.org/abs/2606.05146v1)
  The origins of sub-luminous ($L_\mathrm{γ,\mathrm{iso}} &lt; 10^{49.5}$\,erg\,s$^{-1}$) gamma-ray bursts (GRBs) associated with broad-lined Type~Ic supernovae (Ic-BL SNe) are poorly understood, in part due to the low discovery rate and faint afterglows. Here we present the identification of the optical afterglow of Fermi-GBM-detected GRB\,260310A (AT\,2026fgk) as a rapidly rising ($&gt;1\,$mag\,d$

- **Hawking Temperatures and Radiation Estimates for Dilaton--de Sitter Black Holes** _(factor investing alpha)_
  [2026-06-03](https://arxiv.org/abs/2606.05135v1)
  Charged dilaton black holes with a positive cosmological constant provide a useful arena in which to test how scalar hair modifies semiclassical physics in a spacetime with two Killing horizons. The Gao--Zhang solution realizes such a geometry in Einstein--Maxwell--dilaton theory by replacing a single Liouville potential, which is insufficient for asymptotically de Sitter boundary conditions, by a

## 3. GitHub Repos (Recently Updated)
- **[yebof/quant-agent](https://github.com/yebof/quant-agent)** ⭐ 4 · Python _(updated 2026-06-04)_
  LLM multi-agent quantitative trading system for US equities. 9 specialized agents (8 daily + 1 quarterly meta-reflector) with schema-enforced reasoning chains, deterministic Python risk filters, real 

- **[Leonard-Don/quant-trading-system](https://github.com/Leonard-Don/quant-trading-system)** ⭐ 0 · Python _(updated 2026-06-04)_
  FastAPI + React quantitative research workspace for backtesting, realtime monitoring, industry heatmaps, and cross-market experiments.

- **[haphap/MOSAIC-Agents](https://github.com/haphap/MOSAIC-Agents)** ⭐ 1 · Python _(updated 2026-06-04)_
  A-share self-improving multi-agent quantitative research framework

- **[sedimentary-republicofchile38/Polymarket-Trading-Bot-Rust](https://github.com/sedimentary-republicofchile38/Polymarket-Trading-Bot-Rust)** ⭐ 1 · Rust _(updated 2026-06-04)_
  Automate Polymarket trading in Rust with live, paper, and backtest strategies, CLOB auth, and balance, order, and redemption tools

- **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance)** ⭐ 11 · Python _(updated 2026-06-04)_
  Easily build, backtest and deploy your algo in just a few lines of code. Trade stocks, cryptos, and forex across exchanges one package.

- **[Qyxloq/blankly-finance](https://github.com/Qyxloq/blankly-finance)** ⭐ 0 · Python _(updated 2026-06-04)_
  Blankly-Finance: A powerful Algo-Trading-Framework for stocks, crypto, and forex. Features Multi-Exchange-API, Backtesting, and Trading-Bot tools.

- **[magikgmo4-ui/opt-trading](https://github.com/magikgmo4-ui/opt-trading)** ⭐ 0 · Python _(updated 2026-06-04)_
  Trading algorithms and strategies

- **[titouannwtt/freqtrade-ultimate](https://github.com/titouannwtt/freqtrade-ultimate)** ⭐ 3 · Python _(updated 2026-06-04)_
  Production-grade Freqtrade fork for algorithmic trading on Hyperliquid. Multi-bot OHLCV/pairlist caching, PlateauSampler hyperopt, walk-forward with CPCV, custom hyperopt losses, liquidation detection

- **[Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrency-Margin-Algorithmic](https://github.com/Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrency-Margin-Algorithmic)** ⭐ 2 · Python _(updated 2026-06-04)_
  This repository features Juno, an automated trade bot for Binance, designed for margin trading of cryptocurrencies. It utilizes advanced algorithmic strategies to optimize trading decisions and enhanc

- **[Healermm/AlphaLab](https://github.com/Healermm/AlphaLab)** ⭐ 0 · Python _(updated 2026-06-04)_
  A-share multi-factor research framework: 101/191+ alphas → IC evaluation → IR-weighted synthesis → sector ETF rotation → backtest with T+1, risk controls, and Monte Carlo robustness testing.

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 0 · None _(updated 2026-06-04)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[msd-rs/py-alpha-lib](https://github.com/msd-rs/py-alpha-lib)** ⭐ 95 · Rust _(updated 2026-06-04)_
  Alpha Library: A high-performance rolling window calculation library implemented in Rust with Python bindings. Used for financial data analysis and factor research.

- **[arrearsstocking863/hedgevision](https://github.com/arrearsstocking863/hedgevision)** ⭐ 0 · None _(updated 2026-06-04)_
  Build and backtest statistical arbitrage strategies with a local-first Python and React trading platform for cointegrated pairs, paper trading, and scaling

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-06-04)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[shivansh-sethi-kgp/statarb-walkforward-engine](https://github.com/shivansh-sethi-kgp/statarb-walkforward-engine)** ⭐ 0 · Python _(updated 2026-06-03)_
  An institutional-grade, end-to-end pairs trading pipeline designed to dynamically scan, model, and execute statistical arbitrage strategies across the NIFTY Bank universe.

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-04)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[milgar7969/alpaca-options-framework](https://github.com/milgar7969/alpaca-options-framework)** ⭐ 0 · Python _(updated 2026-06-03)_
  A Python framework for building live options trading bots on Alpaca Markets — asyncio, WebSocket streaming, position management, and all the API workarounds documented.

- **[midebsm-glitch/quant](https://github.com/midebsm-glitch/quant)** ⭐ 0 · HTML _(updated 2026-06-02)_
  Professional Options Trading · Signal Alignment Framework

## 4. Perplexity Strategy Synthesis
For a **$100–$1000** retail account, the most actionable systematic setups right now are the ones that are **low-turnover, cheap to execute, and easy to risk-cap**: short-horizon **crypto momentum with a regime filter**, **pair trading only in very liquid equities/ETFs**, and **defined-risk options hedges only when volatility is elevated enough to make convexity cheap relative to realized risk**. I cannot verify “April 2026” edge changes from live Twitter/substack data in the provided results, so for the “degraded in the last 6 months” part I will flag only where the evidence here suggests crowding or weak retail suitability.  

- **Crypto momentum with regime filter**
  - **Time horizon:** 1 day to 4 weeks, best on **daily data** for small accounts because fees/slippage matter less than on intraday crypto.
  - **Core idea:** Trade only when the broader regime is risk-on, then buy winners that are already outperforming.
  - **Entry rule:**  
    - Regime filter: BTC above its **200-day moving average** and/or its **50-day MA above 200-day MA**.  
    - Momentum filter: coin ranks in the **top decile** of 20–60 day returns versus a liquid universe.  
    - Trigger: enter on a **pullback to the 20-day MA** or a **break above the prior 10-day high** after the pullback.
  - **Exit rule:**  
    - Exit on a close below the **20-day MA** if you used the pullback entry, or below the **10-day low** if you used breakout entry.  
    - Time stop: exit after **20–30 trading days** if no trend expansion occurs.
  - **Position sizing:** Risk **0.5%–1%** of account per trade; for a $500 account that is **$2.50–$5** max loss, so position size must be tiny unless using a very tight stop.
  - **What supports it:** Cross-sectional momentum is one of the most persistent anomalies in liquid markets, and trend-following with regime filters is a standard way to reduce whipsaw in non-trending periods. The general “trade with the trend, use MA filters, and trail exits” logic is also echoed in the 2026 strategy guides in the results, though those are not academic evidence[1][3][6][8].
  - **Crowding / degradation risk:** **Moderate**. Pure momentum in crypto is highly visible and likely crowded at popular large caps, but the regime filter helps. This is the **least likely to have deteriorated severely** among the four categories you asked about.

- **Equity pair trading**
  - **Time horizon:** **5–30 trading days**; for small accounts, use **slow mean reversion**, not HFT.
  - **Universe:** Only very liquid pairs: ETFs, mega-cap duals, or same-sector leaders. Avoid single-name illiquidity.
  - **Entry rule:**  
    - Build a spread \(S = \log(P_A) - \beta \log(P_B)\), or use normalized price ratio.  
    - Enter when spread z-score reaches **\(|z| \ge 2\)** and the pair has a **stable historical hedge ratio** over at least **6–12 months**.  
    - Prefer pairs where both names remain in the same macro/sector regime.
  - **Exit rule:**  
    - Take profit at **\(z=0\) to \(0.5\)**.  
    - Stop out at **\(|z| \ge 3\)** or if the hedge ratio breaks materially.  
    - Add a **time stop** of **10–20 trading days**.
  - **Position sizing:** Dollar-neutral; risk **0.5%** of equity on the spread. For small accounts, use **tiny share counts** or ETFs rather than single stocks to keep borrow and slippage manageable.
  - **What supports it:** Pair trading remains a classic market-neutral approach, but the practical issue is execution cost and borrow availability; that matters more than signal quality for accounts under $1000. The general retail guidance in the results emphasizes clear entry/exit rule

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-04 via Conway's auto-publisher.*
