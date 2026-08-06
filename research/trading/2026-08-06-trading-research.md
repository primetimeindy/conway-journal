# Trading Nightly Research Brief — 2026-08-06

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-08-06T02:31:14, run time 43.3s._

## 1. Self-Analysis (Conway Trade Log)
```json
{
  "total_trades_logged": 130,
  "trades_last_7d": 0,
  "top_symbols_7d": [],
  "side_breakdown_7d": {}
}
```

## 2. arXiv Papers (Last 60 Days)
- **Micro-randomized Trials with Categorical Treatments and Binary Proximal Outcome: Causal Effect Estimation and Sample Size Calculation** _(quantitative trading strategy)_
  [2026-08-05](https://arxiv.org/abs/2608.05135v1)
  Micro-randomized trials (MRTs) provide a framework for evaluating the marginal and moderated effects of mobile health (mHealth) interventions. In many applications, treatments take the form of categorical variables with multiple levels, such as different message contents or delivery strategies. Many scientifically meaningful longitudinal outcomes in mHealth studies are binary, such as whether a pa

- **A central limit theorem for the random assignment problem** _(quantitative trading strategy)_
  [2026-08-05](https://arxiv.org/abs/2608.05123v1)
  Let \(C_n\) be the minimum cost of a perfect matching in an \(n\times n\) matrix of independent uniform random variables. We   prove that \[   \sqrt n\{C_n-ζ(2)\}   \ \Longrightarrow\   \mathcal N\bigl(0,4ζ(2)-4ζ(3)\bigr). \] The proof begins with an exact change of variables based on a uniformly rooted shortest-path selection of an optimal dual potential. After the unused reduced costs are integr

- **Counterexamples to Schiffer's Conjecture** _(quantitative trading strategy)_
  [2026-08-05](https://arxiv.org/abs/2608.05114v1)
  The Schiffer conjecture states that if a smooth domain $Ω\subset \mathbb{R}^n$ admits a Neumann eigenfunction of the Laplacian which is constant at the boundary, then the domain is a ball. It is intimately related to Pompeiu's problem, stating that if a nonzero function integrates zero over any rigid motion of $Ω$, then $Ω$ is a ball.   We disprove both conjectures in $\mathbb{R}^2$, constructing 

- **The Loss Does Not See the Basis, but Adam Does** _(momentum crash risk)_
  [2026-08-05](https://arxiv.org/abs/2608.05136v1)
  Gradient descent on a factored model $W = UV^\top$ is implicitly biased toward low-rank solutions, while Adam, starting from the same small initialization, is not. We trace the difference to the gauge symmetry of the loss, its invariance under $(U, V) \mapsto (UQ, VQ)$. Gradient flow's low-rank mechanism is available to an optimizer only if that optimizer is gauge-equivariant, a condition necessar

- **Agent Against Agent: An Agentic System for Automatic Prompt Injection Red Teaming** _(momentum crash risk)_
  [2026-08-05](https://arxiv.org/abs/2608.05108v1)
  Prompt injection poses significant security risks to LLM agents. Efficient and effective red-teaming is therefore critical, both for evaluating these risks and for collecting training data to improve defenses. Existing state-of-the-art prompt injection red-teaming methods primarily rely on reinforcement learning (RL), producing attacker models that often generalize poorly to new target LLMs. In th

- **MALT: Lightweight Curvature-Aware Muon via Diagonal Preconditioning** _(momentum crash risk)_
  [2026-08-05](https://arxiv.org/abs/2608.05088v1)
  Muon has recently emerged as a promising alternative to AdamW for language model pretraining by orthogonalizing momentum matrices using Newton-Schulz iterations. Although Muon mitigates gradient anisotropy, it does not explicitly account for the curvature geometry of the loss landscape and may therefore remain sensitive to curvature anisotropy. We bridge this gap by proposing MALT (Muon Augmented 

- **Reasoning Core: Designing Broad Procedural Data for Completion-Supervised Reasoning Training** _(mean reversion statistical arbitrage)_
  [2026-08-05](https://arxiv.org/abs/2608.05148v1)
  Procedural generators produce useful verifiable reasoning problems at scale, but have received less attention as data for completion-supervised fine-tuning. We introduce Reasoning Core, a collection of 50 generators spanning mathematics, logic, planning, state tracking, formal languages, structured data, games, causality, and code, with semantic scorers, difficulty controls, and task evaluators. U

- **Predicting Brain Morphometry with MT-GNN: Mesh Evolution in Continuous Time with Graph-Based Metric Tensor Embeddings** _(mean reversion statistical arbitrage)_
  [2026-08-05](https://arxiv.org/abs/2608.05132v1)
  Predicting how a subcortical structure's shape will evolve from a few prior scans could support prognosis and clinical-trial enrichment. Existing longitudinal mesh predictors either extrapolate shape trajectories via high-dimensional embeddings or regress vertex deformations directly. We instead predict the surface's intrinsic geometry in continuous time: a single per-structure graph network predi

- **SSTQ:Privacy-Preserving Vector Quantization via Subsampled Stochastic TurboQuant** _(mean reversion statistical arbitrage)_
  [2026-08-05](https://arxiv.org/abs/2608.05127v1)
  Achieving local differential privacy in distributed optimization while maintaining low communication cost remains challenging. Existing vector quantization methods, such as vqSGD, use high-dimensional geometric constructions but incur unfavorable dimension-dependent variance. In this work, we propose Subsampled Stochastic TurboQuant (SSTQ), a framework that combines overcomplete equal-norm tight f

- **SSTQ:Privacy-Preserving Vector Quantization via Subsampled Stochastic TurboQuant** _(regime detection market)_
  [2026-08-05](https://arxiv.org/abs/2608.05127v1)
  Achieving local differential privacy in distributed optimization while maintaining low communication cost remains challenging. Existing vector quantization methods, such as vqSGD, use high-dimensional geometric constructions but incur unfavorable dimension-dependent variance. In this work, we propose Subsampled Stochastic TurboQuant (SSTQ), a framework that combines overcomplete equal-norm tight f

- **Reward Structure Shapes the Interaction Between Episodic Exploration and Neural Memory in Reinforcement Learning** _(regime detection market)_
  [2026-08-05](https://arxiv.org/abs/2608.05111v1)
  In partially observable reinforcement learning, agents face a dual bottleneck: they must explore to encounter rewarding states and retain that experience in memory to optimize their policies. Exploration bonuses and memory architectures are traditionally evaluated in isolation, leaving their interaction unmeasured, and standard notions of sparse reward conflate temporal signal density with what th

- **Cluster-Cluster model in $\mathbb{Z}^d$** _(regime detection market)_
  [2026-08-05](https://arxiv.org/abs/2608.05105v1)
  We consider a stochastic process on $\mathbb{Z}^d$ for $d \geq 1$. Given a translation invariant and ergodic starting configuration of finite clusters, each cluster $C$ performs a continuous time simple random walk with rate $|C|^{-α}$. If it attempts to move to a vertex occupied by another cluster, it does not move, and instead the two clusters connect via a new edge. In all dimensions, we show t

- **Machine-Learning Search for Lax Connections** _(deep learning volatility forecasting)_
  [2026-08-05](https://arxiv.org/abs/2608.05146v1)
  We apply a machine learning framework to search for Lax connections in two-dimensional non-linear sigma models using local current data. For the $SU(2)$ principal chiral model and the symmetric coset $S^2 = SU(2)/U(1)$, the method successfully recovers the full spectral-parameter families without using the known spectral curves as training targets. For the non-symmetric coset $T^{1,1}$, the optimi

- **Argus: A General-Purpose Agentic Runtime for Long-Horizon Reasoning** _(deep learning volatility forecasting)_
  [2026-08-05](https://arxiv.org/abs/2608.05144v1)
  Long-horizon reasoning requires an agentic runtime that can persist when evidence supports its current approach and pivot when measurements reveal failure, hidden constraints, or a misspecified objective. We present Argus, a persistent, self-evolving runtime in which Manager, Planner, Engineer, and Reviewer execute bounded missions over durable project state. Argus separates stable user intent fro

- **OctoLong: Mid-Training On Cross-Repository Code Contexts Enhances Long-Context Modeling** _(deep learning volatility forecasting)_
  [2026-08-05](https://arxiv.org/abs/2608.05141v1)
  Context lengths of language models (LMs) have dramatically increased, driven by the demands for in-context learning, self-improvement, and long-horizon agentic workflows. Existing long-context corpora, however, are dominated by books, academic articles, and code repositories, which are finite resources and often scarce in long-distance dependencies. In this work, we introduce OctoLong, a context e

- **CoCo-IR: Contextual Composed Image Retrieval** _(transformer financial time series)_
  [2026-08-05](https://arxiv.org/abs/2608.05149v1)
  Current instruction-based image retrieval systems are powerful but limited to single-turn interactions, failing to capture the iterative nature of complex, real-world visual searches. To overcome this limitation, we introduce Contextual Composed Image Retrieval (CoCo-IR), a novel task that enables users to progressively refine search results through interactions. We address this new task by propos

- **Fast Quantum Interconnects via Neutral Atom Ensembles** _(transformer financial time series)_
  [2026-08-05](https://arxiv.org/abs/2608.05147v1)
  Distributing entanglement between distant qubits is a crucial element of scalable quantum computing. Here, we describe a scalable quantum interconnect that generates remote entanglement at rates approaching those compatible with two-qubit gates of current neutral-atom quantum processors. The proposed approach exploits the strong dipole-dipole interactions between atomic Rydberg states to generate 

- **Argus: A General-Purpose Agentic Runtime for Long-Horizon Reasoning** _(transformer financial time series)_
  [2026-08-05](https://arxiv.org/abs/2608.05144v1)
  Long-horizon reasoning requires an agentic runtime that can persist when evidence supports its current approach and pivot when measurements reveal failure, hidden constraints, or a misspecified objective. We present Argus, a persistent, self-evolving runtime in which Manager, Planner, Engineer, and Reviewer execute bounded missions over durable project state. Argus separates stable user intent fro

- **Machine-Learning Search for Lax Connections** _(reinforcement learning portfolio)_
  [2026-08-05](https://arxiv.org/abs/2608.05146v1)
  We apply a machine learning framework to search for Lax connections in two-dimensional non-linear sigma models using local current data. For the $SU(2)$ principal chiral model and the symmetric coset $S^2 = SU(2)/U(1)$, the method successfully recovers the full spectral-parameter families without using the known spectral curves as training targets. For the non-symmetric coset $T^{1,1}$, the optimi

- **Argus: A General-Purpose Agentic Runtime for Long-Horizon Reasoning** _(reinforcement learning portfolio)_
  [2026-08-05](https://arxiv.org/abs/2608.05144v1)
  Long-horizon reasoning requires an agentic runtime that can persist when evidence supports its current approach and pivot when measurements reveal failure, hidden constraints, or a misspecified objective. We present Argus, a persistent, self-evolving runtime in which Manager, Planner, Engineer, and Reviewer execute bounded missions over durable project state. Argus separates stable user intent fro

- **OctoLong: Mid-Training On Cross-Repository Code Contexts Enhances Long-Context Modeling** _(reinforcement learning portfolio)_
  [2026-08-05](https://arxiv.org/abs/2608.05141v1)
  Context lengths of language models (LMs) have dramatically increased, driven by the demands for in-context learning, self-improvement, and long-horizon agentic workflows. Existing long-context corpora, however, are dominated by books, academic articles, and code repositories, which are finite resources and often scarce in long-distance dependencies. In this work, we introduce OctoLong, a context e

- **Gradient Immunity: Null-Space Resistance to Malicious Fine-Tuning** _(cryptocurrency trading)_
  [2026-08-05](https://arxiv.org/abs/2608.05045v1)
  Released aligned large language models remain vulnerable to malicious downstream finetuning. Existing defenses are largely designed for the fine-tuning-as-a-service (FTaaS) paradigm or rely on downstream users to follow additional safety procedures, and therefore do not directly address the setting we study: a provider controlled partially protected open-weight (PPOW) release setting in which most

- **Private Direct Preference Optimization for LLM Alignment** _(cryptocurrency trading)_
  [2026-08-05](https://arxiv.org/abs/2608.05040v1)
  Direct preference optimization (DPO) is now a standard method for aligning large language models (LLMs) using human preference data. Each DPO example contains a prompt and a pair of candidate model responses. While prompts and responses are often public or model-generated, the relative preference between responses reflects subjective judgments and can reveal sensitive attributes of annotators or e

- **Optimal Constrained sc-LTL Planning in MDPs via Switching Policies** _(cryptocurrency trading)_
  [2026-08-05](https://arxiv.org/abs/2608.05021v1)
  We study the synthesis of optimal policies for planning problems on Markov decision processes with both objectives and safety constraints specified in co-safe linear temporal logic (sc-LTL). Our problems are inherently non-Markovian due to the complexity of the sc-LTL specification and may require policy randomization to balance the objective and constraint. We propose a novel approach that reduce

- **Predicting Brain Morphometry with MT-GNN: Mesh Evolution in Continuous Time with Graph-Based Metric Tensor Embeddings** _(options volatility surface)_
  [2026-08-05](https://arxiv.org/abs/2608.05132v1)
  Predicting how a subcortical structure's shape will evolve from a few prior scans could support prognosis and clinical-trial enrichment. Existing longitudinal mesh predictors either extrapolate shape trajectories via high-dimensional embeddings or regress vertex deformations directly. We instead predict the surface's intrinsic geometry in continuous time: a single per-structure graph network predi

- **Tetrahedral linkage as an intrinsic measure of glycan antifreeze behavior** _(options volatility surface)_
  [2026-08-05](https://arxiv.org/abs/2608.05130v1)
  Antifreeze materials prevent ice-formation by disrupting the ice-formation by binding to certain ice-planes. Cellulose, the most abundant biopolymer, has shown the ability to bind to ice-planes but the exact mechanism of this binding is far from being understood. Molecular dynamics simulations are used to investigate the hydration water of chains of cellulose-type glycans and its significance in t

- **Alexandrov Theorem for constant weighted mean curvature surfaces** _(options volatility surface)_
  [2026-08-05](https://arxiv.org/abs/2608.05119v1)
  We prove a Heintze--Karcher type inequality for a large class of log-convex weights in Euclidean and Hyperbolic spaces. As a consequence we obtain an Alexandrov theorem for $λ$-self expanders.

- **Reasoning Core: Designing Broad Procedural Data for Completion-Supervised Reasoning Training** _(factor investing alpha)_
  [2026-08-05](https://arxiv.org/abs/2608.05148v1)
  Procedural generators produce useful verifiable reasoning problems at scale, but have received less attention as data for completion-supervised fine-tuning. We introduce Reasoning Core, a collection of 50 generators spanning mathematics, logic, planning, state tracking, formal languages, structured data, games, causality, and code, with semantic scorers, difficulty controls, and task evaluators. U

- **The Loss Does Not See the Basis, but Adam Does** _(factor investing alpha)_
  [2026-08-05](https://arxiv.org/abs/2608.05136v1)
  Gradient descent on a factored model $W = UV^\top$ is implicitly biased toward low-rank solutions, while Adam, starting from the same small initialization, is not. We trace the difference to the gauge symmetry of the loss, its invariance under $(U, V) \mapsto (UQ, VQ)$. Gradient flow's low-rank mechanism is available to an optimizer only if that optimizer is gauge-equivariant, a condition necessar

- **A waveguide spectrometer for high-resolution millimeter-wave imaging** _(factor investing alpha)_
  [2026-08-05](https://arxiv.org/abs/2608.05129v1)
  We present the design and development of a novel, compact integrated on-chip spectrometer operating at millimeter (mm) and submillimeter (sub-mm) wavelengths. The Superconducting Waveguide Integrated Submillimeter Spectrometer (SWISS) promises significant improvements in spectral resolution, optical efficiency, and frequency coverage over current mm-wave spectrometers by using a free-space rectang

## 3. GitHub Repos (Recently Updated)
- **[Zizhao-HUANG/FullStackAutoQuant](https://github.com/Zizhao-HUANG/FullStackAutoQuant)** ⭐ 21 · Python _(updated 2026-08-06)_
  Production grade end to end automated quantitative trading system.

- **[akfamily/akquant](https://github.com/akfamily/akquant)** ⭐ 1949 · Python _(updated 2026-08-06)_
  AKQuant is a high-performance quantitative research and trading framework built on Rust and Python! 开源量化回测框架

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 0 · Jupyter Notebook _(updated 2026-08-06)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 0 · Python _(updated 2026-08-06)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[Gainium/main-app-sh](https://github.com/Gainium/main-app-sh)** ⭐ 2 · TypeScript _(updated 2026-08-06)_
  TypeScript-based crypto trading platform backend with automated DCA, Grid, Combo, and Hedge bot strategies, real-time WebSocket streaming, backtesting capabilities, and GraphQL API for portfolio manag

- **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance)** ⭐ 12 · Python _(updated 2026-08-06)_
  Easily build, backtest and deploy your algo in just a few lines of code. Trade stocks, cryptos, and forex across exchanges one package.

- **[Garvit-821/multi-asset-algorithmic-trading-software](https://github.com/Garvit-821/multi-asset-algorithmic-trading-software)** ⭐ 1 · TypeScript _(updated 2026-08-06)_
  CryptoAgent is a comprehensive multi-asset algorithmic trading software designed to track, analyze, and manage real-time market data across various asset classes, including Cryptocurrencies, Forex, St

- **[aaggupta07/hft-architecture](https://github.com/aaggupta07/hft-architecture)** ⭐ 0 · C++ _(updated 2026-08-06)_
  A complete low-latency algorithmic trading pipeline, consisting of an exchange simulator, market data handler, limit order book, passive market maker strategy process with pre-trade risk checks, and a

- **[BrockStar3540/mr-scrooge-v6](https://github.com/BrockStar3540/mr-scrooge-v6)** ⭐ 4 · Python _(updated 2026-08-06)_
  Open-source algorithmic forex trading bot for OANDA (Python) — cell-based execution, wide-stop ratchet exits, a full backtesting research program, and a live control-panel dashboard. Strategy-neutral 

- **[Genius-apple/open-alpha](https://github.com/Genius-apple/open-alpha)** ⭐ 1 · Python _(updated 2026-08-06)_
  Enterprise-grade quantitative factor research terminal - Atelier-grade design - Numba DSL - DES backtester - 87% test coverage

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 4 · None _(updated 2026-08-06)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[liuh886/alpha_engine](https://github.com/liuh886/alpha_engine)** ⭐ 0 · Python _(updated 2026-08-06)_
  Alpha Engine: AI-driven quantitative trading research platform with factor lifecycle, model registry, backtesting, and dashboard.

- **[arhaanshaikh1705-sys/pairs-trading](https://github.com/arhaanshaikh1705-sys/pairs-trading)** ⭐ 0 · Jupyter Notebook _(updated 2026-08-06)_
  Cointegration-based statistical arbitrage / pairs trading on regional banks: Engle-Granger pair selection, rolling hedge-ratio re-estimation, two-leg backtest engine

- **[1ruz/Statistical-Arbitrage-Model](https://github.com/1ruz/Statistical-Arbitrage-Model)** ⭐ 0 · Python _(updated 2026-08-06)_
  Develop a pairs trading or statistical arbitrage model to detect price inefficiencies between correlated assets. Use time-series analysis techniques like cointegration and mean reversion to generate s

- **[Varish-Sanad/statistical-arbitrage-research](https://github.com/Varish-Sanad/statistical-arbitrage-research)** ⭐ 0 · None _(updated 2026-08-05)_
  Cointegration-based mean-reversion pairs-trading research in Python

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 0 · Jupyter Notebook _(updated 2026-08-06)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[zzwjlwwdtg/quant-trading-framework](https://github.com/zzwjlwwdtg/quant-trading-framework)** ⭐ 2 · Python _(updated 2026-08-06)_
  Algorithmic trading framework for JP + US equities: daily-K signals, HMM regime detection, Claude LLM decision gate, options wall analysis, paper trading

- **[mikecoombs4/CTS-AI](https://github.com/mikecoombs4/CTS-AI)** ⭐ 0 · Python _(updated 2026-08-05)_
  AI Powered Options trading system using the CTS framework

## 4. Perplexity Strategy Synthesis
I can give you a **practical playbook**, but I can’t honestly claim the specific strategies are “right now, April 2026” edges without live paper/research data; the search results you provided are mostly general strategy roundups and YouTube explainers, not current empirical studies. The only source in your results that explicitly speaks to systematic edges in 2026 is a Substack-style roundup of “60+ ways” traders find edges, plus a general systematic-trading resource list; neither is enough to verify live alpha persistence or recent degradation by itself[5][17].

For a **small account ($100–$1000)**, the most actionable approaches are those with **defined risk**, **low capital lockup**, and **simple execution**. For your four buckets, the most usable setup is:

| Area | Best fit for small accounts | Why it fits | Main risk |
|---|---|---|---|
| Crypto momentum with regime filters | **Trend-following / breakout momentum on liquid majors** with a regime filter | Works with tiny size, 24/7 market, easy to automate | Whipsaws in chop |
| Equity pair trading | **Long/short pairs only in cash or paper**, or **single-name statistical spread proxies** | Market-neutral in theory | Hard to size with $100–$1000; borrow/fill issues |
| Options tail hedges | **Very small put spreads / cheap convexity** only when vol is not already extreme | Defined loss, simple | Most “cheap” tails are usually cheap for a reason |
| New edges | **Use only if you can backtest**; otherwise treat as research ideas | Newness is not edge by itself | Crowding and data-snooping |

## 1) Crypto momentum with regime filters

The most actionable retail version is **long-only momentum in BTC/ETH or the top liquid large caps**, using a **market regime filter** so you only trade trend states and skip mean-reverting conditions. General 2026 trading guides emphasize momentum trading and simple trend-following as suitable for retail accounts, and one guide explicitly suggests using momentum only when conditions are favorable rather than forcing trades[3][18].

A practical rule set:

- **Universe:** BTC, ETH, and at most 3–5 very liquid large-cap alts.
- **Time horizon:** **4 hours to 3 days**.
- **Regime filter:** Trade only if:
  - BTC is above its **200-day EMA** on the daily chart, and
  - the **20-day return** is positive, and
  - realized volatility is not in a panic spike.
- **Entry:** Buy when price closes above the **20-period high** on the 4h chart after at least one pullback to the **20 EMA**.
- **Exit:** 
  - initial stop below the most recent swing low or **2 ATR(14)**,
  - take partial profit at **1.5R**,
  - trail the remainder with a **10 EMA** or **2 ATR**.
- **Position sizing:** Risk **0.5%–1% of account equity per trade**; with a $500 account, that is **$2.50–$5** of risk. This is consistent with small-account risk guidance in the trading results you provided[6][18].

Why this is the best fit:
- It is compatible with **tiny capital** because spot crypto has no PDT barrier and can be traded in fractional size.
- It is easy to automate or rule-based.
- It avoids the worst thing for small accounts: overtrading in chop.

What likely **degraded**:
- Pure breakout systems without a regime filter are usually the first to deteriorate when the market gets more two-sided. Your results do not contain a live degradation study, so that conclusion is an inference from the structure of the strategy, not a cited fact.

## 2) Equity pair trading

For a **$100–$1000** account, classic pair trading is the least practical of your four categories. In real brokerage conditions, pair trading usually needs enough capital to handle two legs, slippage, and borrowing constraints; that makes it awkward for very small accounts. The general systematic-trading references you provided cover the broad category, but they do not give a current, retail-feasible pair-trading edge

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-08-06 via Conway's auto-publisher.*
