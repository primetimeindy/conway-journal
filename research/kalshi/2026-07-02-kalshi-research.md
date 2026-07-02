# Kalshi Nightly Research Brief — 2026-07-02

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-07-02T02:00:44, run time 24.2s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **Theoria: Rewrite-Acceptability Verification over Informal Reasoning States** _(prediction market)_
  [2026-07-01](https://arxiv.org/abs/2607.01223v1)
  When should an AI system's answer be trusted? Formal proof assistants offer certainty but cannot reach most of the problem distribution; scalar LLM judges offer coverage but produce opaque scores that cannot be audited after the fact and are subject to the same coherence issues as any LLM. We present Theoria, a verification architecture that closes this gap. A candidate solution is rewritten into 

- **The State-Prediction Separation Hypothesis** _(prediction market)_
  [2026-07-01](https://arxiv.org/abs/2607.01218v1)
  Transformers use the same forward computation stream to both predict the next token and store useful state for future token predictions. We formulate the \emph{state-prediction separation hypothesis}: disentangling the two roles yields better language modeling performance. We design a Transformer variant that uses two computation streams to separate the two functions, and conduct pretraining exper

- **FurnitureVLA: Learning Long-Horizon Bimanual Furniture Assembly with Vision-Language-Action Model** _(prediction market)_
  [2026-07-01](https://arxiv.org/abs/2607.01212v1)
  Current work on robot furniture assembly mostly focuses on toy-scale settings or single-arm manipulation. We introduce FurnitureVLA, the first systematic study of real-scale bimanual furniture assembly using Vision-Language-Action models (VLAs). We formalize the task, develop a scalable simulation pipeline for expert data generation and evaluation, and build a VR teleoperation system for single-op

- **Query Complexity of Hypergraph Connectivity and Learnability using CUT Oracles** _(binary option pricing convergence)_
  [2026-07-01](https://arxiv.org/abs/2607.01216v1)
  We investigate the power of CUT queries to reveal the structure of unknown hypergraphs. While simple graphs allow for optimal $O(n)$-query connectivity algorithms, hypergraphs face a fundamental identifiability barrier in that distinct hypergraphs can share identical cut-profiles, making exact edge learning impossible in general, a primitive crucial in the graph connectivity algorithms.   We first

- **Touching and Feeling the Data: A Reusable Software Pipeline for Tactile Statistical Graphs in Accessible Education** _(binary option pricing convergence)_
  [2026-07-01](https://arxiv.org/abs/2607.01214v1)
  Statistical visualization is usually treated as a visual medium, but data can also be touched. Three dimensional printed tactile graphs let blind and low vision students feel distributions, trace trends, and explore relationships through direct haptic interaction. Yet classroom scale use remains limited because producing each graph in CAD software requires specialized skill and hours of manual wor

- **When large trades are not news: Liquidity tail risk and price discovery** _(binary option pricing convergence)_
  [2026-07-01](https://arxiv.org/abs/2607.01198v1)
  When is a large trade news, and when is it a liquidity shock? We study this question in a sequential competitive limit order book with asymmetric information. In our model, liquidity suppliers observe aggregate order flow but not its decomposition into informed demand and uninformed liquidity demand. We model uninformed order flow with Student-$t$ tails, interpreted as a reduced form for rare liqu

- **Computationally Efficient Near-Optimal Control for Current Ripple Reduction and Optimization of Three-Phase Motors via LMIs** _(event-driven trading)_
  [2026-07-01](https://arxiv.org/abs/2607.01215v1)
  The optimal control of three-phase permanent-magnet synchronous motors (PMSMs) is challenging due to their nonlinearity and the discrete nature of the control set. Existing approaches either rely on mixed-integer trajectory optimization or require computationally intensive value-iteration procedures. This paper proposes a Linear Matrix Inequality (LMI)-based method for approximating the infinite-h

- **When large trades are not news: Liquidity tail risk and price discovery** _(event-driven trading)_
  [2026-07-01](https://arxiv.org/abs/2607.01198v1)
  When is a large trade news, and when is it a liquidity shock? We study this question in a sequential competitive limit order book with asymmetric information. In our model, liquidity suppliers observe aggregate order flow but not its decomposition into informed demand and uninformed liquidity demand. We model uninformed order flow with Student-$t$ tails, interpreted as a reduced form for rare liqu

- **Muon as a Residual Connection** _(event-driven trading)_
  [2026-07-01](https://arxiv.org/abs/2607.01124v1)
  Muon has recently emerged as one of the most effective optimizers for training large neural networks, yet its empirical success has been explained from several different perspectives. In this paper, we propose a simple mechanistic interpretation: Muon can be understood as an implicit residual connection during training. Specifically, orthogonalizing the update can sacrifice some immediate gradient

- **Play Like Champions: Counterfactual Feedback Generation in Latent Space** _(sports betting arbitrage)_
  [2026-06-30](https://arxiv.org/abs/2607.00190v1)
  Recent advances in reinforcement learning have produced superhuman agents across a wide range of competitive games. As a byproduct, researchers have begun studying how these agents play, extracting behavioral representations, analyzing decision structure, and modeling the latent geometry of expert performance. However, this growing body of work has overwhelmingly focused on defeating human players

- **Verifiable Rewards for Calibrated Probabilistic Forecasting** _(sports betting arbitrage)_
  [2026-06-30](https://arxiv.org/abs/2607.00164v1)
  Reinforcement learning with verifiable rewards can in principle train calibrated probabilistic forecasters, since a proper scoring rule such as the Brier score is computed from outcomes alone and is minimized in expectation by the true probability. In practice it degrades calibration, and existing remedies address epistemic uncertainty, where a model's confidence accompanies a verifiably correct o

- **Planar-SfM: Camera Pose Estimation via Homography Graph Embeddings** _(sports betting arbitrage)_
  [2026-06-30](https://arxiv.org/abs/2606.31979v2)
  Structure from Motion (SfM) systems traditionally struggle with planar scenes, where standard epipolar geometry-based methods become degenerate. Rather than viewing planar surfaces as a limitation, we propose a unified framework that leverages them as a source of geometric constraints. Our key insight is that each planar surface visible across multiple views provides an independent estimate of rel

- **Measuring the Gap Between Human and LLM Research Ideas** _(Kelly criterion small bankroll)_
  [2026-07-01](https://arxiv.org/abs/2607.01233v1)
  LLMs are increasingly used to brainstorm research ideas, but existing evaluations mostly judge individual ideas by novelty, feasibility, or expert preference. We instead ask: how far are current LLM-generated ideas from human researchers? To characterize this gap, we build a large-scale evaluation framework for ideation from high-quality human research papers. For each paper, we reverse-engineer a

- **Is One Layer Enough? Training A Single Transformer Layer Can Match Full-Parameter RL Training** _(Kelly criterion small bankroll)_
  [2026-07-01](https://arxiv.org/abs/2607.01232v1)
  Reinforcement learning (RL) has become a central component of post-training large language models (LLMs), yet little is understood about how RL adaptation is distributed across transformer layers. Existing approaches typically update all model parameters uniformly, implicitly assuming that every layer contributes similarly to the gains obtained during RL post-training. In this work, we challenge t

- **Intertwined Constraints in Extended Cosmologies: Dark Energy, Curvature, Neutrinos, and Inflation** _(Kelly criterion small bankroll)_
  [2026-07-01](https://arxiv.org/abs/2607.01226v1)
  We present a systematic reassessment of cosmological constraints beyond $Λ$CDM by progressively relaxing the assumptions underlying Dark Energy (DE), Curvature, Neutrinos, and Inflation. Using the latest CMB data together with DESI BAO and different SN catalogues, we show that the preference for dynamical DE persists across all the extended cosmologies considered. $Ω_k$ remains compatible with fla

- **Distributed Containment of a Compromised Agent through Repulsive Cages** _(tail risk harvesting)_
  [2026-07-01](https://arxiv.org/abs/2607.01230v1)
  UAV swarms and cyber-physical multi-agent systems are increasingly deployed in safety-critical missions that require coordinated motion, distributed decision making, and autonomy. A major security risk arises when a legitimate agent is hijacked and driven by adversarial high-level commands. Rather than focusing on detection and isolation of malicious agents, we exploit a structural property common

- **Multidimensional Risk Made Easy** _(tail risk harvesting)_
  [2026-07-01](https://arxiv.org/abs/2607.01229v1)
  Suppose we want to assign a certainty equivalent--one number--to a multivariate risk. Which such assignments are law-invariant, monotone with respect to vector stochastic dominance, and invariant to independent background risk? I show that every such certainty equivalent is a positive mixture of scalar entropic certainty equivalents applied to positive projections of the vector risk. The same repr

- **Computationally Efficient Near-Optimal Control for Current Ripple Reduction and Optimization of Three-Phase Motors via LMIs** _(tail risk harvesting)_
  [2026-07-01](https://arxiv.org/abs/2607.01215v1)
  The optimal control of three-phase permanent-magnet synchronous motors (PMSMs) is challenging due to their nonlinearity and the discrete nature of the control set. Existing approaches either rely on mixed-integer trajectory optimization or require computationally intensive value-iteration procedures. This paper proposes a Linear Matrix Inequality (LMI)-based method for approximating the infinite-h

## 3. GitHub Repos (Recently Updated)
- **[oleksandrbannick/Meridian](https://github.com/oleksandrbannick/Meridian)** ⭐ 3 · Python _(updated 2026-07-02)_
  kalshi automated trading bot with custom UI

- **[dcamco/kalshi-snapshots](https://github.com/dcamco/kalshi-snapshots)** ⭐ 0 · HTML _(updated 2026-07-02)_
  Public read-only snapshots of the Kalshi paper-trading dashboard (main repo private)

- **[samuel483/poly-kalshi-arb](https://github.com/samuel483/poly-kalshi-arb)** ⭐ 5 · Rust _(updated 2026-07-02)_
  🎯 Automate cross-platform arbitrage trading between Kalshi and Polymarket with this easy-to-use bot designed for optimal profit.

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-07-02)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-07-02)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[rockmundada/kalshi-weather-bot](https://github.com/rockmundada/kalshi-weather-bot)** ⭐ 0 · Python _(updated 2026-07-01)_
  Automated weather derivatives trading system for Kalshi — 5 API integrations, 10-chart analytics dashboard, data-driven strategy from 339 analyzed trades

- **[Casiniza/polymarket-bot](https://github.com/Casiniza/polymarket-bot)** ⭐ 2 · Python _(updated 2026-07-02)_
  Automated Polymarket trading bot with GitHub Actions

- **[Axiom-Projects/polymarket-dashboard](https://github.com/Axiom-Projects/polymarket-dashboard)** ⭐ 1 · HTML _(updated 2026-07-02)_
  Mobile P&L dashboard for Polymarket trading bots

- **[lathankilbrand/polymarket-copy-trading-bot](https://github.com/lathankilbrand/polymarket-copy-trading-bot)** ⭐ 0 · Rust _(updated 2026-07-02)_
  

- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1939 · TypeScript _(updated 2026-07-02)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-07-02)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant)** ⭐ 3 · Python _(updated 2026-07-02)_
  Trade Kalshi prediction markets with a quantitative system designed for fee-aware position sizing and statistical arbitrage.

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-07-02)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[aasuper1/kalshi-alpha-strategies](https://github.com/aasuper1/kalshi-alpha-strategies)** ⭐ 0 · Python _(updated 2026-06-19)_
  Three independent Kalshi event-contract trading strategies: latency (sell-worthless), liquidity-incentive market making, and a cross-market/correlation engine.

- **[talirabban/prediction-markets-thesis](https://github.com/talirabban/prediction-markets-thesis)** ⭐ 0 · Python _(updated 2026-06-10)_
  Quantitative analysis of Polymarket event contracts: calibration, ML-based pricing-error prediction, and out-of-sample strategy backtesting.

## 4. Perplexity Strategy Synthesis
For small accounts ($50–$500) on Kalshi and Polymarket in 2026, the most actionable strategies are **cross-venue arbitrage** on wide gaps (≥$0.03 net of fees), **convergence plays** buying “Yes” at $0.90–$0.95 on near-certain events, and **tail decay harvesting** by selling deeply out-of-probability “No” contracts at $0.01–$0.05 with strict 10-point stop-losses [2][3]. Domain-expertise trading in niche categories (e.g., crypto-specific Fed rate outcomes) and AI-assisted information processing (verifying claims against primary sources) also enable consistent profits for small wallets [3][5].

---

### 1. Cross-Venue Arbitrage (Best for Small Accounts)
**Strategy:** Buy “Yes” on Platform A and “No” on Platform B when the combined cost is < $1.00 after fees.  
**Parameters:**  
- **Price threshold:** Target gaps ≥ $0.03 net of fees (e.g., A: $0.48 “Yes”, B: $0.47 “No” → total $0.95) [2].  
- **Time horizon:** 1–7 days (shorter for high-volatility events like Fed decisions) [2].  
- **Position sizing:** 1–3% of capital per trade due to momentum risk [2][3].  
- **Edge source:** Structural mispricing between Kalshi (US-regulated, sports-heavy) and Polymarket (global, crypto-niche) [3][9].  
**Small-account tip:** Start manually on wide gaps (≥$0.05) in slower markets (e.g., weather or political polling) to avoid narrow-spread automation costs [3].

---

### 2. Convergence Plays (Low-Risk Short-Term Returns)
**Strategy:** Buy “Yes” at $0.90–$0.95 on events with >90% probability that resolve within days.  
**Parameters:**  
- **Price threshold:** $0.90–$0.95 for “Yes” (profit: 5–10% per contract) [2].  
- **Time horizon:** 1–14 days (contracts nearing resolution converge to $1.00) [2].  
- **Position sizing:** 2–5% of capital; avoid overexposure to single events [2].  
- **Edge source:** Implied probability > market price (e.g., real-world data confirms 95% chance vs. 90% market price) [2].  
**Example:** Buying “Fed holds rate” at $0.92 when economic data suggests 95% certainty [5].

---

### 3. Tail Decay Harvesting (High-Edge, Small Exposure)
**Strategy:** Sell “No” at $0.01–$0.05 on events with <5% probability (e.g., “Bitcoin > $200k in 2026”) to capture time decay.  
**Parameters:**  
- **Price threshold:** $0.01–$0.05 for “No” contracts (profit: 95–100% if event doesn’t occur) [7].  
- **Time horizon:** 1–30 days (shorter for high-volatility crypto events) [7].  
- **Position sizing:** 1–3% of capital; hard stop-loss at 10-point adverse movement [2].  
- **Edge source:** Overpriced tail risk (e.g., market assigns 10%

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-07-02 via Conway's auto-publisher.*
