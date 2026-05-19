# Trading Nightly Research Brief — 2026-05-19

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-05-19T02:31:49, run time 21.8s._

## 1. Self-Analysis (Conway Trade Log)
```json
{
  "total_trades_logged": 68,
  "trades_last_7d": 32,
  "top_symbols_7d": [
    [
      "ZEC/USDC",
      10
    ],
    [
      "DOGE/USDC",
      9
    ],
    [
      "INJ/USDC",
      8
    ],
    [
      "BTC/USDC",
      5
    ]
  ],
  "side_breakdown_7d": {
    "buy": 15,
    "sell": 17
  }
}
```

## 2. arXiv Papers (Last 60 Days)
- **DashAttention: Differentiable and Adaptive Sparse Hierarchical Attention** _(quantitative trading strategy)_
  [2026-05-18](https://arxiv.org/abs/2605.18753v1)
  Current hierarchical attention methods, such as NSA and InfLLMv2, select the top-k relevant key-value (KV) blocks based on coarse attention scores and subsequently apply fine-grained softmax attention on the selected tokens. However, the top-k operation assumes the number of relevant tokens for any query is fixed and it precludes the gradient flow between the sparse and dense stages. In this work,

- **ESI-Bench: Towards Embodied Spatial Intelligence that Closes the Perception-Action Loop** _(quantitative trading strategy)_
  [2026-05-18](https://arxiv.org/abs/2605.18746v1)
  Spatial intelligence unfolds through a perception-action loop: agents act to acquire observations, and reason about how observations vary as a function of action. Rather than passively processing what is seen, they actively uncover what is unseen - occluded structure, dynamics, containment, and functionality that cannot be resolved from passive sensing alone. We move beyond prior formulations of s

- **SURGE: Approximation-free Training Free Particle Filter for Diffusion Surrogate** _(quantitative trading strategy)_
  [2026-05-18](https://arxiv.org/abs/2605.18745v1)
  Diffusion-based generative models increasingly rely on inference-time guidance, adding a drift term or reweighting mixture of experts, to improve sample quality on task-specific objectives. However, most existing techniques require repeated score or gradient evaluations, introducing bias, high computational overhead, or both. We introduce \texttt{URGE}, Unbiased Resampling via Girsanov Estimation,

- **What Does the AI Doctor Value? Auditing Pluralism in the Clinical Ethics of Language Models** _(momentum crash risk)_
  [2026-05-18](https://arxiv.org/abs/2605.18738v1)
  Medicine is inherently pluralistic. Principles such as autonomy, beneficence, nonmaleficence, and justice routinely conflict, and such ethical dilemmas often sharply divide reasonable physicians. Good clinical practice navigates these tensions in concert with each patient's values rather than imposing a single ethical stance. The ethical values that large language models bring to medical advice, h

- **Bayesian Sparse Regression for Microbiome-Metabolite Data Integration** _(momentum crash risk)_
  [2026-05-18](https://arxiv.org/abs/2605.18728v1)
  Numerous studies have shown that microbial metabolites, which represent the products of bacteria in the human gut, play a key role in shaping cancer risk and response to treatment. However, metabolite data typically contain a large proportion of missing values, which may result from either low abundance or technical challenges in data processing. Moreover, given the compositionality of microbiome 

- **Learning Normal Representations for Blood Biomarkers** _(momentum crash risk)_
  [2026-05-18](https://arxiv.org/abs/2605.18701v1)
  Blood-based biomarkers underpin clinical diagnosis and management, yet their interpretation relies largely on fixed population reference intervals that ignore stable, intra-patient variability. As such, population-based interpretation can mask meaningful deviation from an individual's baseline, risking delayed disease detection. To remedy this, there have been increasing efforts to personalize blo

- **Traditional statistical representations outperform generative AI in identifying expert peer reviewers** _(mean reversion statistical arbitrage)_
  [2026-05-18](https://arxiv.org/abs/2605.18752v1)
  The exponential growth of scientific submissions has strained the peer review system. Despite the rapidly expanding global pool of researchers, this unprecedented scale has rendered the previous approach of manual expert identification unfeasible. Therefore, institutions have naturally turned to Large Language Models (LLMs) to automate intricate processes like expert reviewer identification. Howev

- **Kernel Characterisations of Stochastic Orders Within Parametric Density Families** _(mean reversion statistical arbitrage)_
  [2026-05-18](https://arxiv.org/abs/2605.18751v1)
  We develop kernel criteria for the likelihood-ratio, hazard-rate, usual stochastic, and relative log-concavity orders in parametric families of univariate probability laws with densities. The score is the derivative of the log density with respect to the parameter, and a kernel equals the score up to an additive term depending only on the parameter. Kernel monotonicity gives likelihood-ratio order

- **A universal framework to identify eccentric binary mergers: GW200105 case study** _(mean reversion statistical arbitrage)_
  [2026-05-18](https://arxiv.org/abs/2605.18742v1)
  Orbital eccentricity in gravitational-wave signals from merging compact object binaries is a powerful indicator of their formation channel. Several binary black hole mergers and a neutron star--black hole merger have been reported to exhibit signs of eccentricity, but which events are identified and the significance of the eccentricity differs between studies. Measurements of eccentricity can chan

- **DashAttention: Differentiable and Adaptive Sparse Hierarchical Attention** _(regime detection market)_
  [2026-05-18](https://arxiv.org/abs/2605.18753v1)
  Current hierarchical attention methods, such as NSA and InfLLMv2, select the top-k relevant key-value (KV) blocks based on coarse attention scores and subsequently apply fine-grained softmax attention on the selected tokens. However, the top-k operation assumes the number of relevant tokens for any query is fixed and it precludes the gradient flow between the sparse and dense stages. In this work,

- **A universal framework to identify eccentric binary mergers: GW200105 case study** _(regime detection market)_
  [2026-05-18](https://arxiv.org/abs/2605.18742v1)
  Orbital eccentricity in gravitational-wave signals from merging compact object binaries is a powerful indicator of their formation channel. Several binary black hole mergers and a neutron star--black hole merger have been reported to exhibit signs of eccentricity, but which events are identified and the significance of the eccentricity differs between studies. Measurements of eccentricity can chan

- **Quantum Shannon theory made robust: a tale of three protocols for almost i.i.d. sources** _(regime detection market)_
  [2026-05-18](https://arxiv.org/abs/2605.18726v1)
  The asymptotic rates of information-theoretic protocols - including error exponents, compression rates, and channel capacities - are traditionally defined under the idealised assumption that the underlying resource (state or channel) is independent and identically distributed (i.i.d.). Somewhat surprisingly, even slight departures from the exact i.i.d. structure can lead to a drastic breakdown of 

- **Can These Views Be One Scene? Evaluating Multiview 3D Consistency when 3D Foundation Models Hallucinate** _(deep learning volatility forecasting)_
  [2026-05-18](https://arxiv.org/abs/2605.18754v1)
  Multiview 3D evaluation assumes that the images being scored are observations of one static 3D scene. This assumption can fail in NVS and sparse-view reconstruction: inputs or generated outputs may contain artifacts, outlier frames, repeated views, or noise, yet still receive high 3D consistency scores. Existing reference-based metrics require ground truth, while ground-truth-free metrics such as 

- **DashAttention: Differentiable and Adaptive Sparse Hierarchical Attention** _(deep learning volatility forecasting)_
  [2026-05-18](https://arxiv.org/abs/2605.18753v1)
  Current hierarchical attention methods, such as NSA and InfLLMv2, select the top-k relevant key-value (KV) blocks based on coarse attention scores and subsequently apply fine-grained softmax attention on the selected tokens. However, the top-k operation assumes the number of relevant tokens for any query is fixed and it precludes the gradient flow between the sparse and dense stages. In this work,

- **A Readiness-Driven Runtime for Pipeline-Parallel Training under Runtime Variability** _(deep learning volatility forecasting)_
  [2026-05-18](https://arxiv.org/abs/2605.18750v1)
  Pipeline parallelism is a key technique for scaling large-model training, but modern workloads exhibit runtime variability in computation and communication. Existing pipeline systems typically consume static, profiled, or adaptively generated schedules as pre-committed execution orders. When realized task readiness diverges from the pre-committed order, stages may wait for not-yet-ready work even 

- **Can These Views Be One Scene? Evaluating Multiview 3D Consistency when 3D Foundation Models Hallucinate** _(transformer financial time series)_
  [2026-05-18](https://arxiv.org/abs/2605.18754v1)
  Multiview 3D evaluation assumes that the images being scored are observations of one static 3D scene. This assumption can fail in NVS and sparse-view reconstruction: inputs or generated outputs may contain artifacts, outlier frames, repeated views, or noise, yet still receive high 3D consistency scores. Existing reference-based metrics require ground truth, while ground-truth-free metrics such as 

- **DashAttention: Differentiable and Adaptive Sparse Hierarchical Attention** _(transformer financial time series)_
  [2026-05-18](https://arxiv.org/abs/2605.18753v1)
  Current hierarchical attention methods, such as NSA and InfLLMv2, select the top-k relevant key-value (KV) blocks based on coarse attention scores and subsequently apply fine-grained softmax attention on the selected tokens. However, the top-k operation assumes the number of relevant tokens for any query is fixed and it precludes the gradient flow between the sparse and dense stages. In this work,

- **Traditional statistical representations outperform generative AI in identifying expert peer reviewers** _(transformer financial time series)_
  [2026-05-18](https://arxiv.org/abs/2605.18752v1)
  The exponential growth of scientific submissions has strained the peer review system. Despite the rapidly expanding global pool of researchers, this unprecedented scale has rendered the previous approach of manual expert identification unfeasible. Therefore, institutions have naturally turned to Large Language Models (LLMs) to automate intricate processes like expert reviewer identification. Howev

- **Can These Views Be One Scene? Evaluating Multiview 3D Consistency when 3D Foundation Models Hallucinate** _(reinforcement learning portfolio)_
  [2026-05-18](https://arxiv.org/abs/2605.18754v1)
  Multiview 3D evaluation assumes that the images being scored are observations of one static 3D scene. This assumption can fail in NVS and sparse-view reconstruction: inputs or generated outputs may contain artifacts, outlier frames, repeated views, or noise, yet still receive high 3D consistency scores. Existing reference-based metrics require ground truth, while ground-truth-free metrics such as 

- **DashAttention: Differentiable and Adaptive Sparse Hierarchical Attention** _(reinforcement learning portfolio)_
  [2026-05-18](https://arxiv.org/abs/2605.18753v1)
  Current hierarchical attention methods, such as NSA and InfLLMv2, select the top-k relevant key-value (KV) blocks based on coarse attention scores and subsequently apply fine-grained softmax attention on the selected tokens. However, the top-k operation assumes the number of relevant tokens for any query is fixed and it precludes the gradient flow between the sparse and dense stages. In this work,

- **A Readiness-Driven Runtime for Pipeline-Parallel Training under Runtime Variability** _(reinforcement learning portfolio)_
  [2026-05-18](https://arxiv.org/abs/2605.18750v1)
  Pipeline parallelism is a key technique for scaling large-model training, but modern workloads exhibit runtime variability in computation and communication. Existing pipeline systems typically consume static, profiled, or adaptively generated schedules as pre-committed execution orders. When realized task readiness diverges from the pre-committed order, stages may wait for not-yet-ready work even 

- **WaveDriver: a Laser Guide Star AO System for HWO** _(cryptocurrency trading)_
  [2026-05-18](https://arxiv.org/abs/2605.18723v1)
  Habitable Worlds Observatory (HWO) presents a key challenge for technology development in the coming years, requiring a $&gt;$ $100\times$ more stable system than \textit{JWST}. WaveDriver is a concept for a laser guide star spacecraft coupled to an adaptive optics (AO) system onboard HWO that would enable HWO to reach its picometer-level wavefront stability requirements while relaxing other HWO s

- **A Large-Scale Study on the Accuracy vs Cost Trade-offs of Training and Evaluation Settings in Fine-Grained Image Recognition** _(cryptocurrency trading)_
  [2026-05-18](https://arxiv.org/abs/2605.18700v1)
  Prior work on fine-grained image recognition (FGIR) has established the importance of the backbone selection, but has neglected the accuracy-vs-cost trade-offs under different training and evaluation settings. In this work we conduct a large-scale study with over 2000 experiments across 6 training and evaluation settings, 9 pretrained backbones, and 17 datasets. Preliminary observations on the eff

- **GIM: Evaluating models via tasks that integrate multiple cognitive domains** _(cryptocurrency trading)_
  [2026-05-18](https://arxiv.org/abs/2605.18663v1)
  As LLM benchmarks saturate, the evaluation community has pursued two strategies to increase difficulty: escalating knowledge demands (GPQA, HLE) or removing knowledge entirely in favor of abstract reasoning (ARC-AGI). The first conflates memorization with capability; the second divorces reasoning from the practical contexts in which it matters. We take a different approach. The Grounded Integratio

- **Pulse profile modelling of the 2024 outburst of the accreting millisecond pulsar SRGA J144459.2-604207** _(options volatility surface)_
  [2026-05-18](https://arxiv.org/abs/2605.18731v1)
  Pulse profile modelling via relativistic ray-tracing can constrain the system parameters of neutron stars, notably their mass and radius. Among these objects, accreting millisecond pulsars (AMPs) are promising targets, because they are bright in X-rays and their potentially polarized radiation can lead to complementary constraints on the emission geometry. We perform combined analysis of NICER and

- **Nested nodal loops for sums of Laplace eigenfunctions** _(options volatility surface)_
  [2026-05-18](https://arxiv.org/abs/2605.18705v1)
  We study nested loops in zero sets of sums of Laplace eigenfunctions on closed surfaces. In the real-analytic category, answering a question of Logunov, we prove a uniform bound for the number of rooted double nests in terms of the surface, the root, and the spectral cutoff. We show that this analyticity hypothesis is sharp: on a smooth sphere, a linear combination of eigenfunctions with eigenvalu

- **Reversa: A Reverse Documentation Engineering Framework for Converting Legacy Software into Operational Specifications for AI Agents** _(options volatility surface)_
  [2026-05-18](https://arxiv.org/abs/2605.18684v1)
  Legacy systems concentrate business rules, architectural decisions, and operational exceptions that often remain implicit in code, data, configuration, and   maintenance practices. At the same time, language-model-based coding agents depend on reliable context, correctness criteria, and behavioral contracts to   modify real systems with lower risk. This paper presents Reversa, a reverse documentat

- **Kernel Characterisations of Stochastic Orders Within Parametric Density Families** _(factor investing alpha)_
  [2026-05-18](https://arxiv.org/abs/2605.18751v1)
  We develop kernel criteria for the likelihood-ratio, hazard-rate, usual stochastic, and relative log-concavity orders in parametric families of univariate probability laws with densities. The score is the derivative of the log density with respect to the parameter, and a kernel equals the score up to an additive term depending only on the parameter. Kernel monotonicity gives likelihood-ratio order

- **A universal framework to identify eccentric binary mergers: GW200105 case study** _(factor investing alpha)_
  [2026-05-18](https://arxiv.org/abs/2605.18742v1)
  Orbital eccentricity in gravitational-wave signals from merging compact object binaries is a powerful indicator of their formation channel. Several binary black hole mergers and a neutron star--black hole merger have been reported to exhibit signs of eccentricity, but which events are identified and the significance of the eccentricity differs between studies. Measurements of eccentricity can chan

- **Dynamic MRI Reconstruction Via Dual Deep Priors and Low-Rank Plus Sparse Modeling** _(factor investing alpha)_
  [2026-05-18](https://arxiv.org/abs/2605.18709v1)
  Dynamic MRI reconstruction from undersampled measurements is a challenging inverse problem that requires preserving both spatial reconstruction quality and temporal consistency across the frames of the cine series. While recent learning-based approaches achieve strong performance, they heavily rely on large training, mostly fully sampled, datasets, and may otherwise generalize poorly. In contrast,

## 3. GitHub Repos (Recently Updated)
- **[RafaEngineer/strapsim_portfolio_similarity_metric](https://github.com/RafaEngineer/strapsim_portfolio_similarity_metric)** ⭐ 1 · PHP _(updated 2026-05-19)_
  📊 Calculate portfolio similarity metrics to enhance ETF alignment and optimize trading strategies in quantitative finance.

- **[HaSerZin/trade_political_distance_wto](https://github.com/HaSerZin/trade_political_distance_wto)** ⭐ 2 · Jupyter Notebook _(updated 2026-05-19)_
  🌍 Model political distance and trade dynamics using a quantitative framework to enhance understanding of international trade relationships.

- **[Leonard-Don/quant-trading-system](https://github.com/Leonard-Don/quant-trading-system)** ⭐ 0 · Python _(updated 2026-05-19)_
  FastAPI + React quantitative research workspace for backtesting, realtime monitoring, industry heatmaps, and cross-market experiments.

- **[opop753/AI-Powered-Crypto-Trading-Bot](https://github.com/opop753/AI-Powered-Crypto-Trading-Bot)** ⭐ 2 · JavaScript _(updated 2026-05-19)_
  🤖 Power your trading with an AI-driven crypto bot that delivers live data, trading strategies, charts, news, and market session timelines.

- **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance)** ⭐ 11 · Python _(updated 2026-05-19)_
  Easily build, backtest and deploy your algo in just a few lines of code. Trade stocks, cryptos, and forex across exchanges one package.

- **[ankit6868/autotrade-hub](https://github.com/ankit6868/autotrade-hub)** ⭐ 0 · Python _(updated 2026-05-19)_
  AI-powered crypto trading automation bot with paper/live trading, backtesting, TradingView webhooks and risk monitoring

- **[magikgmo4-ui/opt-trading](https://github.com/magikgmo4-ui/opt-trading)** ⭐ 0 · Python _(updated 2026-05-19)_
  Trading algorithms and strategies

- **[astarek1983/street-algo-trader](https://github.com/astarek1983/street-algo-trader)** ⭐ 1 · Jupyter Notebook _(updated 2026-05-19)_
  🚀 Implement algorithmic trading strategies for a Jane Street-style exchange, featuring market-making, arbitrage, and momentum signals.

- **[Anna-007-tech/algorithmic-trading-ai](https://github.com/Anna-007-tech/algorithmic-trading-ai)** ⭐ 2 · None _(updated 2026-05-19)_
  📈 Explore AI-driven trading strategies through data analysis of forex and crypto volatility using PCA, K-means, and neural networks.

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 0 · None _(updated 2026-05-19)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[zzzhhn/alpha-agent](https://github.com/zzzhhn/alpha-agent)** ⭐ 0 · Python _(updated 2026-05-19)_
  LLM-Powered Alpha Research Agent — multi-agent system for automated quantitative factor discovery on A-share markets

- **[husainm97/quant-lab-alpha](https://github.com/husainm97/quant-lab-alpha)** ⭐ 32 · Python _(updated 2026-05-17)_
  Open-source investment analytics platform bridging academic research and retail finance. Features include portfolio risk decomposition [Fama-French Five Factor Model], retirement sustainability modeli

- **[arrearsstocking863/hedgevision](https://github.com/arrearsstocking863/hedgevision)** ⭐ 0 · None _(updated 2026-05-19)_
  Build and backtest statistical arbitrage strategies with a local-first Python and React trading platform for cointegrated pairs, paper trading, and scaling

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-05-19)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[jergusnadasky/pairs-trading-statarb](https://github.com/jergusnadasky/pairs-trading-statarb)** ⭐ 0 · Python _(updated 2026-05-19)_
  An automated Statistical Arbitrage backtesting engine and Streamlit dashboard using Engle-Granger cointegration and Z-score mean-reversion.

- **[ernestprovo23/tradebot_opensource](https://github.com/ernestprovo23/tradebot_opensource)** ⭐ 1 · Python _(updated 2026-05-17)_
  Auto Trade Bot - An advanced algorithmic trading framework incorporating options analytics, dynamic risk management, and portfolio optimization. Built with Python, it enables automated trading through

- **[henryhuangh/wealthsimple-python](https://github.com/henryhuangh/wealthsimple-python)** ⭐ 11 · Python _(updated 2026-05-18)_
  Wealthsimple trade API library for python based on the new wealthsimple graphql framework

- **[HassanKhal1d/regime-first-options](https://github.com/HassanKhal1d/regime-first-options)** ⭐ 0 · Python _(updated 2026-05-10)_
  Regime-aware options trading framework: dynamics diagnosis precedes pricing, calibration carries uncertainty (block-bootstrap SEs), pricing returns a fair-value distribution, and position sizing scale

## 4. Perplexity Strategy Synthesis
Below is a practical, small-account-focused shortlist of **systematic strategies that are still actionable around April 2026**. I’ll keep this oriented toward retail traders with **$100–$1,000**, where **fees, slippage, and simplicity matter more than cleverness**.

A quick caveat: I can’t verify live market conditions or “today’s” option prices from here, so for the options section I’ll describe **what tends to be cheap when realized vol is low vs implied vol** and how to screen it, rather than naming a contract that may have already repriced.

---

## 1) Crypto momentum with regime filters
**Best fit for small accounts:** yes, because you can trade micro-sizing and crypto is open 24/7.  
**Main risk:** regime changes are brutal; momentum works until it doesn’t.

### A. Simple trend-following breakout with regime filter
This is the most actionable “retail systematic” crypto strategy.

#### Universe
- Large, liquid coins only:
  - BTC, ETH, SOL, maybe XRP/BNB depending on venue
- Avoid obscure alts unless you can tolerate huge slippage

#### Regime filter
Trade only when the market is in a favorable trend regime.

Concrete filter:
- **Bull regime:** price above **200-day SMA** on daily chart
- Optional stronger filter:
  - **50-day SMA > 200-day SMA**
  - and 30-day realized volatility not exploding above its 90th percentile

If BTC is below its 200D, reduce size or only use mean reversion, not breakout momentum.

#### Entry
Use a **higher-timeframe breakout + volume confirmation**:
- Daily close above **20-day high**
- Volume on breakout day > **1.5x 20-day average volume**
- Enter next bar or on a shallow intraday retest

Alternative for more frequent signals:
- 4H close above **20-bar high** when daily regime is bullish

#### Exit
- Hard stop: **2 ATR below entry** or below breakout level, whichever is tighter
- Take profit:
  - partial at **2R**
  - trail remainder using **10-day low** or **2 ATR trailing stop**
- Time stop:
  - if trade hasn’t moved after **5–7 days**, exit

#### Position sizing
For a $100–$1,000 account:
- Risk per trade: **0.5% to 1%** of equity
- In practice:
  - $100 acct: risk **$0.50–$1**
  - $1,000 acct: risk **$5–$10**
- Because crypto is volatile, use very small notional if the stop is wide

#### Why this is still actionable
Crypto momentum persists, but only when you filter for trend regime. This is consistent with the general findings in trend-following literature and the practical “trade only with the higher-timeframe trend” advice seen across trader research and systematic writeups.

#### Where this idea aligns with recent/public discussion
- **Setup4Alpha Substack** has been pushing the “stack your edges” idea: combine one signal with a regime/timing filter rather than trading raw momentum alone.
- The broad momentum/breakout concepts also align with the retail-friendly summary in the **Amerisave** guide you provided: momentum, breakouts, volume spikes, and trend context.

#### Degradation risk
- **Crowding has increased** in very obvious breakout levels on BTC/ETH.
- The edge tends to degrade if you chase breakouts without regime confirmation or if you trade illiquid alts.

---

### B. Pullback-in-trend momentum
This often works better than pure breakout chasing.

#### Entry
In a bullish regime:
- Daily trend up: price above 200D
- Pullback into:
  - **20EMA to 50EMA zone**
  - or a prior **fair value gap / support area**
- Enter after a reversal candle or reclaim of short-term high

#### Exit
- Stop under pullback low
- Target prior swing high or **2R**
- Trail with 10EMA after a strong move

#### Time horizon
- Typically **2–10 days**

#### Position sizing
- Risk **0.5–1%** per trade


---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-05-19 via Conway's auto-publisher.*
