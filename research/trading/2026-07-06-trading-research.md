# Trading Nightly Research Brief — 2026-07-06

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-07-06T02:30:58, run time 23.2s._

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
- **[yanxinnnnnn/El-Psy-Quant](https://github.com/yanxinnnnnn/El-Psy-Quant)** ⭐ 0 · Python _(updated 2026-07-06)_
  An AI-native quantitative research and trading platform built in public.

- **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant)** ⭐ 3 · Python _(updated 2026-07-06)_
  Trade Kalshi prediction markets with a quantitative system designed for fee-aware position sizing and statistical arbitrage.

- **[MarcusJMyrick/Quantitative-Strategy-Engine-QSE-](https://github.com/MarcusJMyrick/Quantitative-Strategy-Engine-QSE-)** ⭐ 6 · C++ _(updated 2026-07-06)_
  Quantitative Strategy Engine (QSE) is a high-performance engine for backtesting quant trading strategies. Its C++ core ensures low-latency execution, while Python handles data processing, analysis, an

- **[vatupelage/polymarket-predictor](https://github.com/vatupelage/polymarket-predictor)** ⭐ 0 · Jupyter Notebook _(updated 2026-07-06)_
  Live Polymarket trading bot for 5m/15m Chainlink-settled crypto markets — dollar-bar "price-to-beat" contrarian model, order execution, and the full backtest/research suite behind it.

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 1 · Python _(updated 2026-07-06)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[Gainium/main-app-sh](https://github.com/Gainium/main-app-sh)** ⭐ 1 · TypeScript _(updated 2026-07-06)_
  TypeScript-based crypto trading platform backend with automated DCA, Grid, Combo, and Hedge bot strategies, real-time WebSocket streaming, backtesting capabilities, and GraphQL API for portfolio manag

- **[Th3-H4xx0r/IntelliStock](https://github.com/Th3-H4xx0r/IntelliStock)** ⭐ 9 · Python _(updated 2026-07-06)_
  IntelliStock is a self-hosted algorithmic trading platform you run on your own infrastructure. It builds strategies, runs backtests, monitors live positions, and answers questions about your portfolio

- **[aayushpandey01/AI-Quant-Trading-Platform](https://github.com/aayushpandey01/AI-Quant-Trading-Platform)** ⭐ 0 · Python _(updated 2026-07-06)_
  A personal, full stack algorithmic trading platform for Indian stocks/ETFs, built on Zerodha Kite Connect. It covers the whole loop: pull market data → backtest a strategy → paper/live trade it → watc

- **[khushalgg44/Automated-Trading-Machine](https://github.com/khushalgg44/Automated-Trading-Machine)** ⭐ 0 · Python _(updated 2026-07-06)_
  An automated algorithmic trading platform built using the Zerodha Kite Connect API with paper trading, backtesting, strategy engine, live market data, risk management, and performance analytics.

- **[zzzhhn/alpha-agent](https://github.com/zzzhhn/alpha-agent)** ⭐ 0 · Python _(updated 2026-07-06)_
  LLM-Powered Alpha Research Agent — multi-agent system for automated quantitative factor discovery on A-share markets

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 2 · None _(updated 2026-07-06)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[hllow84/ai-quant-trading](https://github.com/hllow84/ai-quant-trading)** ⭐ 0 · Python _(updated 2026-07-06)_
  Crypto factor research pipeline: alpha story → signal → cost-inclusive backtest → walk-forward → verdict

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-07-06)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[rohailasim123/stat-arb-pairs-trading](https://github.com/rohailasim123/stat-arb-pairs-trading)** ⭐ 0 · Python _(updated 2026-07-06)_
  A statistical arbitrage research pipeline

- **[Xemso/pairs-trading-cointegration](https://github.com/Xemso/pairs-trading-cointegration)** ⭐ 0 · Python _(updated 2026-07-05)_
  Market-neutral statistical arbitrage strategy using Engle-Granger cointegration in Python

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-06)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 49 · Python _(updated 2026-07-04)_
  A stock/futures auto trading framework using Shioaji API

- **[milgar7969/alpaca-options-framework](https://github.com/milgar7969/alpaca-options-framework)** ⭐ 17 · Python _(updated 2026-07-06)_
  A Python framework for building live options trading bots on Alpaca Markets — asyncio, WebSocket streaming, position management, and all the API workarounds documented.

## 4. Perplexity Strategy Synthesis
For retail traders with $100–$1,000 accounts in April 2026, the most actionable systematic strategies are **crypto momentum with regime filters (3–7 day swing horizon)**, **equity pair mean-reversion (1–3 day hold)**, and **options tail hedges via short-dated OTM puts (VIX > 18)**. These avoid crowded momentum trades that have degraded in the last 6 months by focusing on uncorrelated edges and structural market inefficiencies.

---

### 1. Crypto Momentum with Regime Filters (3–7 Day Swing)
**Time Horizon:** 3–7 days  
**Entry Rules:**  
- Only trade when 200-day EMA_slope > 0 (regime filter: bullish trend) [1]  
- Asset breaks above 20-period high with volume ≥ 1.5× 10-day average [3]  
- RSI(14) > 50 but < 70 (not overbought) [1]  
**Exit Rules:**  
- Take profit at 1.5×–2× risk (asymmetric reward) [3]  
- Exit if price closes below 10-day EMA or RSI(14) < 40 [1]  
- Stop-loss: 1× ATR(14) below entry [3]  
**Position Sizing:**  
- Risk ≤ 1–2% of account per trade ($1–$20 on $1,000 account) [3]  
- Max 2 open positions to avoid overexposure [3]  
**Edge Source:**  
- “Pullback Trend Strategy with FVG” (Fair Value Gaps) from YouTube video [2]  
- Regime filter logic: EMA_slope + volume confirmation [1]  

> ⚠️ **Degraded Strategy Alert:** Pure intraday crypto momentum (1–5 min) has degraded due to HFT dominance and crowded retail entries [3].

---

### 2. Equity Pair Trading (Mean-Reversion, 1–3 Day Hold)
**Time Horizon:** 1–3 days  
**Entry Rules:**  
- Select highly correlated pairs (e.g., XOM vs CVX, JPM vs BAC) with correlation > 0.8 over 60 days [1]  
- Enter when spread deviates ≥ 2 standard deviations from 20-day mean (Bollinger Band squeeze) [1]  
- Confirm with RSI(14) < 30 (for long leg) or > 70 (for short leg) [1]  
**Exit Rules:**  
- Exit when spread reverts to 5-day mean [1]  
- Stop-loss: 2.5× ATR(14) from entry [3]  
- Time exit: 3 days max (no hold overnight beyond) [4]  
**Position Sizing:**  
- Risk 1% per leg ($10 on $1,000 account)  
- Equal dollar weight on both legs to neutralize beta [4]  
**Edge Source:**  
- Mean-reversion logic from Bollinger Bands + RSI [1]  
- Pair selection framework: correlation > 0.8 + sector alignment [1]  

---

### 3. Options Tail Hedges (Short-Dated OTM Puts, VIX > 18)
**Time Horizon:** 1–5 days (carry 3–7 days)  
**Entry Rules:**  
- Buy 7–14 DTE OTM puts (Δ = 0.10–0.15) when VIX > 18 and SPX below 50-day EMA [6]  
- Confirm with 2× volume spike in put options [6]  
- Avoid during VIX < 15 (cheap hedges become expensive) [6]  
**Exit Rules:**  
- Take profit at 2×–3× cost (asymmetric payoff) [6]  
- Exit if VIX < 15 or SPX breaks above 50-day EMA [6]  
- Stop-loss: 50% of premium paid [6]  
**Position Sizing:**  
- Risk

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-07-06 via Conway's auto-publisher.*
