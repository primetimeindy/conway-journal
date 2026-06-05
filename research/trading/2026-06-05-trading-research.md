# Trading Nightly Research Brief — 2026-06-05

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-05T02:34:37, run time 144.9s._

## 1. Self-Analysis (Conway Trade Log)
```json
{
  "total_trades_logged": 130,
  "trades_last_7d": 28,
  "top_symbols_7d": [
    [
      "ZEC/USDC",
      10
    ],
    [
      "INJ/USDC",
      8
    ],
    [
      "DOGE/USDC",
      5
    ],
    [
      "BTC/USDC",
      5
    ]
  ],
  "side_breakdown_7d": {
    "sell": 15,
    "buy": 13
  }
}
```

## 2. arXiv Papers (Last 60 Days)
- **TailLoR: Protecting Principal Components in Parameter-Efficient Continual Learning** _(deep learning volatility forecasting)_
  [2026-06-04](https://arxiv.org/abs/2606.06494v1)
  Parameter-efficient finetuning methods based on spectral decomposition have enabled progress in Continual Learning. In this paper we introduce TailLoR, which utilizes the singular bases U and V of the pre-trained weights as a fixed reference frame to learn a low-rank update applied to the singular value matrix. A soft spectral penalty discourages updates aligned with dominant singular directions, 

- **HANDOFF: Humanoid Agentic Task-Space Whole-Body Control via Distilled Complementary Teachers** _(deep learning volatility forecasting)_
  [2026-06-04](https://arxiv.org/abs/2606.06493v1)
  For a humanoid robot to be deployed in the real world, the choice of command space (i.e., the interface between task planning and whole-body control) is crucial. Existing whole-body controllers typically demand dense kinematic or spatial references that planners struggle to synthesize from task semantics. We instead propose a compact, explicit interface that is intuitive, general, modular, and exp

- **TempoVLA: Learning Speed-Controllable Vision-Language-Action Policies** _(deep learning volatility forecasting)_
  [2026-06-04](https://arxiv.org/abs/2606.06491v1)
  Robot manipulation alternates between low-risk transit phases that call for fast execution and high-risk contact stages that demand slow, precise motion. Yet existing Vision-Language-Action models (VLAs) only inherit a single fixed speed from training demonstrations. Prior efforts to accelerate VLAs through model compression, KV-cache reuse, or reinforcement learning only shift the policy from one

- **TailLoR: Protecting Principal Components in Parameter-Efficient Continual Learning** _(reinforcement learning portfolio)_
  [2026-06-04](https://arxiv.org/abs/2606.06494v1)
  Parameter-efficient finetuning methods based on spectral decomposition have enabled progress in Continual Learning. In this paper we introduce TailLoR, which utilizes the singular bases U and V of the pre-trained weights as a fixed reference frame to learn a low-rank update applied to the singular value matrix. A soft spectral penalty discourages updates aligned with dominant singular directions, 

- **HANDOFF: Humanoid Agentic Task-Space Whole-Body Control via Distilled Complementary Teachers** _(reinforcement learning portfolio)_
  [2026-06-04](https://arxiv.org/abs/2606.06493v1)
  For a humanoid robot to be deployed in the real world, the choice of command space (i.e., the interface between task planning and whole-body control) is crucial. Existing whole-body controllers typically demand dense kinematic or spatial references that planners struggle to synthesize from task semantics. We instead propose a compact, explicit interface that is intuitive, general, modular, and exp

- **TempoVLA: Learning Speed-Controllable Vision-Language-Action Policies** _(reinforcement learning portfolio)_
  [2026-06-04](https://arxiv.org/abs/2606.06491v1)
  Robot manipulation alternates between low-risk transit phases that call for fast execution and high-risk contact stages that demand slow, precise motion. Yet existing Vision-Language-Action models (VLAs) only inherit a single fixed speed from training demonstrations. Prior efforts to accelerate VLAs through model compression, KV-cache reuse, or reinforcement learning only shift the policy from one

- **DNQ: Deep Nash Q-Network for Partially Observable n-Player Games** _(cryptocurrency trading)_
  [2026-06-04](https://arxiv.org/abs/2606.06480v1)
  Many real-world competitive systems require multiple decision-makers to act simultaneously under shared constraints, limited information, and repeated interaction, as in auctions, resource allocation, and security competition. We study multi-turn simultaneous bidding as a controlled testbed for such problems and propose DNQ, a solver-in-the-loop equilibrium supervision framework for training biddi

- **You Only Index Once: Cross-Layer Sparse Attention with Shared Routing** _(cryptocurrency trading)_
  [2026-06-04](https://arxiv.org/abs/2606.06467v1)
  Long-context inference in modern LLMs is increasingly constrained by decoding efficiency, especially in reasoning-heavy settings where models generate long intermediate chains of thought. Existing sparse attention methods often face a practical efficiency-quality trade-off. Structured block sparse methods typically provide stronger acceleration but incur noticeable quality loss, while token sparse

- **RiskFlow: Fast and Faithful Safety-Critical Traffic Scenario Generation** _(cryptocurrency trading)_
  [2026-06-04](https://arxiv.org/abs/2606.06423v1)
  Safety-critical traffic scenario generation is essential for evaluating autonomous driving systems under rare but high-risk interactions. Existing diffusion-based methods offer strong controllability in closed-loop generation, but their iterative denoising process is computationally expensive and may accumulate sampling and guidance errors over long rollouts, causing unrealistic motion artifacts s

- **Self-Augmenting Retrieval for Diffusion Language Models** _(options volatility surface)_
  [2026-06-04](https://arxiv.org/abs/2606.06474v1)
  Discrete diffusion language models generate text by iteratively denoising an entire response in parallel. At each step, they predict tentative tokens for every masked position, committing the confident predictions to the output and discarding the unconfident ones. We show that the discarded tokens are in fact a useful lookahead signal for retrieval-augmented generation: even low-confidence tokens 

- **Goedel-Architect: Streamlining Formal Theorem Proving with Blueprint Generation and Refinement** _(options volatility surface)_
  [2026-06-04](https://arxiv.org/abs/2606.06468v1)
  We introduce Goedel-Architect, an agentic framework for formal theorem proving in Lean 4 centered on blueprint generation and refinement. A blueprint is a dependency graph of definitions and lemmas that builds up to the main theorem. First, Goedel-Architect generates a blueprint of formally stated definitions and lemmas, along with declared dependencies. This blueprint is optionally guided by a na

- **Breakeven demonstration of quantum low-density parity-check codes** _(options volatility surface)_
  [2026-06-04](https://arxiv.org/abs/2606.06455v1)
  High-rate quantum low-density parity-check (qLDPC) codes are a leading candidate for fault-tolerant quantum computing. They feature higher encoding rates than planar alternatives such as the surface code, but their implementation often entails significant hardware hurdles like the need for long-range couplers. We leverage the flexibility of a trapped-ion quantum computer to demonstrate nine quantu

- **Event Detection for Parameter-to-KPI Dependency Learning for AI-RAN** _(factor investing alpha)_
  [2026-06-04](https://arxiv.org/abs/2606.06459v1)
  Next-generation wireless networks are expected to rely on multiple concurrent AI-driven control functions that optimize different network objectives simultaneously, particularly in AI-integrated and open radio access network architectures such as AI Radio Access Network (AI-RAN) and Open Radio Access Network (O-RAN). When these functions interact, they can interfere with one another in ways that a

- **1/3 Fractional and Gapless Integer Quantum Anomalous Hall States in Rhombohedral Graphene** _(factor investing alpha)_
  [2026-06-04](https://arxiv.org/abs/2606.06450v1)
  The fractional quantum anomalous Hall (FQAH) effect occurs in moiré superlattices in both twisted bilayer MoTe$_2$ and rhombohedral $n$-layer graphene aligned to hexagonal boron nitride (R$n$G/hBN) as a novel quantum phase driven by intertwined electron correlation and topology. Although several fractional states in the Jain sequence have been identified, the $1/3$ state, the most robust and funda

- **rsx: A high-performance streaming toolkit for RAD-seq sex determination** _(factor investing alpha)_
  [2026-06-04](https://arxiv.org/abs/2606.06434v1)
  Restriction site-associated DNA sequencing (RAD-seq) is widely used to discover sex-linked markers in non-model organisms, but large studies produce marker tables with millions of RAD tags. RADSex provides the reference workflow for building marker-by-individual depth tables and testing sex-biased marker distributions, but its depth, merge, and related table-building commands grow memory-hungry, a

## 3. GitHub Repos (Recently Updated)
- **[haphap/MOSAIC-Agents](https://github.com/haphap/MOSAIC-Agents)** ⭐ 1 · Python _(updated 2026-06-05)_
  A-share self-improving multi-agent quantitative research framework

- **[Leonard-Don/quant-trading-system](https://github.com/Leonard-Don/quant-trading-system)** ⭐ 0 · Python _(updated 2026-06-05)_
  FastAPI + React quantitative research workspace for backtesting, realtime monitoring, industry heatmaps, and cross-market experiments.

- **[allureking/cs2-inventory-manager](https://github.com/allureking/cs2-inventory-manager)** ⭐ 2 · Python _(updated 2026-06-05)_
  CS2 skin quantitative trading monitor — real-time pricing, P&L analysis, quant signals, and automated ops (FastAPI + SQLite + Alpine.js)

- **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance)** ⭐ 11 · Python _(updated 2026-06-05)_
  Easily build, backtest and deploy your algo in just a few lines of code. Trade stocks, cryptos, and forex across exchanges one package.

- **[Qyxloq/blankly-finance](https://github.com/Qyxloq/blankly-finance)** ⭐ 0 · Python _(updated 2026-06-05)_
  Blankly-Finance: A powerful Algo-Trading-Framework for stocks, crypto, and forex. Features Multi-Exchange-API, Backtesting, and Trading-Bot tools.

- **[sedimentary-republicofchile38/Polymarket-Trading-Bot-Rust](https://github.com/sedimentary-republicofchile38/Polymarket-Trading-Bot-Rust)** ⭐ 1 · Rust _(updated 2026-06-05)_
  Automate Polymarket trading in Rust with live, paper, and backtest strategies, CLOB auth, and balance, order, and redemption tools

- **[magikgmo4-ui/opt-trading](https://github.com/magikgmo4-ui/opt-trading)** ⭐ 0 · Python _(updated 2026-06-05)_
  Trading algorithms and strategies

- **[Lumimojjav/Qwik-CoinSwapAi-Crypto-Coins-Bitecoin-BCH](https://github.com/Lumimojjav/Qwik-CoinSwapAi-Crypto-Coins-Bitecoin-BCH)** ⭐ 0 · JavaScript _(updated 2026-06-05)_
  This repository provides Qwik, a CoinSwapAI sniper bot for trading cryptocurrencies, including Bitcoin and Bitcoin Cash (BCH). It utilizes AI algorithms to identify and execute profitable trades, enha

- **[Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrency-Margin-Algorithmic](https://github.com/Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrency-Margin-Algorithmic)** ⭐ 2 · Python _(updated 2026-06-05)_
  This repository features Juno, an automated trade bot for Binance, designed for margin trading of cryptocurrencies. It utilizes advanced algorithmic strategies to optimize trading decisions and enhanc

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 0 · None _(updated 2026-06-05)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[julienwax/Factor-Modeling](https://github.com/julienwax/Factor-Modeling)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-05)_
  Factor modeling framework for US equities, integrating both statistical (PCA-based) and fundamental factor models. The repository features advanced estimation of factor and idiosyncratic covariance ma

- **[Healermm/AlphaLab](https://github.com/Healermm/AlphaLab)** ⭐ 0 · Python _(updated 2026-06-04)_
  A-share multi-factor research framework: 101/191+ alphas → IC evaluation → IR-weighted synthesis → sector ETF rotation → backtest with T+1, risk controls, and Monte Carlo robustness testing.

- **[arrearsstocking863/hedgevision](https://github.com/arrearsstocking863/hedgevision)** ⭐ 0 · None _(updated 2026-06-05)_
  Build and backtest statistical arbitrage strategies with a local-first Python and React trading platform for cointegrated pairs, paper trading, and scaling

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-06-05)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[aman3599/crypto-stat-arb](https://github.com/aman3599/crypto-stat-arb)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-05)_
  End-to-end statistical arbitrage system for framework for identifying and trading mean-reverting spreads between cointegrated cryptocurrency pairs

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-05)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[midebsm-glitch/quant](https://github.com/midebsm-glitch/quant)** ⭐ 0 · HTML _(updated 2026-06-05)_
  Professional Options Trading · Signal Alignment Framework

- **[milgar7969/alpaca-options-framework](https://github.com/milgar7969/alpaca-options-framework)** ⭐ 0 · Python _(updated 2026-06-04)_
  A Python framework for building live options trading bots on Alpaca Markets — asyncio, WebSocket streaming, position management, and all the API workarounds documented.

## 4. Perplexity Strategy Synthesis
I can give you a **practical shortlist**, but I cannot honestly identify **“what is cheap right now” in April 2026** from the search results provided, because the results are generic trading guides and do not include current options-implied-volatility data, live crypto regime metrics, or recent academic papers/threads on the specific edges you asked about. What I *can* do is give you **small-account-friendly, systematic templates** that are defensible from the sources you provided, and flag which ones are likely to have **degraded/crowded** based on the general evidence here.  

## 1) Crypto momentum with regime filters

For small accounts, the most actionable version is a **trend-following breakout/pullback system** on liquid crypto majors, but only when a higher-timeframe regime filter is bullish. General trading guidance in the supplied results emphasizes trading **with the trend**, using **moving averages**, **higher highs/higher lows**, and entering on **pullbacks or breakouts with volume confirmation**.[1][2]

**Concrete rules**
- **Universe:** BTC, ETH, and 1–3 highly liquid large caps only.
- **Time horizon:** 1D swing trades, held **3–20 days**.
- **Regime filter:** Trade longs only when:
  - 50-day SMA > 200-day SMA on daily chart, and
  - price is above the 200-day SMA, and
  - a higher high / higher low structure is intact.[1][2]
- **Entry:**
  - Buy the first pullback to the 20-day EMA after a breakout close above the prior 20-day high, *or*
  - Buy a 20-day high breakout only if daily volume is above its 20-day average.[1]
- **Exit:**
  - Initial stop below the most recent swing low or below the 20-day EMA, whichever is lower.
  - Take partial profits at \(2R\), trail the rest with a 10-day EMA or prior day low.
  - Exit fully if daily close falls below the 20-day EMA for 2 consecutive sessions.
- **Position sizing:**
  - Risk **0.5% to 1%** of account equity per trade; the small-account guidance in the results repeatedly emphasizes strict stop-losses and around the 1% risk rule.[3][4]
  - For a \$100–\$1000 account, that means about \$1–\$10 max loss per trade.

**Crowding / degradation risk**
- **Moderate to high crowding risk**. Trend-following in crypto is widely used, and the provided sources are generic rather than evidence of a new edge.[1][2]
- This is still the **best default** if you want something robust, but it is unlikely to be a secret edge.

## 2) Equity pair trading

For a small account, pair trading is only workable if you keep it **simple, low-leverage, and broker-cost aware**. The sources you provided do not contain a pair-trading paper or live signal set, so this is necessarily a more general market-structure recommendation rather than a source-backed new edge.[2][3][4]

**Concrete rules**
- **Universe:** Highly liquid same-sector pairs, e.g. two large-cap names in semiconductors, banks, or consumer staples.
- **Time horizon:** **5–30 trading days**.
- **Spread construction:** Use the ratio \(P_A/P_B\) or a standardized spread with a 60-day z-score.
- **Entry:**
  - Go long the underperformer and short the outperformer when the spread z-score is \(\ge 2.0\) in magnitude and sector fundamentals/news are not in a strong one-way catalyst regime.
- **Exit:**
  - Close when z-score reverts to **0.5** or crosses zero.
  - Hard stop if z-score moves to **3.0** against you.
  - Time stop after **20 sessions** if no mean reversion occurs.
- **Position sizing:**
  - Equal-dollar long and short legs.
  - Gross exposure capped at **1.5x to 2x** account equity only if your broker allows it and you understand borrow costs; otherwise keep i

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-05 via Conway's auto-publisher.*
