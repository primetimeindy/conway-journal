# Kalshi Nightly Research Brief — 2026-06-23

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-23T02:01:39, run time 21.0s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **Lift4D: Harmonizing Single-View 3D Estimation for 4D Reconstruction In-the-Wild** _(prediction market)_
  [2026-06-22](https://arxiv.org/abs/2606.23688v1)
  Reconstructing dynamic non-rigid objects from monocular video requires integrating visual cues from direct observations with data-driven priors over geometry and appearance. Prior approaches either learn to directly predict 4D representations from visual input or initialize a 3D representation that is subsequently deformed and refined based on video evidence. However, the former are constrained by

- **CoorDex: Coordinating Body and Hand Priors for Continuous Dexterous Humanoid Loco-Manipulation** _(prediction market)_
  [2026-06-22](https://arxiv.org/abs/2606.23680v1)
  Humanoid loco-manipulation is often simplified into a stop-and-go process: walking to an object, stopping to manipulate it, and then resuming locomotion. It also commonly relies on low degree-of-freedom (DoF) end effectors that behave like an open-close grasp primitive. We introduce CoorDex, a learning pipeline that converts high-dimensional body and dexterous hand control into coordinated latent 

- **PsyBridge: A Hybrid Intelligent Framework for Multi-Dimensional Mental Health Assessment and Decision Support** _(prediction market)_
  [2026-06-22](https://arxiv.org/abs/2606.23673v1)
  Mental health assessment commonly relies on isolated screening instruments or data-driven models that often lack interpretability and multi-dimensional integration. Existing approaches frequently focus on individual indicators such as depression or anxiety while providing limited support for comprehensive and explainable decision-making. To address this limitation, this study proposes PsyBridge, a

- **Open Problem: Is AdamW Effective Under Heavy-Tailed Noise?** _(binary option pricing convergence)_
  [2026-06-22](https://arxiv.org/abs/2606.23676v1)
  AdamW is the de facto optimizer for training large language models (LLMs), yet the theory behind it still lives mostly in finite-variance regimes. This is increasingly unsatisfying, as empirical evidence indicates that stochastic gradient noise in LLM pretraining is typically heavy-tailed. Recent work shows that sign-based optimizers such as Lion and Muon achieve sharp heavy-tailed rates, and that

- **Teaching LLMs String Matching, Backtracking, and Error Recovery to Deduce Bases and Truth Tables for the Combinatorially Exploding Bit Manipulation Puzzles** _(binary option pricing convergence)_
  [2026-06-22](https://arxiv.org/abs/2606.23672v1)
  This paper presents our algorithmic innovations for the NVIDIA Nemotron Model Reasoning Challenge, focusing on Bit Manipulation Puzzles. In this task, the objective is to discover a hidden logical rule transforming input binary strings to outputs, then apply it to unseen inputs. Large Language Models (LLMs) notoriously struggle here; traditional methods force them to simulate complex boolean logic

- **Causal Inference with Multiple Misclassified Exposures: A Control Variate-Adjusted Calibration Weighting Approach** _(binary option pricing convergence)_
  [2026-06-22](https://arxiv.org/abs/2606.23656v1)
  Exposure misclassification is a common concern in studies of respiratory infections in cystic fibrosis. Throat swabs are frequently used in place of expectorated or induced sputum cultures, although they have imperfect sensitivity and specificity to detect Pseudomonas aeruginosa and Staphylococcus aureus. We develop calibration weighting and control variate estimators for causal inference with mul

- **AI-driven Optimisation of Quality of Recovery (QoR) in Remote Patient Monitoring** _(event-driven trading)_
  [2026-06-22](https://arxiv.org/abs/2606.23631v1)
  Remote patient monitoring depends on patient-reported data to capture the subjective dimension of recovery that devices cannot measure. The Quality of Recovery (QoR-15) survey is the gold-standard instrument for this purpose. It was designed and validated for occasional in-hospital assessment, yet remote monitoring now administers it to patients daily. In our own post-surgical deployment, only 55%

- **MORL-A2C: Multi-Objective Reinforcement Learning Reranker for Optimizing Healthiness in MOPI-HFRS** _(event-driven trading)_
  [2026-06-22](https://arxiv.org/abs/2606.23603v1)
  Unhealthy dietary behavior continues to be a persistent public health issue in the United States, exacerbated by recommendation systems that prioritize user preference without considering nutritional health. The Multi-Objective Personalized Interpretable Health-aware Food Recommendation System (MOPI-HFRS), from which this work extends, addresses this by jointly optimizing preference, health, and d

- **Quantifying the Agreement Between Data-Influence and Data-Similarity to Understand LLM Behavior** _(event-driven trading)_
  [2026-06-22](https://arxiv.org/abs/2606.23591v1)
  One way to understand LLM behavior is to trace its output back to the training data. Two types of measures are commonly used for output tracing: data-similarity and data-influence. The former is cheaper while the latter is believed to be more accurate. Even though many works have compared them for ground-truth tasks, no such comparisons exist for output tracing. Here, we fill this gap and precisel

- **URecJPQ: Memory-efficient Multimodal Recommendation Models through RecJPQ in Large-Scale Scenarios** _(sports betting arbitrage)_
  [2026-06-22](https://arxiv.org/abs/2606.23291v1)
  Training state-of-the-art recommendation models on large-scale industrial datasets can be a challenging task due to the high number of users and items which are typically represented through ID embeddings. Such embeddings typically require a large amount of memory resources, which are not always available. This problem is further exacerbated in multimodal recommendation, in which multimodal item f

- **Endogenous Randomness from Adversarial Market Learning** _(sports betting arbitrage)_
  [2026-06-22](https://arxiv.org/abs/2606.22743v1)
  We propose a deterministic adversarial market model in which apparent randomness emerges endogenously from the interaction between a market mechanism and a population of predictive traders. Unlike a classical generative adversarial network, the model does not attempt to imitate an external empirical data distribution and does not inject random noise into a generator. The market is represented by a

- **Impact of distribution fees on BESS scheduling and profitability** _(sports betting arbitrage)_
  [2026-06-20](https://arxiv.org/abs/2606.22185v1)
  Battery energy storage systems (BESS) are expected to play an important role in electricity markets with increasing shares of renewable generation. While existing research has primarily focused on price arbitrage and ancillary services, the role of grid fees in shaping BESS operation and profitability remains insufficiently understood. This article investigates how different levels of distribution

- **Ram-pressure signatures in the dwarf irregular galaxy SextansB revealed by deep MeerKAT HI observations** _(Kelly criterion small bankroll)_
  [2026-06-22](https://arxiv.org/abs/2606.23674v1)
  The impact of extremely low-density environments such as the diffuse intergalactic medium (IGM) on the neutral gas distribution of dwarf galaxies remains poorly explored observationally. We present deep MeerKAT HI 21 cm observations of the Local Group dwarf irregular galaxy Sextans B that achieve a spectral resolution of 1.4 km/s and reach column-density sensitivities down to 3.3 x 10^18 cm^-2, al

- **Dynamic estimation of slowly varying sequences** _(Kelly criterion small bankroll)_
  [2026-06-22](https://arxiv.org/abs/2606.23655v1)
  We consider the problem of sequentially approximating functions of each element in a slowly-varying sequence, i.e. one where the magnitude $α_i$ of the difference between the elements at positions $i$ and $i-1$ is small. Recent work on implicit trace estimation shows that when $α_t$ is small, reusing queries to past sequence elements can reduce the overall cost [Dharangutte \&amp; Musco, NeurIPS~2

- **Revisiting the 'Lensing is Low' Problem with UNIONS** _(Kelly criterion small bankroll)_
  [2026-06-22](https://arxiv.org/abs/2606.23651v1)
  We present new measurements of the galaxy-galaxy lensing (GGL) signal around Baryon Oscillation Spectroscopic Survey (BOSS) CMASS galaxies using background sources from the Ultraviolet Near-Infrared Optical Northern Survey (UNIONS). With high-quality imaging of background sources and a survey overlap of approximately 2650 square degrees, we obtain precise large-scale GGL measurements. Building on 

- **Open Problem: Is AdamW Effective Under Heavy-Tailed Noise?** _(tail risk harvesting)_
  [2026-06-22](https://arxiv.org/abs/2606.23676v1)
  AdamW is the de facto optimizer for training large language models (LLMs), yet the theory behind it still lives mostly in finite-variance regimes. This is increasingly unsatisfying, as empirical evidence indicates that stochastic gradient noise in LLM pretraining is typically heavy-tailed. Recent work shows that sign-based optimizers such as Lion and Muon achieve sharp heavy-tailed rates, and that

- **PsyBridge: A Hybrid Intelligent Framework for Multi-Dimensional Mental Health Assessment and Decision Support** _(tail risk harvesting)_
  [2026-06-22](https://arxiv.org/abs/2606.23673v1)
  Mental health assessment commonly relies on isolated screening instruments or data-driven models that often lack interpretability and multi-dimensional integration. Existing approaches frequently focus on individual indicators such as depression or anxiety while providing limited support for comprehensive and explainable decision-making. To address this limitation, this study proposes PsyBridge, a

- **Can LLMs Reliably Self-Report Adversarial Prefills, and How?** _(tail risk harvesting)_
  [2026-06-22](https://arxiv.org/abs/2606.23671v1)
  Prior work shows that large language models (LLMs) exhibit introspective capability on benign tasks. We extend the question to safety contexts and examine how reliably a model can recognize that its own prior response was elicited by an adversarial prefill attack. Across ten open-weight instruction-tuned LLMs (3B to 70B) and four safety benchmarks, no model reliably recognizes its own compromised 

## 3. GitHub Repos (Recently Updated)
- **[anglil/kalshi-ai-trading-bot](https://github.com/anglil/kalshi-ai-trading-bot)** ⭐ 5 · Python _(updated 2026-06-23)_
  AI-powered Kalshi prediction market trading bot using Gemini

- **[samuel483/poly-kalshi-arb](https://github.com/samuel483/poly-kalshi-arb)** ⭐ 5 · Rust _(updated 2026-06-23)_
  🎯 Automate cross-platform arbitrage trading between Kalshi and Polymarket with this easy-to-use bot designed for optimal profit.

- **[aasghar311-source/RAID](https://github.com/aasghar311-source/RAID)** ⭐ 0 · Python _(updated 2026-06-23)_
  Rapid AI Decision Engine — crypto + Kalshi paper trading bot

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-23)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-23)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[sririthishpalani-max/kalshi-latency-arb](https://github.com/sririthishpalani-max/kalshi-latency-arb)** ⭐ 0 · Python _(updated 2026-06-22)_
  Async trading system for Kalshi, a CFTC-regulated event-contract exchange — real-time contract pricing, quarter-Kelly sizing, layered risk controls, RSA-PSS API execution, and a reproducible backteste

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 2 · Python _(updated 2026-06-23)_
  Polymarket Trade Bot

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 98 · Solidity _(updated 2026-06-23)_
  Easy setup and creation of a bot

- **[bit-nexusxtitmtdsuy/Polymarket_Bot](https://github.com/bit-nexusxtitmtdsuy/Polymarket_Bot)** ⭐ 32 · None _(updated 2026-06-23)_
  Polymarket Bot is a tool for interacting with Polymarket, a decentralized prediction market platform where users trade shares representing the probability of real-world events using cryptocurrency (pr

- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1913 · TypeScript _(updated 2026-06-23)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[sailorpepe/undesirables-x402-server](https://github.com/sailorpepe/undesirables-x402-server)** ⭐ 2 · Python _(updated 2026-06-23)_
  x402 micropayment-gated API for The Undesirables Shroomy Oracle — TCG grading, Monte Carlo simulation, and prediction market arbitrage. Agents pay per-call with USDC on Base.

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-06-23)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-21)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[aasuper1/kalshi-alpha-strategies](https://github.com/aasuper1/kalshi-alpha-strategies)** ⭐ 0 · Python _(updated 2026-06-19)_
  Three independent Kalshi event-contract trading strategies: latency (sell-worthless), liquidity-incentive market making, and a cross-market/correlation engine.

- **[talirabban/prediction-markets-thesis](https://github.com/talirabban/prediction-markets-thesis)** ⭐ 0 · Python _(updated 2026-06-10)_
  Quantitative analysis of Polymarket event contracts: calibration, ML-based pricing-error prediction, and out-of-sample strategy backtesting.

## 4. Perplexity Strategy Synthesis
For small accounts ($50–$500) on Kalshi and Polymarket in 2026, the most actionable strategies are **tail decay harvesting** (buying near-certain outcomes at 95–99¢), **cross-venue arbitrage** (locking in 2–5% price gaps between platforms), and **convergence/combinatorial plays** (constructing guaranteed-profit baskets across related markets), while avoiding complex market-making or high-frequency crypto strategies that require automation and large capital buffers [2][5].

### 1. **Tail Decay Harvesting** (“Obvious No” Strategy)
- **Concept**: Buy YES or NO on outcomes that are near-certain (>95% probability) when priced at 95–99¢. Hold until resolution to collect the $1 payout.
- **Time Horizon**: 1–30 days (depends on event resolution date) [2].
- **Price Threshold**: Enter only when market price ≥95¢ and your independent research confirms ≥95% likelihood [2].
- **Position Sizing**: 1–5% of bankroll per trade (e.g., $5–$25 for a $500 account) [2].
- **Why It Works for Small Accounts**: Low risk, minimal capital, and compounding through reinvestment [2].
- **Example**: Bet “NO” on “Will the Fed hike rates in June?” if polling and macro data suggest a hold [4].

### 2. **Cross-Venue Arbitrage**
- **Concept**: Identify identical events priced differently on Kalshi vs. Polymarket. Buy YES on the lower-priced venue and NO on the higher-priced one to lock in a guaranteed spread.
- **Time Horizon**: Seconds to hours (prices adjust rapidly) [2].
- **Price Gap Threshold**: Execute only if combined cost of opposing positions < $0.95 (i.e., ≥5% profit) [2].
  - Example: Polymarket = 60¢ (YES), Kalshi = 50¢ (YES) → Buy YES on Kalshi, NO on Polymarket → Guaranteed $0.10 profit per share [2].
- **Position Sizing**: Scale to available arbitrage opportunity; for small accounts, start with $10–$50 per arb [2].
- **Caveat**: Requires fast execution and monitoring; use tools like Ratio app to track wallets and prices [2].

### 3. **Convergence/Combinatorial Arbitrage**
- **Concept**: Combine multiple related markets (e.g., Fed rate hike + cut + hold) where prices don’t align, creating a basket that guarantees profit regardless of outcome.
- **Time Horizon**: 1–14 days (depends on event cluster resolution) [5].
- **Strategy Example**: 
  - Market A: “Hike” = 30¢, Market B: “Cut” = 20¢, Market C: “Hold” = 55¢ → Sum = 105¢ → Buy all three “YES” tokens → Guaranteed $0.05 profit [5].
- **Position Sizing**: Allocate 5–10% of bankroll per basket (e.g., $25–$50) [2].
- **Assetive for Small Accounts**: exploits mispricing in macro events (e.g., Fed decisions) where institutional players overreact [5].

### 4. **Edge Cases for Small Accounts ($50–$500)**
- **Avoid**: Market-making (spread farming) and high-frequency crypto contracts—they require automation, deep liquidity, and large capital [2][5].
- **Focus On**:
  - **

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-23 via Conway's auto-publisher.*
