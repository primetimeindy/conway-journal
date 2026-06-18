# Trading Nightly Research Brief — 2026-06-18

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-18T02:42:27, run time 22.3s._

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
- **Mean-Payoff-Parity and Lifting Strategies from MDPs to 2-Player Stochastic Games** _(quantitative trading strategy)_
  [2026-06-17](https://arxiv.org/abs/2606.19324v1)
  We consider the strategy complexity (i.e., memory and randomization) of optimal strategies in turn-based 2-player zero-sum stochastic games. Results in [Gimbert,Kelmendi:2023] show how to lift optimal memoryless strategies for shift-invariant inverse-submixing objectives from MDPs to 2-player stochastic games with an exponential increase in the number of memory modes. We show the corresponding low

- **Fitting Accumulated Stock Returns with Tempered Skew t-Distribution** _(quantitative trading strategy)_
  [2026-06-17](https://arxiv.org/abs/2606.19318v1)
  We analyze distributions of historic S&amp;P500 multi-day returns, for the number of days of accumulation from 20 to 120. With the increase of the number of days of accumulation, we observe clear tempering of power-law tails toward a seemingly finite value. To explain this phenomenon, we employ a model that produces a "capped Inverse Gamma" stationary (steady-state) distribution for stochastic vol

- **NeuMesh++: Towards Versatile and Efficient Volumetric Editing with Disentangled Neural Mesh-based Implicit Field** _(quantitative trading strategy)_
  [2026-06-17](https://arxiv.org/abs/2606.19316v1)
  Recently neural implicit rendering techniques have evolved rapidly and demonstrated significant advantages in novel view synthesis and 3D scene reconstruction. However, existing neural rendering methods for editing purposes offer limited functionalities, e.g., rigid transformation and category-specific editing. In this paper, we present a novel mesh-based representation by encoding the neural radi

- **Confidence is Not Reliability: Rethinking MC Dropout in Brain Tumour Segmentation** _(momentum crash risk)_
  [2026-06-17](https://arxiv.org/abs/2606.19300v1)
  Glioma segmentation in multiparametric MRI is a critical component of treatment planning. A segmentation model that fails silently on treatment-critical sub-regions represents a patient safety risk that overlap-based metrics such as Dice scores cannot expose. We ask whether voxel-level uncertainty estimation via Monte Carlo (MC) Dropout can reliably identify segmentation errors in clinically criti

- **Risk Stratification for ICU Delirium using Pervasive Ambient Sensing Information** _(momentum crash risk)_
  [2026-06-17](https://arxiv.org/abs/2606.19292v1)
  Delirium is a common and serious complication in the Intensive Care Unit (ICU), associated with increased morbidity, prolonged hospital stays, and higher healthcare costs. Despite its prevalence, early prediction and prevention remain challenging. Environmental factors such as ambient sound and light may influence the onset of delirium, yet they are often overlooked in risk assessments. In this st

- **Reconstruction Limits for Repeated Differentially Private Aggregates: A Cramer-Rao Perspective on Query Geometry** _(momentum crash risk)_
  [2026-06-17](https://arxiv.org/abs/2606.19275v1)
  Repeated differentially private (DP) releases are often evaluated by transcript length or cumulative privacy accounting. We show that these quantities do not by themselves determine local reconstruction risk. For Gaussian-calibrated repeated statistical queries, the key object is the nuisance-profiled Fisher geometry of the release sequence: repetition helps only when new releases create identifia

- **Topological spectral form factor reveals emergent non-Hermitian single-particle $\mathcal{PT}$ transitions from many-body quantum chaos** _(mean reversion statistical arbitrage)_
  [2026-06-17](https://arxiv.org/abs/2606.19331v1)
  In equilibrium physics, topological defect insertions in quantum and classical partition functions provide non-perturbative probes of phase transitions beyond local observables. In non-equilibrium physics, the spectral form factor provides a minimal probe of universal quantum dynamics, and admits a representation as a product of two partition functions at imaginary inverse temperature. We define t

- **Mean-Payoff-Parity and Lifting Strategies from MDPs to 2-Player Stochastic Games** _(mean reversion statistical arbitrage)_
  [2026-06-17](https://arxiv.org/abs/2606.19324v1)
  We consider the strategy complexity (i.e., memory and randomization) of optimal strategies in turn-based 2-player zero-sum stochastic games. Results in [Gimbert,Kelmendi:2023] show how to lift optimal memoryless strategies for shift-invariant inverse-submixing objectives from MDPs to 2-player stochastic games with an exponential increase in the number of memory modes. We show the corresponding low

- **Fitting Accumulated Stock Returns with Tempered Skew t-Distribution** _(mean reversion statistical arbitrage)_
  [2026-06-17](https://arxiv.org/abs/2606.19318v1)
  We analyze distributions of historic S&amp;P500 multi-day returns, for the number of days of accumulation from 20 to 120. With the increase of the number of days of accumulation, we observe clear tempering of power-law tails toward a seemingly finite value. To explain this phenomenon, we employ a model that produces a "capped Inverse Gamma" stationary (steady-state) distribution for stochastic vol

- **Constraints on Cosmic Strings from the Curl-Mode CMB Lensing Power Spectrum measured by ACT DR6** _(regime detection market)_
  [2026-06-17](https://arxiv.org/abs/2606.19337v1)
  A network of cosmic strings is one of the few well-motivated cosmological sources of vector and tensor metric perturbations on the largest observable scales. Such perturbations imprint a characteristic curl component in the deflection angle of cosmic microwave background (CMB) photons that, unlike the scalar lensing potential, vanishes for adiabatic density fluctuations at linear order. We exploit

- **The Chandra-Gaia Catalog of Counterparts: Resolving ambiguous Gaia matches to X-ray sources in the Chandra Source Catalog using Machine Learning** _(regime detection market)_
  [2026-06-17](https://arxiv.org/abs/2606.19329v1)
  We present a framework to cross-match sources from the Chandra Source Catalog (CSC v2.1) with optical sources from Gaia Data Release 3. Unlike purely spatial approaches, we use source properties such as magnitudes, colors, and distances to identify true counterparts, detect chance coincidences, and resolve ambiguities when multiple plausible candidates exist. We define a training set of high-confi

- **Exclusion Statistics as a Thermodynamic Resource in Quantum Heat Engines** _(regime detection market)_
  [2026-06-17](https://arxiv.org/abs/2606.19310v1)
  The maximum power extractable from a quantum thermoelectric heat engine operating with free fermion carriers is bounded by the universal Whitney limit, $P_{\text{fermion}}^{\max} \simeq 0.0321π^2 k_B^2(T_L-T_R)^2/h$. We demonstrate that this bound is not fundamental to quantum heat engines but is instead an artifact of fermionic statistics. Within the nonlinear Landauer-Büttiker framework, a boson

- **Native Active Perception as Reasoning for Omni-Modal Understanding** _(deep learning volatility forecasting)_
  [2026-06-17](https://arxiv.org/abs/2606.19341v1)
  Passive models for long video understanding typically rely on a "watch-it-all" paradigm, processing frames uniformly regardless of query difficulty, causing computational cost to grow with video duration. Although interactive frameworks have emerged, they often rely on global pre-scanning, and their context cost still scales with video length. We propose OmniAgent, the first native omni-modal agen

- **Learning User Simulators with Turing Rewards** _(deep learning volatility forecasting)_
  [2026-06-17](https://arxiv.org/abs/2606.19336v1)
  Learning to simulate human users in interactive settings could advance the training of agent assistants, evaluation of personalization systems, research in the social sciences, and more. Existing approaches generally do so by training a large language model (LLM) to match a single ground truth response, either by maximizing the log probability or by using a similarity reward. We instead propose {T

- **Freeing the Law with LOCUS: A Local Ordinance Corpus for the United States** _(deep learning volatility forecasting)_
  [2026-06-17](https://arxiv.org/abs/2606.19334v1)
  Progress in legal AI increasingly depends on access to authoritative legal text at scale. Yet one of the most consequential layers of American law remains largely absent from existing machine-readable corpora: local ordinances. Local codes govern zoning, housing, business licensing, public health, noise, animal control, and many other domains of everyday regulation, but they are fragmented across 

- **Native Active Perception as Reasoning for Omni-Modal Understanding** _(transformer financial time series)_
  [2026-06-17](https://arxiv.org/abs/2606.19341v1)
  Passive models for long video understanding typically rely on a "watch-it-all" paradigm, processing frames uniformly regardless of query difficulty, causing computational cost to grow with video duration. Although interactive frameworks have emerged, they often rely on global pre-scanning, and their context cost still scales with video length. We propose OmniAgent, the first native omni-modal agen

- **Quantum solitons and their quantum walks in transmon arrays** _(transformer financial time series)_
  [2026-06-17](https://arxiv.org/abs/2606.19339v1)
  Superconducting qubits are artificial atoms whose spectra and interactions can be engineered through appropriate circuit design, a versatility that can be exploited for quantum simulation. We theoretically investigate a linear array of capacitively coupled transmons, effectively described by a Bose-Hubbard Hamiltonian with attractive interaction. We revisit the discrete-soliton nature of the lowes

- **Constraints on Cosmic Strings from the Curl-Mode CMB Lensing Power Spectrum measured by ACT DR6** _(transformer financial time series)_
  [2026-06-17](https://arxiv.org/abs/2606.19337v1)
  A network of cosmic strings is one of the few well-motivated cosmological sources of vector and tensor metric perturbations on the largest observable scales. Such perturbations imprint a characteristic curl component in the deflection angle of cosmic microwave background (CMB) photons that, unlike the scalar lensing potential, vanishes for adiabatic density fluctuations at linear order. We exploit

- **Native Active Perception as Reasoning for Omni-Modal Understanding** _(reinforcement learning portfolio)_
  [2026-06-17](https://arxiv.org/abs/2606.19341v1)
  Passive models for long video understanding typically rely on a "watch-it-all" paradigm, processing frames uniformly regardless of query difficulty, causing computational cost to grow with video duration. Although interactive frameworks have emerged, they often rely on global pre-scanning, and their context cost still scales with video length. We propose OmniAgent, the first native omni-modal agen

- **Learning User Simulators with Turing Rewards** _(reinforcement learning portfolio)_
  [2026-06-17](https://arxiv.org/abs/2606.19336v1)
  Learning to simulate human users in interactive settings could advance the training of agent assistants, evaluation of personalization systems, research in the social sciences, and more. Existing approaches generally do so by training a large language model (LLM) to match a single ground truth response, either by maximizing the log probability or by using a similarity reward. We instead propose {T

- **Freeing the Law with LOCUS: A Local Ordinance Corpus for the United States** _(reinforcement learning portfolio)_
  [2026-06-17](https://arxiv.org/abs/2606.19334v1)
  Progress in legal AI increasingly depends on access to authoritative legal text at scale. Yet one of the most consequential layers of American law remains largely absent from existing machine-readable corpora: local ordinances. Local codes govern zoning, housing, business licensing, public health, noise, animal control, and many other domains of everyday regulation, but they are fragmented across 

- **Sequential Fair Allocation and Routing in Nonprofit Operations** _(cryptocurrency trading)_
  [2026-06-17](https://arxiv.org/abs/2606.19278v1)
  We study a dynamic fair sequential allocation problem in which a central planner distributes a divisible resource across multiple locations under demand uncertainty. Motivated by applications such as humanitarian relief and food distribution, we incorporate routing decisions into the planner's problem and jointly optimize allocation and visitation order under two max-min fairness objectives, ex-po

- **Trade-offs in Medical LLM Adaptation: An Empirical Study in French QA** _(cryptocurrency trading)_
  [2026-06-17](https://arxiv.org/abs/2606.19266v1)
  The development of large language models (LLMs) has led to an increased focus on their adaptation to specialized domains and languages, yet the effectiveness of domain adaptation strategies remains unclear. We present a study of medical domain adaptation using French medical question-answering (QA) as a case study. We compare continual pretraining (CPT), supervised fine-tuning (SFT), and their com

- **CABLE: Cloud-Assisted Bandwidth-efficient LMM-based Encoding for V2X Systems** _(cryptocurrency trading)_
  [2026-06-17](https://arxiv.org/abs/2606.19258v1)
  Cloud-hosted large multimodal models (LMMs) can provide strong open-vocabulary perception for Vehicle-to-Everything systems, but naively transmitting full-resolution frames from edge to cloud causes severe communication overhead and high cloud-side prefill latency. We present CABLE, a cloud-assisted bandwidth-efficient LMM-based encoding framework for edge-cloud perception. CABLE propagates the pr

- **Floquet framework for driven polar quantum systems** _(options volatility surface)_
  [2026-06-17](https://arxiv.org/abs/2606.19330v1)
  We present an analytical and numerical Floquet treatment of a driven polar two-level quantum system characterized by both longitudinal and transverse coupling to a periodic field. Analytically, we derive a dressed-frame effective Hamiltonian up to first order in the inverse driving frequency, incorporating the longitudinal coupling nonperturbatively. This yields closed expressions for the effectiv

- **Data Intelligence Agents: Interpreting, Modeling, and Querying Enterprise Data via Autonomous Coding Agents** _(options volatility surface)_
  [2026-06-17](https://arxiv.org/abs/2606.19319v1)
  Production data integration is bottlenecked by repeated, lossy handoffs between data owners, engineers, and analysts who must collaboratively discover, structure, and query enterprise data. We present Data Intelligence Agents (DIA), a system of three agents (Data Interpreter, Schema Creator, and Query Generator) that compresses this workflow by treating autonomous coding agents (ACAs) as a first-c

- **Fitting Accumulated Stock Returns with Tempered Skew t-Distribution** _(options volatility surface)_
  [2026-06-17](https://arxiv.org/abs/2606.19318v1)
  We analyze distributions of historic S&amp;P500 multi-day returns, for the number of days of accumulation from 20 to 120. With the increase of the number of days of accumulation, we observe clear tempering of power-law tails toward a seemingly finite value. To explain this phenomenon, we employ a model that produces a "capped Inverse Gamma" stationary (steady-state) distribution for stochastic vol

- **Topological spectral form factor reveals emergent non-Hermitian single-particle $\mathcal{PT}$ transitions from many-body quantum chaos** _(factor investing alpha)_
  [2026-06-17](https://arxiv.org/abs/2606.19331v1)
  In equilibrium physics, topological defect insertions in quantum and classical partition functions provide non-perturbative probes of phase transitions beyond local observables. In non-equilibrium physics, the spectral form factor provides a minimal probe of universal quantum dynamics, and admits a representation as a product of two partition functions at imaginary inverse temperature. We define t

- **Cohomogeneity one actions on symmetric spaces of mixed type** _(factor investing alpha)_
  [2026-06-17](https://arxiv.org/abs/2606.19323v1)
  In this article, we study isometric cohomogeneity-one actions on symmetric spaces of mixed type, i.e., those whose universal cover splits as a nontrivial product of symmetric spaces of compact, noncompact, and Euclidean types. We provide a new family of "diagonal" cohomogeneity-one actions on symmetric spaces of the form $\mathbb{R}^n \times M_-$, where $M_-$ is of noncompact type. We show that, w

- **Spectral Functions of Lorentzian Quantum Gravity** _(factor investing alpha)_
  [2026-06-17](https://arxiv.org/abs/2606.19321v1)
  We compute spectral functions of graviton modes in Lorentzian quantum gravity, interpolating between classical general relativity and an asymptotically safe ultraviolet fixed point. Using functional renormalisation adapted for theories in Lorentzian signature, and enhanced by new symmetry conditions to account for underlying Ward identities, we derive and solve flow equations directly for the Käll

## 3. GitHub Repos (Recently Updated)
- **[bsAmirHeydar/decision-alpha-lab](https://github.com/bsAmirHeydar/decision-alpha-lab)** ⭐ 1 · MQL5 _(updated 2026-06-18)_
  A quantitative research platform for studying structural decision nodes, regime transitions, and convex alpha extraction.

- **[Vixoqz/vnpy-Machine-Learning](https://github.com/Vixoqz/vnpy-Machine-Learning)** ⭐ 0 · C# _(updated 2026-06-18)_
  vnpy-Machine-Learning: integrates machine-learning models with the vn.py quantitative-trading framework for AI-driven, data-driven algorithmic trading and backtesting in Python.

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-18)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[richkuo/go-trader](https://github.com/richkuo/go-trader)** ⭐ 319 · Go _(updated 2026-06-18)_
  Crypto trading bot — backtesting, paper trading, live trading with risk management

- **[Qyxloq/blankly-finance](https://github.com/Qyxloq/blankly-finance)** ⭐ 0 · Python _(updated 2026-06-18)_
  Blankly-Finance: A powerful Algo-Trading-Framework for stocks, crypto, and forex. Features Multi-Exchange-API, Backtesting, and Trading-Bot tools.

- **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance)** ⭐ 11 · Python _(updated 2026-06-18)_
  Easily build, backtest and deploy your algo in just a few lines of code. Trade stocks, cryptos, and forex across exchanges one package.

- **[Th3-H4xx0r/IntelliStock](https://github.com/Th3-H4xx0r/IntelliStock)** ⭐ 9 · Python _(updated 2026-06-18)_
  IntelliStock is a self-hosted algorithmic trading platform you run on your own infrastructure. It builds strategies, runs backtests, monitors live positions, and answers questions about your portfolio

- **[Amesotexz/Krux-Binance-Trading-Futures-Crypto-Coins-Volatility](https://github.com/Amesotexz/Krux-Binance-Trading-Futures-Crypto-Coins-Volatility)** ⭐ 0 · C# _(updated 2026-06-18)_
  This repository provides Krux, a trading bot for Binance focused on futures trading of cryptocurrencies. It is designed to handle market volatility effectively, leveraging advanced algorithms to optim

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-18)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[zzzhhn/alpha-agent](https://github.com/zzzhhn/alpha-agent)** ⭐ 0 · Python _(updated 2026-06-18)_
  LLM-Powered Alpha Research Agent — multi-agent system for automated quantitative factor discovery on A-share markets

- **[aryadoshii/QuantEdge-Market-Neutral-Long-Short-Equity-Research-Platform](https://github.com/aryadoshii/QuantEdge-Market-Neutral-Long-Short-Equity-Research-Platform)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-17)_
  ML pipeline for equity return prediction (Random Forest ranking, 32 engineered features) with rigorous evaluation — factor attribution, leakage detection, and a negative-control test revealing the sig

- **[cauchy481/AlphaForge](https://github.com/cauchy481/AlphaForge)** ⭐ 0 · Python _(updated 2026-06-17)_
  Personal A-share factor research & backtesting framework: IC analysis, neutralization, multi-factor combination, event-driven backtest

- **[Jalagamdolu/Jalagamdolu-Statistical-Arbitrage-Pairs-Trading-Engine](https://github.com/Jalagamdolu/Jalagamdolu-Statistical-Arbitrage-Pairs-Trading-Engine)** ⭐ 0 · None _(updated 2026-06-18)_
  

- **[Gabengcui8/pairs_trading](https://github.com/Gabengcui8/pairs_trading)** ⭐ 0 · HTML _(updated 2026-06-17)_
  A configurable statistical-arbitrage pairs-trading backtester for S&P 500 stocks.

- **[kshitijbhandari/Statistical-Arbitrage-Cointegration-Based-Pairs-Trading-and-Dynamic-Hedge-Ratios](https://github.com/kshitijbhandari/Statistical-Arbitrage-Cointegration-Based-Pairs-Trading-and-Dynamic-Hedge-Ratios)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-17)_
  Statistical arbitrage engine that screens S&P 500 pairs using Engle-Granger and Johansen cointegration tests, fits Ornstein-Uhlenbeck dynamics via MLE, and trades spreads with a Kalman filter hedge ra

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-18)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[milgar7969/alpaca-options-framework](https://github.com/milgar7969/alpaca-options-framework)** ⭐ 1 · Python _(updated 2026-06-17)_
  A Python framework for building live options trading bots on Alpaca Markets — asyncio, WebSocket streaming, position management, and all the API workarounds documented.

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 48 · Python _(updated 2026-06-17)_
  A stock/futures auto trading framework using Shioaji API

## 4. Perplexity Strategy Synthesis
For a **$100–$1000** account, the most actionable strategies right now are the ones with **low holding costs, simple rules, and tiny minimum position sizes**: crypto **trend-following with regime filters**, equities **pairs trading only in very liquid names or via spreads**, and a few **defined-risk options hedges** if you can trade spreads cheaply. The “new edge” bucket is real but less reliable; I’d treat it as an *idea pipeline*, not a live allocation, unless you can backtest it yourself.  

## 1) Crypto momentum with regime filters

The best retail-friendly version is a **daily/4-hour trend-following system** that only trades when the broader crypto regime is bullish and volatility is not collapsing. The source material you provided is mostly generic trading advice, but it does support the core mechanics: trade with momentum, use moving averages/highs-lows, use liquid instruments, and risk small with clear stops.[1][2][3]

**Concrete rules**
- **Universe:** BTC, ETH, and 1–3 large-cap alts with persistent volume.
- **Time horizon:** **2 to 20 days**.
- **Regime filter:** Only long when:
  - BTC is above its **200-day moving average**, and
  - BTC’s **50-day MA > 200-day MA**, and
  - BTC/ETH are not below their **20-day average range** by more than ~1 standard deviation.
- **Entry:** Buy the first **4-hour close above the prior 10-bar high** after a pullback that holds the **20 EMA**.
- **Confirmation:** 4-hour close above breakout level with **volume above 20-bar average**.
- **Exit:** Sell on a **4-hour close below the 20 EMA**, or when price closes below the last higher low.
- **Stop:** Below the swing low or **1.5–2.0 ATR**.
- **Position sizing:** Risk **0.5%–1.0% of account** per trade; for a $500 account, that is **$2.50–$5** risk, so position size must be tiny.
- **Scaling:** Take partial profit at **+1R**, trail the rest with a 10–14 bar low or 20 EMA.

**Why this is still actionable**
- It fits small accounts because you can trade fractional crypto units.
- It avoids overtrading by requiring a regime filter.
- It uses the same kind of momentum-and-structure logic emphasized in the trading guides you provided.[1][4][5]

**What has degraded**
- **Low-cap alt momentum** has likely degraded versus early 2025 because these names tend to crowd quickly; the retail-friendly edge is now mostly in **BTC/ETH and only the strongest rotations**. That is an inference from current market structure, not from the provided sources.

## 2) Equity pair trading

For small accounts, the only practical pairs trades are **very tight, liquid spreads** or **synthetic pair trades via options**. With $100–$1000, the biggest problem is commissions, borrow costs, and minimum capital; so the best retail version is usually **long/short via ETFs or very liquid mega-caps**, not obscure small caps. Your sources don’t include an academic pairs paper, so this part is based on general quantitative practice rather than cited results.

**Concrete rules**
- **Universe:** Same-sector mega-cap pairs, e.g. highly correlated names within semis, banks, or megacap software.
- **Time horizon:** **3 to 30 trading days**.
- **Entry setup:**  
  - Compute the **z-score** of the spread over a **60-day lookback**.  
  - Enter when z-score reaches **±2.0** and the names are still fundamentally comparable.
- **Exit:**  
  - Exit at **z-score 0** to **0.5**, or sooner if correlation breaks.
- **Stop:**  
  - Exit if spread reaches **±3.0 z-score** against you, or if relative strength diverges for 3–5 sessions.
- **Sizing:**  
  - Risk **0.25%–0.5%** of account on the spread, because pair trades can drift longer than expected.
- **

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-18 via Conway's auto-publisher.*
