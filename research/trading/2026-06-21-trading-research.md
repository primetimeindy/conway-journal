# Trading Nightly Research Brief — 2026-06-21

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-21T02:31:07, run time 22.5s._

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
- **MemoryWAM: Efficient World Action Modeling with Persistent Memory** _(quantitative trading strategy)_
  [2026-06-18](https://arxiv.org/abs/2606.20562v1)
  Robust robotic manipulation in the real world requires not only an understanding of the current observation, but also memory and dynamics modeling. World action models (WAMs) possess these capabilities by jointly modeling visual foresight and actions conditioned on both current and historical observations, making them a promising paradigm for robotic manipulation. However, existing WAMs face a fun

- **GPU-accelerated semidefinite programming for causal games** _(quantitative trading strategy)_
  [2026-06-18](https://arxiv.org/abs/2606.20519v1)
  The process matrix formalism describes quantum correlations in scenarios without a fixed causal order between local laboratories. Operational signatures of such correlations can be investigated through causal games. A paradigmatic example is the Guess-Your-Neighbour's-Input game, in which two parties attempt to guess each other's inputs. Correlations compatible with any definite, or probabilistica

- **State estimation of Rayleigh-Bénard convection with reduced-order models** _(quantitative trading strategy)_
  [2026-06-18](https://arxiv.org/abs/2606.20511v1)
  In this work, we develop a state estimation framework for two-dimensional Rayleigh-Bénard (RB) convection that combines a stable Galerkin reduced-order model (ROM) with an extended Kalman filter (EKF). The ROM, constructed from controllability modes of the linearised Boussinesq equations, provides the nonlinear dynamical model for the filter prediction step. Direct numerical simulations (DNS) are 

- **Observation of electroweak production of pairs of Z bosons in proton-proton collisions at 13 TeV** _(momentum crash risk)_
  [2026-06-18](https://arxiv.org/abs/2606.20558v1)
  The first evidence of electroweak (EW) production of pairs of Z bosons in association with two jets (jj) in the final state ZZjj $\to$ $\ell\ellνν$jj, where $\ell$ = e, $μ$, is reported by the CMS experiment. The analysis is based on a data sample of proton-proton (pp) collisions at $\sqrt{s}$ = 13 TeV, corresponding to an integrated luminosity of 138 fb$^{-1}$. Events are selected by requiring ex

- **On the Renormalization Group Flow of Active Flocks** _(momentum crash risk)_
  [2026-06-18](https://arxiv.org/abs/2606.20552v1)
  In this paper, we study the statistical field-theoretic renormalization of active flocks via the MSRDJ action formulation for stochastic systems, focusing on the Toner-Tu theory of `Malthusian flocks', or polar-ordered, momentum non-conserving active fluids where relaxation times for density fluctuations are so short that they can be eliminated as a hydrodynamic variable. Working in the limit of i

- **Optimal Order of Multi-Agent and General Many-Body Systems** _(momentum crash risk)_
  [2026-06-18](https://arxiv.org/abs/2606.20485v1)
  This paper develops a general framework for analyzing multi-agent systems with feedback loops between agents actions and collective observations. The framework is built on two fundamental agent-level variables: power, which measures agent influence on collective outcomes, and response functions, which determine how agents react to observations. We derive how macroscopic properties, including total

- **On the Renormalization Group Flow of Active Flocks** _(mean reversion statistical arbitrage)_
  [2026-06-18](https://arxiv.org/abs/2606.20552v1)
  In this paper, we study the statistical field-theoretic renormalization of active flocks via the MSRDJ action formulation for stochastic systems, focusing on the Toner-Tu theory of `Malthusian flocks', or polar-ordered, momentum non-conserving active fluids where relaxation times for density fluctuations are so short that they can be eliminated as a hydrodynamic variable. Working in the limit of i

- **DeepSWIP: Quotient-WMC Counterfactuals for Neural Probabilistic Logic Programs** _(mean reversion statistical arbitrage)_
  [2026-06-18](https://arxiv.org/abs/2606.20526v1)
  Neurosymbolic systems such as DeepProbLog combine neural perception with probabilistic logic, but standard inference is associational. Counterfactual reasoning additionally requires a causal semantics for interventions and evidence. We introduce DeepSWIP, a single-world counterfactual semantics for DeepProbLog programs. Using neural materialization, we reduce fixed-context neural predicates to ord

- **Probe-and-Refine Tuning of Repository Guidance for Coding Agents** _(mean reversion statistical arbitrage)_
  [2026-06-18](https://arxiv.org/abs/2606.20512v1)
  LLM-based coding agents need higher-level operational knowledge about a repository (which files house which subsystems, how to run the test suite, which workflows have historically led to wrong fixes) that does not exist in the code itself. Engineers typically maintain \texttt{AGENTS.md} files to supply this context as instructions for coding agents, but whether they help is contested: recent stud

- **Benchmark of quantum algorithms for ground state preparation in the presence of noise** _(regime detection market)_
  [2026-06-18](https://arxiv.org/abs/2606.20551v1)
  We compare the performance of representative cooling, adiabatic, and optimization algorithms for ground-state preparation in the presence of noise. Using an exactly solvable family of quadratic fermionic Hamiltonians subject to depolarizing noise, we derive the scaling of the achievable relative energy as a function of the noise rate and support these results with numerical simulations. The Hamilt

- **Predictability as a Fine-Grained Measure for Privacy** _(regime detection market)_
  [2026-06-18](https://arxiv.org/abs/2606.20546v1)
  Differential privacy (DP) ensures rigorous individual-level privacy guarantees against even the most knowledgeable attackers, but its worst-case nature can impose a costly privacy-accuracy tradeoff. We introduce privacy via predictability, a fine-grained framework that explicitly incorporates the attacker's core knowledge, a compromised portion of the dataset generated by a stochastic process, and

- **Caching for Dollars, Not Hits: An Exact Offline Reference for Cloud-Egress Caching and the Crossover That Decides When It Pays** _(regime detection market)_
  [2026-06-18](https://arxiv.org/abs/2606.20539v1)
  When a cache miss fetches from cloud object storage, the bill is per GET request and per byte of egress, not latency. Classic caching minimizes the miss rate, the wrong objective: a rarely but expensively fetched object can cost thousands of times more dollars than a frequently but cheaply fetched one. Generalized-caching theory bounds the miss-cost objective, but no reported benchmark measures ho

- **How Transparent is DiffusionGemma?** _(deep learning volatility forecasting)_
  [2026-06-18](https://arxiv.org/abs/2606.20560v1)
  LLM reasoning transparency is a critical affordance for understanding model decisions, mitigating misuse and misalignment, and debugging surprising model behaviors. However, DiffusionGemma performs a larger fraction of its computation in a continuous latent space; does this make its reasoning less transparent? We study this question by decomposing transparency into two components: variable transpa

- **UNIEGO: Proxies as Mediators for Unified Egocentric Video Representation Learning** _(deep learning volatility forecasting)_
  [2026-06-18](https://arxiv.org/abs/2606.20559v1)
  Egocentric video understanding is inherently limited by the narrow perspective of wearable cameras: a single viewpoint, a single modality, a single model cannot capture the full richness of human action. We argue that a truly expressive egocentric representation must subsume complementary knowledge across viewpoints, modalities, and foundation model representations, yet remain deployable from egoc

- **Optimal Deterministic Multicalibration and Omniprediction** _(deep learning volatility forecasting)_
  [2026-06-18](https://arxiv.org/abs/2606.20557v1)
  A model is multicalibrated on a collection of group weights $G$ if it is calibrated -- i.e. unbiased even conditional on its prediction -- not just overall, but also after reweighting contexts by each $g \in G$. It is a useful property for many downstream applications and is a basic desideratum of trustworthy machine learning. Before this work, all predictors known to attain the minimax-optimal $\

- **MemoryWAM: Efficient World Action Modeling with Persistent Memory** _(transformer financial time series)_
  [2026-06-18](https://arxiv.org/abs/2606.20562v1)
  Robust robotic manipulation in the real world requires not only an understanding of the current observation, but also memory and dynamics modeling. World action models (WAMs) possess these capabilities by jointly modeling visual foresight and actions conditioned on both current and historical observations, making them a promising paradigm for robotic manipulation. However, existing WAMs face a fun

- **Thinking in Boxes: 3D Editing in Real Images Made Easy** _(transformer financial time series)_
  [2026-06-18](https://arxiv.org/abs/2606.20556v1)
  Text and 2D-conditioning interfaces provide weak, ambiguous control over spatial transformations in image editing -- particularly under large object motions and camera changes. Prior work has used 3D primitives such as boxes, but only as loose conditioning signals indicating approximate object location rather than specifying the transformation. We instead use 3D boxes as structured specifications:

- **On the Renormalization Group Flow of Active Flocks** _(transformer financial time series)_
  [2026-06-18](https://arxiv.org/abs/2606.20552v1)
  In this paper, we study the statistical field-theoretic renormalization of active flocks via the MSRDJ action formulation for stochastic systems, focusing on the Toner-Tu theory of `Malthusian flocks', or polar-ordered, momentum non-conserving active fluids where relaxation times for density fluctuations are so short that they can be eliminated as a hydrodynamic variable. Working in the limit of i

- **How Transparent is DiffusionGemma?** _(reinforcement learning portfolio)_
  [2026-06-18](https://arxiv.org/abs/2606.20560v1)
  LLM reasoning transparency is a critical affordance for understanding model decisions, mitigating misuse and misalignment, and debugging surprising model behaviors. However, DiffusionGemma performs a larger fraction of its computation in a continuous latent space; does this make its reasoning less transparent? We study this question by decomposing transparency into two components: variable transpa

- **UNIEGO: Proxies as Mediators for Unified Egocentric Video Representation Learning** _(reinforcement learning portfolio)_
  [2026-06-18](https://arxiv.org/abs/2606.20559v1)
  Egocentric video understanding is inherently limited by the narrow perspective of wearable cameras: a single viewpoint, a single modality, a single model cannot capture the full richness of human action. We argue that a truly expressive egocentric representation must subsume complementary knowledge across viewpoints, modalities, and foundation model representations, yet remain deployable from egoc

- **Optimal Deterministic Multicalibration and Omniprediction** _(reinforcement learning portfolio)_
  [2026-06-18](https://arxiv.org/abs/2606.20557v1)
  A model is multicalibrated on a collection of group weights $G$ if it is calibrated -- i.e. unbiased even conditional on its prediction -- not just overall, but also after reweighting contexts by each $g \in G$. It is a useful property for many downstream applications and is a basic desideratum of trustworthy machine learning. Before this work, all predictors known to attain the minimax-optimal $\

- **MemoryWAM: Efficient World Action Modeling with Persistent Memory** _(cryptocurrency trading)_
  [2026-06-18](https://arxiv.org/abs/2606.20562v1)
  Robust robotic manipulation in the real world requires not only an understanding of the current observation, but also memory and dynamics modeling. World action models (WAMs) possess these capabilities by jointly modeling visual foresight and actions conditioned on both current and historical observations, making them a promising paradigm for robotic manipulation. However, existing WAMs face a fun

- **Efficient and Sound Probabilistic Verification for AI Agents** _(cryptocurrency trading)_
  [2026-06-18](https://arxiv.org/abs/2606.20510v1)
  Securing AI agents that operate in complex digital environments has become a critical need, and runtime monitoring approaches that formulate and enforce policies expressed in a formal language like Datalog offer a promising solution. However, existing approaches are restricted to deterministic policies. In many practical applications of AI agents, there is a need to enforce security policies in th

- **General circuit mapping algorithm for neutral atom quantum computers** _(cryptocurrency trading)_
  [2026-06-18](https://arxiv.org/abs/2606.20503v1)
  Neutral atom quantum computers (NAQC) are emerging as a promising, scalable quantum computing platform because of their long qubit coherence, flexible qubit arrangement, and multiqubit gate capabilities. However, circuit execution often requires physically moving qubits, making compilation a critical optimization challenge. We propose a circuit independent mathematical framework built on graph-the

- **Structuring and Tokenizing Distributed User Interest Context for Generative Recommendation** _(options volatility surface)_
  [2026-06-18](https://arxiv.org/abs/2606.20554v1)
  Generative recommendation is an emerging paradigm that has shown promise in industrial recommendation systems, aiming to predict users' next interactions from their historical behaviors. At the core of generative recommendation lies item tokenization, which bridges item semantics and recommendation models. However, existing methods often struggle to effectively organize and inject complex user-beh

- **Current World Models Lack a Persistent State Core** _(options volatility surface)_
  [2026-06-18](https://arxiv.org/abs/2606.20545v1)
  World models are increasingly regarded as a decisive step toward artificial general intelligence, yet modeling the physical world demands more than rendering convincing frames on demand: it requires an internal world state that keeps evolving over time, decoupled from observation, so that objects endure and events run to their conclusions whether or not a camera is watching, much as the moon holds

- **Controllable Quantum Spin Hall Phases in Bi$_2$Te$_3$-Family van der Waals Heterobilayers** _(options volatility surface)_
  [2026-06-18](https://arxiv.org/abs/2606.20541v1)
  The tunability and control of topological edge/surface states are crucial for the development of new device applications. In this work, by combining first-principles calculations and Wannier-based tight-binding methods, we show the emergence of quantum spin Hall phases in van der Waals heterostructures formed by stacking two trivial quintuple layers from the Bi$_2$Te$_3$ family. We demonstrate the

- **The FID Lottery: Quantifying Hidden Randomness in Generative-Model Evaluation** _(factor investing alpha)_
  [2026-06-18](https://arxiv.org/abs/2606.20536v1)
  The Frechet Inception Distance (FID) is the de facto arbiter of image generation, yet most papers report just a single number from a single trained model using a single sampling seed. How reproducible is that number if we retrain the model, or merely resample from it? In this paper, we treat FID as a random variable on a two-axis panel of training and generation seeds, and measure its variance dir

- **The $B^+ \to K^+ ν\bar ν$ decay as a QCD axion search: comparing reinterpretation approaches** _(factor investing alpha)_
  [2026-06-18](https://arxiv.org/abs/2606.20525v1)
  Two recent independent analyses of Belle II $B^+ \! \to \! K^+ν\barν$ data yield limits on ${\mathcal B}(B^+ \! \to \! K^+ a)$ -- the two-body mode to a light invisible particle such as the QCD axion -- differing by a factor of roughly four; we trace this to the choice of kinematic variable space. The central figure of merit is the resolution in the reconstructed di-neutrino invariant mass $q^2_{\

- **Leveraging tails for adaptation** _(factor investing alpha)_
  [2026-06-18](https://arxiv.org/abs/2606.20480v1)
  We consider contraction of Bayesian posterior distributions in nonparametric settings where coefficients of a function over a basis or dictionary are given priors with $p$--exponential tails, including Laplace tails $(p=1)$ and heavier tails $(p&lt;1)$. It is shown that contraction rates improve as $p$ decreases and that full adaptation to smoothness, up to logarithmic factors, is obtained in an a

## 3. GitHub Repos (Recently Updated)
- **[neohsiung/AI-Investment-Advisor](https://github.com/neohsiung/AI-Investment-Advisor)** ⭐ 1 · Python _(updated 2026-06-21)_
  AI-powered quantitative investment platform with 7-agent swarm orchestration, fractal debate algorithm, 3-tier LLM routing, and automated eToro trading — built for autonomous portfolio management.

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-21)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[Vixoqz/vnpy-Machine-Learning](https://github.com/Vixoqz/vnpy-Machine-Learning)** ⭐ 0 · C# _(updated 2026-06-21)_
  vnpy-Machine-Learning: integrates machine-learning models with the vn.py quantitative-trading framework for AI-driven, data-driven algorithmic trading and backtesting in Python.

- **[tranduy216/auto-alert-gg-chat](https://github.com/tranduy216/auto-alert-gg-chat)** ⭐ 0 · Python _(updated 2026-06-21)_
  Crypto trading bot on OKX (2.5x, stop -5.5%). Coins: ETH, BNB, LINK, ADA, MATIC. Strategy: 3D trend + 1D execution engine with 3-stage scaling entries (limit orders). Rules: max 4 pos, 75% cap, BTC re

- **[Qyxloq/blankly-finance](https://github.com/Qyxloq/blankly-finance)** ⭐ 0 · Python _(updated 2026-06-21)_
  Blankly-Finance: A powerful Algo-Trading-Framework for stocks, crypto, and forex. Features Multi-Exchange-API, Backtesting, and Trading-Bot tools.

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 0 · HTML _(updated 2026-06-21)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-21)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrency-Margin-Algorithmic](https://github.com/Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrency-Margin-Algorithmic)** ⭐ 2 · Python _(updated 2026-06-21)_
  This repository features Juno, an automated trade bot for Binance, designed for margin trading of cryptocurrencies. It utilizes advanced algorithmic strategies to optimize trading decisions and enhanc

- **[DTal621/trading-bot](https://github.com/DTal621/trading-bot)** ⭐ 1 · Python _(updated 2026-06-21)_
  Algorithmic trading strategy for stocks and crypto — Alpaca Markets

- **[liuh886/alpha_engine](https://github.com/liuh886/alpha_engine)** ⭐ 0 · Python _(updated 2026-06-21)_
  Alpha Engine: AI-driven quantitative trading research platform with factor lifecycle, model registry, backtesting, and dashboard.

- **[zzzhhn/alpha-agent](https://github.com/zzzhhn/alpha-agent)** ⭐ 0 · Python _(updated 2026-06-20)_
  LLM-Powered Alpha Research Agent — multi-agent system for automated quantitative factor discovery on A-share markets

- **[fhkong330/alpha-factor-research](https://github.com/fhkong330/alpha-factor-research)** ⭐ 0 · Python _(updated 2026-06-20)_
  Cross-sectional equity alpha factor research for US stocks.

- **[r-t-culbreath/stat-arb-pairs-research](https://github.com/r-t-culbreath/stat-arb-pairs-research)** ⭐ 0 · None _(updated 2026-06-20)_
  Kalman-filter statistical arbitrage including an average trading range research. Pairs trading with rigorous out-of-sample validation. This process incorporated walk-forward, holdouts, cost-aware scre

- **[khwahishgoel/Statistical-Arbitrage-Research-Platform](https://github.com/khwahishgoel/Statistical-Arbitrage-Research-Platform)** ⭐ 0 · Python _(updated 2026-06-20)_
  Research platform for pair trading using cointegration, z-score signals, and transaction-cost-aware backtesting.

- **[muditjain936/stat-arb-pairs-trading](https://github.com/muditjain936/stat-arb-pairs-trading)** ⭐ 0 · Python _(updated 2026-06-20)_
  Statistical arbitrage pairs trading on NIFTY 50 banking stocks — cointegration screening, static OLS vs Kalman filter hedge ratios

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-21)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 49 · Python _(updated 2026-06-19)_
  A stock/futures auto trading framework using Shioaji API

- **[I-am-Uchenna/institutional-options-research](https://github.com/I-am-Uchenna/institutional-options-research)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-18)_
  Academic, risk-first options research framework with stochastic-volatility pricing, defined-risk strategy analysis, and paper-trading controls.

## 4. Perplexity Strategy Synthesis
For a **$100–$1,000 account**, the most actionable systematic setups are usually the ones with *simple execution, low turnover, and small capital requirements*: crypto trend-following with regime filters, market-neutral equity pairs, and very selective options hedges only when volatility is cheap. I cannot verify truly “newly discovered” edges from recent papers or trading Twitter from the provided results alone, so I’ll separate **well-supported systematic ideas** from **unverified hype** and flag where crowding/degradation risk is highest.

- **Best fit for small accounts:** crypto momentum with a regime filter, because it can be traded with fractional sizing, 24/7 data, and no pattern-day-trading constraints.
- **Best fit for robustness:** equity pair trading, because it is market-neutral and can be implemented with small notionals.
- **Best fit for tail hedging:** long convexity only when implied volatility is near the low end of its recent range; otherwise it is usually too expensive for small accounts.
- **Highest crowding risk:** plain breakout momentum, short-volatility income, and simple mean-reversion pairs in the most popular names.

## 1) Crypto momentum with regime filters

A practical retail version is **time-series momentum** on liquid spot crypto, filtered by a risk regime so you only trade when the market is trending and not in a high-chop / high-crash state. The provided sources don’t include a peer-reviewed crypto paper, but they do support the general systematic structure: trend-following, explicit entry/exit rules, and small-account focus on liquid markets[5][7].

### Concrete rule set
- **Universe:** BTC, ETH, and 2–4 liquid large caps only.
- **Time horizon:** **1–7 days** holding period.
- **Signal timeframe:** daily bars.
- **Trend signal:** long when price is above the **50-day moving average** and the **20-day return** is positive; flat otherwise.
- **Regime filter:** only take longs when:
  - BTC is above its 200-day moving average, and
  - 20-day realized volatility is below its 80th percentile over the last 2 years, and
  - 14-day RSI is between **45 and 70** so you avoid both dead markets and late overbought entries.
- **Entry:** buy on a close back above the 10-day high *after* the regime filter is true, or on a pullback to the 10-day EMA inside an uptrend.
- **Exit:** sell on a close below the 10-day EMA, or after **5 trading days**, whichever comes first.
- **Stop-loss:** initial stop at **2 ATR(14)** below entry.
- **Position sizing:** risk **0.5%–1.0%** of account equity per trade; for a $500 account, that is $2.50–$5 risk per trade.
- **Max exposure:** no more than **2 concurrent positions** and no more than **50% gross exposure** of equity.

### Why this is actionable
- It is simple enough to automate with free or low-cost data.
- It works with tiny size because you can use fractional crypto units.
- It avoids the most common small-account failure mode: overtrading chop.

### What has likely degraded in the last 6 months
- **Pure breakout crypto momentum** has likely become more crowded and noisier, especially in majors, because it is heavily discussed in retail channels and is easy to copy.
- **Late-stage altcoin momentum** is especially vulnerable to slippage and reversals.
- If you trade this, the regime filter is the edge; without it, the setup is much closer to a generic breakout system.

## 2) Equity pair trading

For small retail accounts, the most realistic version is **same-sector or economically linked pairs** with strong cointegration-like behavior, but only when the spread is sufficiently volatile relative to trading costs. The small-account principle and systematic-trading emphasis on liquid instruments are consistent with the sources, though they do not provide a pair-trading paper directly[7][5].

### Concrete rule set
- **Universe:** 10–20 highly liquid same-sector pairs, such as:
  - large-cap banks,
  - integrated oil names,
  - mega-cap software names,
  - airline pairs

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-21 via Conway's auto-publisher.*
