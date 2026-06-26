# Kalshi Nightly Research Brief — 2026-06-26

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-26T02:01:45, run time 18.3s._

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
- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1917 · TypeScript _(updated 2026-06-26)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[aasghar311-source/RAID](https://github.com/aasghar311-source/RAID)** ⭐ 0 · Python _(updated 2026-06-26)_
  Rapid AI Decision Engine — crypto + Kalshi paper trading bot

- **[oleksandrbannick/Meridian](https://github.com/oleksandrbannick/Meridian)** ⭐ 2 · Python _(updated 2026-06-26)_
  kalshi automated trading bot with custom UI

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-26)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-26)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[vcorp-dev/kalshi-price-data](https://github.com/vcorp-dev/kalshi-price-data)** ⭐ 0 · Python _(updated 2026-06-25)_
  Kalshi price data — live yes/no prices, full order-book depth, and price history in one API. Python client for the DepthFeed aggregator (Kalshi + Polymarket + Limitless).

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 2 · Python _(updated 2026-06-26)_
  Polymarket Trade Bot

- **[Casiniza/polymarket-bot](https://github.com/Casiniza/polymarket-bot)** ⭐ 2 · Python _(updated 2026-06-26)_
  Automated Polymarket trading bot with GitHub Actions

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 98 · Solidity _(updated 2026-06-26)_
  Easy setup and creation of a bot

- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1917 · TypeScript _(updated 2026-06-26)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[sftgroup/predx](https://github.com/sftgroup/predx)** ⭐ 0 · None _(updated 2026-06-26)_
  PredX: Prediction Market + Arbitrage Engine — Fork Polymarket/Gnosis CTF, Ceres DID, 0x incentives, cross-market arbitrage

- **[Trum3it/polymarket-arbitrage-bot](https://github.com/Trum3it/polymarket-arbitrage-bot)** ⭐ 36 · TypeScript _(updated 2026-06-26)_
  Polymarket arbitrage bot - automated prediction market trading and opportunity detection. Work on crypto prediction markets. Subscribe BTC, ETH, SOL, XRP price tick and real time analyse. Make decisio

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-21)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[aasuper1/kalshi-alpha-strategies](https://github.com/aasuper1/kalshi-alpha-strategies)** ⭐ 0 · Python _(updated 2026-06-19)_
  Three independent Kalshi event-contract trading strategies: latency (sell-worthless), liquidity-incentive market making, and a cross-market/correlation engine.

- **[talirabban/prediction-markets-thesis](https://github.com/talirabban/prediction-markets-thesis)** ⭐ 0 · Python _(updated 2026-06-10)_
  Quantitative analysis of Polymarket event contracts: calibration, ML-based pricing-error prediction, and out-of-sample strategy backtesting.

## 4. Perplexity Strategy Synthesis
There are **no specific, publicly documented trading strategies** with concrete parameters (time horizons, price thresholds, position sizing) for **tail decay harvesting**, **cross-venue arbitrage**, or **convergence plays** on Kalshi and Polymarket as of 2026 in the provided search results because no recent blog posts, Substacks, or Twitter threads covering these niche strategies were included in the data.

However, based on the **general market dynamics** described in the 2026 guides, here is a concrete framework for small accounts ($50–$500) to apply these concepts, derived from the available industry standards:

### 1. Cross-Venue Arbitrage (The Only Concrete Strategy Available)
This is the most actionable strategy for small accounts because the market structure explicitly supports it.
*   **Market Reality:** 2–5% price gaps on major events exist between Kalshi and Polymarket [1].
*   **Strategy Parameters:**
    *   **Time Horizon:** Immediate execution (seconds to minutes) before the gap closes.
    *   **Price Threshold:** Target events where the "Yes" price on Kalshi is **≥ 2% higher** than on Polymarket (or vice versa for "No") [1].
    *   **Position Sizing:** Use the **Kelly formula** to size positions, but for a $50–$500 account, cap exposure per trade at **10–20% of total capital** to mitigate liquidity risk [1].
    *   **Action:** Buy the lower-priced contract on one platform and immediately sell the higher-priced contract on the other to lock in the spread [1][6].
*   **Small Account Advantage:** Unlike traditional finance, arbitrage here requires no minimum capital and settles on-chain or via exchange, allowing fluid entry/exit similar to stocks [6].

### 2. Convergence Plays (Tail Decay Harvesting Framework)
While no specific "tail decay" blog post exists, the general principle of **convergence** (prices moving toward the true probability as the event resolves) is standard.
*   **Strategy Logic:** As the event date nears, "tail" risk (uncertainty) decays, causing prices to converge to 0% or 100% unless news intervenes [4].
*   **Concrete Parameters for Small Accounts:**
    *   **Time Horizon:** Enter trades when an event is **7–14 days away** and exit when the event is **<2 days away** [4].
    *   **Price Threshold:** Target contracts where the price is **mispriced by >5%** relative to early polling or economic data [1].
    *   **Position Sizing:** Use **1/3 Kelly** sizing (conservative) to avoid over-leveraging on long-dated uncertainty [1].
    *   **Hedging:** Hedge with options if available to protect against sudden news shocks [1].

### 3. Edge Cases & Small Account Profitability
For accounts with $50–$500, the primary edge is **speed and flexibility** in niche markets.
*   **Niche Focus:** Avoid major political events (high liquidity, low alpha) and focus on **sports betting** (70% of Kalshi revenue) or **pop-culture events** (e.g., "Will the word 'stupid' appear in headlines?") where institutional funds are less active [2][7].
*   **Fee Efficiency:**
    *   **Kalshi:** Often has lower fees for institutional volume, but check retail tiers.
    *   **Polymarket:** Charges category-based fees up to **1.8%**, which can eat small profits if not calculated [3].


---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-26 via Conway's auto-publisher.*
