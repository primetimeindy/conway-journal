# Kalshi Nightly Research Brief — 2026-06-27

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-27T02:01:58, run time 18.7s._

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
- **[UnitedStars111/polymarket-copy-trading-bot](https://github.com/UnitedStars111/polymarket-copy-trading-bot)** ⭐ 0 · HTML _(updated 2026-06-27)_
  Copy trades from Polymarket leader addresses across politics, sports, crypto, and more with config in trade.toml and secrets in .env

- **[MusicBoiyzzz/Polymarket-Weather-Bot](https://github.com/MusicBoiyzzz/Polymarket-Weather-Bot)** ⭐ 1 · TypeScript _(updated 2026-06-27)_
  Automate Polymarket weather trades with Kelly sizing, NWS forecast scans, and trade simulation for temperature market edge

- **[Yury617/polymarket-impulse-monitoring-trading-bot](https://github.com/Yury617/polymarket-impulse-monitoring-trading-bot)** ⭐ 1 · TypeScript _(updated 2026-06-27)_
  Automate Polymarket momentum trading with impulse detection, trailing stops, hedging, and settlement tracking in real time

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-27)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-27)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[TexasCoding/kalshi-python-sdk](https://github.com/TexasCoding/kalshi-python-sdk)** ⭐ 1 · Python _(updated 2026-06-26)_
  Professional Python SDK for the Kalshi prediction markets API

- **[rexlau-prog/pm-crypto-trend-dashboard](https://github.com/rexlau-prog/pm-crypto-trend-dashboard)** ⭐ 0 · HTML _(updated 2026-06-27)_
  Report dashboard for the pm_crypto_trend Polymarket 5-min trading bot

- **[Corettafinnougricspeaking368/Polymarket-Arbitrage-Trading-Bot-Spreadmaker](https://github.com/Corettafinnougricspeaking368/Polymarket-Arbitrage-Trading-Bot-Spreadmaker)** ⭐ 0 · TypeScript _(updated 2026-06-27)_
  Build a TypeScript Polymarket arbitrage bot that makes hedged two-sided spread trades on 15-minute crypto markets and keeps entry cost below a set limit

- **[Casiniza/polymarket-bot](https://github.com/Casiniza/polymarket-bot)** ⭐ 2 · Python _(updated 2026-06-27)_
  Automated Polymarket trading bot with GitHub Actions

- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1918 · TypeScript _(updated 2026-06-27)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[RizkyDCuirass/Polymarket-Kalshi-arbitrage-bot](https://github.com/RizkyDCuirass/Polymarket-Kalshi-arbitrage-bot)** ⭐ 0 · TypeScript _(updated 2026-06-27)_
  Detect price gaps between Polymarket and Kalshi to make timely buy decisions using configurable arbitrage rules for efficient trading.

- **[Duollc/PredictionMarket](https://github.com/Duollc/PredictionMarket)** ⭐ 0 · None _(updated 2026-06-27)_
  📊 Enhance prediction market security with a complete audit guide, featuring real incidents and a comprehensive checklist for risk management.

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-26)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[jhunter11/openclaw-kalshi-operator](https://github.com/jhunter11/openclaw-kalshi-operator)** ⭐ 0 · HTML _(updated 2026-06-26)_
  Autonomous AI agent operating an event-contract research & trading loop (Kalshi). Python research/orchestration harness + strategy gates + learning log.

- **[aasuper1/kalshi-alpha-strategies](https://github.com/aasuper1/kalshi-alpha-strategies)** ⭐ 0 · Python _(updated 2026-06-19)_
  Three independent Kalshi event-contract trading strategies: latency (sell-worthless), liquidity-incentive market making, and a cross-market/correlation engine.

## 4. Perplexity Strategy Synthesis
For small accounts ($50–$500) on Kalshi and Polymarket in 2026, the most actionable strategies are **convergence plays** (buying near-certain outcomes at $0.90–$0.95), **cross-venue arbitrage** (locking in $0.03+ gaps), and **time-decay harvesting** (capturing the 2–5% annual drift toward settlement), while **tail decay harvesting** is generally too risky for capital-constrained traders due to binary event risk[1][4]. Cross-venue arbitrage remains the most reliable profit source, with 2–5% price gaps common on major events like elections or crypto price milestones[1].

| Strategy | Time Horizon | Price Threshold | Position Sizing | Small Account Viability |
|----------|--------------|-----------------|-----------------|--------------------------|
| **Convergence Plays** | Days to resolution | $0.85–$0.95 (Yes) | 2–5% of capital | **High**: Low risk if probability >90%[4] |
| **Cross-Venue Arb** | Real-time (minutes) | Gap ≥$0.03 net of fees | 50% of capital per leg | **High**: Arbitarage locks in profit regardless of outcome[4] |
| **Time/Decay Harvest** | Weeks to months | $0.40–$0.60 (mid-prob) | 2–5% of capital | **Moderate**: Requires patience; 2–5% annual return[1] |
| **Tail Decay** | Hours to days | Extreme odds (<$0.05 or >$0.95) | 1–2% of capital | **Low**: Binary risk; small accounts can lose entire stake quickly[4] |

### Concrete Strategy Parameters

1. **Convergence Plays (Best for Small Accounts)**  
   - **Action**: Buy “Yes” at **$0.90–$0.95** on events with >90% implied probability (e.g., “Will Bitcoin exceed $100k by 2026?” if odds are 95%).  
   - **Time Horizon**: 1–7 days (until resolution).  
   - **Sizing**: Limit each position to **2–5% of capital** (e.g., $10–$25 of a $500 account)[4].  
   - **Profit**: 5–10% per contract; risk is controlled if probability is truly high[4].

2. **Cross-Venue Arbitrage (Highest Reliability)**  
   - **Action**: Buy “Yes” on Kalshi at **$0.92** and “No” on Polymarket at **$0.09** (gap = $0.03 net of fees).  
   - **Threshold**: Only trade if gap ≥ **$0.03** after fees[4].  
   - **Time Horizon**: Minutes to hours (close before divergence).  
   - **Sizing**: Allocate **50% of capital per leg** (e.g., $250 on each side for $500 account) to maximize locked-in profit[4].  
   - **Profit**: Locks in **$0.04–$0.05 per contract** regardless of outcome[1][4].

3. **Time/Decay Harvesting (Steady, Low-Vol Returns)**  
   - **Action**: Buy “Yes” at **$0.40–$0.60** on mid-probability events (e.g., 50% chance of “Fed raises

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-27 via Conway's auto-publisher.*
