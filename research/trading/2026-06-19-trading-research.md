# Trading Nightly Research Brief — 2026-06-19

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-19T02:32:00, run time 22.5s._

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
- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-19)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[Vixoq/vnpy](https://github.com/Vixoq/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-19)_
  Open source quantitative trading platform development framework based

- **[Vixoqz/vnpy-Machine-Learning](https://github.com/Vixoqz/vnpy-Machine-Learning)** ⭐ 0 · C# _(updated 2026-06-19)_
  vnpy-Machine-Learning: integrates machine-learning models with the vn.py quantitative-trading framework for AI-driven, data-driven algorithmic trading and backtesting in Python.

- **[Qyxloq/blankly-finance](https://github.com/Qyxloq/blankly-finance)** ⭐ 0 · Python _(updated 2026-06-19)_
  Blankly-Finance: A powerful Algo-Trading-Framework for stocks, crypto, and forex. Features Multi-Exchange-API, Backtesting, and Trading-Bot tools.

- **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance)** ⭐ 11 · Python _(updated 2026-06-19)_
  Easily build, backtest and deploy your algo in just a few lines of code. Trade stocks, cryptos, and forex across exchanges one package.

- **[tsathya98/crypto-stock-trading-bot](https://github.com/tsathya98/crypto-stock-trading-bot)** ⭐ 0 · Python _(updated 2026-06-19)_
  A 24/7 CoinDCX crypto paper-trading agent (MCP + Claude). Published as a rigorous negative-result experiment: no deployable retail edge found. Dry-run safe, fully tested.

- **[123AGustien/sextant-trader-alpha](https://github.com/123AGustien/sextant-trader-alpha)** ⭐ 0 · Python _(updated 2026-06-19)_
  Paper trading system with EUR/USD strategy engine + SGD/IDR monitoring module for algorithmic trading simulation.

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-19)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrency-Margin-Algorithmic](https://github.com/Calaestivox/Juno-Binance-Trade-Bot-Automated-Cryptocurrency-Margin-Algorithmic)** ⭐ 2 · Python _(updated 2026-06-19)_
  This repository features Juno, an automated trade bot for Binance, designed for margin trading of cryptocurrencies. It utilizes advanced algorithmic strategies to optimize trading decisions and enhanc

- **[JaneAlpha/AlphaSwarm](https://github.com/JaneAlpha/AlphaSwarm)** ⭐ 0 · Python _(updated 2026-06-19)_
  Multi-agent LLM system for quantitative factor discovery, featuring agent orchestration, tool-based factor validation, hypothesis generation, performance evaluation, and iterative ranking under a cont

- **[zzzhhn/alpha-agent](https://github.com/zzzhhn/alpha-agent)** ⭐ 0 · Python _(updated 2026-06-19)_
  LLM-Powered Alpha Research Agent — multi-agent system for automated quantitative factor discovery on A-share markets

- **[RintuRifle/alpha-engine](https://github.com/RintuRifle/alpha-engine)** ⭐ 1 · Python _(updated 2026-06-18)_
  A modular Quantitative Research & Algorithmic Trading Platform built in Python. Features an event-driven backtesting engine, custom factor research modules, robust risk analytics (Sharpe, Sortino, Dra

- **[hansg0511/statistical-arbitrage-pairs-trading](https://github.com/hansg0511/statistical-arbitrage-pairs-trading)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-19)_
  Statistical arbitrage pairs trading system using cointegration and z-score mean reversion. Validated via strict walk-forward out-of-sample testing with regime analysis and sensitivity checks. Focused 

- **[LeonardoHuayanayGallo/Statistical-Arbitrage-Engine](https://github.com/LeonardoHuayanayGallo/Statistical-Arbitrage-Engine)** ⭐ 0 · Python _(updated 2026-06-18)_
  Algorithmic pairs trading engine using cointegration and statistical arbitrage

- **[user-Param/STATPRO](https://github.com/user-Param/STATPRO)** ⭐ 1 · Makefile _(updated 2026-06-18)_
  STATPRO is a quantitative trading framework for tick-level statistical arbitrage on BNB Chain perpetual futures. It manages market data, analyzes statistical relationships between assets, and provides

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-19)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 49 · Python _(updated 2026-06-19)_
  A stock/futures auto trading framework using Shioaji API

- **[I-am-Uchenna/institutional-options-research](https://github.com/I-am-Uchenna/institutional-options-research)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-18)_
  Academic, risk-first options research framework with stochastic-volatility pricing, defined-risk strategy analysis, and paper-trading controls.

## 4. Perplexity Strategy Synthesis
The most actionable **small-account systematic strategies** right now are still the ones with the cleanest execution and least capital drag: **crypto trend/momentum with a volatility or regime filter**, **statistical equity pair trading in liquid names**, and **defined-risk options hedges only when implied volatility is cheap relative to realized**. For **$100–$1000** accounts, I would avoid anything that depends on frequent fills, complex options structures, or high turnover unless the position sizing is extremely small and the edge is robust.

Because your prompt asks for *April 2026* and for recent degradation/crowding, I need to be explicit: the supplied search results do **not** include recent academic papers or Trading Twitter threads specific to those edges, so I can only ground the concrete strategy templates in the available sources and general quantitative practice. The results do support common momentum, breakout, range, and risk-control rules, but they do **not** verify any “newly discovered” 2026 edge or last-6-month crowding changes.[1][2][3][4]

- **1) Crypto momentum with regime filters**
  - **Best use case:** swing trading 1–14 days on liquid majors like BTC and ETH, not microcaps.
  - **Core idea:** trade only when the market is in an uptrend and volatility is supportive; skip chop.
  - **Entry rule:** long only when price is above a medium-term trend filter such as the **50-day EMA** or **200-day EMA**, and the asset makes a **20-day breakout** or pulls back to the 20-day EMA and reclaims it; this matches the general momentum/breakout logic in the provided sources.[1][3]
  - **Regime filter:** require either:
    - price above the **200-day EMA** and the **50-day EMA** rising, or
    - 30-day realized volatility below a threshold you calibrate to the asset’s history, so you avoid chasing parabolic spikes.
  - **Exit rule:** sell on a close back below the **20-day EMA**, or use a trailing stop under the prior 5-day swing low; the supplied sources emphasize trend continuation and exiting when momentum slows or structure breaks.[1][5]
  - **Position sizing:** risk **0.5%–1%** of account equity per trade; with a $500 account, that is **$2.50–$5** max loss, which usually means very small spot size or perpetuals only if you can use a tiny stop and controlled leverage.[3][5]
  - **Practical note:** for tiny accounts, spot crypto is easier than futures because fees and liquidation risk can overwhelm the edge.
  - **Crowding/degradation risk:** **high** for plain breakout momentum. The provided sources describe momentum and breakout trading as common, which often means the simplest versions are crowded and fragile.[1][3]
  - **What to prefer:** breakout **after consolidation** rather than first-impulse chasing; the search results explicitly note consolidation after breakout as confirmation.[3]

- **2) Equity pair trading**
  - **Best use case:** market-neutral mean reversion in very liquid pairs; for small accounts this is usually more realistic in **ETFs** than single stocks because borrow, commissions, and short-sale frictions matter.
  - **Pair selection:** choose highly correlated names within the same industry or factor bucket; the strategy works best when the spread is stable and the names have similar beta.
  - **Entry rule:** compute a spread z-score and enter when the spread reaches **\(|z| \ge 2\)**; go long the weak leg and short the strong leg if you can short cleanly.
  - **Exit rule:** close when the spread reverts to **\(|z| \le 0.5\)**, or sooner if correlation breaks down.
  - **Horizon:** typically **3–20 trading days**.
  - **Position sizing:** size each leg so the **dollar risk is equal**, and cap total gross exposure at roughly **1–2x account value** only if you can actually short efficiently; for a $100–$1000 account, ETF pairs are far more practical than single-stock pairs.
  - **Risk control:** if the spread extends to **\(|z| \ge 3

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-19 via Conway's auto-publisher.*
