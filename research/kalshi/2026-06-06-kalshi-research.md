# Kalshi Nightly Research Brief — 2026-06-06

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-06T02:01:27, run time 49.2s._

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
- **[InTheNightRaider/KalshiTradingBot](https://github.com/InTheNightRaider/KalshiTradingBot)** ⭐ 0 · HTML _(updated 2026-06-06)_
  This is the public facing trading bot repo. 

- **[SpartanLabsXyz/simmer-sdk](https://github.com/SpartanLabsXyz/simmer-sdk)** ⭐ 45 · Python _(updated 2026-06-06)_
  Python SDK for Agentic Prediction Market trading

- **[dcamco/kalshi-snapshots](https://github.com/dcamco/kalshi-snapshots)** ⭐ 0 · HTML _(updated 2026-06-06)_
  Public read-only snapshots of the Kalshi paper-trading dashboard (main repo private)

- **[lweiss01/pmwatch](https://github.com/lweiss01/pmwatch)** ⭐ 1 · HTML _(updated 2026-06-06)_
  Open-source anomaly detector for politically-sensitive Kalshi prediction markets. Flags unusual trading patterns that may precede public announcements. Public API only, no auth required.

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-06)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-06)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 0 · Python _(updated 2026-06-06)_
  Polymarket Trade Bot

- **[rexlau-prog/pm-crypto-trend-dashboard](https://github.com/rexlau-prog/pm-crypto-trend-dashboard)** ⭐ 0 · HTML _(updated 2026-06-06)_
  Report dashboard for the pm_crypto_trend Polymarket 5-min trading bot

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 97 · Solidity _(updated 2026-06-06)_
  Easy setup and creation of a bot

- **[irfndi/NeuraTrade](https://github.com/irfndi/NeuraTrade)** ⭐ 1 · Go _(updated 2026-06-06)_
  NeuraTrade is a high-performance, scalable platform designed for real-time cryptocurrency arbitrage detection, advanced technical analysis, and prediction market.

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-06-06)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant)** ⭐ 2 · Python _(updated 2026-06-06)_
  Trade Kalshi prediction markets with a quantitative system designed for fee-aware position sizing and statistical arbitrage.

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

- **[Waike122333/Automated-Trading-Kalshi](https://github.com/Waike122333/Automated-Trading-Kalshi)** ⭐ 0 · None _(updated 2026-03-17)_
  An algorithmic trading bot for kalshi.com event contracts that automates trading strategies based on economic data, news events, weather patterns, and political markets in real-time.

- **[GitHubMaster07/Enterprise-Test-Strategy-Blueprint](https://github.com/GitHubMaster07/Enterprise-Test-Strategy-Blueprint)** ⭐ 0 · None _(updated 2026-01-17)_
  Enterprise‑grade QA Automation & Test Strategy Blueprint for UI, API, DB, Events, Contracts, CI/CD, and Non‑Functional Testing.

## 4. Perplexity Strategy Synthesis
The most actionable 2026 prediction-market edges on **Kalshi** and **Polymarket** are still the classic ones: **fading late overreaction**, **cross-venue price discrepancies**, and **convergence trades** where you buy dislocated contracts that should mechanically settle near the same value. For **small accounts** (\$50–\$500), the best opportunities are usually **low-priced tails**, **mispriced binary pairs**, and **very short-horizon trades** where fees and illiquidity don’t eat the edge. The platform mechanics matter: both venues are CLOB-style markets with limit orders, visible depth, and the ability to post passive liquidity instead of crossing the spread.[2][8][1]

## 1) Tail decay harvesting
This is the most usable “small account” strategy when a market’s price gets pushed to an extreme and then slowly mean-reverts or collapses as the event date passes without new information.

- **What to look for:** contracts trading at **90–99c** or **1–10c** that are being held up mostly by narrative, not fresh information.[1][2]
- **Why it works:** as time passes, the market often overprices a dramatic outcome and then “decays” as realization improves.
- **Best time horizon:** **hours to days** for news-driven events; **1–4 weeks** for deadline-based markets.
- **Practical trigger:** enter only when the probability-implied price is **at least 10–15 points away** from your own estimate, and preferably when the order book is thin on the side you want to fade.[1][3]
- **Position sizing for \$50–\$500:** risk **2–5% of bankroll per trade**; on a \$100 account that means roughly **\$2–\$5** per idea, because one bad fill or delayed resolution can tie up capital.
- **Execution tip:** use **resting limit orders** rather than market orders, since both platforms expose tradable depth and limit pricing.[1][8]

A concrete example: if a contract jumps to **92c** after a headline but there is no follow-through in the next few hours, a small account can place a passive offer near **88–90c** and target a decay back toward the **80s** as the market digests the event. The edge here is not “being right on the headline”; it is buying after the emotional spike has exhausted itself.[1][2]

## 2) Cross-venue arbitrage
This is the cleanest structural edge when the same event is listed on both platforms and the prices diverge beyond fees and transfer friction.

- **What to look for:** Kalshi vs. Polymarket markets that map to the same real-world outcome and are off by **3–8 cents or more** after accounting for fees, withdrawal friction, and fill uncertainty.[2][6][8]
- **Best use case:** events with simple settlement language, high attention, and active two-sided markets.
- **Trade structure:** buy the cheaper venue and sell the richer one, or, if shorting is difficult, buy the underpriced side while leaning against the overpriced side through a correlated market.
- **Time horizon:** **minutes to a few hours**; pure arb disappears quickly once visible.
- **Position sizing:** with \$50–\$500, keep each leg tiny—often **\$10–\$50 notional**—because failed hedges can create accidental directional exposure.

The key practical point is that Kalshi and Polymarket both trade on event probabilities, and the ecosystem in 2026 is large enough that traders increasingly use analytics to find arbitrage and cross-market dislocations.[2][3] If the same yes/no event is **60c on one venue and 54c on the other**, the spread may be tradable i

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-06 via Conway's auto-publisher.*
