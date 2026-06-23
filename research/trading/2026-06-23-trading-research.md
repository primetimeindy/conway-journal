# Trading Nightly Research Brief — 2026-06-23

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-23T02:31:30, run time 22.7s._

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
- **Keep The Essentials: Efficient Reference Conditioned Generation via Token Dropping** _(quantitative trading strategy)_
  [2026-06-22](https://arxiv.org/abs/2606.23682v1)
  Reference-based diffusion models enable highly controllable image generation by leveraging elements from input images to guide prompt-driven synthesis. However, these models are computationally expensive in runtime, and their cost scales severely with the number of input references. While the efficiency of diffusion models has been extensively studied in the context of prompt-driven generation, it

- **AIR: Adaptive Interleaved Reasoning with Code in MLLMs** _(quantitative trading strategy)_
  [2026-06-22](https://arxiv.org/abs/2606.23678v1)
  Following the paradigm shift initiated by OpenAI o3, interleaved reasoning with code to enhance multimodal large language models (MLLMs) has become a pivotal research frontier. The existing literature focuses primarily on tool-use within vision-perception tasks. However, such approaches typically rely on predefined heuristics for visual manipulation and are inherently incapable of addressing numer

- **Statistical Proof as a Window into Human-AI Collaboration: Practical Insights and a Community Agenda** _(quantitative trading strategy)_
  [2026-06-22](https://arxiv.org/abs/2606.23666v1)
  Large language models (LLMs) are increasingly woven into expert cognitive work in daily research, yet we know little about how human expertise should adapt when an AI system can execute substantial technical reasoning on its own. Here we use statistical proof development, a demanding and structured form of expert reasoning, as a window into this broader question. Drawing on day-to-day proof proble

- **PsyBridge: A Hybrid Intelligent Framework for Multi-Dimensional Mental Health Assessment and Decision Support** _(momentum crash risk)_
  [2026-06-22](https://arxiv.org/abs/2606.23673v1)
  Mental health assessment commonly relies on isolated screening instruments or data-driven models that often lack interpretability and multi-dimensional integration. Existing approaches frequently focus on individual indicators such as depression or anxiety while providing limited support for comprehensive and explainable decision-making. To address this limitation, this study proposes PsyBridge, a

- **Can LLMs Reliably Self-Report Adversarial Prefills, and How?** _(momentum crash risk)_
  [2026-06-22](https://arxiv.org/abs/2606.23671v1)
  Prior work shows that large language models (LLMs) exhibit introspective capability on benign tasks. We extend the question to safety contexts and examine how reliably a model can recognize that its own prior response was elicited by an adversarial prefill attack. Across ten open-weight instruction-tuned LLMs (3B to 70B) and four safety benchmarks, no model reliably recognizes its own compromised 

- **Quantum Geometry Driven Finite-Momentum Exciton Fluctuations in Flat-Band Systems** _(momentum crash risk)_
  [2026-06-22](https://arxiv.org/abs/2606.23598v1)
  Quantum geometry is instrumental in stabilizing exotic phenomena in systems ranging from topological insulators to superconductors. In dispersionless flat bands, where the kinetic energy is quenched, the quantum metric emerges as the fundamental driver of macroscopic collective phenomena. Here, we theoretically demonstrate that lattice-geometry-induced flat bands, such as those in kagome and Lieb 

- **Emergent Andreev Reflection from a Lattice Duality Defect** _(mean reversion statistical arbitrage)_
  [2026-06-22](https://arxiv.org/abs/2606.23684v1)
  Andreev reflection converts an incoming fermion into an outgoing hole and is usually tied to a superconducting interface. We show that an analogous charge-conjugating boundary condition emerges from a purely lattice duality defect. Starting from a Majorana representation of the transverse-field Ising chain, we construct a folded lattice model in which a boundary Majorana impurity implements a one-

- **Effective hyperuniformity in time-integrated stochastic Turing patterns** _(mean reversion statistical arbitrage)_
  [2026-06-22](https://arxiv.org/abs/2606.23677v1)
  Demographic noise generates stochastic Turing patterns even when reaction-diffusion systems are deterministically stable. We show analytically and verify numerically in the Levin-Segel model that temporal integration of configurations reveals emergent large-scale organization. The intensive number variance in a window of size $R \gg 1$ approaches a finite reaction-kinetic floor as $1/R$, over a sp

- **Tapered Language Models** _(mean reversion statistical arbitrage)_
  [2026-06-22](https://arxiv.org/abs/2606.23670v1)
  Modern language models, including transformer, recurrent, and memory-based variants, share a common chassis: a stack of identical layers in which parameters are allocated uniformly across depth. This is a default inherited from the original transformer and largely unchanged since, yet a growing body of evidence suggests that layers contribute non-uniformly to the final output, with later layers re

- **Little Red Dots on FIRE: Exploring the formation and observational signatures of ultra-compact early galaxies** _(regime detection market)_
  [2026-06-22](https://arxiv.org/abs/2606.23683v1)
  Little Red Dots (LRDs) are compact sources with broad Balmer lines, Balmer breaks, anomalous UV emission, rising red continuum, and uncertain origin. We use FIRE cosmological simulations, 3D dust radiative transfer, and synthetic emission-line data cubes to test whether ultra-compact early galaxies can reproduce LRD-like observables without invoking AGN. In progenitors of present-day group halos (

- **Effective hyperuniformity in time-integrated stochastic Turing patterns** _(regime detection market)_
  [2026-06-22](https://arxiv.org/abs/2606.23677v1)
  Demographic noise generates stochastic Turing patterns even when reaction-diffusion systems are deterministically stable. We show analytically and verify numerically in the Levin-Segel model that temporal integration of configurations reveals emergent large-scale organization. The intensive number variance in a window of size $R \gg 1$ approaches a finite reaction-kinetic floor as $1/R$, over a sp

- **Open Problem: Is AdamW Effective Under Heavy-Tailed Noise?** _(regime detection market)_
  [2026-06-22](https://arxiv.org/abs/2606.23676v1)
  AdamW is the de facto optimizer for training large language models (LLMs), yet the theory behind it still lives mostly in finite-variance regimes. This is increasingly unsatisfying, as empirical evidence indicates that stochastic gradient noise in LLM pretraining is typically heavy-tailed. Recent work shows that sign-based optimizers such as Lion and Muon achieve sharp heavy-tailed rates, and that

- **AutoDex: An Automated Real-World System for Dexterous Grasping Data Collection** _(deep learning volatility forecasting)_
  [2026-06-22](https://arxiv.org/abs/2606.23689v1)
  Learning robust dexterous grasping requires real-world data that records the physical outcomes of grasp attempts. Such data is hard to obtain at scale: teleoperation yields valid physical outcomes but is slow and operator-biased, while simulation-based generation is cheap and scalable but cannot certify contact validity. A natural solution is to generate candidate grasps and verify them on real ha

- **Lift4D: Harmonizing Single-View 3D Estimation for 4D Reconstruction In-the-Wild** _(deep learning volatility forecasting)_
  [2026-06-22](https://arxiv.org/abs/2606.23688v1)
  Reconstructing dynamic non-rigid objects from monocular video requires integrating visual cues from direct observations with data-driven priors over geometry and appearance. Prior approaches either learn to directly predict 4D representations from visual input or initialize a 3D representation that is subsequently deformed and refined based on video evidence. However, the former are constrained by

- **LaST-HD: Learning Latent Physical Reasoning from Scalable Human Data for Robot Manipulation** _(deep learning volatility forecasting)_
  [2026-06-22](https://arxiv.org/abs/2606.23685v1)
  Human-hand demonstrations provide a direct and scalable source of physical interaction data for robot learning. While manual retargeting is indispensable for establishing kinematic action correspondence across different morphologies, robust transfer requires going beyond geometry to address the underlying alignment of physical dynamics between human and robot manipulation. To address this, we intr

- **Lift4D: Harmonizing Single-View 3D Estimation for 4D Reconstruction In-the-Wild** _(transformer financial time series)_
  [2026-06-22](https://arxiv.org/abs/2606.23688v1)
  Reconstructing dynamic non-rigid objects from monocular video requires integrating visual cues from direct observations with data-driven priors over geometry and appearance. Prior approaches either learn to directly predict 4D representations from visual input or initialize a 3D representation that is subsequently deformed and refined based on video evidence. However, the former are constrained by

- **Little Red Dots on FIRE: Exploring the formation and observational signatures of ultra-compact early galaxies** _(transformer financial time series)_
  [2026-06-22](https://arxiv.org/abs/2606.23683v1)
  Little Red Dots (LRDs) are compact sources with broad Balmer lines, Balmer breaks, anomalous UV emission, rising red continuum, and uncertain origin. We use FIRE cosmological simulations, 3D dust radiative transfer, and synthetic emission-line data cubes to test whether ultra-compact early galaxies can reproduce LRD-like observables without invoking AGN. In progenitors of present-day group halos (

- **Keep The Essentials: Efficient Reference Conditioned Generation via Token Dropping** _(transformer financial time series)_
  [2026-06-22](https://arxiv.org/abs/2606.23682v1)
  Reference-based diffusion models enable highly controllable image generation by leveraging elements from input images to guide prompt-driven synthesis. However, these models are computationally expensive in runtime, and their cost scales severely with the number of input references. While the efficiency of diffusion models has been extensively studied in the context of prompt-driven generation, it

- **AutoDex: An Automated Real-World System for Dexterous Grasping Data Collection** _(reinforcement learning portfolio)_
  [2026-06-22](https://arxiv.org/abs/2606.23689v1)
  Learning robust dexterous grasping requires real-world data that records the physical outcomes of grasp attempts. Such data is hard to obtain at scale: teleoperation yields valid physical outcomes but is slow and operator-biased, while simulation-based generation is cheap and scalable but cannot certify contact validity. A natural solution is to generate candidate grasps and verify them on real ha

- **Lift4D: Harmonizing Single-View 3D Estimation for 4D Reconstruction In-the-Wild** _(reinforcement learning portfolio)_
  [2026-06-22](https://arxiv.org/abs/2606.23688v1)
  Reconstructing dynamic non-rigid objects from monocular video requires integrating visual cues from direct observations with data-driven priors over geometry and appearance. Prior approaches either learn to directly predict 4D representations from visual input or initialize a 3D representation that is subsequently deformed and refined based on video evidence. However, the former are constrained by

- **LaST-HD: Learning Latent Physical Reasoning from Scalable Human Data for Robot Manipulation** _(reinforcement learning portfolio)_
  [2026-06-22](https://arxiv.org/abs/2606.23685v1)
  Human-hand demonstrations provide a direct and scalable source of physical interaction data for robot learning. While manual retargeting is indispensable for establishing kinematic action correspondence across different morphologies, robust transfer requires going beyond geometry to address the underlying alignment of physical dynamics between human and robot manipulation. To address this, we intr

- **MORL-A2C: Multi-Objective Reinforcement Learning Reranker for Optimizing Healthiness in MOPI-HFRS** _(cryptocurrency trading)_
  [2026-06-22](https://arxiv.org/abs/2606.23603v1)
  Unhealthy dietary behavior continues to be a persistent public health issue in the United States, exacerbated by recommendation systems that prioritize user preference without considering nutritional health. The Multi-Objective Personalized Interpretable Health-aware Food Recommendation System (MOPI-HFRS), from which this work extends, addresses this by jointly optimizing preference, health, and d

- **Quantifying the Agreement Between Data-Influence and Data-Similarity to Understand LLM Behavior** _(cryptocurrency trading)_
  [2026-06-22](https://arxiv.org/abs/2606.23591v1)
  One way to understand LLM behavior is to trace its output back to the training data. Two types of measures are commonly used for output tracing: data-similarity and data-influence. The former is cheaper while the latter is believed to be more accurate. Even though many works have compared them for ground-truth tasks, no such comparisons exist for output tracing. Here, we fill this gap and precisel

- **SVD-Surgeon: Optimal Singular-Value Surgery for Large Language Model Compression** _(cryptocurrency trading)_
  [2026-06-22](https://arxiv.org/abs/2606.23568v1)
  Large language models (LLMs) achieve remarkable performance across a wide range of tasks, but their deployment is constrained by substantial memory and compute requirements. Low-rank compression via singular value decomposition (SVD) is an effective remedy, but existing methods focus on how to factorize and which components to keep. We introduce SVD-Surgeon, a training-free method that brings the 

- **Lift4D: Harmonizing Single-View 3D Estimation for 4D Reconstruction In-the-Wild** _(options volatility surface)_
  [2026-06-22](https://arxiv.org/abs/2606.23688v1)
  Reconstructing dynamic non-rigid objects from monocular video requires integrating visual cues from direct observations with data-driven priors over geometry and appearance. Prior approaches either learn to directly predict 4D representations from visual input or initialize a 3D representation that is subsequently deformed and refined based on video evidence. However, the former are constrained by

- **MAS-PromptBench: When Does Prompt Optimization Improve Multi-Agent LLM Systems?** _(options volatility surface)_
  [2026-06-22](https://arxiv.org/abs/2606.23664v1)
  Multi-agent systems (MAS) offer a scalable path forward for agentic AI, comprising multiple LLM-based agents, each assigned a system prompt and a position within a workflow that governs inter-agent coordination and output aggregation. System prompts thus form a critical and accessible optimization surface: they specify agents' roles and behaviors, enabling system-level improvements without model f

- **Lightweight Neural Framework for Robust 3D Volume and Surface Estimation from Multi-View Images** _(options volatility surface)_
  [2026-06-22](https://arxiv.org/abs/2606.23653v1)
  Accurate volume and surface area estimation is critical for diverse applications, from marine ecology to medical diagnostics. However, existing methods often suffer from high computational costs and poor performance with sparse and noisy data. We propose a fully feed-forward framework that regresses scale-normalized volume and surface area and their associated uncertainties directly from multi-vie

- **Resolving support-mismatch by local basis rotation in variational Monte Carlo** _(factor investing alpha)_
  [2026-06-22](https://arxiv.org/abs/2606.23657v1)
  Real-time dynamics after a local quench by a charged operator encodes the response functions measured in spectroscopic experiments, yet they have long posed a challenge for variational Monte Carlo calculations. The obstacle is a support mismatch: the projective action by a charged local operator forces an exponentially large number of configurations to vanish, but these configurations may still co

- **The EDGE-CALIFA Survey: Star Formation Efficiency and Galaxy Quenching across 62 Main Sequence, Green Valley, and Red Galaxies** _(factor investing alpha)_
  [2026-06-22](https://arxiv.org/abs/2606.23649v1)
  We present GBT-EDGE, a new CO(1-0) survey using the Green Bank Telescope to map 62 nearby (10-140 Mpc) galaxies spanning the star-forming main sequence (SFMS), green valley, and red sequence. The galaxy sample is selected from the CALIFA survey with integral field spectroscopy (IFS), which provides a representative census of local galactic environments. Combining the CO dataset with CALIFA's optic

- **Fundamental Limits of Stability Inference in High-Dimensional Complex Systems** _(factor investing alpha)_
  [2026-06-22](https://arxiv.org/abs/2606.23644v1)
  Many complex systems, including ecosystems, neural circuits, and financial markets, are inferred to operate close to a threshold of instability, at which a small perturbation can propagate across the entire system. This proximity is often interpreted as functionally advantageous, yet it poses a question common to all these fields: from a finite, noisy recording, how precisely can the distance of a

## 3. GitHub Repos (Recently Updated)
- **[Yankeremerycloth537/finquant](https://github.com/Yankeremerycloth537/finquant)** ⭐ 0 · None _(updated 2026-06-23)_
  Provide efficient event-driven Python tools for accurate multi-asset quantitative backtesting with local data caching and detailed trade logging.

- **[cikafeee/algorithmic-trading-backtest](https://github.com/cikafeee/algorithmic-trading-backtest)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-23)_
  📊 Analyze and validate trading strategies with a high-performance backtesting engine using PySpark, processing thousands of backtests on real market data.

- **[11Bhavin/Quant_Trading_Portfolio-](https://github.com/11Bhavin/Quant_Trading_Portfolio-)** ⭐ 0 · None _(updated 2026-06-23)_
  📈 Build and backtest automated trading strategies using Python to enhance your quantitative finance skills and explore the financial markets.

- **[tranduy216/auto-alert-gg-chat](https://github.com/tranduy216/auto-alert-gg-chat)** ⭐ 0 · Python _(updated 2026-06-23)_
  Crypto trading bot on OKX (2.5x, stop -5.5%). Coins: ETH, BNB, LINK, ADA, MATIC. Strategy: 3D trend + 1D execution engine with 3-stage scaling entries (limit orders). Rules: max 4 pos, 75% cap, BTC re

- **[hummingbot/hummingbot](https://github.com/hummingbot/hummingbot)** ⭐ 18963 · Python _(updated 2026-06-23)_
  Open source software that helps you create and deploy high-frequency crypto trading bots

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 0 · HTML _(updated 2026-06-23)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[MohanpandeyA/quantmind](https://github.com/MohanpandeyA/quantmind)** ⭐ 1 · Python _(updated 2026-06-23)_
  AI-Powered Algorithmic Trading Strategy Advisor — LangGraph + RAG 

- **[moo-22/opencrypto](https://github.com/moo-22/opencrypto)** ⭐ 2 · Python _(updated 2026-06-23)_
  Develop a modular framework to build, backtest, and deploy algorithmic trading strategies for cryptocurrency markets efficiently.

- **[DTal621/trading-bot](https://github.com/DTal621/trading-bot)** ⭐ 1 · Python _(updated 2026-06-23)_
  Algorithmic trading strategy for stocks and crypto — Alpaca Markets

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 1 · None _(updated 2026-06-23)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[liuh886/alpha_engine](https://github.com/liuh886/alpha_engine)** ⭐ 0 · Python _(updated 2026-06-23)_
  Alpha Engine: AI-driven quantitative trading research platform with factor lifecycle, model registry, backtesting, and dashboard.

- **[Roboute-ex/AlphaLab-Agent](https://github.com/Roboute-ex/AlphaLab-Agent)** ⭐ 0 · Python _(updated 2026-06-23)_
  Deterministic local workflow for low/mid-frequency equity multi-factor research and quant-agent demos

- **[NavnoorBawa/russell3000-pairs-trading](https://github.com/NavnoorBawa/russell3000-pairs-trading)** ⭐ 1 · Python _(updated 2026-06-23)_
  Russell 3000 statistical arbitrage research system: Kalman spreads, cointegration pair selection, regime gating, walk-forward validation, and a controlled ML ablation.

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-06-23)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[OmarHayat-DEV/pairs-trading-shopify](https://github.com/OmarHayat-DEV/pairs-trading-shopify)** ⭐ 1 · Python _(updated 2026-06-22)_
  Basic statistical arbitrage analysis for pairs trading of SHOP (TSE) and SHOP (NASDAQ).

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-23)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 49 · Python _(updated 2026-06-19)_
  A stock/futures auto trading framework using Shioaji API

- **[I-am-Uchenna/institutional-options-research](https://github.com/I-am-Uchenna/institutional-options-research)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-18)_
  Academic, risk-first options research framework with stochastic-volatility pricing, defined-risk strategy analysis, and paper-trading controls.

## 4. Perplexity Strategy Synthesis
The most actionable systematic trading strategies for retail traders with small accounts ($100–$1000) in April 2026 focus on **catalyst-driven momentum pullbacks**, **swing momentum with regime filters**, and strict **risk management (1–2% per trade)**; note that **news-based disposition trading and scalping** have significantly degraded due to crowded execution and high volatility, making them less viable for small accounts [1][2].

Below are concrete parameters for each strategy category you requested, with specific entry/exit rules, time horizons, position sizing, and sources. Strategies flagged as **DEGRADED** are clearly marked.

---

### 1. Crypto Momentum with Regime Filters (Time Horizon: 4H–Daily)

**Strategy:** Buy first orderly pullback of crypto assets with strong catalysts (e.g., ETF approvals, major upgrades) into the “Bone Zone” (between 9 EMA and 20 EMA on 5-minute charts), confirmed by a green candle holding in the zone [1].

**Concrete Parameters:**
- **Time Horizon:** Intraday to 3-day swing (5-min entry, 4H/Daily trend filter).
- **Entry Rule:**
  - Asset must have a catalyst (press release, earnings, major upgrade) bringing real volume.
  - Price spikes, then pulls back orderly into 9 EMA–20 EMA zone.
  - Confirm with a green candle holding in the zone.
- **Exit Rule:**
  - Stop: Hard stop under low of the green candle [1].
  - Target: Recent high (1.5–2× risk) [2].
- **Position Sizing:**
  - Risk no more than 1–2% of account per trade [2].
  - For $100 account: max $1–2 risk per trade.
- **Regime Filter:**
  - Only trade if 4H/Daily structure is in uptrend or downtrend (not consolidation) [4].
  - Avoid trading if market sentiment is emotionally dominated (use sentiment gauges) [2].

**Source:** Bulls on Wall Street (catalyst first pullback into Bone Zone) [1]; Amerisave (momentum trading & risk management) [2]; SLC Execution Blueprint (structure + levels + confirmation) [4].

---

### 2. Equity Pair Trading (Time Horizon: 3–7 Days)

**Strategy:** Pair two correlated stocks (e.g., same sector) where one is oversold near support and the other is overbought near resistance; enter long on the oversold, short on the overbought, expecting a 3–5-day bounce back to resistance [2].

**Concrete Parameters:**
- **Time Horizon:** 3–7 day swing.
- **Entry Rule:**
  - Select pair with high correlation (e.g., tech or energy stocks).
  - Asset A: oversold near support, holding.
  - Asset B: overbought near resistance.
  - Confirm with volume ≥2× normal average and decisive breakout [2].
- **Exit Rule:**
  - Stop-loss: predetermined before entry, not during [2].
  - Target: 1.5–2× risk (asymmetric reward) [2].
- **Position Sizing:**
  - Risk 1–2% per trade [2].
  - For $1000 account: max $10–20 per pair.
- **Regime Filter:**
  - Only trade if weekly structure is bullish (for long) or bearish (for short) [5].
  - Add only at support with confluence; never add as price rises [5].

**Source:** Amerisave (pair trading & momentum patterns) [2]; Momentum Trading Alliance (support-based scaling & structure) [5].

---

### 3. Options Tail Hedges (Currently Cheap) (Time Horizon: 1–3 Months)

**Strategy:** Buy out-of-the-money (OTM) put options on broad indices (e.g., S&P 500) when VIX is low (<15) and tail risk is cheap; use VIX

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-23 via Conway's auto-publisher.*
