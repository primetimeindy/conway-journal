# Trading Nightly Research Brief — 2026-08-03

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-08-03T02:33:00, run time 25.3s._

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
- **Differentially Private Nonparametric Modal Learning with Applications to Regression and Clustering** _(quantitative trading strategy)_
  [2026-07-31](https://arxiv.org/abs/2607.29675v1)
  Density modes provide a localized and interpretable summary of multimodal distributions, but their estimation under rigorous differential privacy constraints remains largely unexplored. We study differentially private recovery of density modes for multivariate distributions under local smoothness, curvature, and separation conditions. We propose DP-GRAMS, a mean-shift inspired method that performs

- **ArcLP: A Matlab implementation of an $\mathcal{O}(\sqrt{n}L)$ arc-search infeasible interior-point algorithm for linear programming** _(quantitative trading strategy)_
  [2026-07-31](https://arxiv.org/abs/2607.29673v1)
  This paper presents a Matlab implementation of an arc-search infeasible interior point algorithm for linear programming (LP), which has a proven polynomial bound of $\mathcal{O}(\sqrt{n}L)$, the best among all interior-point algorithms for LP. Software architecture and major functions are discussed. Its ease of use is described by a simple example. Crucial strategies are summarized. Quality of the

- **The Kikuchi Hierarchy is Sharp for $k$XOR** _(quantitative trading strategy)_
  [2026-07-31](https://arxiv.org/abs/2607.29672v1)
  Planted noisy $k$XOR and the strong refutation of random $k$XOR are governed by a conjectured trade-off between signal strength and time: Level $\ell$ of the Kikuchi hierarchy should achieve the smooth curve \begin{equation*}   m\ \gtrsim\ ρ^{-2}n^{k/2}/\ell^{k/2-1}\ \text{clauses}   \quad\Longleftrightarrow\quad   \text{solvable in time }n^{O(\ell)}, \end{equation*} where $ρ$ is the bias of the p

- **Sign compression for Muon: SignMuon, MuonSign, and the Limits of Error Feedback** _(momentum crash risk)_
  [2026-07-31](https://arxiv.org/abs/2607.29674v1)
  SignMuon compresses the Muon update to one bit per parameter by taking its elementwise sign, providing the most direct way to run a matrix-aware optimizer under an extremely low communication budget. It outperforms SignSGD in practice, yet it can ascend even on a linear function. Signing the gradient before the Linear Minimization Oracle (LMO), rather than after, does not repair this: we construct

- **Elastic Curves via Geometric Mechanics** _(momentum crash risk)_
  [2026-07-31](https://arxiv.org/abs/2607.29654v1)
  Elastic curves are the mathematical shapes of thin elastic rods in equilibrium, with deep connections to mechanics, geometry, and computer graphics. Traditionally described as stationary points of bending energy under length and torsion constraints, their rich theory admits many equivalent characterizations. We develop a new one from the viewpoint of geometric mechanics. Our main contribution reli

- **The IACOB project XIX. Revisiting massive-star evolution with empirical TAMS constraints: updated models, overshoot calibration, and the population of blue supergiants** _(momentum crash risk)_
  [2026-07-31](https://arxiv.org/abs/2607.29650v1)
  Massive stars play a fundamental role in the evolution of the Universe. Yet, several physical processes governing their evolution remain poorly constrained. Notably, the main-sequence width is sensitive to the convective boundary mixing efficiency; it becomes necessary to account for binary interactions to explain some observed properties of massive-star populations. We constrain single-star model

- **Emulating the nonlinear effects of modified gravity on the matter power spectrum for reconstruction** _(mean reversion statistical arbitrage)_
  [2026-07-31](https://arxiv.org/abs/2607.29683v1)
  Including nonlinear information from modified gravity (MG) brings more constraining power to the model-independent reconstruction of MG functions. However, the calculation of the nonlinear matter power spectrum with MGCAMB+ReACT is expensive in repeated likelihood evaluations, which limits the exploration of the high-dimensional parameter space. In this work, we construct a neural-network emulator

- **Differentially Private Nonparametric Modal Learning with Applications to Regression and Clustering** _(mean reversion statistical arbitrage)_
  [2026-07-31](https://arxiv.org/abs/2607.29675v1)
  Density modes provide a localized and interpretable summary of multimodal distributions, but their estimation under rigorous differential privacy constraints remains largely unexplored. We study differentially private recovery of density modes for multivariate distributions under local smoothness, curvature, and separation conditions. We propose DP-GRAMS, a mean-shift inspired method that performs

- **Sign compression for Muon: SignMuon, MuonSign, and the Limits of Error Feedback** _(mean reversion statistical arbitrage)_
  [2026-07-31](https://arxiv.org/abs/2607.29674v1)
  SignMuon compresses the Muon update to one bit per parameter by taking its elementwise sign, providing the most direct way to run a matrix-aware optimizer under an extremely low communication budget. It outperforms SignSGD in practice, yet it can ascend even on a linear function. Signing the gradient before the Linear Minimization Oracle (LMO), rather than after, does not repair this: we construct

- **Dark Photons from Perturbative Decay of a Misaligned Higgs Field** _(regime detection market)_
  [2026-07-31](https://arxiv.org/abs/2607.29682v1)
  We reconsider the production of dark photons $A'$ as dark matter, from the perturbative decay of a dark Higgs field $h$, that is stochastically misaligned from the minimum of its potential during inflation. This is a simple and predictive framework for generating the $A'$ relic abundance. It is constrained by structure formation, since the $A'$ are initially boosted, and inflationary isocurvature 

- **Magnetic properties of a quasi-two-dimensional spin-1/2 antiferromagnet Y2CuGe4O12** _(regime detection market)_
  [2026-07-31](https://arxiv.org/abs/2607.29676v1)
  Competing magnetic interactions and frustration-induced quantum fluctuations in spatially anisotropic low-dimensional magnets often give rise to exotic magnetic phenomena, including field-induced phases. Here, we present crystal structure, magnetic susceptibility, specific heat, and electron spin resonance (ESR) measurements on polycrystalline Y$2$CuGe$4$O${12}$, supported by density functional th

- **The Kikuchi Hierarchy is Sharp for $k$XOR** _(regime detection market)_
  [2026-07-31](https://arxiv.org/abs/2607.29672v1)
  Planted noisy $k$XOR and the strong refutation of random $k$XOR are governed by a conjectured trade-off between signal strength and time: Level $\ell$ of the Kikuchi hierarchy should achieve the smooth curve \begin{equation*}   m\ \gtrsim\ ρ^{-2}n^{k/2}/\ell^{k/2-1}\ \text{clauses}   \quad\Longleftrightarrow\quad   \text{solvable in time }n^{O(\ell)}, \end{equation*} where $ρ$ is the bias of the p

- **Emulating the nonlinear effects of modified gravity on the matter power spectrum for reconstruction** _(deep learning volatility forecasting)_
  [2026-07-31](https://arxiv.org/abs/2607.29683v1)
  Including nonlinear information from modified gravity (MG) brings more constraining power to the model-independent reconstruction of MG functions. However, the calculation of the nonlinear matter power spectrum with MGCAMB+ReACT is expensive in repeated likelihood evaluations, which limits the exploration of the high-dimensional parameter space. In this work, we construct a neural-network emulator

- **Differentially Private Nonparametric Modal Learning with Applications to Regression and Clustering** _(deep learning volatility forecasting)_
  [2026-07-31](https://arxiv.org/abs/2607.29675v1)
  Density modes provide a localized and interpretable summary of multimodal distributions, but their estimation under rigorous differential privacy constraints remains largely unexplored. We study differentially private recovery of density modes for multivariate distributions under local smoothness, curvature, and separation conditions. We propose DP-GRAMS, a mean-shift inspired method that performs

- **Sign compression for Muon: SignMuon, MuonSign, and the Limits of Error Feedback** _(deep learning volatility forecasting)_
  [2026-07-31](https://arxiv.org/abs/2607.29674v1)
  SignMuon compresses the Muon update to one bit per parameter by taking its elementwise sign, providing the most direct way to run a matrix-aware optimizer under an extremely low communication budget. It outperforms SignSGD in practice, yet it can ascend even on a linear function. Signing the gradient before the Linear Minimization Oracle (LMO), rather than after, does not repair this: we construct

- **Warped product spaces: Gromov hyperbolicity and identification of the visual boundary** _(transformer financial time series)_
  [2026-07-31](https://arxiv.org/abs/2607.29685v1)
  In this paper, we consider warped product spaces $X\times_{\varphi}Y$, where $X$ is a complete geodesic Gromov hyperbolic space, $Y$ is a compact geodesic metric space, and the warping function $\varphi$ satisfies suitable exponential growth conditions. We prove that the warped product is Gromov hyperbolic and derive an explicit estimate for its hyperbolicity constant. We further establish a homeo

- **TokTier: Exact Stateful Tokenization for Agentic LLM Serving** _(transformer financial time series)_
  [2026-07-31](https://arxiv.org/abs/2607.29678v1)
  LLM serving systems cache prompt KV state, yet most front ends still re-tokenize the full request text on every call. The cost lands on coding agents, which resubmit a long transcript after each small tool result, and reuse is hard because even a short append can change token boundaries near the end of the previous sequence. Across 153,951 calls from two agent ecosystems, the median call appends a

- **The Kikuchi Hierarchy is Sharp for $k$XOR** _(transformer financial time series)_
  [2026-07-31](https://arxiv.org/abs/2607.29672v1)
  Planted noisy $k$XOR and the strong refutation of random $k$XOR are governed by a conjectured trade-off between signal strength and time: Level $\ell$ of the Kikuchi hierarchy should achieve the smooth curve \begin{equation*}   m\ \gtrsim\ ρ^{-2}n^{k/2}/\ell^{k/2-1}\ \text{clauses}   \quad\Longleftrightarrow\quad   \text{solvable in time }n^{O(\ell)}, \end{equation*} where $ρ$ is the bias of the p

- **Differentially Private Nonparametric Modal Learning with Applications to Regression and Clustering** _(reinforcement learning portfolio)_
  [2026-07-31](https://arxiv.org/abs/2607.29675v1)
  Density modes provide a localized and interpretable summary of multimodal distributions, but their estimation under rigorous differential privacy constraints remains largely unexplored. We study differentially private recovery of density modes for multivariate distributions under local smoothness, curvature, and separation conditions. We propose DP-GRAMS, a mean-shift inspired method that performs

- **Sign compression for Muon: SignMuon, MuonSign, and the Limits of Error Feedback** _(reinforcement learning portfolio)_
  [2026-07-31](https://arxiv.org/abs/2607.29674v1)
  SignMuon compresses the Muon update to one bit per parameter by taking its elementwise sign, providing the most direct way to run a matrix-aware optimizer under an extremely low communication budget. It outperforms SignSGD in practice, yet it can ascend even on a linear function. Signing the gradient before the Linear Minimization Oracle (LMO), rather than after, does not repair this: we construct

- **Freeze, Then Select: Structured Field Adapters and Stability-Validated Weak Selection for PDE Discovery from Sparse Observations** _(reinforcement learning portfolio)_
  [2026-07-31](https://arxiv.org/abs/2607.29665v1)
  PDE discovery from sparse observations requires reconstructing a continuous field and selecting the correct differential terms. Our analysis of optimization paths in coupled neural PDE discovery reveals three behaviors: the exact support can persist to the end of training, appear only transiently, or fail to emerge. To decouple equation selection from neural optimization, we develop a freeze-then-

- **Differentially Private Nonparametric Modal Learning with Applications to Regression and Clustering** _(cryptocurrency trading)_
  [2026-07-31](https://arxiv.org/abs/2607.29675v1)
  Density modes provide a localized and interpretable summary of multimodal distributions, but their estimation under rigorous differential privacy constraints remains largely unexplored. We study differentially private recovery of density modes for multivariate distributions under local smoothness, curvature, and separation conditions. We propose DP-GRAMS, a mean-shift inspired method that performs

- **The Kikuchi Hierarchy is Sharp for $k$XOR** _(cryptocurrency trading)_
  [2026-07-31](https://arxiv.org/abs/2607.29672v1)
  Planted noisy $k$XOR and the strong refutation of random $k$XOR are governed by a conjectured trade-off between signal strength and time: Level $\ell$ of the Kikuchi hierarchy should achieve the smooth curve \begin{equation*}   m\ \gtrsim\ ρ^{-2}n^{k/2}/\ell^{k/2-1}\ \text{clauses}   \quad\Longleftrightarrow\quad   \text{solvable in time }n^{O(\ell)}, \end{equation*} where $ρ$ is the bias of the p

- **Data Visualization Style Guides in Practice: Why They Emerge, How They Work, and When They Bend** _(cryptocurrency trading)_
  [2026-07-31](https://arxiv.org/abs/2607.29645v1)
  Visualization style guides play a crucial role in shaping how data is interpreted and trusted, yet they often receive little scrutiny in their creation and use. Understanding their impact requires looking beyond the specific rules that style guides prescribe and examining how they function within organizations to coordinate visual work, manage trade-offs, and support judgment under real constraint

- **A-type Sigma Models from Differential Poisson Geometry** _(options volatility surface)_
  [2026-07-31](https://arxiv.org/abs/2607.29668v1)
  We study the differential Poisson sigma model (DPSM) in the symplectic case and show that its classical reduction defines a distinguished class of A-type models on symplectic targets, not necessarily Kähler. The DPSM is a covariant first-order sigma model whose graded target is the parity-shifted tangent bundle $T[1]M$ of a Poisson manifold $M$. Its graded Poisson tensor encodes a differential Poi

- **Study of the Anomalous Hall effect by tuning the spin orientation in the Altermagnetic material CrSb** _(options volatility surface)_
  [2026-07-31](https://arxiv.org/abs/2607.29646v1)
  Recent development in the field of altermagnetism, and increased demand for the search of applications of anomalous hall effect have ushered in a new era for novel quantum phases in materials. Quantum materials previously anticipated to be scientifically predictable have unfolded novel properties that brought them into the spotlight. These manifestations have led us to rethink our understanding of

- **Distribution and Transport of Fragmenting Microplastics in a 3D Global Eulerian Model** _(options volatility surface)_
  [2026-07-31](https://arxiv.org/abs/2607.29643v1)
  Fragmentation, the breakage of matter into smaller pieces, is an important mechanism responsible for generating microplastics (MPs). We present the first global three-dimensional Eulerian model that resolves fragmentation alongside MP transport. The evolution of particle size is modeled as a transfer from larger- to smaller-size bins, governed by a fragmentation kinetics framework. Relative to a r

- **Diagnosing Compositional Generalization in Sequential Robot Tasks** _(factor investing alpha)_
  [2026-07-31](https://arxiv.org/abs/2607.29687v1)
  Sequential robot manipulation requires policies to execute novel combinations of familiar instruction components. However, collecting demonstrations for all possible instruction tuples is combinatorially expensive, while sparsely covered datasets often fail under out-of-distribution recombination. This paper studies compositional generalization through the lens of instruction-space coverage. We de

- **Online Shadow Tomography Matching the Classical Bounds** _(factor investing alpha)_
  [2026-07-31](https://arxiv.org/abs/2607.29686v1)
  In \emph{Online Shadow Tomography}, we are given copies of an unknown $d$-dimensional quantum state $ρ$, an adversary (adaptively) proposes a sequence of bounded observables $A^{(1)},\ldots,A^{(m)}$, and after each $A^{(t)}$ is given we must estimate $\Tr(A^{(t)}ρ)$ to within $\pm ε$.   This is the direct quantum generalization of the classical problem of \emph{Adaptive Data Analysis}. %The ``offl

- **Differentially Private Nonparametric Modal Learning with Applications to Regression and Clustering** _(factor investing alpha)_
  [2026-07-31](https://arxiv.org/abs/2607.29675v1)
  Density modes provide a localized and interpretable summary of multimodal distributions, but their estimation under rigorous differential privacy constraints remains largely unexplored. We study differentially private recovery of density modes for multivariate distributions under local smoothness, curvature, and separation conditions. We propose DP-GRAMS, a mean-shift inspired method that performs

## 3. GitHub Repos (Recently Updated)
- **[OpenByteInc/QuantDinger](https://github.com/OpenByteInc/QuantDinger)** ⭐ 10207 · Python _(updated 2026-08-03)_
  AI quantitative trading platform for crypto, stocks, and forex with backtesting, live trading, market data, and multi-agent research.vibe-trading ,trading-agents,ai-trader,ai-trading

- **[Guannings/alpha_dual_engine](https://github.com/Guannings/alpha_dual_engine)** ⭐ 2 · Python _(updated 2026-08-03)_
  Regime-aware quantitative trading system: XGBoost regime classifier + hierarchical PPO allocator + cubed momentum optimisation + 1M-path Monte Carlo stress test. Dockerised Streamlit dashboard.

- **[Vixoq/vnpy](https://github.com/Vixoq/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-08-03)_
  Open source quantitative trading platform development framework based

- **[ojeology/mean-reversion-vwap-lab](https://github.com/ojeology/mean-reversion-vwap-lab)** ⭐ 0 · Python _(updated 2026-08-03)_
  A VWAP ±2σ mean-reversion crypto strategy, developed across 14 documented experiments (E1–E14) with full walk-forward validation. Includes the complete research journal, strategy version history, back

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 0 · Python _(updated 2026-08-03)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[Gainium/main-app-sh](https://github.com/Gainium/main-app-sh)** ⭐ 2 · TypeScript _(updated 2026-08-03)_
  TypeScript-based crypto trading platform backend with automated DCA, Grid, Combo, and Hedge bot strategies, real-time WebSocket streaming, backtesting capabilities, and GraphQL API for portfolio manag

- **[BrockStar3540/mr-scrooge-v6](https://github.com/BrockStar3540/mr-scrooge-v6)** ⭐ 4 · Python _(updated 2026-08-03)_
  Open-source algorithmic forex trading bot for OANDA (Python) — cell-based execution, wide-stop ratchet exits, a full backtesting research program, and a live control-panel dashboard. Strategy-neutral 

- **[Calaestivox/Juno-Binance-Trade-Automated-Cryptocurrency-Margin-Algorithmic](https://github.com/Calaestivox/Juno-Binance-Trade-Automated-Cryptocurrency-Margin-Algorithmic)** ⭐ 0 · Python _(updated 2026-08-03)_
  This repository features Juno, an automated trade bot for Binance, designed for margin trading of cryptocurrencies. It utilizes advanced algorithmic strategies to optimize trading decisions and enhanc

- **[ojeology/QUANTLAB](https://github.com/ojeology/QUANTLAB)** ⭐ 0 · Python _(updated 2026-08-03)_
  QuantLab — Systematic research framework for discovering and stress-testing algorithmic crypto trading strategies. 70+ research iterations using walk-forward optimization, bootstrap confidence interva

- **[liuh886/alpha_engine](https://github.com/liuh886/alpha_engine)** ⭐ 0 · Python _(updated 2026-08-03)_
  Alpha Engine: AI-driven quantitative trading research platform with factor lifecycle, model registry, backtesting, and dashboard.

- **[zzzhhn/alpha-agent](https://github.com/zzzhhn/alpha-agent)** ⭐ 0 · Python _(updated 2026-08-03)_
  LLM-Powered Alpha Research Agent — multi-agent system for automated quantitative factor discovery on A-share markets

- **[aircrushin/wq-alpha-agent](https://github.com/aircrushin/wq-alpha-agent)** ⭐ 11 · Python _(updated 2026-08-03)_
  Automated WorldQuant BRAIN alpha factor research agent — generate, simulate, diversity-check, submit, and evolve alpha expressions with LLM-driven automation.

- **[kakhramonovsh-prog/stat-arb-pairs-trading](https://github.com/kakhramonovsh-prog/stat-arb-pairs-trading)** ⭐ 0 · Python _(updated 2026-08-03)_
  Anatomy of a backtest: look-ahead bias in statistical arbitrage quantified at +9.7pp/yr (95% CI). Three specifications on 184 US large caps 2010-2026 with pre-registered extensions and a once-only hol

- **[pgrajzl/stat-arb-07-29-2026](https://github.com/pgrajzl/stat-arb-07-29-2026)** ⭐ 1 · Jupyter Notebook _(updated 2026-08-02)_
  Developing a statistical arbitrage pairs trading strategy 

- **[ataghipourfard/pairs-trading-backtester](https://github.com/ataghipourfard/pairs-trading-backtester)** ⭐ 0 · Python _(updated 2026-08-01)_
  Statistical arbitrage backtester using Engle-Granger cointegration screening and z-score mean reversion, strict train/test split across 120 candidate pairs

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 0 · Jupyter Notebook _(updated 2026-08-03)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[Fintenh/quantitative-trading-framework](https://github.com/Fintenh/quantitative-trading-framework)** ⭐ 0 · Python _(updated 2026-08-02)_
  From volatility forecasting to live portfolio optimisation: GARCH modelling, Efficient Frontier construction, Monte Carlo option pricing, Kelly Criterion position sizing, walk-forward backtesting, Fam

- **[parthjoshi1998/nifty-backtester](https://github.com/parthjoshi1998/nifty-backtester)** ⭐ 0 · Python _(updated 2026-08-02)_
  A modular Python framework for researching, backtesting, optimizing, and evaluating NIFTY intraday options trading strategies using configurable technical indicators, filters, risk management, and per

## 4. Perplexity Strategy Synthesis
For **$100–$1,000 accounts**, the most actionable systematic edges are usually the ones with **low turnover, tight risk, and minimal fees/slippage**: **crypto momentum with regime filters**, **pairs/mean reversion in liquid equities**, and **defined-risk options structures**. I could not verify truly “newly discovered” live edges from recent papers or trading Twitter from the provided results alone, so I’m flagging that part as *insufficiently sourced* rather than guessing. [10][19]

## 1) Crypto momentum with regime filters

The most robust retail-friendly version is a **trend-following breakout** that only trades when the market is in a favorable volatility/trend regime, using **BTC and ETH as the main universe** to keep execution simple and liquid. The provided sources emphasize momentum, RVOL, VWAP/EMA structure, and waiting for confirmation rather than chasing; they also stress clear risk limits and small position sizing. [17][18][2][3]

**Concrete rules**
- **Universe:** BTC, ETH, and only the most liquid large-cap alts if spreads are tight. This is an inference from liquidity and execution constraints for small accounts rather than a direct quote from the sources.  
- **Time horizon:** **2 hours to 10 days**; use **4H and 1D** for regime, **1H/15m** for entries.  
- **Regime filter:** Trade only when:
  - **20-day realized volatility is rising**, and
  - price is **above the 50-day moving average**, and
  - BTC is above its **20-day and 50-day MA** if trading alts.  
  This is a standard systematic momentum filter; the provided sources support momentum/trend filtering generally, but not this exact parameter set. [17][18][19]
- **Entry:** Buy a breakout above the **20-day high** or the **first pullback to the 9/21 EMA** after a breakout, only if volume expands and price holds above VWAP intraday. The “pullback trend” and EMA/VWAP framing is consistent with the cited strategy materials. [17][1]
- **Exit:**  
  - Initial stop below the **recent swing low** or **1.5× ATR(14)**.  
  - Take partial profits at **2R**, trail the rest with a **2×ATR** or below the **10-day low**.  
- **Position sizing:** Risk **0.5%–1% of account equity per trade**; for $100–$1,000, that means **$0.50–$10** max loss per trade. The sources repeatedly emphasize 1% max risk and avoiding overtrading. [3][17][2]
- **Practical sizing note:** With sub-$1,000 accounts, use **spot** or **very small perps** only if fees/funding are negligible. This is an inference based on small-account economics.

**Why this is actionable now**
- It is easy to automate.
- It works on liquid instruments.
- It avoids the “micro-cap noise” problem that kills small accounts.

**What likely degraded in the last 6 months**
- **Late-entry altcoin momentum** has likely degraded because crowded social-media breakouts tend to compress quickly when they become widely followed. I cannot prove that from the provided sources, so treat this as a market-structure caution, not a sourced fact.

## 2) Equity pair trading

For small accounts, the best version is **long/short pair mean reversion** in **large-cap, highly liquid stocks or ETFs** with persistent co-movement, because the strategy needs low borrow friction, stable spreads, and low turnover. The provided sources mention **pairs trading / price reversion to the mean** as a retail strategy class, but they do not specify the exact pairs or thresholds. [18][19]

**Concrete rules**
- **Universe:**  
  - Same-sector liquid names, or  
  - ETF/stock pairs, or  
  - Two highly correlated mega-caps in the same industry.  
- **Time horizon:** **2–20 trading days**.  
- **Signal:**  
  - Compute **z-score** of the price ratio or spread over a **60-day lookback**.  


---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-08-03 via Conway's auto-publisher.*
