# Trading Nightly Research Brief — 2026-07-01

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-07-01T02:31:18, run time 23.5s._

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
- **The online monotone array completion problem** _(quantitative trading strategy)_
  [2026-06-30](https://arxiv.org/abs/2606.32015v1)
  Consider the following online filling game. An array of length $n$ is initially empty. At each time step one observes an independent sample from $\mathrm{Unif}[0,1]$ and must either discard it or place it irrevocably into an empty position of the array, while preserving the constraint that the occupied entries are non-decreasing from left to right. Among all possible strategies, what is the optima

- **Random Reshuffling Dominates Stochastic Gradient Descent** _(quantitative trading strategy)_
  [2026-06-30](https://arxiv.org/abs/2606.32005v1)
  Stochastic Gradient Descent ($\textsf{SGD}$) is one of the most classical optimization algorithms with favorable theoretical guarantees, yet the practical implementation of $\textsf{SGD}$ differs subtly from its well-known form and is often referred to as Shuffling Stochastic Gradient Descent ($\textsf{Shuffling SGD}$). A particularly popular strategy in $\textsf{Shuffling SGD}$ is Random Reshuffl

- **On the Comparison of Reinforcement Learning and Adaptive Control for Linear Systems under Packet Loss and Uncertainty** _(quantitative trading strategy)_
  [2026-06-30](https://arxiv.org/abs/2606.32003v1)
  This paper presents a comparative study between Adaptive Quantized Control (AQC) and Deep Deterministic Policy Gradient (DDPG) reinforcement learning for uncertain linear systems with input quantization over communication channels subject to packet loss. The considered setting also includes dynamic switching from a nominal unstable system to a more unstable one during operation. The AQC is designe

- **Radiation-pressure instability is an artifact of constant-$α$ closure** _(momentum crash risk)_
  [2026-06-30](https://arxiv.org/abs/2606.31998v1)
  The standard $α$-disk formalism parametrizes turbulent angular momentum transport through a dimensionless coefficient $α$, assumed to be spatially and thermodynamically invariant. While analytically convenient, this assumption leads to the well-known thermal and viscous instabilities in radiation-pressure dominated (RPD) regions. We show that this instability is not the consequence of radiation pr

- **Delegation Rights: Property, Agency, and Investment Incentives in the Age of AI Agents** _(momentum crash risk)_
  [2026-06-30](https://arxiv.org/abs/2606.31935v1)
  AI agents increasingly operate inside digital accounts by exercising privileges that users already hold, raising a new control question: whether an existing account entitlement must be exercised manually or may be exercised through a user-authorized automated proxy. We define \emph{delegation rights} as the revocable, identity-preserving, scope-limited, and mode-specific authority of an account ho

- **Theory of Mind and Persuasion Beyond Conversation: Assessing the Capacity of LLMs to Induce Belief States via Planning and Action** _(momentum crash risk)_
  [2026-06-30](https://arxiv.org/abs/2606.31916v1)
  Theory of Mind (ToM) benchmarks for Large Language Models (LLMs) typically rely on passive question-answering formats, but the deployment of LLMs in increasingly agentic and autonomous forms demands new evaluations. In this paper we evaluate an agent's ability to induce specific belief states in other agents by taking actions rather than using conversational persuasion, a capability we call Non-Co

- **Finite-range EFT for the $E1$ strength distribution of ${}^6$He** _(mean reversion statistical arbitrage)_
  [2026-06-30](https://arxiv.org/abs/2606.32037v1)
  Halo effective field theory (Halo EFT) is a powerful tool to describe halo nuclei and predict low-energy observables with quantified uncertainties. However, in the case that there is a leading-order interaction determined by two or more effective-range parameters, such as the $^2P_{3/2}$ $nα$ interaction in $^6$He, the standard implementation in the dimer formalism leads to an energy-dependent int

- **Exactly solvable non-unitary conformal interfaces in unitary CFTs** _(mean reversion statistical arbitrage)_
  [2026-06-30](https://arxiv.org/abs/2606.32035v1)
  We construct directly on the lattice a class of non-unitary interfaces that are both exactly conformal and exactly solvable, and establish their corresponding boundary and interface conformal field theory (CFT) descriptions. The construction is obtained by analytically continuing the scattering data of known exact unitary conformal interfaces on the lattice, yielding an $SL(2,\mathbb C)$-parametri

- **SemRF: A Semantic Reference Frame for Residual-Stream Dynamics in Language Models** _(mean reversion statistical arbitrage)_
  [2026-06-30](https://arxiv.org/abs/2606.32022v1)
  Residual-stream analysis asks how language-model computation evolves across depth, but intermediate decoding requires comparable readout coordinates across layers. If embedding anchors and unembedding readout disagree on the chosen span, apparent motion may reflect measurement drift rather than computation. We introduce \emph{Semantic Reference Frames} (SemRF), an anchor-based formalism separating

- **When LLMs Read Tables Carelessly: Measuring and Reducing Data Referencing Errors** _(regime detection market)_
  [2026-06-30](https://arxiv.org/abs/2606.32029v1)
  While large language models (LLMs) perform well on table tasks, they still make data referencing errors (DREs), i.e., incorrectly citing or omitting table values, despite understanding the table structure. Beyond final-answer accuracy, DREs directly compromise the correctness and reliability of intermediate reasoning steps. Yet prior studies have only offered limited, small-scale analyses. In this

- **Flexibility as a Universal Nature-Inspired Mechanism for Thrust Enhancement** _(regime detection market)_
  [2026-06-30](https://arxiv.org/abs/2606.32021v1)
  Nature has equipped jet-propelled swimmers with flexible nozzles that outperform rigid ones, yet the origin of this advantage has remained unexplained. By tracking where and when energy is exchanged between fluid and structure, three-dimensional numerical simulations resolve the underlying mechanism: a standing-wave response of the nozzle, in which the structure dilates and then recoils synchronou

- **Cross-Space Distillation: Teaching One-Step Students with Modern Diffusion Teachers** _(regime detection market)_
  [2026-06-30](https://arxiv.org/abs/2606.32020v1)
  Modern one-step diffusion models achieve impressive quality through distribution-based timestep distillation. Yet, they rely on a critical assumption: Teacher and Student must inhabit the same latent space. This Shared-Space constraint prevents knowledge transfer from modern high-capacity Teachers (e.g., SD 3.5 and Flux) into compact, deployment-friendly Students such as SD 1.5, whose latent resol

- **GEAR: Guided End-to-End AutoRegression for Image Synthesis** _(deep learning volatility forecasting)_
  [2026-06-30](https://arxiv.org/abs/2606.32039v1)
  Visual generative models are typically trained in two stages. A tokenizer is first trained for reconstruction and then frozen, after which a generator is trained on its discrete indices or continuous latents. This decoupling leaves the tokenizer unaware of what the generator finds easy to model. We present GEAR (Guided End-to-end AutoRegression), which trains a vector-quantized (VQ) tokenizer and 

- **Introspective Coupling: Self-Explanation Training Tracks Behavioral Change Despite Fixed Supervision** _(deep learning volatility forecasting)_
  [2026-06-30](https://arxiv.org/abs/2606.32038v1)
  When does training language models (LMs) to generate explanations of their predictions yield faithful introspection, rather than superficial imitation? We study LMs trained to explain which features of their inputs influenced their behavior, using models' counterfactual behavior on modified inputs as supervision. Surprisingly, we find that LMs trained on fixed counterfactual explanations derived f

- **PointSplat: Compact Gaussian Splatting via Human-Centric Prediction** _(deep learning volatility forecasting)_
  [2026-06-30](https://arxiv.org/abs/2606.32036v1)
  Producing 3D human representations from input views on the fly is essential for immersive live streaming systems, where representation compactness is as critical as high fidelity given limited computational power and transmission bandwidth. Although recent feed-forward reconstruction methods achieve impressive quality through the view-centric prediction of 3D representations, they repeatedly encod

- **PointSplat: Compact Gaussian Splatting via Human-Centric Prediction** _(transformer financial time series)_
  [2026-06-30](https://arxiv.org/abs/2606.32036v1)
  Producing 3D human representations from input views on the fly is essential for immersive live streaming systems, where representation compactness is as critical as high fidelity given limited computational power and transmission bandwidth. Although recent feed-forward reconstruction methods achieve impressive quality through the view-centric prediction of 3D representations, they repeatedly encod

- **SpheRoPE: Zero-Shot Optimization-Free 360 Panorama Generation with Spherical RoPE** _(transformer financial time series)_
  [2026-06-30](https://arxiv.org/abs/2606.32033v1)
  We present a zero-shot, training-free and optimization-free framework for generating 360 panoramic images and videos by directly injecting spherical priors into pre-trained diffusion transformers. Existing methods either rely on costly fine-tuning on scarce panoramic data that limits generalization, or leverage multi-step optimization that incurs prohibitive inference latency. We observe that cont

- **Simulation of Two-qubit Gate Variability and Fidelity of Spin Qubits Built on Nanosheet Technology** _(transformer financial time series)_
  [2026-06-30](https://arxiv.org/abs/2606.32030v1)
  Silicon spin qubits are promising for large-scale quantum-computer integration because they can fully leverage the well-developed semiconductor infrastructure. However, the low fidelity of two-qubit entanglement gates remains a key barrier to large-scale integrations. Recent simulations of silicon spin-qubit two-qubit gates have been performed on silicon-on-insulator (SOI) platforms, while nanoshe

- **GEAR: Guided End-to-End AutoRegression for Image Synthesis** _(reinforcement learning portfolio)_
  [2026-06-30](https://arxiv.org/abs/2606.32039v1)
  Visual generative models are typically trained in two stages. A tokenizer is first trained for reconstruction and then frozen, after which a generator is trained on its discrete indices or continuous latents. This decoupling leaves the tokenizer unaware of what the generator finds easy to model. We present GEAR (Guided End-to-end AutoRegression), which trains a vector-quantized (VQ) tokenizer and 

- **Introspective Coupling: Self-Explanation Training Tracks Behavioral Change Despite Fixed Supervision** _(reinforcement learning portfolio)_
  [2026-06-30](https://arxiv.org/abs/2606.32038v1)
  When does training language models (LMs) to generate explanations of their predictions yield faithful introspection, rather than superficial imitation? We study LMs trained to explain which features of their inputs influenced their behavior, using models' counterfactual behavior on modified inputs as supervision. Surprisingly, we find that LMs trained on fixed counterfactual explanations derived f

- **PointSplat: Compact Gaussian Splatting via Human-Centric Prediction** _(reinforcement learning portfolio)_
  [2026-06-30](https://arxiv.org/abs/2606.32036v1)
  Producing 3D human representations from input views on the fly is essential for immersive live streaming systems, where representation compactness is as critical as high fidelity given limited computational power and transmission bandwidth. Although recent feed-forward reconstruction methods achieve impressive quality through the view-centric prediction of 3D representations, they repeatedly encod

- **On the Comparison of Reinforcement Learning and Adaptive Control for Linear Systems under Packet Loss and Uncertainty** _(cryptocurrency trading)_
  [2026-06-30](https://arxiv.org/abs/2606.32003v1)
  This paper presents a comparative study between Adaptive Quantized Control (AQC) and Deep Deterministic Policy Gradient (DDPG) reinforcement learning for uncertain linear systems with input quantization over communication channels subject to packet loss. The considered setting also includes dynamic switching from a nominal unstable system to a more unstable one during operation. The AQC is designe

- **Accelerating Conformal Prediction via Approximate Leave-One-Out** _(cryptocurrency trading)_
  [2026-06-30](https://arxiv.org/abs/2606.31915v1)
  While conformal prediction provides a general framework for uncertainty quantification in predictive inference, its application is often limited by computational cost. Recent methods, including Jackknife+ and Jackknife-minmax, achieve faster computation by trading a slight loss of efficiency relative to full conformal prediction, but still requires computing leave-one-out refits for all observatio

- **Trade-Offs in Decentralized Gigantic MIMO with Hard-Boundary Constraints** _(cryptocurrency trading)_
  [2026-06-30](https://arxiv.org/abs/2606.31911v1)
  To maintain the antenna apertures offered by 5G massive MIMO systems operating at the sub-6GHz band, known as FR1, 6G base stations (BSs) using the upper-mid band, FR3, should increase the number of antennas by a factor 4-8, giving rise to gigantic MIMO. This poses challenges in terms of processing complexity and interconnection bandwidth. The WAX framework, previously introduced for exploring tra

- **Competition and Anomalies Redux: Evidence from U.S. Auto Dealers** _(options volatility surface)_
  [2026-06-30](https://arxiv.org/abs/2606.32011v1)
  We examine a choice between bonus contracts offered to dealers of a U.S. auto manufacturer. In our data, dealers select the non-profit-maximizing option in 20 percent of observations, costing the mistaken dealers $18,453 per year on average. We examine how the propensity to make this mistake varies with competition, identified both cross-sectionally and within dealers over time. Both analyses show

- **Self-Study Reconsidered: The Hidden Fragility of Learning from Self-Generated QA** _(options volatility surface)_
  [2026-06-30](https://arxiv.org/abs/2606.32002v1)
  Language models are increasingly taught from synthetic question--answer (QA) supervision: a model generates questions about a document, answers them from the same text, and the resulting pairs are used to fine-tune, distill, or compress knowledge into another model. We show that this generation step is not neutral preprocessing. It is an implicit policy that both selects which evidence becomes tra

- **Planar-SfM: Camera Pose Estimation via Homography Graph Embeddings** _(options volatility surface)_
  [2026-06-30](https://arxiv.org/abs/2606.31979v1)
  Structure from Motion (SfM) systems traditionally struggle with planar scenes, where standard epipolar geometry-based methods become degenerate. Rather than viewing planar surfaces as a limitation, we propose a unified framework that leverages them as a source of geometric constraints. Our key insight is that each planar surface visible across multiple views provides an independent estimate of rel

- **Finite-range EFT for the $E1$ strength distribution of ${}^6$He** _(factor investing alpha)_
  [2026-06-30](https://arxiv.org/abs/2606.32037v1)
  Halo effective field theory (Halo EFT) is a powerful tool to describe halo nuclei and predict low-energy observables with quantified uncertainties. However, in the case that there is a leading-order interaction determined by two or more effective-range parameters, such as the $^2P_{3/2}$ $nα$ interaction in $^6$He, the standard implementation in the dimer formalism leads to an energy-dependent int

- **The sharp diagonal spectral correlation inequality on the discrete cube** _(factor investing alpha)_
  [2026-06-30](https://arxiv.org/abs/2606.32024v1)
  We prove the sharp diagonal spectral correlation conjecture of Friedgut, Kahn, Kalai and Keller, proposed in their Fourier-analytic approach to Chvátal's conjecture. For every pair of increasing Boolean functions $f,g:\{0,1\}^n\to\{0,1\}$, $$\mathrm{Cov}(f,g)\ge4\sum_{\varnothing\ne S\subseteq[n]}|S|\hat{f}(S)^2\hat{g}(S)^2.$$ Thus covariance controls the degree-weighted collision of the two nonco

- **Spatially Coupled MacKay-Neal/Hsu-Anastasopoulos CSS Codes Achieve the Quantum-Erasure Hashing Bound by Seeded BP Decoding** _(factor investing alpha)_
  [2026-06-30](https://arxiv.org/abs/2606.32001v1)
  In classical sparse-graph coding, spatial coupling is a mechanism by which belief-propagation (BP) decoding attains the maximum-a-posteriori (MAP) or area-threshold performance of the uncoupled system. Since MacKay-Neal/Hsu-Anastasopoulos (MN/HA) punctured sparse ensembles achieve capacity under MAP decoding, it is natural to ask whether spatially coupled MN/HA-type Calderbank-Shor-Steane (CSS) co

## 3. GitHub Repos (Recently Updated)
- **[cikafeee/algorithmic-trading-backtest](https://github.com/cikafeee/algorithmic-trading-backtest)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-01)_
  📊 Analyze and validate trading strategies with a high-performance backtesting engine using PySpark, processing thousands of backtests on real market data.

- **[11Bhavin/Quant_Trading_Portfolio-](https://github.com/11Bhavin/Quant_Trading_Portfolio-)** ⭐ 0 · None _(updated 2026-07-01)_
  📈 Build and backtest automated trading strategies using Python to enhance your quantitative finance skills and explore the financial markets.

- **[Vixoq/vnpy](https://github.com/Vixoq/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-01)_
  Open source quantitative trading platform development framework based

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 0 · Svelte _(updated 2026-07-01)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[Qyxloq/blankly-finance](https://github.com/Qyxloq/blankly-finance)** ⭐ 0 · Python _(updated 2026-07-01)_
  Blankly-Finance: A powerful Algo-Trading-Framework for stocks, crypto, and forex. Features Multi-Exchange-API, Backtesting, and Trading-Bot tools.

- **[sedimentary-republicofchile38/Polymarket-Trading-Bot-Rust](https://github.com/sedimentary-republicofchile38/Polymarket-Trading-Bot-Rust)** ⭐ 1 · Rust _(updated 2026-07-01)_
  Automate Polymarket trading in Rust with live, paper, and backtest strategies, CLOB auth, and balance, order, and redemption tools

- **[moo-22/opencrypto](https://github.com/moo-22/opencrypto)** ⭐ 2 · Python _(updated 2026-07-01)_
  Develop a modular framework to build, backtest, and deploy algorithmic trading strategies for cryptocurrency markets efficiently.

- **[ashikscreativemath-commits/Paldo-ALM](https://github.com/ashikscreativemath-commits/Paldo-ALM)** ⭐ 16 · Python _(updated 2026-07-01)_
  🧠 Build adaptive algorithmic trading bots using machine learning and custom logic for MetaTrader 5 scalping and swing strategies.

- **[cikafeee/algorithmic-trading-backtest](https://github.com/cikafeee/algorithmic-trading-backtest)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-01)_
  📊 Analyze and validate trading strategies with a high-performance backtesting engine using PySpark, processing thousands of backtests on real market data.

- **[Greenrestlessness223/alpha-skills](https://github.com/Greenrestlessness223/alpha-skills)** ⭐ 2 · None _(updated 2026-07-01)_
  Turn any AI coding assistant into a quant researcher for factor discovery, alpha testing, decay tracking, and backtests in natural language

- **[Roboute-ex/AlphaLab-Agent](https://github.com/Roboute-ex/AlphaLab-Agent)** ⭐ 0 · Python _(updated 2026-07-01)_
  Deterministic local workflow for low/mid-frequency equity multi-factor research and quant-agent demos

- **[msd-rs/py-alpha-lib](https://github.com/msd-rs/py-alpha-lib)** ⭐ 97 · Rust _(updated 2026-07-01)_
  Alpha Library: A high-performance rolling window calculation library implemented in Rust with Python bindings. Used for financial data analysis and factor research.

- **[sehyunVan/Poly-model](https://github.com/sehyunVan/Poly-model)** ⭐ 0 · Python _(updated 2026-07-01)_
  A 24/7 Python trading stack for Polymarket prediction markets, paired with a Binance funding-rate arbitrage bot. Runs unattended on a Linux VM, makes real CLOB orders on Polygon, and exposes a local w

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-07-01)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[Gzeu/quantluna](https://github.com/Gzeu/quantluna)** ⭐ 0 · Python _(updated 2026-07-01)_
  QuantLuna — Adaptive Kalman Filter pairs trading engine for crypto markets (spot + perpetual futures). Statistical arbitrage, cointegration testing, market-neutral strategies.

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-07-01)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[chrisli-kw/AutoTradingPlatform](https://github.com/chrisli-kw/AutoTradingPlatform)** ⭐ 49 · Python _(updated 2026-06-25)_
  A stock/futures auto trading framework using Shioaji API

- **[I-am-Uchenna/institutional-options-research](https://github.com/I-am-Uchenna/institutional-options-research)** ⭐ 0 · Jupyter Notebook _(updated 2026-06-18)_
  Academic, risk-first options research framework with stochastic-volatility pricing, defined-risk strategy analysis, and paper-trading controls.

## 4. Perplexity Strategy Synthesis
No systematic trading strategies for **crypto momentum with regime filters**, **equity pair trading**, **options tail hedges**, or **newly discovered edges from recent papers** with the *concrete parameters, time horizons, entry/exit rules, and position sizing* you requested are explicitly detailed in the provided search results for small accounts ($100–$1,000) in April 2026. The search results focus on general retail trading concepts (e.g., trend following, pullbacks, risk management) rather than the specific quantitative strategies you asked for.

However, based on the **general principles** and **actionable frameworks** found in the results, here is a synthesis of what is *currently viable* for small accounts, along with critical warnings about crowded or degraded trades:

### 1. Generalized Momentum & Trend Strategies (Most Actionable for Small Accounts)
The search results consistently highlight that **trend following** and **pullback strategies** are the most accessible and "low-stress" for small accounts [2][3][6].
*   **Concrete Parameters (Adapted from General Frameworks):**
    *   **Time Horizon:** Swing trading (holding for multiple days) is optimal to avoid split-second execution stress [3].
    *   **Entry Rule:** Enter on **pullbacks to Fair Value Gaps (FVG)** or key support levels, rather than chasing breakouts [2]. Use **10/10 Hull Moving Average** settings to confirm trend direction [6].
    *   **Exit Rule:** Scale out partial profits at predefined targets; exit all positions before market close if day trading, or hold until the trend breaks [1][2].
    *   **Position Sizing:** Risk **no more than 1–2%** of the account per trade [3][5]. If risking $500, target $750–$1,000 (2:1 reward-to-risk) [3][5].
*   **Degraded/Crowded Warning:** **News-based trading** is explicitly flagged as degraded for inexperienced traders due to speed and information processing lags [3]. **Scalping** on 1-minute charts is also noted as stressful and less suitable for beginners [3].

### 2. Equity Pair Trading & Pairing Strategies
While specific *pair trading* parameters (e.g., specific ETF pairs) are not detailed, the results emphasize **market selection** and **relative strength** as core components [1][4].
*   **Actionable Approach:**
    *   **Strategy:** Focus on **assets strengthening relative to others** with high volume and accelerating price [1].
    *   **Entry:** Buy near support when indicators (RSI, MACD) confirm oversold conditions; sell near resistance when overbought [1].
    *   **Risk:** New traders should limit themselves to **1–3 securities** to understand their patterns [3].
*   **Degraded Warning:** Strategies relying on **slight breaches of resistance** without decisive moves or consolidation are ineffective [3].

### 3. Options Tail Hedges & Crypto Momentum
The search results **do not contain** specific data on "cheap options tail hedges" or "crypto momentum with regime filters" for 2026.
*   **Critical Note:** The results mention **volatility trading** (trading based on volatility itself, not news direction) as a potential strategy, but explicitly warn that markets move too fast for inexperienced traders to process [3].
*   **Small Account Reality:** For accounts under $25k in the US, the most "actionable" path is using a **cash account** to avoid intraday margin rules and PDT restrictions, or using **swing trading** to reduce daily pressure [5].

### 4. Newly Discovered Edges (Papers & Twitter)
*   **Papers:** One result cites a paper on **Small-Cap Stock Trading Strategies** demonstrating risk-adjusted returns exceeding a **0.8 Sharpe ratio** in out-of-sample periods [8]. However, it does not provide the concrete entry/exit rules requested.
*   **Twitter/Threads:** The "CEST Framework" (Conditions, Entries, Stops, Targets) is mentioned as a precision

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-07-01 via Conway's auto-publisher.*
