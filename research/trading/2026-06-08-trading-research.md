# Trading Nightly Research Brief — 2026-06-08

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-08T02:32:44, run time 53.4s._

## 1. Self-Analysis (Conway Trade Log)
```json
{
  "total_trades_logged": 130,
  "trades_last_7d": 18,
  "top_symbols_7d": [
    [
      "ZEC/USDC",
      6
    ],
    [
      "INJ/USDC",
      5
    ],
    [
      "BTC/USDC",
      4
    ],
    [
      "DOGE/USDC",
      3
    ]
  ],
  "side_breakdown_7d": {
    "buy": 8,
    "sell": 10
  }
}
```

## 2. arXiv Papers (Last 60 Days)
- **Counterintuitive problems in discrete probability** _(quantitative trading strategy)_
  [2026-06-05](https://arxiv.org/abs/2606.07516v1)
  This manuscript contains a collection of counterintuitive problems in discrete probability, together with detailed solutions. The dataset was constructed as part of a broader research project investigating the capabilities of the latest-generation Large Language Models (LLMs) in solving discrete probability problems, in order to assess whether LLMs tend to make systematic reasoning errors associat

- **Unsupervised Continual Clustering via Forward-Backward Knowledge Distillation** _(quantitative trading strategy)_
  [2026-06-05](https://arxiv.org/abs/2606.07474v1)
  Unsupervised Continual Learning (UCL) aims to enable neural networks to learn sequential tasks without labels or access to past data. A major challenge in this setting is Catastrophic Forgetting, where models forget previously learned tasks upon learning new ones. This challenge is amplified in UCL due to the absence of labels to guide learning and memory retention. Existing mitigation strategies,

- **Whisper Hallucination Detection and Mitigation via Hidden Representation Steering and Sparse AutoEncoders** _(quantitative trading strategy)_
  [2026-06-05](https://arxiv.org/abs/2606.07473v1)
  Whisper, a widely adopted ASR model, is known to suffer from hallucinations - coherent transcriptions generated for non-speech audio entirely disconnected from the input. We investigate whether hallucinations can be detected and mitigated through Whisper's internal representations. We extract audio encoder activations and evaluate two representation spaces: raw Whisper activations and Sparse AutoE

- **Second-Order Path Kernel Interpolation Formulas in Machine Learning** _(momentum crash risk)_
  [2026-06-05](https://arxiv.org/abs/2606.07495v1)
  Understanding how training data shape neural network predictions is a central problem in modern learning theory. In 2020, Pedro Domingos proposed an interpolation formula valid for every model learned by deterministic gradient descent. It expresses the model's prediction as an integral, along the optimization path, of a data-dependent kernel that aligns the model's gradients at the test and traini

- **Covariance-Adaptive Residualization and Stagewise Calibration for Dependent Multiple Testing** _(momentum crash risk)_
  [2026-06-05](https://arxiv.org/abs/2606.07466v1)
  In this paper, we study simultaneous hypothesis testing for multivariate Gaussian means under arbitrary covariance dependence. Building on the Maximum Residual Down (MRD) procedure of Cohen et al. (2009), we investigate a new calibration strategy based on the generalized step-down critical constants of Gavrilov et al. (2009). The resulting procedure retains the covariance-adaptive residualization 

- **Planning-aligned Token Compression for Long-Context Autonomous Driving** _(momentum crash risk)_
  [2026-06-05](https://arxiv.org/abs/2606.07464v1)
  Monolithic vision-action models represent an emerging paradigm in autonomous driving. However, this architecture produces token sequences that quickly exceed real-time computational budgets when encoding extended temporal context for complex interactions. While approaches like linear transformers and external memory try to make the context lightweight, token compression is most compatible with the

- **MemDreamer: Decoupling Perception and Reasoning for Long Video Understanding via Hierarchical Graph Memory and Agentic Retrieval Mechanism** _(mean reversion statistical arbitrage)_
  [2026-06-05](https://arxiv.org/abs/2606.07512v1)
  Current Vision-Language Models struggle with hours-long videos because processing full-length visual sequences induces prohibitive token explosion and attention dilution. To overcome this, we introduce MemDreamer to decouple perception and reasoning, shifting long-video understanding into an agentic exploration process. As a plug-and-play framework, it incrementally streams videos to construct a H

- **Differences in Detection: Explainability Where it Matters** _(mean reversion statistical arbitrage)_
  [2026-06-05](https://arxiv.org/abs/2606.07503v1)
  We propose Differences in Detection (DnD), an intuitive method to compare two object detection models. Based on the same matching algorithm, it complements the standard metrics of mean Average Precision ($mAP$) and TIDE error analysis with the ability to compare two models directly. More specifically, we calculate the intersection of ground truth labels that are recognized by both models, followed

- **The Roasting Marshmallows Program with IGRINS on Gemini South V: Atmosphere of MASCARA-1b is Enriched in Refractory Elements** _(mean reversion statistical arbitrage)_
  [2026-06-05](https://arxiv.org/abs/2606.07497v1)
  Ultra-hot Jupiters (UHJs; $T_{\rm eq} \gtrsim 2000$ K) enable simultaneous detection of volatile (ice-forming) and refractory (rock-forming) species in planetary atmospheres, providing a powerful diagnostic of planet formation and atmospheric processing. We present a comprehensive high-resolution cross-correlation spectroscopy (HRCCS) analysis of the UHJ MASCARA-1b ($T_{\rm eq} \approx 2600$ K) us

- **Boundary criticality in the Gross-Neveu-Yukawa model at higher orders** _(regime detection market)_
  [2026-06-05](https://arxiv.org/abs/2606.07510v1)
  We extend the study of boundary criticality in the Gross-Neveu-Yukawa universality class beyond leading order. Using the hyperbolic space formulation of boundary conformal field theories, we compute the first subleading corrections at large $N$ to the free energies of the ``normal", ``ordinary" and ``special" boundary universality classes. We also determine the order $1/N$ correction to the dimens

- **Differences in Detection: Explainability Where it Matters** _(regime detection market)_
  [2026-06-05](https://arxiv.org/abs/2606.07503v1)
  We propose Differences in Detection (DnD), an intuitive method to compare two object detection models. Based on the same matching algorithm, it complements the standard metrics of mean Average Precision ($mAP$) and TIDE error analysis with the ability to compare two models directly. More specifically, we calculate the intersection of ground truth labels that are recognized by both models, followed

- **The Roasting Marshmallows Program with IGRINS on Gemini South V: Atmosphere of MASCARA-1b is Enriched in Refractory Elements** _(regime detection market)_
  [2026-06-05](https://arxiv.org/abs/2606.07497v1)
  Ultra-hot Jupiters (UHJs; $T_{\rm eq} \gtrsim 2000$ K) enable simultaneous detection of volatile (ice-forming) and refractory (rock-forming) species in planetary atmospheres, providing a powerful diagnostic of planet formation and atmospheric processing. We present a comprehensive high-resolution cross-correlation spectroscopy (HRCCS) analysis of the UHJ MASCARA-1b ($T_{\rm eq} \approx 2600$ K) us

- **Agentopia: Long-Term Life Simulation and Learning in Agent Societies** _(deep learning volatility forecasting)_
  [2026-06-05](https://arxiv.org/abs/2606.07513v1)
  Humans learn from social life. Simulating this process with LLM-powered agents represents a promising research direction, raising a natural question: whether LLMs can learn from such simulated social experience to better understand and replicate human behavior. However, prior agent society simulations typically operate at the scale of days, limiting the depth of social interactions and long-term g

- **GJ 3929 b as the First Complete Rocky Worlds DDT Data Set** _(deep learning volatility forecasting)_
  [2026-06-05](https://arxiv.org/abs/2606.07511v1)
  Despite their large abundance, it is still unknown whether and under what conditions rocky planets around M dwarf stars can host atmospheres. This open question motivated the on-going Rocky Worlds DDT survey focused on searching for atmospheres on relatively low-temperature rocky exoplanets by systematically probing for the presence of day-night heat redistribution and CO2 absorption through JWST/

- **Affordance-Based Hierarchical Reinforcement Learning for Quadruped Pedipulation** _(deep learning volatility forecasting)_
  [2026-06-05](https://arxiv.org/abs/2606.07506v1)
  The object manipulation capabilities of quadruped robots is an open research challenge. While previous studies have focused on low-level policy learning, task execution still relies on expert-designed high-level trajectories. Autonomous selection of both an affordable interaction point on the target object and an affordable robot base pose removes the need for pre-designed trajectories. This study

- **Counterintuitive problems in discrete probability** _(transformer financial time series)_
  [2026-06-05](https://arxiv.org/abs/2606.07516v1)
  This manuscript contains a collection of counterintuitive problems in discrete probability, together with detailed solutions. The dataset was constructed as part of a broader research project investigating the capabilities of the latest-generation Large Language Models (LLMs) in solving discrete probability problems, in order to assess whether LLMs tend to make systematic reasoning errors associat

- **Streaming Video Generation with Streaming Force Control** _(transformer financial time series)_
  [2026-06-05](https://arxiv.org/abs/2606.07508v1)
  We introduce StreamForce, a streaming video generation framework that enables physically grounded control through continuous force inputs. Unlike prior video models that train separate models for different force types, assume fixed forces, or rely on non-causal processing, StreamForce is a causal and unified model that responds instantly and coherently to both local and global, time-varying forces

- **Primordial Black Hole Triggered Type Ia Supernovae II: Comparison with Supernova Remnants and Galactic Chemical Evolution** _(transformer financial time series)_
  [2026-06-05](https://arxiv.org/abs/2606.07505v1)
  The asteroid-mass class of Primordial Black Holes (PBHs) is one of the candidates for the dark matter in the universe. With a mass between $4 \times 10^{-17} &lt; M_{\rm PBH} &lt; 4 \times 10^{-12}~M_{\odot}$, they could be the major component of dark matter in the cosmic mass budget. The infall of these PBH into a white dwarf could be one triggering mechanism of Type Ia supernovae (SNe Ia). In [L

- **Agentopia: Long-Term Life Simulation and Learning in Agent Societies** _(reinforcement learning portfolio)_
  [2026-06-05](https://arxiv.org/abs/2606.07513v1)
  Humans learn from social life. Simulating this process with LLM-powered agents represents a promising research direction, raising a natural question: whether LLMs can learn from such simulated social experience to better understand and replicate human behavior. However, prior agent society simulations typically operate at the scale of days, limiting the depth of social interactions and long-term g

- **GJ 3929 b as the First Complete Rocky Worlds DDT Data Set** _(reinforcement learning portfolio)_
  [2026-06-05](https://arxiv.org/abs/2606.07511v1)
  Despite their large abundance, it is still unknown whether and under what conditions rocky planets around M dwarf stars can host atmospheres. This open question motivated the on-going Rocky Worlds DDT survey focused on searching for atmospheres on relatively low-temperature rocky exoplanets by systematically probing for the presence of day-night heat redistribution and CO2 absorption through JWST/

- **Affordance-Based Hierarchical Reinforcement Learning for Quadruped Pedipulation** _(reinforcement learning portfolio)_
  [2026-06-05](https://arxiv.org/abs/2606.07506v1)
  The object manipulation capabilities of quadruped robots is an open research challenge. While previous studies have focused on low-level policy learning, task execution still relies on expert-designed high-level trajectories. Autonomous selection of both an affordable interaction point on the target object and an affordable robot base pose removes the need for pre-designed trajectories. This study

- **Amortized Neural Optimization for Pre-Layout Signal Integrity Design Space Exploration using Differentiable Surrogates** _(cryptocurrency trading)_
  [2026-06-05](https://arxiv.org/abs/2606.07463v1)
  Pre-layout design space exploration (DSE) for high-speed signal integrity (SI) analysis is often limited by the computational cost of simulations and iterative optimization algorithms within modern electronic design automation (EDA) workflows. While machine learning surrogate models accelerate the simulation step, optimizing designs still requires utilizing iterative black-box search methods. This

- **Tracing Stablecoin Contagion during the USDC Depeg after the Silicon Valley Bank Collapse** _(cryptocurrency trading)_
  [2026-06-05](https://arxiv.org/abs/2606.07442v1)
  The March 2023 collapse of Silicon Valley Bank (SVB) disrupted the core premise of stablecoins, which are digital tokens designed to maintain a fixed value against the U.S. dollar and serve as on-chain substitutes for dollar liquidity. The event triggered a sharp depeg of USDC, creating a rare exogenous shock to the stablecoin ecosystem. While price deviations during this crisis are well documente

- **RealDocBench: A Benchmark for Field-Level QA and Layout Understanding on Real-World Regulated Documents** _(cryptocurrency trading)_
  [2026-06-05](https://arxiv.org/abs/2606.07401v1)
  Document parsing systems are increasingly deployed in high-stakes, regulated workflows such as mortgage underwriting, financial reporting, supply-chain logistics, and clinical records. Yet most public benchmarks evaluate parsers on clean academic layouts or synthetic prose, and report a single OCR or markdown-level similarity score. Such documents and metrics correlate poorly with what downstream 

- **GJ 3929 b as the First Complete Rocky Worlds DDT Data Set** _(options volatility surface)_
  [2026-06-05](https://arxiv.org/abs/2606.07511v1)
  Despite their large abundance, it is still unknown whether and under what conditions rocky planets around M dwarf stars can host atmospheres. This open question motivated the on-going Rocky Worlds DDT survey focused on searching for atmospheres on relatively low-temperature rocky exoplanets by systematically probing for the presence of day-night heat redistribution and CO2 absorption through JWST/

- **Bulk Superconductivity driven by Disorder-Induced Delocalization in 4Hb-Ta(S$_{1-x}$Se$_x$)$_2$** _(options volatility surface)_
  [2026-06-05](https://arxiv.org/abs/2606.07509v1)
  The unconventional superconductor 4Hb-TaS$_2$ is a natural heterostructure that can be broadly understood as interleaving Mott-like and metallic layers. We study the properties of this material as a function of quenched disorder in the form of Se/S substitution and find that while disordered samples show bulk superconductivity, clean samples do not. We show that a disorder-driven delocalization of

- **The Roasting Marshmallows Program with IGRINS on Gemini South V: Atmosphere of MASCARA-1b is Enriched in Refractory Elements** _(options volatility surface)_
  [2026-06-05](https://arxiv.org/abs/2606.07497v1)
  Ultra-hot Jupiters (UHJs; $T_{\rm eq} \gtrsim 2000$ K) enable simultaneous detection of volatile (ice-forming) and refractory (rock-forming) species in planetary atmospheres, providing a powerful diagnostic of planet formation and atmospheric processing. We present a comprehensive high-resolution cross-correlation spectroscopy (HRCCS) analysis of the UHJ MASCARA-1b ($T_{\rm eq} \approx 2600$ K) us

- **Accelerated Decentralized Stochastic Gradient Descent for Strongly Convex Optimization** _(factor investing alpha)_
  [2026-06-05](https://arxiv.org/abs/2606.07496v1)
  Decentralized stochastic optimization is a fundamental paradigm for large-scale learning over networks, where agents communicate only with their neighbors and no central coordinator is required. For strongly convex problems, communication efficiency is mainly determined by the condition number \(κ=L/μ\) and the network spectral gap \(1-β\). Although deterministic decentralized methods can simultan

- **Second-Order Path Kernel Interpolation Formulas in Machine Learning** _(factor investing alpha)_
  [2026-06-05](https://arxiv.org/abs/2606.07495v1)
  Understanding how training data shape neural network predictions is a central problem in modern learning theory. In 2020, Pedro Domingos proposed an interpolation formula valid for every model learned by deterministic gradient descent. It expresses the model's prediction as an integral, along the optimization path, of a data-dependent kernel that aligns the model's gradients at the test and traini

- **Odd Cycle Transversal in $P_k$-Free Graphs** _(factor investing alpha)_
  [2026-06-05](https://arxiv.org/abs/2606.07453v1)
  The Odd Cycle Transversal (OCT) problem, which asks for a minimum subset of vertices whose removal renders a graph bipartite, is a central problem in algorithmic graph theory. It is known to be NP-complete even on $P_k$-free graphs for $k \ge 6$. Furthermore, assuming the Unique Games Conjecture (UGC), OCT does not admit a constant-factor approximation algorithm on general graphs.   Motivated by t

## 3. GitHub Repos (Recently Updated)
- **[Leonard-Don/quant-trading-system](https://github.com/Leonard-Don/quant-trading-system)** ⭐ 0 · Python _(updated 2026-06-08)_
  FastAPI + React quantitative research workspace for backtesting, realtime monitoring, industry heatmaps, and cross-market experiments.

- **[Vixoqz/vnpy-Machine-Learning](https://github.com/Vixoqz/vnpy-Machine-Learning)** ⭐ 0 · C# _(updated 2026-06-08)_
  vnpy-Machine-Learning: integrates machine-learning models with the vn.py quantitative-trading framework for AI-driven, data-driven algorithmic trading and backtesting in Python.

- **[Barrazar274/the-0050-project](https://github.com/Barrazar274/the-0050-project)** ⭐ 0 · Python _(updated 2026-06-08)_
  Document a quantitative trading project that compares custom machine learning strategies against a simple 0050 buy and hold approach using backtested data.

- **[sedimentary-republicofchile38/Polymarket-Trading-Bot-Rust](https://github.com/sedimentary-republicofchile38/Polymarket-Trading-Bot-Rust)** ⭐ 1 · Rust _(updated 2026-06-08)_
  Automate Polymarket trading in Rust with live, paper, and backtest strategies, CLOB auth, and balance, order, and redemption tools

- **[naimkatiman/tradeclaw](https://github.com/naimkatiman/tradeclaw)** ⭐ 32 · TypeScript _(updated 2026-06-08)_
  🤖 Self-hosted AI trading signals - 5 swappable strategy presets (Classic, HMM, regime-aware, VWAP+EMA+BB, Full-Risk Pipline), multi-preset backtest comparison, paper trading, Telegram bot. BTC, ETH, G

- **[v0acc0002/deepseek-trading-experiment](https://github.com/v0acc0002/deepseek-trading-experiment)** ⭐ 5 · Python _(updated 2026-06-08)_
  🤖 Explore AI-driven trading with the DeepSeek crypto bot, designed for learning rather than profit through backtesting strategies and financial analysis.

- **[Eruxa001/trading-strategy](https://github.com/Eruxa001/trading-strategy)** ⭐ 0 · Python _(updated 2026-06-08)_
  Algorithmic trading strategy with RSI, MACD and backtesting

- **[Algo-Ankit/AlphaSwarm](https://github.com/Algo-Ankit/AlphaSwarm)** ⭐ 0 · Python _(updated 2026-06-08)_
  A multi-tenant SaaS platform featuring an LLM-driven strategy compiler, FastAPI control plane, and isolated   Celery, background workers for executing parallel quantitative trading algorithms

- **[Sloped-familyunit908/finclaw](https://github.com/Sloped-familyunit908/finclaw)** ⭐ 0 · None _(updated 2026-06-08)_
  Discover trading strategies using genetic algorithms that evolve automatically to improve financial decision-making.

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 0 · None _(updated 2026-06-08)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[BretjHribar/AutomatedFactorResearcher](https://github.com/BretjHribar/AutomatedFactorResearcher)** ⭐ 1 · Python _(updated 2026-06-06)_
  Automated equity factor alpha research, backtesting, combination, and portfolio optimization platform

- **[Akshith-Gandham/alpha-factor-research](https://github.com/Akshith-Gandham/alpha-factor-research)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-05)_
  Sector-neutral long/short equity pipeline with rolling IC evaluation, IC-weighted signal combination, and regime analysis on S&P 500   2015-2024

- **[arrearsstocking863/hedgevision](https://github.com/arrearsstocking863/hedgevision)** ⭐ 0 · None _(updated 2026-06-08)_
  Build and backtest statistical arbitrage strategies with a local-first Python and React trading platform for cointegrated pairs, paper trading, and scaling

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-06-08)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[AbhishekKumarGuptaDev/Statistical-Arbitrage-PairsTrading](https://github.com/AbhishekKumarGuptaDev/Statistical-Arbitrage-PairsTrading)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-07)_
  

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-08)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[Estherc-ai/market-microstructure-frameworks](https://github.com/Estherc-ai/market-microstructure-frameworks)** ⭐ 0 · None _(updated 2026-06-07)_
  “Public research repository documenting theoretical frameworks for derivative, open interest modeling, market maker inventory mechanics, order dynamics,”quantitative-research  quantitative-modeling  v

- **[henryhuangh/wealthsimple-python](https://github.com/henryhuangh/wealthsimple-python)** ⭐ 12 · Python _(updated 2026-06-05)_
  Wealthsimple trade API library for python based on the new wealthsimple graphql framework

## 4. Perplexity Strategy Synthesis
Below is the most *actionable* way to think about this for a **$100–$1,000 retail account**: focus on strategies that are **rule-based, low-cost to execute, and compatible with tiny position sizes**, and avoid anything that depends on tight spreads, lots of turnover, or expensive option premium. The big caveat is that your search results do **not** include enough high-quality, April 2026-specific evidence on “recent papers” or “trading Twitter” to verify what has truly worked *right now*, so I’m labeling those parts as *current practice / plausible edge* rather than confirmed alpha.[1][3][5]

**1) Crypto momentum with regime filters — best fit for small accounts**  
A practical version is: trade only the top liquid coins, only when the broader crypto regime is risk-on, and only in the direction of the higher-timeframe trend.[1][3][6]

- **Universe:** BTC, ETH, and 1–3 large-cap alts with deep liquidity; keep it to a small watchlist because new traders generally do better with only a few names.[3]
- **Regime filter:**  
  - Long-only when BTC is above its 200-day moving average and the 50-day is rising.  
  - Prefer entries when BTC’s 20-day realized volatility is falling or flat and the market is not in a sharp drawdown; this is an inference from standard trend/momentum practice, not directly stated in the sources.[1][3][6]
- **Entry rule:**  
  - Buy on pullbacks in an uptrend, not on vertical breakouts.  
  - On the chart, require price to reclaim a short-term moving average or break the prior day’s high after a pullback; this is consistent with the “buy support, not resistance” and “pullback trend” guidance in the sources.[2][6][7]
- **Exit rule:**  
  - Initial stop below the pullback low or below the liquidity sweep low.  
  - Take partial profits at 1.5–2R, then trail the rest under higher lows or a moving average.[3][7]
- **Position sizing:**  
  - Risk **0.5%–1% of account equity per trade**; for a $500 account, that is $2.50–$5 risk.  
  - Because crypto spot positions can be tiny, this usually means 1–3 concurrent positions max.[3][6]
- **What to avoid:**  
  - Pure breakout chasing; breakout strategies were reported as relatively weak in the cited 2026 material, with one source saying breakout success rates were only about 30% among studied traders.[3]

**2) Equity pair trading — good only if you can keep costs low**  
For small accounts, classic market-neutral pair trading is usually *hard to implement well* because commissions, borrow costs, and low capital make sizing inefficient. It is still viable if you use **high-liquidity ETF pairs** or very liquid large-cap pairs and keep holding periods longer.[5]

- **Best form for small accounts:**  
  - Trade **ETF pairs** or very liquid mega-cap pairs rather than thin single-stock pairs; this is an inference based on execution constraints, not directly stated in the sources.
- **Time horizon:**  
  - **3 to 20 trading days** is the most practical range for a small account, because intraday pair trading is too fee-sensitive; this is also an inference.
- **Entry rule:**  
  - Build a spread z-score from a 20–60 day lookback.  
  - Enter when the spread reaches about **±2 standard deviations** from its mean, in the direction of mean reversion; this is standard pair-trading practice, but the specific z-score threshold is not given in your sources.
- **Exit rule:**  
  - Exit when the spread returns to about **0 to 0.5 standard deviations** from mean, or after a time stop of 10–15 trading days if the spread does not revert.
- **Position sizing:**  
  - Equal-dollar long/short legs, with total risk limited to **0.5%–1%** of account equity.  
  - If your account is $200, this often means the trade is too small to be worth

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-08 via Conway's auto-publisher.*
