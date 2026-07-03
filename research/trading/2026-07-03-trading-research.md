# Trading Nightly Research Brief — 2026-07-03

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-07-03T02:31:31, run time 24.7s._

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
- **Distributed Attacks in Persistent-State AI Control** _(quantitative trading strategy)_
  [2026-07-02](https://arxiv.org/abs/2607.02514v1)
  As AI coding agents become more autonomous, they increasingly ship code iteratively, with the codebase persisting across sessions. This persistence creates a new attack surface: a misaligned or prompt-injected agent can distribute attacks across pull requests (PRs) and time its payload for the PR with the best natural cover. To study the resulting dynamics, we introduce Iterative VibeCoding, a set

- **On the emergence of quantum many-body chaos for tunably-broken integrability** _(quantitative trading strategy)_
  [2026-07-02](https://arxiv.org/abs/2607.02506v1)
  We develop a quantitative theory for the emergence of quantum many-body chaos as integrability is broken via a tunable parameter. In a circuit model of free fermions, 'doped' with a tunable density of integrability-breaking gates, we uncover the microscopic mechanisms underpinning the crossover from early-time integrable behaviour to late-time chaos through the lens of the out-of-time-ordered corr

- **Alleviating prior dependencies for DESI DR1 clustering fits through reparameterization** _(quantitative trading strategy)_
  [2026-07-02](https://arxiv.org/abs/2607.02498v1)
  Bayesian analyses of the full-shape clustering of Dark Energy Spectroscopic Instrument (DESI) Data Release 1 (DR1) exhibit prior-volume projection effects, whereby weakly constrained nuisance parameters of the Effective Field Theory of Large Scale Structure (EFTofLSS) shift marginalized cosmological posteriors away from the posterior maximum. We reanalyze DESI DR1 power spectrum multipoles using t

- **Online Safety Monitoring for LLMs** _(momentum crash risk)_
  [2026-07-02](https://arxiv.org/abs/2607.02510v1)
  Despite alignment training, LLMs remain prone to generating unsafe outputs at deployment time. Monitoring outputs online and raising an alarm when safety can no longer be assumed is therefore critical. We study a simple real-time monitor that turns a verifier signal from an external model into an alarm decision by thresholding, with the threshold calibrated via risk control. In experiments on math

- **What LLM Agents Say When No One Is Watching: Social Structure and Latent Objective Emergence in Multi-Agent Debates** _(momentum crash risk)_
  [2026-07-02](https://arxiv.org/abs/2607.02507v1)
  LLM agents will increasingly act in socially structured settings where role, audience, and relational context can shape what is advantageous or costly to say. We study whether such social structure, without any explicit objective in the prompt, changes what an agent expresses publicly relative to an off-the-record (OTR) channel elicited under the same condition. We introduce a dual-channel debate 

- **Controllable Sim Agents with Behavior Latents** _(momentum crash risk)_
  [2026-07-02](https://arxiv.org/abs/2607.02496v1)
  Realistic traffic simulation requires agents that imitate logged behavior and can also be steered along interpretable axes. Such controllability enables engineers to isolate variables, reproduce specific edge cases, and test autonomous systems without real-world risk. We introduce Controllable Neural Variational Agents (CNeVA), a controllable simulated-agent framework that learns to infer a per-ag

- **On the emergence of quantum many-body chaos for tunably-broken integrability** _(mean reversion statistical arbitrage)_
  [2026-07-02](https://arxiv.org/abs/2607.02506v1)
  We develop a quantitative theory for the emergence of quantum many-body chaos as integrability is broken via a tunable parameter. In a circuit model of free fermions, 'doped' with a tunable density of integrability-breaking gates, we uncover the microscopic mechanisms underpinning the crossover from early-time integrable behaviour to late-time chaos through the lens of the out-of-time-ordered corr

- **DemoPSD: Disagreement-Modulated Policy Self-Distillation** _(mean reversion statistical arbitrage)_
  [2026-07-02](https://arxiv.org/abs/2607.02502v1)
  On-policy self-distillation (OPSD) has emerged as a practical method for training large language models (LLMs) to reason, where a single model acts as both the teacher and the student with different levels of information access. However, recent studies have found that the teacher's dense token-level supervision, conditioned on privileged information, can lead to overfitting to in-domain patterns, 

- **The structure of FAC posets and the Aharoni--Korman conjecture** _(mean reversion statistical arbitrage)_
  [2026-07-02](https://arxiv.org/abs/2607.02500v1)
  A poset $P$ is said to satisfy the finite antichain condition, or FAC for short, if it has no infinite antichain. Such posets exhibit rich and complex structure, and it was conjectured by Aharoni and Korman in 1992 that any FAC poset $P$ possesses a chain $C$ and a partition into antichains such that $C$ meets every antichain of the partition. While this conjecture is now known to be false, in thi

- **Distributed Attacks in Persistent-State AI Control** _(regime detection market)_
  [2026-07-02](https://arxiv.org/abs/2607.02514v1)
  As AI coding agents become more autonomous, they increasingly ship code iteratively, with the codebase persisting across sessions. This persistence creates a new attack surface: a misaligned or prompt-injected agent can distribute attacks across pull requests (PRs) and time its payload for the PR with the best natural cover. To study the resulting dynamics, we introduce Iterative VibeCoding, a set

- **What LLM Agents Say When No One Is Watching: Social Structure and Latent Objective Emergence in Multi-Agent Debates** _(regime detection market)_
  [2026-07-02](https://arxiv.org/abs/2607.02507v1)
  LLM agents will increasingly act in socially structured settings where role, audience, and relational context can shape what is advantageous or costly to say. We study whether such social structure, without any explicit objective in the prompt, changes what an agent expresses publicly relative to an off-the-record (OTR) channel elicited under the same condition. We introduce a dual-channel debate 

- **G-RRM: Guiding Symbolic Solvers with Recurrent Reasoning Models** _(regime detection market)_
  [2026-07-02](https://arxiv.org/abs/2607.02491v1)
  In this work, we focus on SE-RRMs, a symbol-equivariant instantiation of RRMs that exhibits improved extrapolation to larger problem sizes. We propose a neuro-symbolic approach, ``Guiding with Recurrent Reasoning Models'' (G-RRM), which integrates SE-RRMs with symbolic solvers for constraint satisfaction problems. SE-RRMs act as neural solvers that generate full solution proposals and guide classi

- **LACUNA: A Testbed for Evaluating Localization Precision for LLM Unlearning** _(deep learning volatility forecasting)_
  [2026-07-02](https://arxiv.org/abs/2607.02513v1)
  LLMs memorize sensitive training data, including personally identifiable information (PII), creating a pressing need for reliable post hoc removal methods. Unlearning has emerged as a promising solution, with state-of-the-art(SOTA) methods often following a localize-first, unlearn-second paradigm that targets specific model parameters. However, existing benchmarks evaluate unlearning solely at the

- **Program-as-Weights: A Programming Paradigm for Fuzzy Functions** _(deep learning volatility forecasting)_
  [2026-07-02](https://arxiv.org/abs/2607.02512v1)
  Many everyday programming tasks resist clean rule-based implementation, such as alerting on important log lines, repairing malformed JSON, or ranking search results by intent, and are increasingly outsourced to large language model APIs at the cost of locality, reproducibility, and price. We propose fuzzy-function programming: compiling such a function from a natural-language specification into a 

- **Online Safety Monitoring for LLMs** _(deep learning volatility forecasting)_
  [2026-07-02](https://arxiv.org/abs/2607.02510v1)
  Despite alignment training, LLMs remain prone to generating unsafe outputs at deployment time. Monitoring outputs online and raising an alarm when safety can no longer be assumed is therefore critical. We study a simple real-time monitor that turns a verifier signal from an external model into an alarm decision by thresholding, with the threshold calibrated via risk control. In experiments on math

- **PointDiT: Pixel-Space Diffusion for Monocular Geometry Estimation** _(transformer financial time series)_
  [2026-07-02](https://arxiv.org/abs/2607.02515v1)
  State-of-the-art single-image 3D reconstruction methods often rely on complex hybrid architectures and loss functions, or compress geometry into latent spaces in order to leverage pre-trained latent diffusion models. In this work, we show that such architectural overhead and intricate loss formulations are unnecessary. We introduce a minimalist pixel-space Diffusion Transformer, built on a plain V

- **Distributed Attacks in Persistent-State AI Control** _(transformer financial time series)_
  [2026-07-02](https://arxiv.org/abs/2607.02514v1)
  As AI coding agents become more autonomous, they increasingly ship code iteratively, with the codebase persisting across sessions. This persistence creates a new attack surface: a misaligned or prompt-injected agent can distribute attacks across pull requests (PRs) and time its payload for the PR with the best natural cover. To study the resulting dynamics, we introduce Iterative VibeCoding, a set

- **A Probabilistic Sign Rule for Quotients of Positive Series and Integral Transforms** _(transformer financial time series)_
  [2026-07-02](https://arxiv.org/abs/2607.02511v1)
  This paper develops a probabilistic sign rule for quotients of functions represented by positive series or integrals. For a function in this class, normalising the summand function in the series case or the integrand function in the integral case induces a probability law under which parameter log-derivatives of the function are expressed as moments of kernels, the log-derivatives of the same summ

- **LACUNA: A Testbed for Evaluating Localization Precision for LLM Unlearning** _(reinforcement learning portfolio)_
  [2026-07-02](https://arxiv.org/abs/2607.02513v1)
  LLMs memorize sensitive training data, including personally identifiable information (PII), creating a pressing need for reliable post hoc removal methods. Unlearning has emerged as a promising solution, with state-of-the-art(SOTA) methods often following a localize-first, unlearn-second paradigm that targets specific model parameters. However, existing benchmarks evaluate unlearning solely at the

- **Program-as-Weights: A Programming Paradigm for Fuzzy Functions** _(reinforcement learning portfolio)_
  [2026-07-02](https://arxiv.org/abs/2607.02512v1)
  Many everyday programming tasks resist clean rule-based implementation, such as alerting on important log lines, repairing malformed JSON, or ranking search results by intent, and are increasingly outsourced to large language model APIs at the cost of locality, reproducibility, and price. We propose fuzzy-function programming: compiling such a function from a natural-language specification into a 

- **Online Safety Monitoring for LLMs** _(reinforcement learning portfolio)_
  [2026-07-02](https://arxiv.org/abs/2607.02510v1)
  Despite alignment training, LLMs remain prone to generating unsafe outputs at deployment time. Monitoring outputs online and raising an alarm when safety can no longer be assumed is therefore critical. We study a simple real-time monitor that turns a verifier signal from an external model into an alarm decision by thresholding, with the threshold calibrated via risk control. In experiments on math

- **Combating Textual Noise and Redundancy: Entropy-Aware Dense Visual Token Pruning** _(cryptocurrency trading)_
  [2026-07-02](https://arxiv.org/abs/2607.02484v1)
  Visual token pruning is a crucial strategy for accelerating VLMs by compressing redundant image patches, yet existing methods often fail to preserve critical cues under dense instructions and fine-grained queries. In this paper, we investigate this failure and identify two underlying bottlenecks: the widespread dispersion of textual noise that corrupts dense cross-modal scoring, and the feature fr

- **Optimal stellar rank approximation of squeezed cat states with photon catalysis** _(cryptocurrency trading)_
  [2026-07-02](https://arxiv.org/abs/2607.02427v1)
  Non-Gaussian quantum states and operations constitute essential resources for achieving quantum computational advantage and enabling quantum error correction in bosonic platforms. However, their generation in optical settings remains a challenging experimental task, often relying on probabilistic heralded protocols. Here, we present an in-depth analysis of the suitability of photon catalysis betwe

- **Coalesced Matrix-Free Finite Elements in Cell-Wise Storage** _(cryptocurrency trading)_
  [2026-07-02](https://arxiv.org/abs/2607.02335v1)
  We present a GPU-oriented formulation of continuous high-order finite elements in which the redundant, cell-wise (element-local) vector is the persistent primary representation of all field data, rather than a transient stage of matrix-free operator evaluation. We prove that, given a preconditioner whose image is continuous, the entire flexible conjugate gradient iteration can be carried out exact

- **Distributed Attacks in Persistent-State AI Control** _(options volatility surface)_
  [2026-07-02](https://arxiv.org/abs/2607.02514v1)
  As AI coding agents become more autonomous, they increasingly ship code iteratively, with the codebase persisting across sessions. This persistence creates a new attack surface: a misaligned or prompt-injected agent can distribute attacks across pull requests (PRs) and time its payload for the PR with the best natural cover. To study the resulting dynamics, we introduce Iterative VibeCoding, a set

- **The Debris Disk Host $β$ Piscis Austrinus is a Rapidly Rotating Star Seen Nearly Pole-On** _(options volatility surface)_
  [2026-07-02](https://arxiv.org/abs/2607.02487v1)
  Previous studies of $β$ Piscis Austrinus (PsA) have speculated that the narrow and saddle-like shapes of some of its weak metallic lines are a consequence of it being a rapidly rotating star viewed nearly pole-on. Here we use the \texttt{fastrot-spec} spectral synthesis code to model high-dispersion (R = 115,000) HARPS spectra of $β$ PsA in order to determine its inclination and photospheric prope

- **Automated logical Clifford gadgets for heterogeneous architectures via chain maps** _(options volatility surface)_
  [2026-07-02](https://arxiv.org/abs/2607.02482v1)
  Transversal CNOTs are ubiquitous for entangling logical qubits of identical CSS codes pairwise. For distinct codes, the options are much more limited, and are typically known only for structurally related code families. We introduce an automated framework for synthesising inter-code logical CNOT circuits between arbitrary CSS codes using chain maps. Given a prescribed bipartite logical CNOT networ

- **From SRA to Self-Flow: Data Augmentation or Self-Supervision?** _(factor investing alpha)_
  [2026-07-02](https://arxiv.org/abs/2607.02508v1)
  Representation alignment has become an effective way to accelerate diffusion transformer training and improve generation quality. Recent self-alignment methods, such as SRA and Self-Flow, further remove the dependency on external pretrained encoders by constructing alignment within the diffusion model itself. However, the mechanism behind the improvement from SRA to Self-Flow, dual-time scheduling

- **Cut-off Jastrow Factors and Spectral Barron Regularity of Coulombic Electronic Wave Functions** _(factor investing alpha)_
  [2026-07-02](https://arxiv.org/abs/2607.02492v1)
  We study the spectral Barron regularity of Coulombic electronic eigenfunctions after extraction of a cut-off Jastrow factor. Let \(H=-Δ+V\) be an \(N\)-electron Coulomb Hamiltonian with clamped nuclei, and let \(ψ\) be an eigenfunction associated with a discrete eigenvalue below the bottom of the essential spectrum. For the cut-off Jastrow factor \(F_{\rm cut}\) of Fournais--Hoffmann-Ostenhof--Hof

- **The Merger-Driven Origin of the Vast Extended Stellar Disc Around the Andromeda Galaxy** _(factor investing alpha)_
  [2026-07-02](https://arxiv.org/abs/2607.02480v1)
  The closest giant spiral, the Andromeda galaxy (M31), shows compelling evidence for a recent, gas-rich major merger event. Pronounced substructures in its inner halo and a kinematically hot stellar disc, whose star formation history shows a widespread star formation episode 2.5 Gyr ago, are telltale evidence that may be directly linked to a major (mass ratio 1 to 4) merger event that took place 2-

## 3. GitHub Repos (Recently Updated)
- **[11Bhavin/Quant_Trading_Portfolio-](https://github.com/11Bhavin/Quant_Trading_Portfolio-)** ⭐ 0 · None _(updated 2026-07-03)_
  📈 Build and backtest automated trading strategies using Python to enhance your quantitative finance skills and explore the financial markets.

- **[Millan678/trading-research-platform](https://github.com/Millan678/trading-research-platform)** ⭐ 0 · Python _(updated 2026-07-03)_
  Autonomous 64-phase research ecosystem for systematic trading strategy analysis, validation, and scientific discovery. Research-only.

- **[manishhegde011/Quantitative-Research-Architecture](https://github.com/manishhegde011/Quantitative-Research-Architecture)** ⭐ 0 · HTML _(updated 2026-07-03)_
  Architected a modular production-style platform using Python, Streamlit, Pandas, NumPy, RESTAPI integration, and real-time options market data, comprising independent Signal Generation, Trade Quality,

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 0 · Python _(updated 2026-07-03)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[sedimentary-republicofchile38/Polymarket-Trading-Bot-Rust](https://github.com/sedimentary-republicofchile38/Polymarket-Trading-Bot-Rust)** ⭐ 1 · Rust _(updated 2026-07-03)_
  Automate Polymarket trading in Rust with live, paper, and backtest strategies, CLOB auth, and balance, order, and redemption tools

- **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance)** ⭐ 12 · Python _(updated 2026-07-03)_
  Easily build, backtest and deploy your algo in just a few lines of code. Trade stocks, cryptos, and forex across exchanges one package.

- **[7skooooo/mql5-systems-mirror](https://github.com/7skooooo/mql5-systems-mirror)** ⭐ 151 · HTML _(updated 2026-07-03)_
  MQL5 Algorithmic Trading Scripts 2026 – Automated MT5 Strategies

- **[astarek1983/street-algo-trader](https://github.com/astarek1983/street-algo-trader)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-03)_
  🚀 Implement algorithmic trading strategies for a Jane Street-style exchange, featuring market-making, arbitrage, and momentum signals.

- **[Anna-007-tech/algorithmic-trading-ai](https://github.com/Anna-007-tech/algorithmic-trading-ai)** ⭐ 2 · None _(updated 2026-07-03)_
  📈 Explore AI-driven trading strategies through data analysis of forex and crypto volatility using PCA, K-means, and neural networks.

- **[zzzhhn/alpha-agent](https://github.com/zzzhhn/alpha-agent)** ⭐ 0 · Python _(updated 2026-07-03)_
  LLM-Powered Alpha Research Agent — multi-agent system for automated quantitative factor discovery on A-share markets

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 2 · None _(updated 2026-07-03)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[cuijinkuo/quant-research-platform](https://github.com/cuijinkuo/quant-research-platform)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-01)_
  Engineering showcase of a private China A-share quant research platform — architecture docs, factor-gating walkthrough, sanitised evaluation outputs. Alpha code kept private by design.

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-07-03)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[octaviodegodoy/PairTradingAlgo](https://github.com/octaviodegodoy/PairTradingAlgo)** ⭐ 0 · Python _(updated 2026-07-02)_
  Algotrading pair trading arbitrage

- **[JadTijani/PairTradingBacktester](https://github.com/JadTijani/PairTradingBacktester)** ⭐ 0 · Python _(updated 2026-07-02)_
  A basic pair trading algorithm inspired by the principles of Quantitative Trading by Ernie Chan. This script implements a statistical arbitrage strategy using a mean-reversion model. It calculates the

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-03)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 49 · Python _(updated 2026-07-02)_
  A stock/futures auto trading framework using Shioaji API

- **[I-am-Uchenna/institutional-options-research](https://github.com/I-am-Uchenna/institutional-options-research)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-18)_
  Academic, risk-first options research framework with stochastic-volatility pricing, defined-risk strategy analysis, and paper-trading controls.

## 4. Perplexity Strategy Synthesis
No search results provide the specific, verified parameters (entry/exit rules, position sizing), recent academic papers, or live “degraded” status for crypto momentum with regime filters, equity pair trading, cheap options tail hedges, or newly discovered edges as of April 2026 for retail traders with $100–$1,000 accounts. The available sources offer only general trading strategy descriptions (e.g., pullback trends, FVGs, CEST framework, trend-following) without the concrete systematic parameters, regime-filter logic, pair-selection criteria, options skew thresholds, or recent edge discoveries you requested.

Because the question asks for **actionable, systematic strategies with concrete parameters** and **citation of specific papers/threads**, and the search results lack this level of specificity, **no strategy can be safely recommended as currently actionable or verified** based on the provided data. In particular:

- **Crypto momentum with regime filters**: No source defines the regime filter (e.g., volatility threshold, moving average slope, market cap trend), time horizon (e.g., 4H vs. daily), or entry/exit rules (e.g., FVG retest + MACD confirmation) for small accounts.
- **Equity pair trading**: No source specifies which pairs (e.g., long/short tech stocks), hedging method, or correlation breakdown signals.
- **Options tail hedges**: No source identifies which options (e.g., 30-delta puts on VIX), which markets, or why they are “cheap” (e.g., low implied volatility relative to historical).
- **Newly discovered edges**: No source cites a recent paper (e.g., SSRN, arXiv), Substack (e.g., “The Quantified Trader”), or Twitter thread from 2025–2026.
- **Degraded strategies**: No source flags which strategies (e.g., mean-reversion on 500-cap crypto) have degraded in the last 6 months due to crowding.

### What You Can Do Instead (Based on General Best Practices)

Since the search results do not contain the required data, you must **backtest and validate** any strategy yourself using the following general framework from the available sources:

| Strategy Type | General Parameters (from [1], [2], [3]) | How to Validate |
|---------------|------------------------------------------|-----------------|
| **Pullback Trend with FVG** ([2]) | - Time horizon: 5–15 min (intraday) or daily<br>- Entry: Pullback to Fair Value Gap + RSI < 30 (oversold)<br>- Exit: Break of prior high or target 1:3 RR<br>- Sizing: 1–2% of account per trade ([3]) | Backtest on 2024–2026 crypto data; check if FVG retests still hold after 2025 volatility spikes |
| **CEST Framework** ([2]) | - Conditions: Market structure + volume spike (2–3x normal)<br>- Entries: Confluence at support/resistance<br>- Stops: Beyond pattern extreme<br>- Targets: 1:3 RR minimum ([3]) | Apply to small-cap equities; test if conditions (e.g., volume) still predict moves |
| **Trend-Following (Hull MA)** ([5]) | - Time horizon: Daily/weekly<br>- Entry: Price above Hull MA (10/10 settings) in uptrend<br>- Exit: Price crosses below Hull MA<br>- Sizing: Adjust lot size if stop too big ([5]) | Test on 2025–2026 crypto/ETF pairs; check if trend persistence has degraded |
| **Range Trading** ([1], [3]) | - Time horizon: Daily<br>- Entry: Buy near support (oversold RSI), sell near resistance (overbold)<br>- Exit: Break of range or target 1:2 RR<br>- Sizing: 1–2% per trade ([3]) | Validate if ranges (e.g., in BTC) are still stable post-2025 regulatory changes |

### Critical Caveats (Based on [3], [4])

1. **

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-07-03 via Conway's auto-publisher.*
