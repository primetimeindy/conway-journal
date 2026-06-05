# Kalshi Nightly Research Brief — 2026-06-05

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-05T02:03:50, run time 19.7s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **TempoVLA: Learning Speed-Controllable Vision-Language-Action Policies** _(prediction market)_
  [2026-06-04](https://arxiv.org/abs/2606.06491v1)
  Robot manipulation alternates between low-risk transit phases that call for fast execution and high-risk contact stages that demand slow, precise motion. Yet existing Vision-Language-Action models (VLAs) only inherit a single fixed speed from training demonstrations. Prior efforts to accelerate VLAs through model compression, KV-cache reuse, or reinforcement learning only shift the policy from one

- **DNQ: Deep Nash Q-Network for Partially Observable n-Player Games** _(prediction market)_
  [2026-06-04](https://arxiv.org/abs/2606.06480v1)
  Many real-world competitive systems require multiple decision-makers to act simultaneously under shared constraints, limited information, and repeated interaction, as in auctions, resource allocation, and security competition. We study multi-turn simultaneous bidding as a controlled testbed for such problems and propose DNQ, a solver-in-the-loop equilibrium supervision framework for training biddi

- **Pretraining Recurrent Networks without Recurrence** _(prediction market)_
  [2026-06-04](https://arxiv.org/abs/2606.06479v1)
  Training recurrent neural networks (RNNs) requires assigning credit across long sequences of computations. Standard backpropagation through time (BPTT) addresses this problem poorly: it is sequential in time, limiting parallelism, and suffers from vanishing or exploding gradients, making long-range associations difficult to learn. We propose Supervised Memory Training (SMT), a method for training 

- **Homeomorphic modified wave operators for the Vlasov-Poisson system** _(binary option pricing convergence)_
  [2026-06-04](https://arxiv.org/abs/2606.06488v1)
  We prove modified scattering for small data solutions to the Vlasov-Poisson system in a functional framework where the initial data, scattering states, and asymptotic convergence are measured in the same topology. In addition, we show that the corresponding wave operators define homeomorphisms between the spaces of initial and scattering data, while enjoying a local Lipschitz continuity property i

- **Two-Sample Hypothesis Testing for Subspace Equality in Network Data** _(binary option pricing convergence)_
  [2026-06-04](https://arxiv.org/abs/2606.06482v1)
  In many settings one is often interested in determining whether two networks share some joint structural connectivity patterns such as communities. However, while communities may be shared across networks, edge probabilities may differ significantly. Therefore, in this paper we consider testing a general null hypothesis that two networks have the same underlying subspace, which in particular inclu

- **Short Gravitational-Wave Transients as Probes of Cosmic Domain Walls** _(binary option pricing convergence)_
  [2026-06-04](https://arxiv.org/abs/2606.06478v1)
  GW190521 and GW231123 have been reported as short-duration gravitational-wave transients consistent with very massive binary black hole (BBH) coalescences whose inferred parameters, i.e., exceptionally high total masses and spin magnitudes, challenge standard isolated binary stellar evolution. We test a topological dark matter (TDM) interpretation invoking cosmic domain walls by fitting a physical

- **DNQ: Deep Nash Q-Network for Partially Observable n-Player Games** _(event-driven trading)_
  [2026-06-04](https://arxiv.org/abs/2606.06480v1)
  Many real-world competitive systems require multiple decision-makers to act simultaneously under shared constraints, limited information, and repeated interaction, as in auctions, resource allocation, and security competition. We study multi-turn simultaneous bidding as a controlled testbed for such problems and propose DNQ, a solver-in-the-loop equilibrium supervision framework for training biddi

- **You Only Index Once: Cross-Layer Sparse Attention with Shared Routing** _(event-driven trading)_
  [2026-06-04](https://arxiv.org/abs/2606.06467v1)
  Long-context inference in modern LLMs is increasingly constrained by decoding efficiency, especially in reasoning-heavy settings where models generate long intermediate chains of thought. Existing sparse attention methods often face a practical efficiency-quality trade-off. Structured block sparse methods typically provide stronger acceleration but incur noticeable quality loss, while token sparse

- **Event Detection for Parameter-to-KPI Dependency Learning for AI-RAN** _(event-driven trading)_
  [2026-06-04](https://arxiv.org/abs/2606.06459v1)
  Next-generation wireless networks are expected to rely on multiple concurrent AI-driven control functions that optimize different network objectives simultaneously, particularly in AI-integrated and open radio access network architectures such as AI Radio Access Network (AI-RAN) and Open Radio Access Network (O-RAN). When these functions interact, they can interfere with one another in ways that a

- **Derivative-Informed Operator Learning for Finance: On-the-Fly Greeks, Surfaces, Hedging, and Control** _(sports betting arbitrage)_
  [2026-06-04](https://arxiv.org/abs/2606.05900v1)
  Financial decision systems require fast surrogate models for pricing, calibration, hedging, XVA, stress testing, and portfolio optimization. Standard neural surrogates reproduce prices or risk quantities, but downstream tasks depend as much on derivatives: deltas, vegas, curve and credit-spread sensitivities, exposure and objective gradients. We formulate a derivative-informed operator-learning fr

- **A formal framework for the economic security of DeFi compositions** _(sports betting arbitrage)_
  [2026-06-03](https://arxiv.org/abs/2606.05418v1)
  Decentralized Finance (DeFi) services are usually constructed by composing a variety of smart contracts. While composability is a key driver of the success of DeFi, it also creates security risks: adversaries may exploit interactions between newly deployed contracts and the pre-existing ones to inflict economic losses. We introduce MEV non-interference, a formal security notion for DeFi composabil

- **4D Reconstruction from Sparse Dynamic Cameras** _(sports betting arbitrage)_
  [2026-06-03](https://arxiv.org/abs/2606.04593v1)
  Although dynamic 3D (i.e., 4D) reconstruction from a monocular dynamic camera has recently advanced, it remains fundamentally limited by depth ambiguity. In this paper, we focus on an alternative practical way, i.e., sparse dynamic camera setup, where a handful of independently moving cameras capture the same subjects. While keeping capture costs low, this setup introduces multi-view constraints a

- **Homeomorphic modified wave operators for the Vlasov-Poisson system** _(Kelly criterion small bankroll)_
  [2026-06-04](https://arxiv.org/abs/2606.06488v1)
  We prove modified scattering for small data solutions to the Vlasov-Poisson system in a functional framework where the initial data, scattering states, and asymptotic convergence are measured in the same topology. In addition, we show that the corresponding wave operators define homeomorphisms between the spaces of initial and scattering data, while enjoying a local Lipschitz continuity property i

- **Numerical self-force calculations for scalar particles, formulated in the lab frame** _(Kelly criterion small bankroll)_
  [2026-06-04](https://arxiv.org/abs/2606.06487v1)
  We derive equations of motion for scalar particles self-consistently interacting with a scalar field,including the radiation produced by the particles' acceleration. Our approach differs in three key aspects from current methods: (1) we assume a small but finite discretization length scale $h$, which allows us to treat the particle as a small but finite object, (2) we choose the state vector for t

- **When positive and negative pairs differ in femtoscopy: residual Coulomb and isospin effects** _(Kelly criterion small bankroll)_
  [2026-06-04](https://arxiv.org/abs/2606.06472v1)
  We study charge-dependent modifications of identical-pion and identical-kaon femtoscopic correlation functions from two sources: the residual Coulomb field of the charged source and isospin-related hadronic dynamics. The residual Coulomb effect is modeled with a modified Retiere--Lisa blast-wave source, where the same emitted particles are propagated with positive and negative charge signs through

- **TailLoR: Protecting Principal Components in Parameter-Efficient Continual Learning** _(tail risk harvesting)_
  [2026-06-04](https://arxiv.org/abs/2606.06494v1)
  Parameter-efficient finetuning methods based on spectral decomposition have enabled progress in Continual Learning. In this paper we introduce TailLoR, which utilizes the singular bases U and V of the pre-trained weights as a fixed reference frame to learn a low-rank update applied to the singular value matrix. A soft spectral penalty discourages updates aligned with dominant singular directions, 

- **TempoVLA: Learning Speed-Controllable Vision-Language-Action Policies** _(tail risk harvesting)_
  [2026-06-04](https://arxiv.org/abs/2606.06491v1)
  Robot manipulation alternates between low-risk transit phases that call for fast execution and high-risk contact stages that demand slow, precise motion. Yet existing Vision-Language-Action models (VLAs) only inherit a single fixed speed from training demonstrations. Prior efforts to accelerate VLAs through model compression, KV-cache reuse, or reinforcement learning only shift the policy from one

- **How abundant are good interpolators?** _(tail risk harvesting)_
  [2026-06-04](https://arxiv.org/abs/2606.06469v1)
  Let $S$ be the set of unit norm linear classifiers $θ\in \mathbb{R}^d$ which correctly classify every point of a labeled dataset $(X_i,y_i)_{i=1}^n$, $X_i \in \mathbb{R}^d$, $y_i \in \{-1,+1\}$, with a possibly negative margin $κ$ fixed in advance. Under two natural data-generating distributions of the $(X,y)$ pairs -- a Gaussian mixture model and a logistic model with Gaussian features -- and in 

## 3. GitHub Repos (Recently Updated)
- **[InTheNightRaider/KalshiTradingBot](https://github.com/InTheNightRaider/KalshiTradingBot)** ⭐ 0 · HTML _(updated 2026-06-05)_
  This is the public facing trading bot repo. 

- **[dcamco/kalshi-snapshots](https://github.com/dcamco/kalshi-snapshots)** ⭐ 0 · HTML _(updated 2026-06-05)_
  Public read-only snapshots of the Kalshi paper-trading dashboard (main repo private)

- **[anglil/kalshi-ai-trading-bot](https://github.com/anglil/kalshi-ai-trading-bot)** ⭐ 3 · Python _(updated 2026-06-05)_
  AI-powered Kalshi prediction market trading bot using Gemini

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-05)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-05)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[rockmundada/kalshi-weather-bot](https://github.com/rockmundada/kalshi-weather-bot)** ⭐ 0 · Python _(updated 2026-06-04)_
  Automated weather derivatives trading system for Kalshi — 5 API integrations, 10-chart analytics dashboard, data-driven strategy from 339 analyzed trades

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 0 · Python _(updated 2026-06-05)_
  Polymarket Trade Bot

- **[Casiniza/polymarket-bot](https://github.com/Casiniza/polymarket-bot)** ⭐ 1 · Python _(updated 2026-06-05)_
  Automated Polymarket trading bot with GitHub Actions

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 97 · Solidity _(updated 2026-06-05)_
  Easy setup and creation of a bot

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-06-05)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant)** ⭐ 2 · Python _(updated 2026-06-05)_
  Trade Kalshi prediction markets with a quantitative system designed for fee-aware position sizing and statistical arbitrage.

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-06-05)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

- **[Waike122333/Automated-Trading-Kalshi](https://github.com/Waike122333/Automated-Trading-Kalshi)** ⭐ 0 · None _(updated 2026-03-17)_
  An algorithmic trading bot for kalshi.com event contracts that automates trading strategies based on economic data, news events, weather patterns, and political markets in real-time.

- **[GitHubMaster07/Enterprise-Test-Strategy-Blueprint](https://github.com/GitHubMaster07/Enterprise-Test-Strategy-Blueprint)** ⭐ 0 · None _(updated 2026-01-17)_
  Enterprise‑grade QA Automation & Test Strategy Blueprint for UI, API, DB, Events, Contracts, CI/CD, and Non‑Functional Testing.

## 4. Perplexity Strategy Synthesis
The most actionable edge set for **2026 prediction markets** is still the same core trio: **cross-venue arbitrage**, **late-stage convergence trades**, and **tail-decay harvesting** on overextended prices. For **small accounts ($50–500)**, the best opportunities are usually *not* classic risk-free arb because fees, limits, and fills eat most of it; instead, the practical edge is trading short-dated mispricings, fading overreactions, and using tiny size where the market’s implied probability is clearly off by several points.[1][2][3]

**1) Tail-decay harvesting (“fade the spike”)**

- The most repeatable version is to **sell YES after a news shock pushes a contract far above fair value**, then cover as the market cools over the next few hours or days.[2]
- The strongest setup is a **binary news market** where the headline is emotionally salient but does **not** change the underlying event probability much; these are the “nothing ever happens” spots described in the 2026 trading guide.[2]
- **Entry rule:** look for a contract jumping to roughly **70–95c** on a headline, then compare against your own estimate and external evidence; if you think the true probability is at least **5–10 points lower**, fading becomes plausible.[2]
- **Time horizon:** usually **minutes to 3 days** for news-driven spikes; shorter when liquidity is high and the headline is already fully digested.[2]
- **Position sizing:** for small accounts, keep each fade to **5–15% of bankroll** so you can survive being early; on a $100 account, that means about **$5–15** per idea.[2]
- This style works best on **high-volume markets** where prices overshoot because retail flows dominate, not on thin markets where you cannot exit.[2][3]

**2) Cross-venue arbitrage (Kalshi vs Polymarket vs other venues)**

- If the same event is listed on both venues, compare the **implied probabilities after fees and settlement differences**; a gap only matters if it survives costs.[1]
- A useful rule from the systematic-edges writeup is to trade only when the spread is larger than the **round-trip transaction cost**, because otherwise the “arb” is fake.[1]
- Practical threshold: target at least **2–4 percentage points** of edge *after* fees/slippage before risking capital, especially for small accounts.[1]
- For two complementary outcomes, if the **sum of opposing probabilities is meaningfully below 100%** after costs, you may have a buy-both / buy-all style arb; if it is above 100%, the reverse side may exist where available.[1]
- **Time horizon:** usually **intraday to a few days**, because the edge disappears quickly once traders notice it.[1]
- For small accounts, the limitation is that true arbs often require enough size to matter; if you can only deploy **$50–500**, focus on **single-contract mispricings** rather than trying to construct large multi-leg baskets.[1]
- Polymarket may often be the **leading / more informative venue in the final hours** because of liquidity, so price discovery can start there and then leak to Kalshi; that can create short-lived lead-lag trades if you monitor both books.[1]

**3) Convergence plays**

- These are trades where you buy a contract that is **temporarily underpriced relative to its likely final settlement** and wait for the market to drift toward that outcome as information accumulates.[2]
- The most actionable version is the **high-liquidity favorite** trade: if a market should realistically be around **90–95c** but trades at **75–85c**, yo

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-05 via Conway's auto-publisher.*
