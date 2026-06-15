# Trading Nightly Research Brief — 2026-06-15

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-06-15T02:46:59, run time 23.1s._

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
- **Learning Coordinated Preference for Multi-Objective Multi-Agent Reinforcement Learning** _(quantitative trading strategy)_
  [2026-06-12](https://arxiv.org/abs/2606.14693v1)
  Cooperative multi-objective multi-agent reinforcement learning (MOMARL) models team decision making under multiple, potentially conflicting objectives. In this setting, conflicts arise not only across objectives but also across agents with different observations, roles, and contributions. We propose Preference Coordinated Multi-agent Policy Optimization (PCMA), which learns coordinated agent-speci

- **Implications of hierarchical Markov models of behavior: on irreversibility, predictability, and dimensionality** _(quantitative trading strategy)_
  [2026-06-12](https://arxiv.org/abs/2606.14692v1)
  The maturation of quantitative tools for studying the high-level structure of animal behavior, and especially tools which represent spontaneous behavior as a sequence of stereotyped and neurally well-defined 'syllables', demands that the field revisit a fundamental theoretical question: if the coarse structure of behavior can be accurately described by Markov models, what do these models really te

- **Impact of 21-cm foreground mitigation strategies on reionization power spectrum constraints** _(quantitative trading strategy)_
  [2026-06-12](https://arxiv.org/abs/2606.14682v1)
  The 21-cm signal probes the intergalactic medium during the Epoch of Reionization (EoR) but is overwhelmed by astrophysical foregrounds orders of magnitude stronger than the cosmological signal. We evaluate two mitigation strategies: (i) Foreground Avoidance, restricting analysis to the EoR window in Fourier space, and (ii) Foreground Removal via Gaussian Process Regression, which exploits spectra

- **A Complexity Measure for Active Learning in Multi-group Mean Estimation** _(momentum crash risk)_
  [2026-06-12](https://arxiv.org/abs/2606.14690v1)
  We study a \emph{max-risk} objective for active learning in a multi-group mean estimation $d$-armed bandits: a learner adaptively allocates a budget of $T$ samples across $d$ groups to minimize the worst-case uncertainty index $\max_{k\in[d]}σ_k^2/n_k$, where $σ_k$ is the standard deviation of the distribution of arm $d$, and $n_k$ is the number of times arm $d$ is sampled. We develop a local mini

- **Expert-Driven Survival Machines: Improving Stratification and Interpretability in Multiple Clinical Cohorts** _(momentum crash risk)_
  [2026-06-12](https://arxiv.org/abs/2606.14608v1)
  Survival prediction plays a central role for healthcare providers and clinical researchers. Accurate risk stratification enables early intervention and improved patient management. Most existing deep survival models learn one common feature representation for all patients, which may hide important differences between patient subgroups. In contrast, a Mixture-of-Experts (MoE) framework allows diffe

- **A Temporal Planning Framework for Disruption Aware Dynamic Route Optimization in Heterogeneous Railway Systems** _(momentum crash risk)_
  [2026-06-12](https://arxiv.org/abs/2606.14582v1)
  Efficient route optimization play a vital role in ensuring both safety and punctuality in railway operations. It is very crucial particularly in heterogeneous multi-gauge railway networks with varying train speed, stopping pattern, infrastructure compatibility constraints increase coordination complexity. In single-track systems these challenges are further intensify due to all trains to share the

- **The Edges of Planetary Systems: Falling Off the Kuiper Cliff in a Dissipating Gas Disk** _(mean reversion statistical arbitrage)_
  [2026-06-12](https://arxiv.org/abs/2606.14704v1)
  Probably the last planetesimals to have formed from dust in the solar nebula are Cold Classical Kuiper belt objects (CCKBOs). To the extent that they are isolated and unchanged since birth, CCKBOs offer direct insights into nebular processes. Their population density drops abruptly beyond a heliocentric radius of $\sim$47 au, a feature known as the "Kuiper Cliff". We show with global, 1D (radial),

- **Instruct-Particulate: Scaling Feed-Forward 3D Object Articulation with Kinematic Control** _(mean reversion statistical arbitrage)_
  [2026-06-12](https://arxiv.org/abs/2606.14699v1)
  Reconstructing articulated 3D objects is important for animation, gaming, and robotic simulations. Recent neural networks can estimate the articulated structure of 3D objects, but their generalization remains limited by the scarcity of annotated data for this task. To address this gap, we introduce Instruct-Particulate, a model that takes a 3D mesh together with a target kinematic specification, i

- **Scalar dissipation anomaly and scalar-gradient scaling in turbulence: A joint velocity-scalar multifractal view** _(mean reversion statistical arbitrage)_
  [2026-06-12](https://arxiv.org/abs/2606.14696v1)
  We revisit the problem of scalar dissipation anomaly and scaling of scalar gradients in passive scalar turbulence using theory and data from well-resolved direct numerical simulations (DNS) on grid sizes of up to $8192^3$, spanning Taylor-scale Reynolds numbers $Re_λ=140-1000$ and Schmidt numbers $Sc = 1-512$. The theory is based on a joint multifractal description of longitudinal velocity increme

- **A Complexity Measure for Active Learning in Multi-group Mean Estimation** _(regime detection market)_
  [2026-06-12](https://arxiv.org/abs/2606.14690v1)
  We study a \emph{max-risk} objective for active learning in a multi-group mean estimation $d$-armed bandits: a learner adaptively allocates a budget of $T$ samples across $d$ groups to minimize the worst-case uncertainty index $\max_{k\in[d]}σ_k^2/n_k$, where $σ_k$ is the standard deviation of the distribution of arm $d$, and $n_k$ is the number of times arm $d$ is sampled. We develop a local mini

- **Leptonic flavour transfer: a new window on flavour gauge symmetries** _(regime detection market)_
  [2026-06-12](https://arxiv.org/abs/2606.14689v1)
  New flavour non-abelian gauge groups, which may arise as part of a fundamental theory of flavour, can lead to distinctive flavour-transfer processes. When restricted to the lepton sector, such processes partially mimic the standard charged current interactions at low energy. We explicitly study such constructions with various flavour structures, and investigate systematically all relevant accelera

- **Flood and Harvest: The Provable Necessity of Trivia for Generating Valuable Mathematics via the Lens of Language Generation in the Limit** _(regime detection market)_
  [2026-06-12](https://arxiv.org/abs/2606.14688v1)
  AI systems coupled to proof assistants now generate formal mathematics at scale, and the gap between what a checker can verify and what a mathematician would value has become the binding constraint. We model the generation of valuable mathematics as nested language generation in the limit: a verifiable formal language $F$, accessed through a membership oracle (the proof checker), contains an unkno

- **Gaze Heads: How VLMs Look at What They Describe** _(deep learning volatility forecasting)_
  [2026-06-12](https://arxiv.org/abs/2606.14703v1)
  How a vision-language model internally solves the task of describing an image is far from obvious. We find that the model develops a specific mechanism for this: a small set of attention heads in its language-model backbone, which we call gaze heads, whose attention tracks the image region the model is currently describing. We find them with a simple correlation score from a few forward passes, us

- **OmniVideo-100K: A Dataset for Audio-Visual Reasoning through Structured Scripts and Evidence Chains** _(deep learning volatility forecasting)_
  [2026-06-12](https://arxiv.org/abs/2606.14702v1)
  Current automated pipelines for audio-visual Question Answering (QA) generally adopt a ``video-caption-QA'' paradigm. However, these methods typically segment videos into short clips and generate separate descriptions for audio and visual modalities. This decoupled processing severs inherent associations between sounds and their visual sources, while independent clip processing often causes incons

- **RATS! Patches Talk Through Registers: Emergent Parts in Register Attention Transformers** _(deep learning volatility forecasting)_
  [2026-06-12](https://arxiv.org/abs/2606.14701v1)
  When humans see a bird, they recognize far more than just "bird" -- they see a head, wings, and talons, a structured assembly of reusable parts that can be identified across every bird they have ever seen. We ask whether a self-supervised visual model can discover the same compositional structure on its own. To this end, we propose RATS (Register Attention Transformers), which decomposes the class

- **The Edges of Planetary Systems: Falling Off the Kuiper Cliff in a Dissipating Gas Disk** _(transformer financial time series)_
  [2026-06-12](https://arxiv.org/abs/2606.14704v1)
  Probably the last planetesimals to have formed from dust in the solar nebula are Cold Classical Kuiper belt objects (CCKBOs). To the extent that they are isolated and unchanged since birth, CCKBOs offer direct insights into nebular processes. Their population density drops abruptly beyond a heliocentric radius of $\sim$47 au, a feature known as the "Kuiper Cliff". We show with global, 1D (radial),

- **Gaze Heads: How VLMs Look at What They Describe** _(transformer financial time series)_
  [2026-06-12](https://arxiv.org/abs/2606.14703v1)
  How a vision-language model internally solves the task of describing an image is far from obvious. We find that the model develops a specific mechanism for this: a small set of attention heads in its language-model backbone, which we call gaze heads, whose attention tracks the image region the model is currently describing. We find them with a simple correlation score from a few forward passes, us

- **OmniVideo-100K: A Dataset for Audio-Visual Reasoning through Structured Scripts and Evidence Chains** _(transformer financial time series)_
  [2026-06-12](https://arxiv.org/abs/2606.14702v1)
  Current automated pipelines for audio-visual Question Answering (QA) generally adopt a ``video-caption-QA'' paradigm. However, these methods typically segment videos into short clips and generate separate descriptions for audio and visual modalities. This decoupled processing severs inherent associations between sounds and their visual sources, while independent clip processing often causes incons

- **Gaze Heads: How VLMs Look at What They Describe** _(reinforcement learning portfolio)_
  [2026-06-12](https://arxiv.org/abs/2606.14703v1)
  How a vision-language model internally solves the task of describing an image is far from obvious. We find that the model develops a specific mechanism for this: a small set of attention heads in its language-model backbone, which we call gaze heads, whose attention tracks the image region the model is currently describing. We find them with a simple correlation score from a few forward passes, us

- **RATS! Patches Talk Through Registers: Emergent Parts in Register Attention Transformers** _(reinforcement learning portfolio)_
  [2026-06-12](https://arxiv.org/abs/2606.14701v1)
  When humans see a bird, they recognize far more than just "bird" -- they see a head, wings, and talons, a structured assembly of reusable parts that can be identified across every bird they have ever seen. We ask whether a self-supervised visual model can discover the same compositional structure on its own. To this end, we propose RATS (Register Attention Transformers), which decomposes the class

- **Persona-Pruner: Sculpting Lightweight Models for Role-Playing** _(reinforcement learning portfolio)_
  [2026-06-12](https://arxiv.org/abs/2606.14695v1)
  Language Models (LMs) have shown remarkable potential as role-playing chatbots, delivering consistent, stylized interactions when given a specification of a character or user persona. However, applying these capabilities to real-world applications (e.g., ecosystems with numerous NPCs interacting simultaneously) exposes a critical inefficiency due to the excessive computational cost. In this paper,

- **Learning Coordinated Preference for Multi-Objective Multi-Agent Reinforcement Learning** _(cryptocurrency trading)_
  [2026-06-12](https://arxiv.org/abs/2606.14693v1)
  Cooperative multi-objective multi-agent reinforcement learning (MOMARL) models team decision making under multiple, potentially conflicting objectives. In this setting, conflicts arise not only across objectives but also across agents with different observations, roles, and contributions. We propose Preference Coordinated Multi-agent Policy Optimization (PCMA), which learns coordinated agent-speci

- **AgentSpec: Understanding Embodied Agent Scaffolds Through Controlled Composition** _(cryptocurrency trading)_
  [2026-06-12](https://arxiv.org/abs/2606.14674v1)
  LLM agents are increasingly built not as single model calls, but as scaffolded systems that combine reasoning, memory, reflection, action execution, and learning. While such scaffolds often improve performance, they are often embedded in tightly coupled pipelines, making it difficult to isolate component contributions, compare alternative designs, or understand how module interactions shape agent 

- **Private Information Retrieval for Large-Scale DNA-Based Data Storage** _(cryptocurrency trading)_
  [2026-06-12](https://arxiv.org/abs/2606.14557v1)
  We investigate Private Information Retrieval (PIR) in the context of synthetic DNA-based data storage. While PIR is a well-studied primitive for digital databases, extending it to DNA-based databases presents unique challenges arising from biochemical query mechanisms and their complexity. We propose two approaches for adapting two-server PIR protocols to DNA-based storage, balancing privacy, effi

- **The Edges of Planetary Systems: Falling Off the Kuiper Cliff in a Dissipating Gas Disk** _(options volatility surface)_
  [2026-06-12](https://arxiv.org/abs/2606.14704v1)
  Probably the last planetesimals to have formed from dust in the solar nebula are Cold Classical Kuiper belt objects (CCKBOs). To the extent that they are isolated and unchanged since birth, CCKBOs offer direct insights into nebular processes. Their population density drops abruptly beyond a heliocentric radius of $\sim$47 au, a feature known as the "Kuiper Cliff". We show with global, 1D (radial),

- **Instruct-Particulate: Scaling Feed-Forward 3D Object Articulation with Kinematic Control** _(options volatility surface)_
  [2026-06-12](https://arxiv.org/abs/2606.14699v1)
  Reconstructing articulated 3D objects is important for animation, gaming, and robotic simulations. Recent neural networks can estimate the articulated structure of 3D objects, but their generalization remains limited by the scarcity of annotated data for this task. To address this gap, we introduce Instruct-Particulate, a model that takes a 3D mesh together with a target kinematic specification, i

- **AgentSpec: Understanding Embodied Agent Scaffolds Through Controlled Composition** _(options volatility surface)_
  [2026-06-12](https://arxiv.org/abs/2606.14674v1)
  LLM agents are increasingly built not as single model calls, but as scaffolded systems that combine reasoning, memory, reflection, action execution, and learning. While such scaffolds often improve performance, they are often embedded in tightly coupled pipelines, making it difficult to isolate component contributions, compare alternative designs, or understand how module interactions shape agent 

- **A Complexity Measure for Active Learning in Multi-group Mean Estimation** _(factor investing alpha)_
  [2026-06-12](https://arxiv.org/abs/2606.14690v1)
  We study a \emph{max-risk} objective for active learning in a multi-group mean estimation $d$-armed bandits: a learner adaptively allocates a budget of $T$ samples across $d$ groups to minimize the worst-case uncertainty index $\max_{k\in[d]}σ_k^2/n_k$, where $σ_k$ is the standard deviation of the distribution of arm $d$, and $n_k$ is the number of times arm $d$ is sampled. We develop a local mini

- **Enigmatic Line Broadening During Solar Flares: Magnetic Field Broadening?** _(factor investing alpha)_
  [2026-06-12](https://arxiv.org/abs/2606.14681v1)
  The origin of the extreme broadening observed in chromospheric metal lines during solar and stellar flares, particularly Mg II h&amp;k and Ca II H&amp;K, remains poorly understood. These lines often display Lorentzian like wings whose widths exceed standard Stark broadening predictions by factors of approx. 30, with no known collisional mechanism capable of producing such enhancements. We posit th

- **Compressed Computation is (probably) not Computation in Superposition** _(factor investing alpha)_
  [2026-06-12](https://arxiv.org/abs/2606.14673v1)
  We study whether the Compressed Computation (CC) toy model (Braun et al., 2025) is an instance of computation in superposition. The CC model appears to compute 100 ReLU functions with just 50 neurons, achieving a better loss than expected from only representing 50 ReLU functions. We show that the model mixes inputs via its noisy residual stream, corresponding to an unintended mixing matrix in the 

## 3. GitHub Repos (Recently Updated)
- **[Vixoq/vnpy](https://github.com/Vixoq/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-15)_
  Open source quantitative trading platform development framework based

- **[Barrazar274/the-0050-project](https://github.com/Barrazar274/the-0050-project)** ⭐ 0 · Python _(updated 2026-06-15)_
  Document a quantitative trading project that compares custom machine learning strategies against a simple 0050 buy and hold approach using backtested data.

- **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant)** ⭐ 2 · Python _(updated 2026-06-15)_
  Trade Kalshi prediction markets with a quantitative system designed for fee-aware position sizing and statistical arbitrage.

- **[opop753/AI-Powered-Crypto-Trading-Bot](https://github.com/opop753/AI-Powered-Crypto-Trading-Bot)** ⭐ 2 · JavaScript _(updated 2026-06-15)_
  🤖 Power your trading with an AI-driven crypto bot that delivers live data, trading strategies, charts, news, and market session timelines.

- **[Qyxloq/blankly-finance](https://github.com/Qyxloq/blankly-finance)** ⭐ 0 · Python _(updated 2026-06-15)_
  Blankly-Finance: A powerful Algo-Trading-Framework for stocks, crypto, and forex. Features Multi-Exchange-API, Backtesting, and Trading-Bot tools.

- **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance)** ⭐ 11 · Python _(updated 2026-06-15)_
  Easily build, backtest and deploy your algo in just a few lines of code. Trade stocks, cryptos, and forex across exchanges one package.

- **[aminehad725/AlgorithmicTradingEngine](https://github.com/aminehad725/AlgorithmicTradingEngine)** ⭐ 2 · C++ _(updated 2026-06-15)_
  Build a robust Algorithmic Trading Engine for automated trading strategies. Optimize performance and enhance decision-making with advanced algorithms. 🚀💻

- **[arnolddelaguila/Advanced-Multi-Asset-Algorithmic-Trading-System-with-Machine-Learning-Integration](https://github.com/arnolddelaguila/Advanced-Multi-Asset-Algorithmic-Trading-System-with-Machine-Learning-Integration)** ⭐ 2 · Jupyter Notebook _(updated 2026-06-15)_
  Explore an advanced multi-asset algorithmic trading system with machine learning integration. Optimize strategies, backtest rigorously, and achieve high performance. 🐙📈

- **[magikgmo4-ui/opt-trading](https://github.com/magikgmo4-ui/opt-trading)** ⭐ 0 · Python _(updated 2026-06-15)_
  Trading algorithms and strategies

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 0 · None _(updated 2026-06-15)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[kushagrapandey2852/Alternative-Data-Signal-Extractor](https://github.com/kushagrapandey2852/Alternative-Data-Signal-Extractor)** ⭐ 0 · None _(updated 2026-06-13)_
  📡 Alternative data research platform that extracts signals from web traffic, job postings, patent filings, and app store reviews. Performs feature engineering, statistical testing, factor analysis, an

- **[SHUREEEE/multi-factor-alpha-platform](https://github.com/SHUREEEE/multi-factor-alpha-platform)** ⭐ 0 · Python _(updated 2026-06-13)_
  Built a research-complete multi-factor equity platform with honest diagnostics, gross/net separation, and fail-closed attribution.

- **[arrearsstocking863/hedgevision](https://github.com/arrearsstocking863/hedgevision)** ⭐ 0 · None _(updated 2026-06-15)_
  Build and backtest statistical arbitrage strategies with a local-first Python and React trading platform for cointegrated pairs, paper trading, and scaling

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-06-15)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[NavnoorBawa/russell3000-pairs-trading](https://github.com/NavnoorBawa/russell3000-pairs-trading)** ⭐ 1 · Python _(updated 2026-06-15)_
  Russell 3000 statistical arbitrage research system: Kalman spreads, cointegration pair selection, regime gating, walk-forward validation, and a controlled ML ablation.

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-06-15)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[steve-ongera/X-Dollar-Printer](https://github.com/steve-ongera/X-Dollar-Printer)** ⭐ 0 · CSS _(updated 2026-06-14)_
  A binary trading platform clone built with Django REST Framework and React Vite. Users can trade binary options (Odd/Even, Over/Under), deposit and withdraw via M-Pesa, and monitor live chart activity

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 48 · Python _(updated 2026-06-12)_
  A stock/futures auto trading framework using Shioaji API

## 4. Perplexity Strategy Synthesis
For a **$100–$1,000** retail account, the most actionable systematic approaches are the ones that keep turnover low, use liquid instruments, and define risk per trade tightly. The best fit from your list is usually **crypto trend-following with regime filters**, then a **pairs-trading basket in equities**, while **options tail hedges** are generally the hardest to make *cheap* and meaningful in such a small account because contract costs eat a large share of capital. The search results you provided are mostly generic trading-education pieces rather than the recent papers, Substacks, or Twitter threads you requested, so I can give you a practical framework but not responsibly claim “right now” alpha from those sources alone.[1][2][3][4][5]

- **Crypto momentum with regime filters**  
  - **Best use case:** small accounts that can trade spot or very small perpetual positions on liquid majors like BTC and ETH. The generic momentum/trend-following setup described in the results is to trade in the direction of higher-timeframe structure, use moving-average or higher-high/higher-low filters, and exit when momentum fades.[1][6][7]  
  - **Time horizon:** **1–20 trading days**; this is the sweet spot for retail accounts because it avoids noisy intraday execution and still captures trend continuation.[1][3][5]  
  - **Entry rules:**  
    - Trade only when the higher timeframe is in an **uptrend** or **downtrend** rather than consolidation.[6]  
    - For longs, require price above a rising **20-day** and **50-day** moving average, or a positive slope in a momentum measure such as 10-day rate of change; the results explicitly mention moving averages, higher highs/lows, MACD, and ROC as valid trend filters.[1]  
    - Add a **regime filter** such as “only long when BTC is above its 200-day moving average” or “only trade when 20-day realized volatility is above its 6-month median,” which is a common inference from trend-filtered momentum systems but is not directly stated in the provided sources.[1][6]  
  - **Exit rules:**  
    - Initial stop below the most recent swing low for longs, or above the swing high for shorts.[1][7]  
    - Take partial profits into strength and use a trailing stop as momentum decays.[1][7]  
    - A practical mechanical exit is a close below the 10-day or 20-day EMA, whichever is tighter for the timeframe; that is an implementation choice, not directly from the sources.  
  - **Position sizing:**  
    - Risk **0.5%–1.0% of account equity per trade**.[3][4]  
    - For a $500 account, that means risking about $2.50–$5 per trade; for a $1,000 account, $5–$10 per trade.[3][4]  
    - In practice, this usually means a very small spot allocation or micro-perpetual size because stops must be wide enough to avoid noise.  
  - **Crowding/degradation:**  
    - The provided sources do not show evidence that this specific setup has degraded in the last 6 months, but generic momentum/trend-following is widely crowded in large-cap assets; the biggest retail edge comes from using **regime filters** and avoiding chop, not from unfiltered breakout buying.[1][5][6]

- **Equity pair trading**  
  - **Best use case:** small accounts that can hold a few shares or fractional shares in liquid U.S. equities or ETFs; pairs trading is attractive because it is market-neutral in concept and can reduce directional risk. None of the provided results are real pair-trading papers, so this section is mainly a robust implementation template rather than a sourced “new” edge.  
  - **Time horizon:** **3–30 trading days** for mean reversion; shorter horizons tend to get hit by transaction costs unless you have very low commissions and tight spreads.  
  - **Entry rules:**  
    - Build pairs from highly correlated names in the same industry, then trade the **spread** when it deviates by roughly **2 standard deviations** from its rolling mean; this is the classi

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-06-15 via Conway's auto-publisher.*
