# Kalshi Nightly Research Brief — 2026-06-25

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-25T02:02:20, run time 19.5s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **ForceBand: Learning Forceful Manipulation with sEMG** _(prediction market)_
  [2026-06-24](https://arxiv.org/abs/2606.26093v1)
  Human demonstrations are a scalable data source for learning robot manipulation policies. However, common sources of human demonstration data, such as motion-capture trajectories and internet videos, capture mostly motion and appearance while missing the contact forces that are critical for force-sensitive manipulation. In this paper, we introduce ForceBand, a low-cost wrist-worn sEMG system that 

- **Simulating Universal Quantum Gate Sets on Photonic OAM Qubits: Single-Qubit and Multi-Qubit Operations via Spatial Light Modulator Phase Holography** _(prediction market)_
  [2026-06-24](https://arxiv.org/abs/2606.26088v1)
  Spatial light modulators (SLMs) have emerged as reconfigurable platforms for photonic quantum information processing, offering software-defined control over the orbital angular momentum (OAM) of light encoded in Laguerre-Gaussian (LG) beams. This paper presents a comprehensive simulation and hardware-grounded fidelity analysis of quantum gate operations implemented on the HOLOEYE LC 2012 transmiss

- **Same Evidence, Different Answer: Auditing Order Sensitivity in Multimodal Large Language Models** _(prediction market)_
  [2026-06-24](https://arxiv.org/abs/2606.26079v1)
  Standard benchmarks for multimodal large language models (MLLMs) score each item on one canonical ordering and miss whether order-irrelevant shuffling changes the answer, a baseline reliability property called for by emerging AI evaluation guidelines. We introduce Facet-Probe, a five-facet audit (option, evidence-chunk, document-rank, image-set, and mixed-modality ordering) of 18 frontier and open

- **Learning Action Priors for Cross-embodiment Robot Manipulation** _(binary option pricing convergence)_
  [2026-06-24](https://arxiv.org/abs/2606.26095v1)
  Most Vision-Language-Action (VLA) models build on a Vision-Language Model (VLM) backbone by attaching an action module and optimizing the full policy jointly. This design inherits strong visual and linguistic priors from the VLM, but leaves the action module to learn physical motion almost from scratch. As a result, the policy lacks an explicit motion prior, forcing early optimization to simultane

- **On the entropic convergence for piecewise deterministic samplers: speedup and obstruction** _(binary option pricing convergence)_
  [2026-06-24](https://arxiv.org/abs/2606.26086v1)
  For piecewise deterministic samplers such as Randomized Hamiltonian Monte Carlo (RHMC), Bouncy Particle Sampler (BPS) or Zig-Zag Process (ZZP), long-time exponential convergence rates have been established in previous works using Harris or $L^2$ hypocoercivity approaches. In particular, in the $L^2$ framework, a so-called \emph{diffusive-to-ballistic} speedup was known for log-concave targets, acc

- **Same Evidence, Different Answer: Auditing Order Sensitivity in Multimodal Large Language Models** _(binary option pricing convergence)_
  [2026-06-24](https://arxiv.org/abs/2606.26079v1)
  Standard benchmarks for multimodal large language models (MLLMs) score each item on one canonical ordering and miss whether order-irrelevant shuffling changes the answer, a baseline reliability property called for by emerging AI evaluation guidelines. We introduce Facet-Probe, a five-facet audit (option, evidence-chunk, document-rank, image-set, and mixed-modality ordering) of 18 frontier and open

- **Deep Reinforcement Learning-Enhanced Event-Triggered Data-Driven Predictive Control for a 3D Cable-Driven Soft Robotic Arm** _(event-driven trading)_
  [2026-06-24](https://arxiv.org/abs/2606.26048v1)
  Soft robots are challenging to control due to their nonlinear and time-varying dynamics. Data-enabled predictive control (DeePC) offers a model-free alternative by directly leveraging measured input-output trajectories to construct a predictive controller. However, its receding-horizon formulation requires solving a constrained optimization problem at every sampling instant, which can be computati

- **The Inference-Compute Frontier and a Latency-Efficient Architecture for Limit Order Book Prediction** _(event-driven trading)_
  [2026-06-24](https://arxiv.org/abs/2606.25986v1)
  We study whether a scaling-law-style inference-compute frontier appears in limit order book prediction. Using FI-2010 and a suite of models ranging from small decision trees to neural LOB architectures, we find that the realized empirical frontier of predictive loss versus structural forward work is well summarized by a power law. In particular, with MLPLOB held out as an architecture family, a po

- **Monitoring Discounted Sum Properties** _(event-driven trading)_
  [2026-06-24](https://arxiv.org/abs/2606.25979v1)
  Runtime monitoring of quantitative signals faces a fundamental trade-off between volatility and over-aggregation: instantaneous observations are noisy, while long-run averages obscure local structure. Localisation measures such as discounted averages offer a principled middle ground, yet remain poorly understood in runtime verification. This paper studies discounted sums from a monitoring perspect

- **Hierarchical Graph Learning for Calendar Spread Strategies in Commodity Futures Markets** _(sports betting arbitrage)_
  [2026-06-24](https://arxiv.org/abs/2606.25811v1)
  Commodity futures can be represented hierarchically, with underlying assets at the upper level and individual futures contracts at the lower level. Entities at each level can be connected by edges reflecting inherent correlations, with cross-level edges capturing contract-to-underlying asset connections. Building on our observations of these structures, we propose a hierarchical graph learning app

- **1000 Rallies: An Event-Camera Dataset and Real-Time Learned Ball-State Estimation for Robotic Table Tennis** _(sports betting arbitrage)_
  [2026-06-24](https://arxiv.org/abs/2606.25620v1)
  Robotic table tennis has emerged as a compelling benchmark for real-time robotic perception due to its fast ball dynamics and stringent timing requirements. Accurate, high-frequency, and low-latency ball state estimation is critical for reliable trajectory prediction and timely control. Traditional frame-based cameras face an inherent trade-off: low frame rates leave temporal blind spots that miss

- **Strong duality for the GROW criterion** _(sports betting arbitrage)_
  [2026-06-23](https://arxiv.org/abs/2606.24768v1)
  This paper presents general strong duality results when testing hypotheses by betting against them. A bet is an e-variable for a composite null hypothesis $\mathcal{P}$: a nonnegative random variable $X$ whose expected value is at most one under every $¶\in \Pcal$. Following Kelly, Breiman, Cover, Shafer, Grünwald and others, we study a natural minimax \emph{log-optimality} criterion: given a comp

- **A Population of Little Red Dot-like Quasars in SDSS** _(Kelly criterion small bankroll)_
  [2026-06-24](https://arxiv.org/abs/2606.26098v1)
  Compact and red sources in the high redshift ($z\sim5$) Universe, known as "Little Red Dots" (LRDs), are among JWST's most intriguing discoveries. These sources have broad Balmer emission lines, weak X-ray emission, and unique spectral energy distributions (SEDs) poorly fit by either stellar or AGN templates. Local analogs of LRDs allow for detailed studies of the underlying physical processes wit

- **Operational detection of Wigner negativity in arbitrary quantum states from few copies** _(Kelly criterion small bankroll)_
  [2026-06-24](https://arxiv.org/abs/2606.26084v1)
  States with negative Wigner functions form a fundamental class of nonclassical resource underlying quantum advantage. Here we develop a unified framework to detect Wigner negativity of arbitrary states using experimentally accessible moments of the Wigner function that can be estimated from a modest number of state copies. Exploiting constraints satisfied by positive phase-space distributions, we 

- **Labels** _(Kelly criterion small bankroll)_
  [2026-06-24](https://arxiv.org/abs/2606.26064v1)
  Labels -- grades, credentials, scores, ratings, ranks -- do two things. They inform receivers, and they give agents something to chase. I study optimal classification when labels must be earned through costly self-selection. I show that exact certification is inefficiently fine: pooling a small bottom interval saves first-order signaling costs while losing only higher-order decision value. I provi

- **FedReLa: Imbalanced Federated Learning via Re-Labeling** _(tail risk harvesting)_
  [2026-06-24](https://arxiv.org/abs/2606.26037v1)
  Federated learning has emerged as the foremost approach for decentralized model training with privacy preservation. The global class imbalance and cross-client data heterogeneity naturally coexist, and the mismatch between local and global imbalances exacerbates the performance degradation of the aggregated model. The agnosticism of global class distribution poses significant challenges for data-l

- **Geometrically convex return risk measures on AM-algebras** _(tail risk harvesting)_
  [2026-06-24](https://arxiv.org/abs/2606.26031v1)
  Monetary risk measures quantify the risk of uncertain monetary payoffs (or losses), whereas in time series analysis risk is typically assessed using logarithmic returns. Return risk measures (RRMs) provide an axiomatic foundation for this latter approach, which relies crucially on the positive cone of the space of essentially bounded random variables. We extend RRMs to general ordered vector space

- **Privacy Vulnerabilities of Attention Layers in Tabular Foundation Models and Protection of High-Risk Queries** _(tail risk harvesting)_
  [2026-06-24](https://arxiv.org/abs/2606.26021v1)
  Tabular foundation models are commonly assumed to present limited privacy concerns as they are often pre-trained on large collections of synthetic data. However, these models leverage in-context learning, where sensitive records may be provided directly at inference time as labelled context examples. In this paper, we demonstrate that predictions generated via the attention mechanism leak sufficie

## 3. GitHub Repos (Recently Updated)
- **[dcamco/kalshi-snapshots](https://github.com/dcamco/kalshi-snapshots)** ⭐ 0 · HTML _(updated 2026-06-25)_
  Public read-only snapshots of the Kalshi paper-trading dashboard (main repo private)

- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1916 · TypeScript _(updated 2026-06-25)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-25)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-25)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-25)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[rockmundada/kalshi-weather-bot](https://github.com/rockmundada/kalshi-weather-bot)** ⭐ 0 · Python _(updated 2026-06-24)_
  Automated weather derivatives trading system for Kalshi — 5 API integrations, 10-chart analytics dashboard, data-driven strategy from 339 analyzed trades

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 2 · Python _(updated 2026-06-25)_
  Polymarket Trade Bot

- **[Casiniza/polymarket-bot](https://github.com/Casiniza/polymarket-bot)** ⭐ 2 · Python _(updated 2026-06-25)_
  Automated Polymarket trading bot with GitHub Actions

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 98 · Solidity _(updated 2026-06-25)_
  Easy setup and creation of a bot

- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1916 · TypeScript _(updated 2026-06-25)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[mbordash/DRADIS](https://github.com/mbordash/DRADIS)** ⭐ 13 · Rust _(updated 2026-06-25)_
  Direct Reaction And Dynamic Intelligence System — Low-latency Rust prediction-market trading bot for Polymarket. 7 autonomous strategies (Momentum, Maker, Arbitrage, Time Decay, Basis, ML, Trend), rea

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-06-25)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-21)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[aasuper1/kalshi-alpha-strategies](https://github.com/aasuper1/kalshi-alpha-strategies)** ⭐ 0 · Python _(updated 2026-06-19)_
  Three independent Kalshi event-contract trading strategies: latency (sell-worthless), liquidity-incentive market making, and a cross-market/correlation engine.

- **[talirabban/prediction-markets-thesis](https://github.com/talirabban/prediction-markets-thesis)** ⭐ 0 · Python _(updated 2026-06-10)_
  Quantitative analysis of Polymarket event contracts: calibration, ML-based pricing-error prediction, and out-of-sample strategy backtesting.

## 4. Perplexity Strategy Synthesis
The most actionable 2026 strategies for **Kalshi** and **Polymarket** for small accounts ($50–$500) combine **arbitrage** (locking in 2–5% guaranteed spreads), “**Obvious No**” plays (near-certain outcomes), and **manual edge** trading (research-driven mispricings), with strict position sizing of **1–5% of bankroll per trade**[1][2].

### 1. Cross-Venue Arbitrage (2–5% Guaranteed Profit)
This is the most reliable strategy for small accounts because it eliminates directional risk.
*   **Mechanism**: Identify the same event priced differently across platforms. If **Polymarket** prices an event at **60%** and **Kalshi** at **50%**, buy **YES on Kalshi** and **NO on Polymarket**[1][2].
*   **Parameters**:
    *   **Profit Threshold**: Calculate if the combined cost of opposing positions is **< $1.00** per share (e.g., $0.50 + $0.45 = $0.95) to lock in a **5% spread**[2].
    *   **Time Horizon**: Execute **immediately** before prices adjust; typical resolution is days to weeks for major events (e.g., Fed rates, election outcomes)[2].
    *   **Position Sizing**: Limit to **1–5% of bankroll** per trade due to capital efficiency requirements; do not over-leverage[2].
*   **Execution**: Use analytics tools to monitor **Polymarket, Kalshi, and other platforms** simultaneously; use a **low-latency bot** or a **German VPS** near Poly Market servers for faster execution[2][6].

### 2. The “Obvious No” Strategy (Near-Certain Outcomes)
Ideal for small accounts with limited capital; targets markets where the outcome is statistically near-certain.
*   **Mechanism**: Find markets where the outcome is **>90% likely** (e.g., “Will the Earth explode tomorrow?” or specific Fed holds). Buy the **NO** side (if priced low) or the **YES** side if the market is irrational[2].
*   **Parameters**:
    *   **Price Threshold**: Buy the side priced **< 10%** (for NO) or **> 90%** (for YES) where the market is underpricing certainty[2].
    *   **Time Horizon**: Wait for **resolution** (days to months); reinvest returns into the next obvious market[2].
    *   **Risk**: Low volatility; returns are typically **15–25% annual** with lower risk than stocks[1].

### 3. Manual Edge Trading (Research-Driven Mispricings)
Leverages small accounts’ ability to do deep research faster than institutional algorithms.
*   **Mechanism**: Focus on **2–3 categories** you understand (e.g., crypto, weather, politics). Conduct your own research *before* checking market prices. If your research says **70%** probability and the market says **50%**, that is a trade[2].
*   **Parameters**:
    *   **Price Threshold**: Target mispricings where **your edge > 10%** (e.g., 70% vs. 50%)[2].
    *   **Time Horizon**: Short-term (days) for news-driven events; long-term (months) for macro trends like **Fed rate decisions**[2][4].
    *   **Position Sizing**: **1–5% of bankroll** per trade to manage risk; use the **

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-25 via Conway's auto-publisher.*
