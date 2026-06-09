# Trading Nightly Research Brief — 2026-06-09

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-09T01:30:59, run time 25.9s._

## 1. Self-Analysis (Conway Trade Log)
```json
{
  "total_trades_logged": 130,
  "trades_last_7d": 14,
  "top_symbols_7d": [
    [
      "ZEC/USDC",
      4
    ],
    [
      "INJ/USDC",
      4
    ],
    [
      "BTC/USDC",
      3
    ],
    [
      "DOGE/USDC",
      3
    ]
  ],
  "side_breakdown_7d": {
    "sell": 8,
    "buy": 6
  }
}
```

## 2. arXiv Papers (Last 60 Days)
- **Weighted universal approximation of differentiable maps on infinite-dimensional manifolds** _(quantitative trading strategy)_
  [2026-06-08](https://arxiv.org/abs/2606.09820v1)
  We generalize the universal approximation theorem for functional input neural networks (FNN) to differentiable maps by including the approximation of the derivatives. A FNN maps the input from a possibly infinite-dimensional weighted manifold to the real-valued hidden layer, on which a non-linear scalar activation function is applied, and then returns the output into a Banach space via some linear

- **Persistent currents, whirlpools, and local Chern markers in twisted TMD Chern insulators** _(quantitative trading strategy)_
  [2026-06-08](https://arxiv.org/abs/2606.09812v1)
  Recent materials advances have made it possible to fabricate twisted transition metal dichalcogenide homobilayers. These systems have been shown to host integer and fractional Chern insulating states. Because of spontaneous time reversal symmetry breaking, their ground state harbors intriguing spin-polarized currents with whirlpools on the moiré length scale that can be measured by scanning probe 

- **High Mach number limit of the compressible Navier--Stokes equations in critical Besov spaces** _(quantitative trading strategy)_
  [2026-06-08](https://arxiv.org/abs/2606.09808v1)
  We investigate the high Mach number limit for the scaled compressible Navier--Stokes system in the critical Besov framework. In the scaled momentum equation, the pressure force is represented by the term \(\varepsilon^2\nabla a^\varepsilon\), where $\varepsilon$ is the inverse Mach number; as \(\varepsilon\to0\), the formal limiting system is the compressible pressureless Navier--Stokes system. Th

- **Adaptive Derivative Estimation via Stein's Unbiased Risk** _(momentum crash risk)_
  [2026-06-08](https://arxiv.org/abs/2606.09829v1)
  Estimating derivatives from noisy sampled data is fundamental to control, human--computer interaction, and biomedical engineering. Causal FIR derivative filters offer a natural approach for this challenge, yet their performance depend on their length. While short filters amplify noise, long filters introduce smoothing bias. We present SURDE (SURE Derivative Estimator), which addresses this tradeof

- **Satellite compaction pathways: environmental drivers shaping dwarf galaxy corpulence in the TNG50 simulation** _(momentum crash risk)_
  [2026-06-08](https://arxiv.org/abs/2606.09817v1)
  We explore the physical mechanisms driving dwarf galaxy corpulence, focusing on those that end up as compact satellites. We select dwarf galaxies at $z=0$ with $\log(M_\star/{\rm M}_\odot)$ between 8.4 and 9.2 from the TNG50 hydrodynamical simulation after excluding systems flagged as potentially spurious. Compact dwarfs are defined according to the $z=0$ size-mass relation as those on the lower e

- **Evaluation Cards: An Interpretive Layer for AI Evaluation Reporting** _(momentum crash risk)_
  [2026-06-08](https://arxiv.org/abs/2606.09809v1)
  AI evaluation results are produced at scale but reported inconsistently across leaderboards, model cards, benchmark papers, and company blogs. The cost is interpretive: readers cannot reliably compare results across sources, identify what a report omits, or trace an aggregate claim to its underlying evidence. Recent efforts address isolated components but leave three gaps: they cover only narrow s

- **An Agency-Transferring Model-Free Policy Enhancement Technique** _(mean reversion statistical arbitrage)_
  [2026-06-08](https://arxiv.org/abs/2606.09825v1)
  Training reinforcement learning (RL) policies from scratch is   costly: it requires careful reward and environment design,   extensive tuning, and substantial computation.   Yet many control problems already have a functional but   suboptimal policy available as a baseline.   This paper proposes a method for embedding such a baseline into   the RL training process, simultaneously improving trainin

- **Topological Triplons in the Pinwheel Valence Bond Solid on the Kagome Lattice** _(mean reversion statistical arbitrage)_
  [2026-06-08](https://arxiv.org/abs/2606.09823v1)
  We investigate the triplon excitations of the pinwheel valence-bond-solid phase on the deformed kagome lattice compound Rb2Cu3SnF12. Using bond-operator mean-field theory, we compute the triplon band structure, dynamical structure factor, Berry curvatures and the associated thermal Hall response. We show that the presence of Dzyaloshinskii-Moriya interactions and an external magnetic field are key

- **PTL-Diffusion: Manifold-Aware Diffusion with Periodic Terminal Laws** _(mean reversion statistical arbitrage)_
  [2026-06-08](https://arxiv.org/abs/2606.09816v1)
  Standard diffusion models typically use a single time-homogeneous Gaussian terminal distribution as the reference law for generation. While this choice is analytically convenient and empirically powerful, it provides little explicit structure for data concentrated near low-dimensional manifolds, where different regions of the data distribution may correspond to distinct local geometric or semantic

- **An Agency-Transferring Model-Free Policy Enhancement Technique** _(regime detection market)_
  [2026-06-08](https://arxiv.org/abs/2606.09825v1)
  Training reinforcement learning (RL) policies from scratch is   costly: it requires careful reward and environment design,   extensive tuning, and substantial computation.   Yet many control problems already have a functional but   suboptimal policy available as a baseline.   This paper proposes a method for embedding such a baseline into   the RL training process, simultaneously improving trainin

- **Topological Triplons in the Pinwheel Valence Bond Solid on the Kagome Lattice** _(regime detection market)_
  [2026-06-08](https://arxiv.org/abs/2606.09823v1)
  We investigate the triplon excitations of the pinwheel valence-bond-solid phase on the deformed kagome lattice compound Rb2Cu3SnF12. Using bond-operator mean-field theory, we compute the triplon band structure, dynamical structure factor, Berry curvatures and the associated thermal Hall response. We show that the presence of Dzyaloshinskii-Moriya interactions and an external magnetic field are key

- **ALMA measurements of mass loss and wind clumping in the massive stars of the Arches cluster** _(regime detection market)_
  [2026-06-08](https://arxiv.org/abs/2606.09814v1)
  We present the first Atacama Large Millimeter/submillimeter Array (ALMA) Band 3 (100 GHz) and Band 6 (243 GHz) continuum observations of the Arches cluster, one of the youngest and most massive stellar clusters in the Milky Way. We detect and characterise millimetre emission from 23 massive stars, including WN7-9h Wolf-Rayet stars, O-type supergiants and hypergiants. By combining our ALMA measurem

- **Latent Spatial Memory for Video World Models** _(deep learning volatility forecasting)_
  [2026-06-08](https://arxiv.org/abs/2606.09828v1)
  Video world models that maintain 3D spatial consistency across generated frames typically rely on explicit point cloud memory constructed in RGB space. This design is both computationally expensive, requiring repeated rendering and VAE encoding, and inherently lossy, as the round trip through pixel space discards rich features of the learned latent representation. In this paper, we introduce \emph

- **OmniGameArena: A Unified UE5 Benchmark for VLM Game Agents with Improvement Dynamics** _(deep learning volatility forecasting)_
  [2026-06-08](https://arxiv.org/abs/2606.09826v1)
  Vision-language model (VLM) agents are increasingly deployed in interactive game environments. Yet game benchmarks for VLM agents typically report a single first-attempt score per (agent, game) pair, focus on single-agent Solo play, and lack unified protocols for evaluating heterogeneous agent classes (commercial VLMs, open-weight VLMs, and specialized game policies) on the same footing. We addres

- **An Agency-Transferring Model-Free Policy Enhancement Technique** _(deep learning volatility forecasting)_
  [2026-06-08](https://arxiv.org/abs/2606.09825v1)
  Training reinforcement learning (RL) policies from scratch is   costly: it requires careful reward and environment design,   extensive tuning, and substantial computation.   Yet many control problems already have a functional but   suboptimal policy available as a baseline.   This paper proposes a method for embedding such a baseline into   the RL training process, simultaneously improving trainin

- **Adaptive Derivative Estimation via Stein's Unbiased Risk** _(transformer financial time series)_
  [2026-06-08](https://arxiv.org/abs/2606.09829v1)
  Estimating derivatives from noisy sampled data is fundamental to control, human--computer interaction, and biomedical engineering. Causal FIR derivative filters offer a natural approach for this challenge, yet their performance depend on their length. While short filters amplify noise, long filters introduce smoothing bias. We present SURDE (SURE Derivative Estimator), which addresses this tradeof

- **Latent Spatial Memory for Video World Models** _(transformer financial time series)_
  [2026-06-08](https://arxiv.org/abs/2606.09828v1)
  Video world models that maintain 3D spatial consistency across generated frames typically rely on explicit point cloud memory constructed in RGB space. This design is both computationally expensive, requiring repeated rendering and VAE encoding, and inherently lossy, as the round trip through pixel space discards rich features of the learned latent representation. In this paper, we introduce \emph

- **OmniGameArena: A Unified UE5 Benchmark for VLM Game Agents with Improvement Dynamics** _(transformer financial time series)_
  [2026-06-08](https://arxiv.org/abs/2606.09826v1)
  Vision-language model (VLM) agents are increasingly deployed in interactive game environments. Yet game benchmarks for VLM agents typically report a single first-attempt score per (agent, game) pair, focus on single-agent Solo play, and lack unified protocols for evaluating heterogeneous agent classes (commercial VLMs, open-weight VLMs, and specialized game policies) on the same footing. We addres

- **Latent Spatial Memory for Video World Models** _(reinforcement learning portfolio)_
  [2026-06-08](https://arxiv.org/abs/2606.09828v1)
  Video world models that maintain 3D spatial consistency across generated frames typically rely on explicit point cloud memory constructed in RGB space. This design is both computationally expensive, requiring repeated rendering and VAE encoding, and inherently lossy, as the round trip through pixel space discards rich features of the learned latent representation. In this paper, we introduce \emph

- **OmniGameArena: A Unified UE5 Benchmark for VLM Game Agents with Improvement Dynamics** _(reinforcement learning portfolio)_
  [2026-06-08](https://arxiv.org/abs/2606.09826v1)
  Vision-language model (VLM) agents are increasingly deployed in interactive game environments. Yet game benchmarks for VLM agents typically report a single first-attempt score per (agent, game) pair, focus on single-agent Solo play, and lack unified protocols for evaluating heterogeneous agent classes (commercial VLMs, open-weight VLMs, and specialized game policies) on the same footing. We addres

- **An Agency-Transferring Model-Free Policy Enhancement Technique** _(reinforcement learning portfolio)_
  [2026-06-08](https://arxiv.org/abs/2606.09825v1)
  Training reinforcement learning (RL) policies from scratch is   costly: it requires careful reward and environment design,   extensive tuning, and substantial computation.   Yet many control problems already have a functional but   suboptimal policy available as a baseline.   This paper proposes a method for embedding such a baseline into   the RL training process, simultaneously improving trainin

- **A fast and consistent sharp-interface immersed boundary method for moving bodies of arbitrary thicknes** _(cryptocurrency trading)_
  [2026-06-08](https://arxiv.org/abs/2606.09799v1)
  Immersed boundary methods (IBMs) are widely used to simulate flows around complex geometries and moving bodies, but they often involve a trade-off between precision and computational efficiency. Eulerian formulations require special treatments for moving walls and may generate spurious force oscillations, whereas Lagrangian formulations can suffer from slip errors at the immersed surfaces. We prop

- **PsychoSafe: Eliciting Psychologically-Informed Refusals in Large Language Models** _(cryptocurrency trading)_
  [2026-06-08](https://arxiv.org/abs/2606.09697v1)
  Large language models (LLMs) routinely face requests that should be refused, creating a trade-off between helpfulness and harm prevention. However, refusals themselves can be helpful. In high-risk interactions involving crisis, coercion, or escalating intent, blunt non-compliance may prevent direct harm while still failing to support the needs of the person behind the request. We present PsychoSaf

- **Powering the Future of AI: Navigating the Trade-offs for Europe's Energy Transition and Net-Zero Goals** _(cryptocurrency trading)_
  [2026-06-08](https://arxiv.org/abs/2606.09617v1)
  The rapid expansion of AI globally has led to the proliferation of energy-intensive hyperscale data centres (DCs), making them as a structurally challenging component in power system planning and operation. Using a spatially explicit optimisation model of Europe across 21 AI growth scenarios, we systematically quantify additional demand, capacity requirements, emissions, and operational impacts of

- **Evaluation Cards: An Interpretive Layer for AI Evaluation Reporting** _(options volatility surface)_
  [2026-06-08](https://arxiv.org/abs/2606.09809v1)
  AI evaluation results are produced at scale but reported inconsistently across leaderboards, model cards, benchmark papers, and company blogs. The cost is interpretive: readers cannot reliably compare results across sources, identify what a report omits, or trace an aggregate claim to its underlying evidence. Recent efforts address isolated components but leave three gaps: they cover only narrow s

- **A fast and consistent sharp-interface immersed boundary method for moving bodies of arbitrary thicknes** _(options volatility surface)_
  [2026-06-08](https://arxiv.org/abs/2606.09799v1)
  Immersed boundary methods (IBMs) are widely used to simulate flows around complex geometries and moving bodies, but they often involve a trade-off between precision and computational efficiency. Eulerian formulations require special treatments for moving walls and may generate spurious force oscillations, whereas Lagrangian formulations can suffer from slip errors at the immersed surfaces. We prop

- **Zero Touch Predictive Orchestration: Automating Time-Series Models for the Cloud-Edge Continuum** _(options volatility surface)_
  [2026-06-08](https://arxiv.org/abs/2606.09787v1)
  The Cloud-Edge Continuum (CEC) enables latency-critical applications by distributing resources to the far edge, but its extreme volatility makes proactive Zero Touch Management via time-series forecasting essential. However, orchestrators face a severe "cold start" problem: newly discovered nodes lack the historical data required to train localized predictive models, while generalized models fail 

- **Topological Triplons in the Pinwheel Valence Bond Solid on the Kagome Lattice** _(factor investing alpha)_
  [2026-06-08](https://arxiv.org/abs/2606.09823v1)
  We investigate the triplon excitations of the pinwheel valence-bond-solid phase on the deformed kagome lattice compound Rb2Cu3SnF12. Using bond-operator mean-field theory, we compute the triplon band structure, dynamical structure factor, Berry curvatures and the associated thermal Hall response. We show that the presence of Dzyaloshinskii-Moriya interactions and an external magnetic field are key

- **PTL-Diffusion: Manifold-Aware Diffusion with Periodic Terminal Laws** _(factor investing alpha)_
  [2026-06-08](https://arxiv.org/abs/2606.09816v1)
  Standard diffusion models typically use a single time-homogeneous Gaussian terminal distribution as the reference law for generation. While this choice is analytically convenient and empirically powerful, it provides little explicit structure for data concentrated near low-dimensional manifolds, where different regions of the data distribution may correspond to distinct local geometric or semantic

- **Deep learning reveals a stronger fossil fuel influence than biomass burning in shaping remote tropospheric ozone** _(factor investing alpha)_
  [2026-06-08](https://arxiv.org/abs/2606.09793v1)
  Tropospheric ozone (O3) is a key greenhouse gas and atmospheric oxidant, yet its sources in the remote troposphere remain strongly debated. Observation-based tracer analyses suggest that O3 attributed to biomass burning is much greater than that from fossil fuel sources (by a factor of ~2-10), contradicting state-of-the-art global models. Here we show that this discrepancy primarily arises from th

## 3. GitHub Repos (Recently Updated)
- **[AArt1552/Vectorized-Crypto-Backtester](https://github.com/AArt1552/Vectorized-Crypto-Backtester)** ⭐ 1 · Python _(updated 2026-06-09)_
  ⚡ Optimize crypto trading strategies by using this high-performance backtester for Altcoins, driven by Bitcoin price action and advanced quantitative analysis.

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-09)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[Vixoqz/vnpy-Machine-Learning](https://github.com/Vixoqz/vnpy-Machine-Learning)** ⭐ 0 · C# _(updated 2026-06-09)_
  vnpy-Machine-Learning: integrates machine-learning models with the vn.py quantitative-trading framework for AI-driven, data-driven algorithmic trading and backtesting in Python.

- **[hummingbot/hummingbot](https://github.com/hummingbot/hummingbot)** ⭐ 18843 · Python _(updated 2026-06-09)_
  Open source software that helps you create and deploy high-frequency crypto trading bots

- **[v0acc0002/deepseek-trading-experiment](https://github.com/v0acc0002/deepseek-trading-experiment)** ⭐ 5 · Python _(updated 2026-06-09)_
  🤖 Explore AI-driven trading with the DeepSeek crypto bot, designed for learning rather than profit through backtesting strategies and financial analysis.

- **[Qyxloq/blankly-finance](https://github.com/Qyxloq/blankly-finance)** ⭐ 0 · Python _(updated 2026-06-09)_
  Blankly-Finance: A powerful Algo-Trading-Framework for stocks, crypto, and forex. Features Multi-Exchange-API, Backtesting, and Trading-Bot tools.

- **[SevFle/nexus-trade-engine](https://github.com/SevFle/nexus-trade-engine)** ⭐ 0 · Python _(updated 2026-06-09)_
  AI-native plugin trading framework with full cost modeling. Supports algorithmic, ML, and LLM-powered strategies via a plugin marketplace.

- **[drag0sd0g/MariaAlpha](https://github.com/drag0sd0g/MariaAlpha)** ⭐ 2 · Java _(updated 2026-06-09)_
  AI-powered algorithmic trading engine: market data, options pricing & Greeks, execution algos (VWAP/TWAP/POV/IS/Close/Momentum), smart order routing, layered pre-trade risk (sector / beta / ADV / VaR 

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-09)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 0 · None _(updated 2026-06-09)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[kalpeshshah11/Quant-Research-Project](https://github.com/kalpeshshah11/Quant-Research-Project)** ⭐ 0 · None _(updated 2026-06-09)_
  Factor modelling and research to uncover alpha.

- **[anveshachuri/macro-alpha-oil-shock-india](https://github.com/anveshachuri/macro-alpha-oil-shock-india)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-08)_
  Production-style macro alpha research pipeline for detecting oil shock transmission effects in Indian equity markets using event studies, factor modeling, sentiment analysis, and machine learning.

- **[arrearsstocking863/hedgevision](https://github.com/arrearsstocking863/hedgevision)** ⭐ 0 · None _(updated 2026-06-09)_
  Build and backtest statistical arbitrage strategies with a local-first Python and React trading platform for cointegrated pairs, paper trading, and scaling

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-06-09)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[octaviodegodoy/PairTradingAlgo](https://github.com/octaviodegodoy/PairTradingAlgo)** ⭐ 0 · Python _(updated 2026-06-08)_
  Algotrading pair trading arbitrage

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-09)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 48 · Python _(updated 2026-06-08)_
  A stock/futures auto trading framework using Shioaji API

- **[Estherc-ai/market-microstructure-frameworks](https://github.com/Estherc-ai/market-microstructure-frameworks)** ⭐ 0 · None _(updated 2026-06-07)_
  “Public research repository documenting theoretical frameworks for derivative, open interest modeling, market maker inventory mechanics, order dynamics,”quantitative-research  quantitative-modeling  v

## 4. Perplexity Strategy Synthesis
For a **small retail account** in April 2026, the most actionable setup is usually a *simple, liquid, rule-based strategy* you can execute with tiny risk per trade; that means **crypto momentum with a regime filter** and **equity pair trading** are the most realistic, while **options tail hedges** are only actionable if you can keep cost very low and accept bleed. I can give you concrete trade rules, but I should flag that your request for “recent papers or trading Twitter” and “currently cheap” tail hedges cannot be fully verified from the provided results, so I’ll clearly separate *well-supported structure* from *live-market judgment* that would require fresh market data.

## 1) Crypto momentum with regime filters — most actionable for $100–$1000

This is the best fit for small accounts because crypto is accessible, trades 24/7, and momentum systems can be run on liquid majors like BTC and ETH with very small sizing. General trading guidance for 2026 still emphasizes trend-following, breakout, and momentum rules with explicit entry/exit criteria and tight risk control, which fits this style[1][2][6].

**Core idea**
- Trade only when the higher-timeframe regime is supportive.
- Use momentum breakouts or pullback continuations on liquid spot or perp markets.
- Risk a fixed fraction of equity per trade, typically **0.5%–1%** for a tiny account, because multiple sources stress small-risk discipline for small accounts[3][4].

**Concrete parameters**
- **Universe:** BTC, ETH, and optionally one or two highly liquid large-cap alts.
- **Time horizon:** 1–10 days.
- **Regime filter:** Only long when price is above the **200-day moving average** on the daily chart and the **20-day MA is above the 50-day MA**; only take breakouts when 7-day realized volatility is not collapsing. This is an inference built from the trend-following guidance in the sources, not a directly quoted tested rule[1][2][6].
- **Entry rule:** Buy when price closes above the **20-day high** after a pullback that holds above the 20-day EMA, or enter on a successful retest of the breakout level.
- **Exit rule:** Exit on a daily close back below the 20-day EMA, or use a trailing stop under the last 3-day swing low.
- **Stop loss:** Below the breakout base or below the last swing low, whichever is tighter.
- **Position sizing:** Risk **0.5%–1% of account equity** per trade; with a $500 account, that is **$2.50–$5 risk** per trade[3][4]. If your stop distance is 5%, position size is roughly \( \text{risk} / 0.05 \), so a $5 risk allows about $100 notional.

**What to avoid**
- Chasing parabolic candles.
- Trading mid-range chop without a regime filter.
- Using too many indicators; the sources repeatedly emphasize clear rules and backtesting rather than indicator overload[2][3].

**Degradation risk**
- **Likely degraded if used naively:** pure breakout systems without a regime filter, because these tend to get crowded and whipsawed in sideways markets. The provided sources do not give evidence of last-6-month degradation, so this is a general structural warning rather than a documented recent decline[1][2].

## 2) Equity pair trading — very actionable if you can trade shares/ETF pairs or CFDs

Pair trading is one of the few systematic equity strategies that can work in a small account because it is market-neutral and can be implemented with simple stat-arb logic, though you need enough access to shorting or a broker that supports pair structures. The generic trading sources you provided emphasize defining entry/exit criteria, position sizing, and backtesting before live deployment[2][4][6].

**Core idea**
- Find two highly correlated stocks or ETFs.
- Trade the spread when it deviates from its recent mean.
- Exit when the spread reverts.

**Concrete parameters**
- **Universe:** Same-sector, highly liquid names or ETFs; examples would be two large banks, two semis, or two energy names.
- **Tim

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-09 via Conway's auto-publisher.*
