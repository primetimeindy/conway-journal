# Trading Nightly Research Brief — 2026-06-28

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-28T02:34:42, run time 152.5s._

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
- **Hidden-ordered Dirac fermions** _(momentum crash risk)_
  [2026-06-25](https://arxiv.org/abs/2606.27368v1)
  I propose a Hermitian extension of the Lorentz-symmetric Dirac theory by complementing the associated Hamiltonian with another \emph{masslike} anticommuting Dirac operator. The resulting theory manifests the iconic linear energy-momentum relationship in any dimension ($d$) and hence the emergent nodal quasiparticle excitations are named \emph{hidden-ordered Dirac fermions}, which are symmetry prot

- **PhysiFormer: Learning to Simulate Mechanics in World Space** _(momentum crash risk)_
  [2026-06-25](https://arxiv.org/abs/2606.27364v1)
  We present PhysiFormer, a diffusion transformer for physically-plausible 3D object motion. Unlike video world models that operate in view-dependent pixel space, PhysiFormer represents objects as 3D meshes expressed in world coordinates. Given the initial vertex positions and velocities, as well as object material type, rigid or elastic, the model samples future vertex trajectories. While related n

- **Bridging Performance and Generalization in Reinforcement Learning for Agile Flight** _(momentum crash risk)_
  [2026-06-25](https://arxiv.org/abs/2606.27348v1)
  Autonomous drone racing is a fundamentally challenging regime for autonomous aerial robots, requiring time-optimal control while operating under persistent actuation saturation. While reinforcement learning (RL) has achieved human-level performance in this domain, current methods fail to generalize; policies trained on specific environments often crash immediately in unseen configurations. This fa

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
- **[yanxinnnnnn/El-Psy-Quant](https://github.com/yanxinnnnnn/El-Psy-Quant)** ⭐ 0 · Python _(updated 2026-06-28)_
  An AI-native quantitative research and trading platform built in public.

- **[11Bhavin/Quant_Trading_Portfolio-](https://github.com/11Bhavin/Quant_Trading_Portfolio-)** ⭐ 0 · None _(updated 2026-06-28)_
  📈 Build and backtest automated trading strategies using Python to enhance your quantitative finance skills and explore the financial markets.

- **[RafaEngineer/strapsim_portfolio_similarity_metric](https://github.com/RafaEngineer/strapsim_portfolio_similarity_metric)** ⭐ 1 · PHP _(updated 2026-06-28)_
  📊 Calculate portfolio similarity metrics to enhance ETF alignment and optimize trading strategies in quantitative finance.

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 0 · Svelte _(updated 2026-06-28)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[ssproduction13-ship-it/crypto-signal-bot](https://github.com/ssproduction13-ship-it/crypto-signal-bot)** ⭐ 0 · TypeScript _(updated 2026-06-28)_
  Telegram bot for crypto trading signals with AI analysis (Gemini), backtesting, paper trading

- **[Qyxloq/blankly-finance](https://github.com/Qyxloq/blankly-finance)** ⭐ 0 · Python _(updated 2026-06-28)_
  Blankly-Finance: A powerful Algo-Trading-Framework for stocks, crypto, and forex. Features Multi-Exchange-API, Backtesting, and Trading-Bot tools.

- **[dhanyaemsky-commits/-Algorithmic-Crypto-Trading-Backtesting-Engine](https://github.com/dhanyaemsky-commits/-Algorithmic-Crypto-Trading-Backtesting-Engine)** ⭐ 0 · None _(updated 2026-06-28)_
  A server for backtesting cryptocurrency trading strategies against historical data. A complete webapp with live price tracking, ML-based price forecasting, and risk-adjusted performance analytics.

- **[astarek1983/street-algo-trader](https://github.com/astarek1983/street-algo-trader)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-28)_
  🚀 Implement algorithmic trading strategies for a Jane Street-style exchange, featuring market-making, arbitrage, and momentum signals.

- **[Anna-007-tech/algorithmic-trading-ai](https://github.com/Anna-007-tech/algorithmic-trading-ai)** ⭐ 2 · None _(updated 2026-06-28)_
  📈 Explore AI-driven trading strategies through data analysis of forex and crypto volatility using PCA, K-means, and neural networks.

- **[nutdnuy/quant-investment-papers](https://github.com/nutdnuy/quant-investment-papers)** ⭐ 37 · None _(updated 2026-06-28)_
  Personal quant & investment research papers library — alpha, factor, algo trading, portfolio management

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 2 · None _(updated 2026-06-28)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[zzzhhn/alpha-agent](https://github.com/zzzhhn/alpha-agent)** ⭐ 0 · Python _(updated 2026-06-27)_
  LLM-Powered Alpha Research Agent — multi-agent system for automated quantitative factor discovery on A-share markets

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-06-28)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[maddoxk/quant-statarb-research](https://github.com/maddoxk/quant-statarb-research)** ⭐ 0 · Python _(updated 2026-06-28)_
  Cointegration-based statistical-arbitrage / pairs-trading research: Engle-Granger & Johansen tests, z-score backtest, LaTeX paper + reproducible code (EWA/EWC)

- **[OmarHayat-DEV/pairs-trading-shopify](https://github.com/OmarHayat-DEV/pairs-trading-shopify)** ⭐ 1 · JavaScript _(updated 2026-06-27)_
  Basic statistical arbitrage analysis for pairs trading of SHOP (TSE) and SHOP (NASDAQ).

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-28)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 49 · Python _(updated 2026-06-25)_
  A stock/futures auto trading framework using Shioaji API

- **[I-am-Uchenna/institutional-options-research](https://github.com/I-am-Uchenna/institutional-options-research)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-18)_
  Academic, risk-first options research framework with stochastic-volatility pricing, defined-risk strategy analysis, and paper-trading controls.

## 4. Perplexity Strategy Synthesis
No single systematic trading strategy is universally “best” for retail traders with $100–$1000 accounts in April 2026, but **pullback trend strategies with Fair Value Gap (FVG) entries** and **simple momentum setups using Hull Moving Averages** offer the most actionable, backtested edges for small accounts—provided they are paired with strict risk management (1–2% per trade) and regime filters to avoid crowded or degraded markets[1][3][6]. Below are concrete, actionable strategies aligned with your four focus areas, including parameters, sources, and degradation flags.

---

### 1. **Crypto Momentum with Regime Filters**  
*(Most Actionable Edge for Small Crypto Accounts)*

**Time Horizon:** 4-hour to daily charts (swing trades: 2–7 days)  
**Entry Rule:**  
- Enter long only when:  
  - Price pulls back to a **Fair Value Gap (FVG)** below a prior swing high[1]  
  - 4-hour Hull Moving Average (10/10 settings) is trending up[6]  
  - BTC dominance < 50% (altcoin regime filter) and 7-day volume > 2× average[1][3]  
**Exit Rule:**  
- Take profit at next swing high or 2× risk (R:R)  
- Exit if 4-hour structure flips bearish or volume drops below 1× average[1][3]  
**Position Sizing:**  
- Initial: 1–2% of account  
- Max per trade: ≤10% (scale in only at support with bullish structure)[5]  
- Stop-loss: Below recent swing low or FVG boundary[1][6]  

**Source:**  
- Pullback Trend Strategy with FVG: YouTube video “Small Account Trading: 2026 Strategies That ACTUALLY Work!”[1]  
- Hull MA trend filter: “The EASIEST Trading Strategy To Use in 2026”[6]  
- Volatility-based entry: “7 Day Trading Strategies That Work in 2026”[3]  

**Degradation Flag:**  
- ❌ **Avoid crypto momentum without regime filters**: Altcoin momentum has degraded since Q4 2025 due to saturation and regulatory pressure. Only trade when BTC dominance is falling and volume is confirmed[1][3].

---

### 2. **Equity Pair Trading (Sector Rotation + Mean Reversion)**  
*(Best for U.S. Equities with Small Accounts)*

**Time Horizon:** Daily (hold 3–10 days)  
**Entry Rule:**  
- Buy **strong sector ETF** (e.g., XLK for tech, XLE for energy) when:  
  - 20-day RSI > 60 and price above 20/200 EMA[2]  
  - Relative strength (vs. SPY) > 1.05 for 5 days  
- Short **weak sector ETF** (e.g., XLU, XHB) when:  
  - RSI < 40 and price below EMA[2]  
- Enter only when spread between strong/weak ETFs breaks 20-day high[2]  
**Exit Rule:**  
- Close when spread reverts to 20-day mean or RSI crosses 50  
- Exit if sector RSI flips opposite or volume drops[2][3]  
**Position Sizing:**  
- 1% per leg (net 2% risk)  
- Max pair exposure: ≤5% of account[2]  
- Stop: Behind 20-day swing low/high or 2× ATR[2]  

**Source:**  
- Top 8 Trading Strategies for 2026: Hantec Markets (pair trading as mean-reversion)[2]  
- Momentum trading with volume confirmation: Amerisave guide[3]  

**Degradation Flag:**  
- ✅ **Still viable**: Sector rotation pairs (e.g., tech vs. utilities) remain un-degraded.  
- ❌ **Avoid**: Mag-stocks vs. value pairs (e.g., NVDA vs. JPM) — crowded since Q1 2026

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-28 via Conway's auto-publisher.*
