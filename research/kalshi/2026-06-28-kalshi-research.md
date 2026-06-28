# Kalshi Nightly Research Brief — 2026-06-28

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-28T02:02:16, run time 19.7s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **Ask, Solve, Generate: Self-Evolving Unified Multimodal Understanding and Generation via Self-Consistency Rewards** _(prediction market)_
  [2026-06-25](https://arxiv.org/abs/2606.27376v1)
  Most unified large multimodal models (LMMs) that support both visual understanding and image generation still rely on curated post-training supervision, such as human annotations, preference labels, or external reward models. We ask whether a unified LMM can improve both abilities autonomously using only unlabeled images. We propose a self-evolving training framework with three internal roles: a P

- **World Action Models Enable Continual Imitation Learning with Recurrent Generative Replays** _(prediction market)_
  [2026-06-25](https://arxiv.org/abs/2606.27374v1)
  Going beyond predicting robot actions, World Action Models (WAMs) can also generate future visual observations. We build on this generative capability to propose Recurrent Generative Replay (REGEN), a continual imitation learning framework that synthesizes pseudo-replay trajectories, enabling a robot policy to rehearse previously learned tasks without storing their original human demonstrations. D

- **Paying More Attention to Visual Tokens in Self-Evolving Large Multimodal Models** _(prediction market)_
  [2026-06-25](https://arxiv.org/abs/2606.27373v1)
  Recently, self-evolving large multimodal models (LMMs) have received attention for improving visual reasoning in a purely unsupervised setting. However, multi-role self-play and self-consistency reward schemes in existing self-evolving LMMs optimize answer agreement without ensuring the decoder attends to visual content, relying instead on statistical language priors to produce self consistent out

- **Probing Probability Geometry with Schwinger--Dyson Identities: Score Mismatch, Fisher Information, and Configurational Temperature** _(binary option pricing convergence)_
  [2026-06-25](https://arxiv.org/abs/2606.27360v1)
  We develop a geometric interpretation of Schwinger--Dyson identities by showing that their violations are controlled by a single score-mismatch field $δs$. For an arbitrary sampled probability distribution $Q$ and equilibrium measure $P_{\rm eq}$, every Schwinger--Dyson violation is determined by $δs = \nabla \log (Q / P_{\rm eq})$, which characterizes the departure from equilibrium. Each Schwinge

- **Typical distances in high-genus triangulations** _(binary option pricing convergence)_
  [2026-06-25](https://arxiv.org/abs/2606.27357v1)
  We study the distance between two uniformly chosen points on a uniform random triangulation whose genus g is proportional to the number of faces 2n. We show that the distance rescaled by log(n) converges in probability to a deterministic constant, which answers a conjecture of Budzinski, Chapuy and Louf. The proof relies on the precise study of the volume growth of the ball of radius r for r of or

- **Valuing American options and Flexible Forwards contracts in time-dependent models** _(binary option pricing convergence)_
  [2026-06-25](https://arxiv.org/abs/2606.27335v1)
  A flexible forward (FF) is a customized FX hedging instrument that guarantees a fixed exchange rate while letting the holder choose the delivery date within a pre-agreed window. It is therefore an American-style option on timing, and its valuation must respect the volatility skew of the underlying currency pair. We price FF contracts (and, more generally, American options) under a time-inhomogeneo

- **Cultivating logical catalysts for fault-tolerant dyadic phase rotations** _(event-driven trading)_
  [2026-06-25](https://arxiv.org/abs/2606.27358v1)
  We introduce a surface-code cultivation protocol for reusable logical catalyst states that implement exact fine dyadic phase gates $Z^{2^{-b}}$ by phase kickback. The catalyst is an eigenstate of a high-period Clifford circuit $U$, with a direct construction supported on $O(2^b)$ logical qubits. Once cultivated, each invocation implements the target phase through a controlled-$U$ gadget, removing 

- **Exact and Deterministic Patch Descriptor Retrieval via Hierarchical Normalization** _(event-driven trading)_
  [2026-06-25](https://arxiv.org/abs/2606.27280v1)
  We present a patch descriptor retrieval method that returns the exact nearest neighbour -- provably identical to exhaustive full-vector search -- while evaluating only a small fraction of the database, and does so deterministically: the same (database, query) pair always produces the same result, independent of run order, thread count, or hardware. This contrasts with approximate nearest-neighbour

- **Advancing Omnimodal Embodied Agents from Isolated Skills to Everyday Physical Autonomy** _(event-driven trading)_
  [2026-06-25](https://arxiv.org/abs/2606.27251v1)
  Building persistent embodied agents in unstructured environments demands unified orchestration of heterogeneous tools spanning both cyber (APIs, IoT) and physical (manipulation, navigation) domains, coupled with autonomous recovery from physical failures that inevitably arise over extended operation. Existing systems treat these as separate problems: VLM-based planners lack a unified cyber-physica

- **All you need is log** _(sports betting arbitrage)_
  [2026-06-25](https://arxiv.org/abs/2606.27349v1)
  Comparing two probability distributions is a basic building block of statistics and machine learning, and the right family is well understood: the Rényi divergences of order $α\in[0,\infty]$ are the unique family monotone under data processing and additive on independent products. Many problems instead compare more than two distributions at once -- multi-population fairness, multi-prior PAC-Bayes 

- **BetXplain: An Explanation-Annotated Dataset for Detecting Manipulative Betting Advertisements on Social Media** _(sports betting arbitrage)_
  [2026-06-25](https://arxiv.org/abs/2606.27274v1)
  The promotion of betting applications on social media platforms has increased significantly in recent years. Many of these advertisements use persuasive techniques that may mislead users, encourage risky behavior, and potentially influence users' mental well-being. However, research on the automated detection of manipulative and deceptive betting advertisements remains limited due to the lack of p

- **State Representation Matters in Deep Reinforcement Learning: Application to Energy Trading** _(sports betting arbitrage)_
  [2026-06-25](https://arxiv.org/abs/2606.27032v1)
  Energy trading decisions depend not only on current market prices, but also on expected future market conditions, and operational constraints. This makes the state representation given to a reinforcement learning agent an important design choice. We study this in HydroDam, a pumped-storage arbitrage environment, using a fixed Double DQN agent. The environment, action space, reward function, networ

- **Specific absorption rate of uniaxial single-domain nanomagnets: stochastic spin dynamics versus linear response theory** _(Kelly criterion small bankroll)_
  [2026-06-25](https://arxiv.org/abs/2606.27351v1)
  We compute the specific absorption rate of a uniaxial single-domain nanomagnet driven by an alternating magnetic field by two methods: i) direct numerical integration of the stochastic (Langevin) Landau--Lifshitz--Gilbert equation (the LLL approach), and ii) linear response theory (LRT) based on the Debye susceptibility with the Néel relaxation time $τ_\mathrm{N}$. We first analytically show that 

- **CHIA: An open-source framework for principled, agentic AI-driven hardware/software co-design research** _(Kelly criterion small bankroll)_
  [2026-06-25](https://arxiv.org/abs/2606.27350v1)
  Agentic artificial intelligence shows great promise for radically improving the pace of innovation in hardware/software co-design research across computer architecture, systems, compilers, and VLSI. Thus far, however, applications of AI in these contexts have generally been demonstrated in isolated settings on small-scale problems, due to the difficulty of designing and deploying complex AI-infuse

- **RoPEMover: Depth-Aware Object Relocation via Positional Embeddings** _(Kelly criterion small bankroll)_
  [2026-06-25](https://arxiv.org/abs/2606.27332v1)
  Moving an object in a single image requires geometry-consistent spatial rearrangement, including handling occlusions, revealing previously unseen regions, and maintaining coherent shadows and reflections. Existing approaches are not well suited to this setting and often fail to preserve such scene-level consistency. We address this problem by introducing a geometry-aware object motion method that 

- **When Does Combining Language Models Help? A Co-Failure Ceiling on Routing, Voting, and Mixture-of-Agents Across 67 Frontier Models** _(tail risk harvesting)_
  [2026-06-25](https://arxiv.org/abs/2606.27288v1)
  Multi-model LLM systems such as routing, voting, cascades, fusion, and mixture-of-agents are used to beat single-model accuracy. We show that their gain is capped by a quantity the field rarely reports. For any policy whose output is one member model answer, accuracy cannot exceed one minus beta, where beta is the rate at which every model is wrong on the same query. In contrast, the usual diagnos

- **"Everyone Says Them": Deception Typologies, Probabilistic Trust, and Grassroots Safety Knowledge Among Gay Dating App Users in China** _(tail risk harvesting)_
  [2026-06-25](https://arxiv.org/abs/2606.27284v1)
  Gay dating applications have become critical platforms for sexual minority men to seek relationships and community, yet they also expose users to deceptive interactions that remain underexplored in HCI and CSCW research. This study examines how gay male users in China experience, identify, and respond to deception on dating applications. Through semi-structured interviews with 22 participants acro

- **Non-colliding space-time inhomogeneous Markov chains** _(tail risk harvesting)_
  [2026-06-25](https://arxiv.org/abs/2606.27261v1)
  We establish the explicit leading order asymptotics, with a quantitative error bound, of tail probabilities of collision times for a class of integrable space-time inhomogeneous Markov chains, in discrete and continuous time. The corresponding process conditioned not to intersect arises in interacting particle systems with local push-block interactions thereby confirming a recent prediction. The g

## 3. GitHub Repos (Recently Updated)
- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-28)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[dcamco/kalshi-snapshots](https://github.com/dcamco/kalshi-snapshots)** ⭐ 0 · HTML _(updated 2026-06-28)_
  Public read-only snapshots of the Kalshi paper-trading dashboard (main repo private)

- **[anglil/kalshi-ai-trading-bot](https://github.com/anglil/kalshi-ai-trading-bot)** ⭐ 6 · Python _(updated 2026-06-28)_
  AI-powered Kalshi prediction market trading bot using Gemini

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-28)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-28)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[TexasCoding/kalshi-python-sdk](https://github.com/TexasCoding/kalshi-python-sdk)** ⭐ 1 · Python _(updated 2026-06-27)_
  Professional Python SDK for the Kalshi prediction markets API

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 2 · Python _(updated 2026-06-28)_
  Polymarket Trade Bot

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 98 · Solidity _(updated 2026-06-28)_
  Easy setup and creation of a bot

- **[bit-nexusxtitmtdsuy/Polymarket_Bot](https://github.com/bit-nexusxtitmtdsuy/Polymarket_Bot)** ⭐ 32 · None _(updated 2026-06-28)_
  Polymarket Bot is a tool for interacting with Polymarket, a decentralized prediction market platform where users trade shares representing the probability of real-world events using cryptocurrency (pr

- **[DanielTabakman/Probability-prediction-engine](https://github.com/DanielTabakman/Probability-prediction-engine)** ⭐ 0 · Python _(updated 2026-06-28)_
  Probability prediction engine. used to understand what the market is saying using calls and puts to understand the probability distribution of future prices. will eventually cross reference with predi

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-06-28)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant)** ⭐ 2 · Python _(updated 2026-06-28)_
  Trade Kalshi prediction markets with a quantitative system designed for fee-aware position sizing and statistical arbitrage.

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-27)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[jhunter11/openclaw-kalshi-operator](https://github.com/jhunter11/openclaw-kalshi-operator)** ⭐ 0 · HTML _(updated 2026-06-26)_
  Autonomous AI agent operating an event-contract research & trading loop (Kalshi). Python research/orchestration harness + strategy gates + learning log.

- **[aasuper1/kalshi-alpha-strategies](https://github.com/aasuper1/kalshi-alpha-strategies)** ⭐ 0 · Python _(updated 2026-06-19)_
  Three independent Kalshi event-contract trading strategies: latency (sell-worthless), liquidity-incentive market making, and a cross-market/correlation engine.

## 4. Perplexity Strategy Synthesis
The most actionable prediction market strategies for Kalshi and Polymarket in 2026 for small accounts ($50–$500) are **cross-platform arbitrage on wide gaps (5¢+)**, **domain-expertise trading in niche markets**, and **tail decay harvesting on "impossible" events**, executed with **1–5% position sizing per idea** and **weekly capital recycling**. These strategies leverage the 2–5% price gaps between venues, the unlimited position sizes for non-systemic events, and the structural mispricing of low-probability contracts, as detailed in recent 2026 guides [1][2].

### 1. Cross-Venue Arbitrage (The "Small Account" Arbitrage Play)
While high-frequency arbitrage often requires automation for narrow spreads, small accounts can profit manually by targeting **wide, structural mispricing**.

*   **Strategy Parameters:**
    *   **Time Horizon:** Slow-moving markets with resolution >1 week to avoid "racing" fees.
    *   **Price Threshold:** Target **YES/NO gaps of 5¢ or more** (e.g., Kalshi YES at $0.42, Polymarket YES at $0.37) [2].
    *   **Position Sizing:** **10–20% of total bankroll** per arbitrage pair, split equally across venues (e.g., $50 split as $25 on Kalshi, $25 on Polymarket) [2].
    *   **Fees:** Account for Polymarket’s category-based fees (up to 1.8%) and ensure the net spread exceeds the sum of fees on both legs [5].
*   **Execution Checklist:**
    1.  Verify **real book depth** behind the headline price (avoid thin liquidity traps) [2].
    2.  Confirm **fee math** on both legs (ensure net profit > 0) [2].
    3.  Match **resolution criteria** exactly (e.g., ensure "Fed Rate Hold" defines the same time window on both) [2].
*   **Why it works:** Arbitrage between platforms is possible with 2–5% price gaps on major events like Fed rates or election outcomes [1].

### 2. Tail Decay Harvesting (The "Impossible Event" Strategy)
This strategy involves buying **YES shares on extreme "impossible" events** (e.g., "US invades Cuba in 2026") where the market price is artificially low due to panic or overreaction, then holding for the price to decay toward zero if the event doesn't happen, or to rise if the event is unlikely but exhibits "tail risk" [2][6].

*   **Strategy Parameters:**
    *   **Time Horizon:** Short-to-medium term (1–6 months) to allow time for probability decay.
    *   **Price Threshold:** Target shares priced **< $0.05** (indicating <5% perceived probability) [6].
    *   **Position Sizing:** **1–2% of bankroll** per trade; highly diversified across uncorrelated "impossible" events [2][6].
    *   **Logic:** Buy YES on dramatic events (e.g., "US acquires part of Greenland in 2026") where the market price is too low; over time, if the event doesn't happen, the price decays to zero, but you profit from the *gap* if you sell early or hold if the market corrects [6].
*   **Key Insight:** The strategy is "finding mispriced markets" where panic drives prices below true probability [6]. Never put everything in; **small positions and broad divers

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-28 via Conway's auto-publisher.*
