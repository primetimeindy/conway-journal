# Trading Nightly Research Brief — 2026-06-26

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-26T02:31:41, run time 22.8s._

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
- **Cultivating logical catalysts for fault-tolerant dyadic phase rotations** _(quantitative trading strategy)_
  [2026-06-25](https://arxiv.org/abs/2606.27358v1)
  We introduce a surface-code cultivation protocol for reusable logical catalyst states that implement exact fine dyadic phase gates $Z^{2^{-b}}$ by phase kickback. The catalyst is an eigenstate of a high-period Clifford circuit $U$, with a direct construction supported on $O(2^b)$ logical qubits. Once cultivated, each invocation implements the target phase through a controlled-$U$ gadget, removing 

- **Congruent copies of finite patterns in planar point sets** _(quantitative trading strategy)_
  [2026-06-25](https://arxiv.org/abs/2606.27352v1)
  Given a finite nonempty planar point set $S$, what is the maximum number of congruent copies of $S$ contained in a set of $n$ points in the Euclidean plane? Building on OpenAI's recent breakthrough on the unit distance problem, we construct planar sets consisting of $n$ points that contain $Ω_S(n^{1+δ_S})$ congruent copies of $S$, for some positive constant $δ_S$ depending only on $S$. This answer

- **Specific absorption rate of uniaxial single-domain nanomagnets: stochastic spin dynamics versus linear response theory** _(quantitative trading strategy)_
  [2026-06-25](https://arxiv.org/abs/2606.27351v1)
  We compute the specific absorption rate of a uniaxial single-domain nanomagnet driven by an alternating magnetic field by two methods: i) direct numerical integration of the stochastic (Langevin) Landau--Lifshitz--Gilbert equation (the LLL approach), and ii) linear response theory (LRT) based on the Debye susceptibility with the Néel relaxation time $τ_\mathrm{N}$. We first analytically show that 

- **Hidden-ordered Dirac fermions** _(momentum crash risk)_
  [2026-06-25](https://arxiv.org/abs/2606.27368v1)
  I propose a Hermitian extension of the Lorentz-symmetric Dirac theory by complementing the associated Hamiltonian with another \emph{masslike} anticommuting Dirac operator. The resulting theory manifests the iconic linear energy-momentum relationship in any dimension ($d$) and hence the emergent nodal quasiparticle excitations are named \emph{hidden-ordered Dirac fermions}, which are symmetry prot

- **PhysiFormer: Learning to Simulate Mechanics in World Space** _(momentum crash risk)_
  [2026-06-25](https://arxiv.org/abs/2606.27364v1)
  We present PhysiFormer, a diffusion transformer for physically-plausible 3D object motion. Unlike video world models that operate in view-dependent pixel space, PhysiFormer represents objects as 3D meshes expressed in world coordinates. Given the initial vertex positions and velocities, as well as object material type, rigid or elastic, the model samples future vertex trajectories. While related n

- **Bridging Performance and Generalization in Reinforcement Learning for Agile Flight** _(momentum crash risk)_
  [2026-06-25](https://arxiv.org/abs/2606.27348v1)
  Autonomous drone racing is a fundamentally challenging regime for autonomous aerial robots, requiring time-optimal control while operating under persistent actuation saturation. While reinforcement learning (RL) has achieved human-level performance in this domain, current methods fail to generalize; policies trained on specific environments often crash immediately in unseen configurations. This fa

- **Paying More Attention to Visual Tokens in Self-Evolving Large Multimodal Models** _(mean reversion statistical arbitrage)_
  [2026-06-25](https://arxiv.org/abs/2606.27373v1)
  Recently, self-evolving large multimodal models (LMMs) have received attention for improving visual reasoning in a purely unsupervised setting. However, multi-role self-play and self-consistency reward schemes in existing self-evolving LMMs optimize answer agreement without ensuring the decoder attends to visual content, relying instead on statistical language priors to produce self consistent out

- **Autoregressive Boltzmann Generators** _(mean reversion statistical arbitrage)_
  [2026-06-25](https://arxiv.org/abs/2606.27361v1)
  Efficient sampling of molecular systems at thermodynamic equilibrium is a hallmark challenge in statistical physics. This challenge has driven the development of Boltzmann Generators (BGs), which allow rapid generation of uncorrelated equilibrium samples by combining a generative model with exact likelihoods and an importance sampling correction. However, modern BGs predominantly rely on normalizi

- **RouterVLA: Turning Smoke Tests into Supervision for Heterogeneous VLA Selection** _(mean reversion statistical arbitrage)_
  [2026-06-25](https://arxiv.org/abs/2606.27355v1)
  We study whether pre-deployment evaluation rollouts can be reused to supervise policy selection. Robot teams routinely smoke test candidate vision-language-action (VLA) policies, then compress those trials into a global winner. RouterVLA evaluates this idea with outcome-disjoint cross-fitting: recorded probes build a profile for each frozen expert, and a separate trial scores the selected expert w

- **Accessing both electrochemical SEIRA and SERS with ultrasensitive metamaterials for enhanced molecular identification** _(regime detection market)_
  [2026-06-25](https://arxiv.org/abs/2606.27367v1)
  Surface-enhanced IR absorption (SEIRA) and surface-enhanced Raman spectroscopy (SERS) are complementary techniques that allow for ultrasensitive chemical fingerprinting. Non-invasive optical sensing would be significantly improved by a robust implementation of a reusable substrate that combines these techniques. Here, we present an electrochemically-cleanable metamaterial that enables combined rea

- **Beyond the equation of state: a second-order diagnostic for dynamical dark energy** _(regime detection market)_
  [2026-06-25](https://arxiv.org/abs/2606.27356v1)
  The first-order continuity equations determine the evolution of the energy densities but depend only on the instantaneous value of the dark-energy equation-of-state parameter. Differentiating these equations with respect to e-fold time introduces the term $ω'_{\rm DE}$ explicitly, providing a second-order probe of dark-energy dynamics. Consequently, while information about the evolution of the equ

- **Error-Conditioned Neural Solvers** _(regime detection market)_
  [2026-06-25](https://arxiv.org/abs/2606.27354v1)
  Neural surrogate models offer fast approximate mappings from PDE parameters to solutions, but they typically treat solving as a purely statistical task: once trained, they struggle to correct their own constraint violations and extrapolate beyond the training distribution. Recent hybrid methods promote physical correctness by targeting the PDE residual via gradient descent or Gauss--Newton steps, 

- **DanceOPD: On-Policy Generative Field Distillation** _(deep learning volatility forecasting)_
  [2026-06-25](https://arxiv.org/abs/2606.27377v1)
  Modern image generation demands a single model that unifies diverse capabilities, including text-to-image (T2I), local editing, and global editing. However, these capabilities are rarely naturally aligned and often conflict. For instance, editing tends to degrade T2I performance, while global and local editing interfere with each other. Consequently, effectively composing these capabilities has be

- **Ask, Solve, Generate: Self-Evolving Unified Multimodal Understanding and Generation via Self-Consistency Rewards** _(deep learning volatility forecasting)_
  [2026-06-25](https://arxiv.org/abs/2606.27376v1)
  Most unified large multimodal models (LMMs) that support both visual understanding and image generation still rely on curated post-training supervision, such as human annotations, preference labels, or external reward models. We ask whether a unified LMM can improve both abilities autonomously using only unlabeled images. We propose a self-evolving training framework with three internal roles: a P

- **Scalable Behavior Cloning with Open Data, Training, and Evaluation** _(deep learning volatility forecasting)_
  [2026-06-25](https://arxiv.org/abs/2606.27375v1)
  We introduce ABC, a fully open-source stack for manipulation with behavior cloning. At its core is ABC-130K: the largest open-source teleoperation dataset to date, featuring 3,500 hours of data spanning over 130K episodes across 195 diverse tasks. Furthermore, we open-source our accessible hardware setup, training infrastructure, and simulation pipeline. We also release 400 hours of sim-teleop dat

- **Scalable Behavior Cloning with Open Data, Training, and Evaluation** _(transformer financial time series)_
  [2026-06-25](https://arxiv.org/abs/2606.27375v1)
  We introduce ABC, a fully open-source stack for manipulation with behavior cloning. At its core is ABC-130K: the largest open-source teleoperation dataset to date, featuring 3,500 hours of data spanning over 130K episodes across 195 diverse tasks. Furthermore, we open-source our accessible hardware setup, training infrastructure, and simulation pipeline. We also release 400 hours of sim-teleop dat

- **Paying More Attention to Visual Tokens in Self-Evolving Large Multimodal Models** _(transformer financial time series)_
  [2026-06-25](https://arxiv.org/abs/2606.27373v1)
  Recently, self-evolving large multimodal models (LMMs) have received attention for improving visual reasoning in a purely unsupervised setting. However, multi-role self-play and self-consistency reward schemes in existing self-evolving LMMs optimize answer agreement without ensuring the decoder attends to visual content, relying instead on statistical language priors to produce self consistent out

- **DnA: Denoising Attention for Visual Tasks** _(transformer financial time series)_
  [2026-06-25](https://arxiv.org/abs/2606.27372v1)
  The softmax activation in multihead attention (MHA) is the de facto standard for attention-based models in visual perception tasks. However, standard softmax can produce noisy attention patterns that dilute relevant features and degrade its performance. In this paper, we propose Denoising Attention or DnA, in which, first, a positive query identifies which image features belong to the correct clas

- **DanceOPD: On-Policy Generative Field Distillation** _(reinforcement learning portfolio)_
  [2026-06-25](https://arxiv.org/abs/2606.27377v1)
  Modern image generation demands a single model that unifies diverse capabilities, including text-to-image (T2I), local editing, and global editing. However, these capabilities are rarely naturally aligned and often conflict. For instance, editing tends to degrade T2I performance, while global and local editing interfere with each other. Consequently, effectively composing these capabilities has be

- **Ask, Solve, Generate: Self-Evolving Unified Multimodal Understanding and Generation via Self-Consistency Rewards** _(reinforcement learning portfolio)_
  [2026-06-25](https://arxiv.org/abs/2606.27376v1)
  Most unified large multimodal models (LMMs) that support both visual understanding and image generation still rely on curated post-training supervision, such as human annotations, preference labels, or external reward models. We ask whether a unified LMM can improve both abilities autonomously using only unlabeled images. We propose a self-evolving training framework with three internal roles: a P

- **Scalable Behavior Cloning with Open Data, Training, and Evaluation** _(reinforcement learning portfolio)_
  [2026-06-25](https://arxiv.org/abs/2606.27375v1)
  We introduce ABC, a fully open-source stack for manipulation with behavior cloning. At its core is ABC-130K: the largest open-source teleoperation dataset to date, featuring 3,500 hours of data spanning over 130K episodes across 195 diverse tasks. Furthermore, we open-source our accessible hardware setup, training infrastructure, and simulation pipeline. We also release 400 hours of sim-teleop dat

- **Cultivating logical catalysts for fault-tolerant dyadic phase rotations** _(cryptocurrency trading)_
  [2026-06-25](https://arxiv.org/abs/2606.27358v1)
  We introduce a surface-code cultivation protocol for reusable logical catalyst states that implement exact fine dyadic phase gates $Z^{2^{-b}}$ by phase kickback. The catalyst is an eigenstate of a high-period Clifford circuit $U$, with a direct construction supported on $O(2^b)$ logical qubits. Once cultivated, each invocation implements the target phase through a controlled-$U$ gadget, removing 

- **Exact and Deterministic Patch Descriptor Retrieval via Hierarchical Normalization** _(cryptocurrency trading)_
  [2026-06-25](https://arxiv.org/abs/2606.27280v1)
  We present a patch descriptor retrieval method that returns the exact nearest neighbour -- provably identical to exhaustive full-vector search -- while evaluating only a small fraction of the database, and does so deterministically: the same (database, query) pair always produces the same result, independent of run order, thread count, or hardware. This contrasts with approximate nearest-neighbour

- **Evaluating Architectural Trade-offs in CGRAs: The Impact of Scratchpad Memory and Heterogeneity on Compute-Intensive Kernels** _(cryptocurrency trading)_
  [2026-06-25](https://arxiv.org/abs/2606.27240v1)
  Modern edge computing applications, particularly high-throughput stream processing like Vision Transformers (ViTs), demand massive spatial parallelism and efficient data movement under tight power and area constraints. Coarse-Grained Reconfigurable Architectures (CGRAs) offer a promising paradigm to balance performance, flexibility, and energy efficiency. This paper analyzes the impact of two crit

- **Accessing both electrochemical SEIRA and SERS with ultrasensitive metamaterials for enhanced molecular identification** _(options volatility surface)_
  [2026-06-25](https://arxiv.org/abs/2606.27367v1)
  Surface-enhanced IR absorption (SEIRA) and surface-enhanced Raman spectroscopy (SERS) are complementary techniques that allow for ultrasensitive chemical fingerprinting. Non-invasive optical sensing would be significantly improved by a robust implementation of a reusable substrate that combines these techniques. Here, we present an electrochemically-cleanable metamaterial that enables combined rea

- **3D Imaging of Complex Skyrmion and Hopf Topologies in an Extended Sample** _(options volatility surface)_
  [2026-06-25](https://arxiv.org/abs/2606.27365v1)
  Spin textures are key for emergent magnetic phenomena such as topological protection and underpin novel spintronic device paradigms based on racetrack memory, logic gates, and neuromorphic computing. Using a coherent diffractive imaging technique called vector ptycho-tomography, in combination with algorithms that are robust to noise, we image the 3D magnetic texture of skyrmion and Hopf topologie

- **Cultivating logical catalysts for fault-tolerant dyadic phase rotations** _(options volatility surface)_
  [2026-06-25](https://arxiv.org/abs/2606.27358v1)
  We introduce a surface-code cultivation protocol for reusable logical catalyst states that implement exact fine dyadic phase gates $Z^{2^{-b}}$ by phase kickback. The catalyst is an eigenstate of a high-period Clifford circuit $U$, with a direct construction supported on $O(2^b)$ logical qubits. Once cultivated, each invocation implements the target phase through a controlled-$U$ gadget, removing 

- **World Action Models Enable Continual Imitation Learning with Recurrent Generative Replays** _(factor investing alpha)_
  [2026-06-25](https://arxiv.org/abs/2606.27374v1)
  Going beyond predicting robot actions, World Action Models (WAMs) can also generate future visual observations. We build on this generative capability to propose Recurrent Generative Replay (REGEN), a continual imitation learning framework that synthesizes pseudo-replay trajectories, enabling a robot policy to rehearse previously learned tasks without storing their original human demonstrations. D

- **$\mathrm{W}^*$-algebraic Integration Theory** _(factor investing alpha)_
  [2026-06-25](https://arxiv.org/abs/2606.27366v1)
  Given a pair of $\mathrm{W}^*$-algebras $(\mathcal{M}_\mathcal{S},\mathcal{M}_\mathcal{R})$ with $(\mathcal{M}_\mathcal{S})_*$ separable, a measurable space $(Σ, \mathcal{F})$ and a POVM $\mathsf{E}: \mathcal{F} \to \mathcal{E}(\mathcal{M}_\mathcal{R})$, the integral of a function $f: Σ\to \mathcal{M}_\mathcal{S}$ is defined as an element of the spatial tensor product $\int f \otimes d\mathsf{E} \

- **Jet impingement cooling with multi-stage ducted electroaerodynamic actuators** _(factor investing alpha)_
  [2026-06-25](https://arxiv.org/abs/2606.27338v1)
  Modern high-performance mobile electronics impose extreme constraints on thermal management, and traditional cooling methods often fail to meet requirements for power density, form factor, and durability. Jet impingement cooling offers a compelling solution but is typically hindered by the need for bulky ancillary hardware. Here, we demonstrate that compact arrays of reduced-scale electroaerodynam

## 3. GitHub Repos (Recently Updated)
- **[RafaEngineer/strapsim_portfolio_similarity_metric](https://github.com/RafaEngineer/strapsim_portfolio_similarity_metric)** ⭐ 1 · PHP _(updated 2026-06-26)_
  📊 Calculate portfolio similarity metrics to enhance ETF alignment and optimize trading strategies in quantitative finance.

- **[HaSerZin/trade_political_distance_wto](https://github.com/HaSerZin/trade_political_distance_wto)** ⭐ 2 · Jupyter Notebook _(updated 2026-06-26)_
  🌍 Model political distance and trade dynamics using a quantitative framework to enhance understanding of international trade relationships.

- **[Vixoqz/vnpy-Machine-Learning](https://github.com/Vixoqz/vnpy-Machine-Learning)** ⭐ 0 · C# _(updated 2026-06-26)_
  vnpy-Machine-Learning: integrates machine-learning models with the vn.py quantitative-trading framework for AI-driven, data-driven algorithmic trading and backtesting in Python.

- **[tranduy216/auto-alert-gg-chat](https://github.com/tranduy216/auto-alert-gg-chat)** ⭐ 1 · Python _(updated 2026-06-26)_
  Crypto trading bot on OKX (2.5x, stop -5.5%). Coins: ETH, BNB, LINK, ADA, MATIC. Strategy: 3D trend + 1D execution engine with 3-stage scaling entries (limit orders). Rules: max 4 pos, 75% cap, BTC re

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 0 · HTML _(updated 2026-06-26)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[ssproduction13-ship-it/crypto-signal-bot](https://github.com/ssproduction13-ship-it/crypto-signal-bot)** ⭐ 0 · TypeScript _(updated 2026-06-26)_
  Telegram bot for crypto trading signals with AI analysis (Gemini), backtesting, paper trading

- **[DippsDev/AR-InvestTech](https://github.com/DippsDev/AR-InvestTech)** ⭐ 1 · Python _(updated 2026-06-26)_
  Automated algorithmic trading system for the US30 (Dow Jones Industrial Average) index. Built on a Python backend that implements the AR-Investments strategy, handling market data ingestion, signal ge

- **[astarek1983/street-algo-trader](https://github.com/astarek1983/street-algo-trader)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-26)_
  🚀 Implement algorithmic trading strategies for a Jane Street-style exchange, featuring market-making, arbitrage, and momentum signals.

- **[Anna-007-tech/algorithmic-trading-ai](https://github.com/Anna-007-tech/algorithmic-trading-ai)** ⭐ 2 · None _(updated 2026-06-26)_
  📈 Explore AI-driven trading strategies through data analysis of forex and crypto volatility using PCA, K-means, and neural networks.

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 2 · None _(updated 2026-06-26)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[RintuRifle/alpha-engine](https://github.com/RintuRifle/alpha-engine)** ⭐ 2 · Python _(updated 2026-06-25)_
  A Quantitative Research & Algorithmic Trading Platform built in Python. It features an event-driven backtesting engine, custom factor research modules, robust risk analytics (Sharpe, Sortino, Drawdown

- **[liuh886/alpha_engine](https://github.com/liuh886/alpha_engine)** ⭐ 0 · Python _(updated 2026-06-25)_
  Alpha Engine: AI-driven quantitative trading research platform with factor lifecycle, model registry, backtesting, and dashboard.

- **[Joshy837/pairs-trading](https://github.com/Joshy837/pairs-trading)** ⭐ 0 · TypeScript _(updated 2026-06-26)_
  Statistical arbitrage backtester — FastAPI backend, Next.js frontend

- **[OmarHayat-DEV/pairs-trading-shopify](https://github.com/OmarHayat-DEV/pairs-trading-shopify)** ⭐ 1 · JavaScript _(updated 2026-06-26)_
  Basic statistical arbitrage analysis for pairs trading of SHOP (TSE) and SHOP (NASDAQ).

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-06-26)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-26)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 49 · Python _(updated 2026-06-25)_
  A stock/futures auto trading framework using Shioaji API

- **[I-am-Uchenna/institutional-options-research](https://github.com/I-am-Uchenna/institutional-options-research)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-18)_
  Academic, risk-first options research framework with stochastic-volatility pricing, defined-risk strategy analysis, and paper-trading controls.

## 4. Perplexity Strategy Synthesis
For retail traders with small accounts ($100–$1000) in April 2026, the most actionable systematic strategies are **swing- or pullback-based momentum with regime filters**, **simple range-break equity pairs**, and **low-cost index put tail hedges via 0% DV01 options**; avoid intraday scalping, unfiltered crypto momentum, and crowded equity mean-reversion pairs that have **degraded** in the last 6 months due to increased algorithmic competition and compressed margins.

Below are concrete parameters for each focused area:

---

### 1. **Crypto Momentum with Regime Filters**

**Strategy**: Pullback Trend Strategy with Fair Value Gaps (FVG) + Regime Filter  
**Time Horizon**: 1–5 days (swing)  
**Entry Rules**:
- Identify an uptrend using Hull Moving Average (10/10) or 34/55 EMAs on 4H chart [5][4]
- Wait for price to pull back into a **Fair Value Gap** (FVG) formed after a strong move [1]
- Confirm regime: Only trade if **RSI(14) > 50** and **volume > 2× average** [1][2]
- Enter long on bounce from FVG with stop below swing low [1][5]

**Exit Rules**:
- Target: **1:3 risk-to-reward** (e.g., risk $50 → target $150) [1]
- Exit at prior resistance or if 20-period Donchian Channel breaks downward [4]

**Position Sizing**:
- Risk **1% of account per trade** (e.g., $10 on $1000) [2][3]
- Use equities: trade 0.1–0.5 lots or shares depending on broker [5]

**Edge Source**:
- YouTube: “Small Account Trading: 2026 Strategies That ACTUALLY Work!” – Pullback Trend with FVG + CEST Framework [1]
- CEST = Conditions, Entries, Stops, Targets precision system [1]

**Degraded Strategy**:  
⚠️ **Unfiltered crypto momentum (e.g., chasing breakouts without FVG/regime)** has degraded due to front-running by algos and increased volatility dampening [1][2]

---

### 2. **Equity Pair Trading**

**Strategy**: Range-Break Pair with Volatility Confirmation  
**Time Horizon**: 3–7 days  
**Entry Rules**:
- Select two highly correlated stocks (e.g., XOM vs. CVX, JPM vs. BAC)
- Define trading range using **support/resistance** or **20-period Donchian Channel** [4]
- Enter long on **break above resistance + 2× volume spike** [2][4]
- Hedge with short leg (offset delta) if volatility > 1.5× average [2]

**Exit Rules**:
- Target: **1.5–2× risk** (e.g., $75–$100 profit for $50 risk) [2]
- Exit if price consolidates below new level or RSI > 70 [2][4]

**Position Sizing**:
- Risk **1% per leg** (total 2% max) [3]
- Use fractional shares or micro-lots to fit small accounts [3]

**Edge Source**:
- Amerisave: “7 Day Trading Strategies That Work in 2026” – volume spikes, breakout signals [2]
- Moomoo: updated 2026 intraday margin rules + swing trading for small accounts [3]

**Degraded Strategy**:  
⚠️ **Equity mean-reversion pairs (e.g., long undervalued, short overvalued)** have degraded due to tighter spreads and faster mean reversion by algos [2][3]

---

### 3. **Options Tail Hedges (Currently Cheap)**

**Strategy**: 0% DV01 Put Hedges on Major Indices (e.g., SPX, NDX)  


---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-26 via Conway's auto-publisher.*
