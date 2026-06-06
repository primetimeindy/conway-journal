# Trading Nightly Research Brief — 2026-06-06

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-06T02:32:20, run time 23.0s._

## 1. Self-Analysis (Conway Trade Log)
```json
{
  "total_trades_logged": 130,
  "trades_last_7d": 24,
  "top_symbols_7d": [
    [
      "ZEC/USDC",
      8
    ],
    [
      "INJ/USDC",
      7
    ],
    [
      "BTC/USDC",
      5
    ],
    [
      "DOGE/USDC",
      4
    ]
  ],
  "side_breakdown_7d": {
    "sell": 13,
    "buy": 11
  }
}
```

## 2. arXiv Papers (Last 60 Days)
- **Regret Minimization with Adaptive Opponents in Repeated Games** _(quantitative trading strategy)_
  [2026-06-04](https://arxiv.org/abs/2606.06486v1)
  In this paper, we study regret minimization in repeated games with \emph{adaptive} opponents who can respond based on histories of play. The standard metric of \emph{external regret} in online learning is known to fail to capture such adaptivity. To account for players' counterfactual reasoning, we introduce {\tt Repeated Policy Regret (RP-Regret)}, a game-theoretic metric that measures the differ

- **DNQ: Deep Nash Q-Network for Partially Observable n-Player Games** _(quantitative trading strategy)_
  [2026-06-04](https://arxiv.org/abs/2606.06480v1)
  Many real-world competitive systems require multiple decision-makers to act simultaneously under shared constraints, limited information, and repeated interaction, as in auctions, resource allocation, and security competition. We study multi-turn simultaneous bidding as a controlled testbed for such problems and propose DNQ, a solver-in-the-loop equilibrium supervision framework for training biddi

- **Goedel-Architect: Streamlining Formal Theorem Proving with Blueprint Generation and Refinement** _(quantitative trading strategy)_
  [2026-06-04](https://arxiv.org/abs/2606.06468v1)
  We introduce Goedel-Architect, an agentic framework for formal theorem proving in Lean 4 centered on blueprint generation and refinement. A blueprint is a dependency graph of definitions and lemmas that builds up to the main theorem. First, Goedel-Architect generates a blueprint of formally stated definitions and lemmas, along with declared dependencies. This blueprint is optionally guided by a na

- **TempoVLA: Learning Speed-Controllable Vision-Language-Action Policies** _(momentum crash risk)_
  [2026-06-04](https://arxiv.org/abs/2606.06491v1)
  Robot manipulation alternates between low-risk transit phases that call for fast execution and high-risk contact stages that demand slow, precise motion. Yet existing Vision-Language-Action models (VLAs) only inherit a single fixed speed from training demonstrations. Prior efforts to accelerate VLAs through model compression, KV-cache reuse, or reinforcement learning only shift the policy from one

- **How abundant are good interpolators?** _(momentum crash risk)_
  [2026-06-04](https://arxiv.org/abs/2606.06469v1)
  Let $S$ be the set of unit norm linear classifiers $θ\in \mathbb{R}^d$ which correctly classify every point of a labeled dataset $(X_i,y_i)_{i=1}^n$, $X_i \in \mathbb{R}^d$, $y_i \in \{-1,+1\}$, with a possibly negative margin $κ$ fixed in advance. Under two natural data-generating distributions of the $(X,y)$ pairs -- a Gaussian mixture model and a logistic model with Gaussian features -- and in 

- **Revising Context, Shifting Simulated Stance: Auditing LLM-Based Stance Simulation in Online Discussions** _(momentum crash risk)_
  [2026-06-04](https://arxiv.org/abs/2606.06443v1)
  Large language models are increasingly used to simulate social media users and infer how individuals may respond to online discussions. However, it remains unclear whether these simulations reflect precise user-specific beliefs or whether they are highly sensitive to semantically independent changes in conversational contexts. In this work, we study counterfactual context revision as a framework f

- **TempoVLA: Learning Speed-Controllable Vision-Language-Action Policies** _(mean reversion statistical arbitrage)_
  [2026-06-04](https://arxiv.org/abs/2606.06491v1)
  Robot manipulation alternates between low-risk transit phases that call for fast execution and high-risk contact stages that demand slow, precise motion. Yet existing Vision-Language-Action models (VLAs) only inherit a single fixed speed from training demonstrations. Prior efforts to accelerate VLAs through model compression, KV-cache reuse, or reinforcement learning only shift the policy from one

- **Statistically and Computationally Optimal Estimation and Inference of Common Subspaces** _(mean reversion statistical arbitrage)_
  [2026-06-04](https://arxiv.org/abs/2606.06483v1)
  Given multiple data matrices, many problems in statistics and data science rely on estimating a common subspace that captures certain structure shared by all the data matrices. In this paper we investigate the statistical and computational limits for the common subspace model in which one observes a collection of symmetric low-rank matrices perturbed by noise, where each low-rank matrix shares the

- **Two-Sample Hypothesis Testing for Subspace Equality in Network Data** _(mean reversion statistical arbitrage)_
  [2026-06-04](https://arxiv.org/abs/2606.06482v1)
  In many settings one is often interested in determining whether two networks share some joint structural connectivity patterns such as communities. However, while communities may be shared across networks, edge probabilities may differ significantly. Therefore, in this paper we consider testing a general null hypothesis that two networks have the same underlying subspace, which in particular inclu

- **Statistically and Computationally Optimal Estimation and Inference of Common Subspaces** _(regime detection market)_
  [2026-06-04](https://arxiv.org/abs/2606.06483v1)
  Given multiple data matrices, many problems in statistics and data science rely on estimating a common subspace that captures certain structure shared by all the data matrices. In this paper we investigate the statistical and computational limits for the common subspace model in which one observes a collection of symmetric low-rank matrices perturbed by noise, where each low-rank matrix shares the

- **Operation-Guided Progressive Human-to-AI Text Transformation Benchmark for Multi-Granularity AI-Text Detection** _(regime detection market)_
  [2026-06-04](https://arxiv.org/abs/2606.06481v1)
  As AI writing assistants become increasingly integrated into real-world drafting and revision workflows, many documents are no longer purely human-written or AI-generated, but instead result from progressive human-AI co-editing. However, existing AI-text detection benchmarks largely focus on final outputs and provide limited understanding of how AI authorship signals emerge, accumulate, or disappe

- **Complexity-Balanced Diffusion Splitting** _(regime detection market)_
  [2026-06-04](https://arxiv.org/abs/2606.06477v1)
  Standard continuous-time generative models rely on monolithic architectures that must navigate vastly different signal regimes, from isotropic noise to intricate data distributions. While scaling model capacity improves performance, deploying a massive network uniformly across the entire generative timeline is inherently inefficient. In this work, we propose Complexity-Balanced Splitting (CBS), a 

- **TailLoR: Protecting Principal Components in Parameter-Efficient Continual Learning** _(deep learning volatility forecasting)_
  [2026-06-04](https://arxiv.org/abs/2606.06494v1)
  Parameter-efficient finetuning methods based on spectral decomposition have enabled progress in Continual Learning. In this paper we introduce TailLoR, which utilizes the singular bases U and V of the pre-trained weights as a fixed reference frame to learn a low-rank update applied to the singular value matrix. A soft spectral penalty discourages updates aligned with dominant singular directions, 

- **HANDOFF: Humanoid Agentic Task-Space Whole-Body Control via Distilled Complementary Teachers** _(deep learning volatility forecasting)_
  [2026-06-04](https://arxiv.org/abs/2606.06493v1)
  For a humanoid robot to be deployed in the real world, the choice of command space (i.e., the interface between task planning and whole-body control) is crucial. Existing whole-body controllers typically demand dense kinematic or spatial references that planners struggle to synthesize from task semantics. We instead propose a compact, explicit interface that is intuitive, general, modular, and exp

- **TempoVLA: Learning Speed-Controllable Vision-Language-Action Policies** _(deep learning volatility forecasting)_
  [2026-06-04](https://arxiv.org/abs/2606.06491v1)
  Robot manipulation alternates between low-risk transit phases that call for fast execution and high-risk contact stages that demand slow, precise motion. Yet existing Vision-Language-Action models (VLAs) only inherit a single fixed speed from training demonstrations. Prior efforts to accelerate VLAs through model compression, KV-cache reuse, or reinforcement learning only shift the policy from one

- **What it takes to solve the Hubble tension through Modifications of Cosmological Recombination II: in light of ACT DR6 and DESI DR2** _(transformer financial time series)_
  [2026-06-04](https://arxiv.org/abs/2606.06495v1)
  We construct data-driven solutions to the Hubble tension, in light of recent data from the Atacama Cosmology Telescope (ACT DR6) and the Dark Energy Spectroscopic Instrument (DESI DR2). We search for the minimal modification to the recombination history through a time-varying electron mass $m_e(z)$ that increases the best-fit $H_0$ inferred from CMB data toward the SH0ES value, without worsening t

- **Code2LoRA: Hypernetwork-Generated Adapters for Code Language Models under Software Evolution** _(transformer financial time series)_
  [2026-06-04](https://arxiv.org/abs/2606.06492v1)
  Code language models need repository-level context to resolve imports, APIs, and project conventions. Existing methods inject this knowledge as long inputs (retrieved through RAG or dependency analysis) or through per-repository fine-tuning and LoRA -- costly at repository scale and brittle to evolving codebases. We introduce Code2LoRA, a hypernetwork framework that generates repository-specific L

- **TempoVLA: Learning Speed-Controllable Vision-Language-Action Policies** _(transformer financial time series)_
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
- **[Vixoq/vnpy](https://github.com/Vixoq/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-06)_
  Open source quantitative trading platform development framework based

- **[RafaEngineer/strapsim_portfolio_similarity_metric](https://github.com/RafaEngineer/strapsim_portfolio_similarity_metric)** ⭐ 1 · PHP _(updated 2026-06-06)_
  📊 Calculate portfolio similarity metrics to enhance ETF alignment and optimize trading strategies in quantitative finance.

- **[HaSerZin/trade_political_distance_wto](https://github.com/HaSerZin/trade_political_distance_wto)** ⭐ 2 · Jupyter Notebook _(updated 2026-06-06)_
  🌍 Model political distance and trade dynamics using a quantitative framework to enhance understanding of international trade relationships.

- **[v0acc0002/deepseek-trading-experiment](https://github.com/v0acc0002/deepseek-trading-experiment)** ⭐ 5 · Python _(updated 2026-06-06)_
  🤖 Explore AI-driven trading with the DeepSeek crypto bot, designed for learning rather than profit through backtesting strategies and financial analysis.

- **[opop753/AI-Powered-Crypto-Trading-Bot](https://github.com/opop753/AI-Powered-Crypto-Trading-Bot)** ⭐ 2 · JavaScript _(updated 2026-06-06)_
  🤖 Power your trading with an AI-driven crypto bot that delivers live data, trading strategies, charts, news, and market session timelines.

- **[Qyxloq/blankly-finance](https://github.com/Qyxloq/blankly-finance)** ⭐ 0 · Python _(updated 2026-06-06)_
  Blankly-Finance: A powerful Algo-Trading-Framework for stocks, crypto, and forex. Features Multi-Exchange-API, Backtesting, and Trading-Bot tools.

- **[magikgmo4-ui/opt-trading](https://github.com/magikgmo4-ui/opt-trading)** ⭐ 0 · Python _(updated 2026-06-06)_
  Trading algorithms and strategies

- **[astarek1983/street-algo-trader](https://github.com/astarek1983/street-algo-trader)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-06)_
  🚀 Implement algorithmic trading strategies for a Jane Street-style exchange, featuring market-making, arbitrage, and momentum signals.

- **[Anna-007-tech/algorithmic-trading-ai](https://github.com/Anna-007-tech/algorithmic-trading-ai)** ⭐ 2 · None _(updated 2026-06-06)_
  📈 Explore AI-driven trading strategies through data analysis of forex and crypto volatility using PCA, K-means, and neural networks.

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 0 · None _(updated 2026-06-06)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[Akshith-Gandham/alpha-factor-research](https://github.com/Akshith-Gandham/alpha-factor-research)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-05)_
  Sector-neutral long/short equity pipeline with rolling IC evaluation, IC-weighted signal combination, and regime analysis on S&P 500   2015-2024

- **[julienwax/Factor-Modeling](https://github.com/julienwax/Factor-Modeling)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-05)_
  Factor modeling framework for US equities, integrating both statistical (PCA-based) and fundamental factor models. The repository features advanced estimation of factor and idiosyncratic covariance ma

- **[arrearsstocking863/hedgevision](https://github.com/arrearsstocking863/hedgevision)** ⭐ 0 · None _(updated 2026-06-06)_
  Build and backtest statistical arbitrage strategies with a local-first Python and React trading platform for cointegrated pairs, paper trading, and scaling

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-06-06)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[Nithyadodda07/pairs-trading-strategy](https://github.com/Nithyadodda07/pairs-trading-strategy)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-05)_
  Market-neutral pairs trading strategy using cointegration and statistical arbitrage on Indian equities (RELIANCE & ONGC)

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-06)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[henryhuangh/wealthsimple-python](https://github.com/henryhuangh/wealthsimple-python)** ⭐ 12 · Python _(updated 2026-06-05)_
  Wealthsimple trade API library for python based on the new wealthsimple graphql framework

- **[midebsm-glitch/quant](https://github.com/midebsm-glitch/quant)** ⭐ 0 · HTML _(updated 2026-06-05)_
  Professional Options Trading · Signal Alignment Framework

## 4. Perplexity Strategy Synthesis
I can give you a **practical shortlist**, but I need to flag a limitation: the search results you provided do **not** include the kind of source base needed to responsibly identify “most actionable right now” edges in **April 2026** for crypto momentum, equity pair trading, options tail hedges, or fresh papers/Twitter alpha. The results are mostly general trading-education pages and YouTube/podcast content, not the specific recent papers, option-surface data, or trade-performance evidence needed to verify live edges or degradation. [1][2][3][4][5][6][7][9]

That means I can do two things reliably:
- Give you **small-account-friendly systematic frameworks** that fit your constraints and are consistent with the generic risk-management guidance in the results. [2][3][4][7]
- Flag what is **likely crowded/degraded in principle**, but I cannot honestly claim “last 6 months” degradation without proper recent performance data. [1][2][9]

## 1) Crypto momentum with regime filters

A retail-suitable version is a **trend-following breakout system** on liquid majors, traded only when the market is in a clear risk-on regime. Momentum and trend-following are explicitly listed as workable strategy families in the sources, and the sources emphasize clear entry/exit rules, trend confirmation, and strict risk limits. [1][2][3][4][7]

**Concrete setup**
- **Universe:** BTC, ETH, and the top 5–10 liquid large-cap alts only.
- **Time horizon:** 1-day to 10-day holds.
- **Regime filter:** Trade long only when:
  - BTC is above its 50-day moving average, and
  - BTC’s 20-day realized volatility is not spiking sharply versus the prior month, and
  - BTC is making higher highs/higher lows on the daily chart.  
  This is an inference built from the trend-following and higher-high/higher-low guidance in the sources, not a directly sourced crypto-specific rule. [1][2][5]
- **Entry:** Buy on a close above the prior 20-day high, or buy the first pullback that holds above the 20-day breakout level. Breakout-with-volume and pullback-in-trend are both explicitly supported by the strategy descriptions in the results. [1][5]
- **Exit:** Exit on a daily close back below the 20-day low, or use a 2×ATR trailing stop from entry. The sources support exits on trend weakening, reversal signals, or trailing stops. [1][5][6]
- **Position sizing:** Risk **0.5% to 1% of account equity per trade**; the results repeatedly emphasize 1% or less for small accounts. For a $100 account, that means risking $0.50–$1 per trade; for $1,000, $5–$10. [3][4]
- **Practical note for $100–$1000:** Use **spot only** if fees/slippage are material; per-trade sizing must be tiny because crypto leverage can turn a good edge into account destruction very quickly. This is an inference from the risk-management guidance. [2][4]

**What to avoid**
- **Low-cap alt momentum** is the most likely to be crowded and brittle because liquidity is worse and reversals are sharper; the provided sources do not directly measure degradation, but the liquidity advice strongly implies focusing on liquid assets. [1][2][3]

## 2) Equity pair trading

Pair trading is not directly covered in the provided sources, so I can only give you a **standard retail implementation** based on the general rules in the results: objective entry/exit rules, backtesting, and strict risk control. [2][4][7]

**Concrete setup**
- **Universe:** Highly liquid U.S. stocks in the same sector/industry.
- **Time horizon:** 5 to 30 trading days.
- **Selection filter:** Pick pairs with:
  - similar business model,
  - high average daily dollar volume,
  - stable historical correlation over 6–24 months.  
  This is standard pair-trading practice, but it is an inference rather than something directly stated in the search results.
- **Signal:** Compute 

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-06 via Conway's auto-publisher.*
