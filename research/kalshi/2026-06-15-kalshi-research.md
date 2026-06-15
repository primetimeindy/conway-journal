# Kalshi Nightly Research Brief — 2026-06-15

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-15T02:01:04, run time 19.9s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **Instruct-Particulate: Scaling Feed-Forward 3D Object Articulation with Kinematic Control** _(prediction market)_
  [2026-06-12](https://arxiv.org/abs/2606.14699v1)
  Reconstructing articulated 3D objects is important for animation, gaming, and robotic simulations. Recent neural networks can estimate the articulated structure of 3D objects, but their generalization remains limited by the scarcity of annotated data for this task. To address this gap, we introduce Instruct-Particulate, a model that takes a 3D mesh together with a target kinematic specification, i

- **Scalar dissipation anomaly and scalar-gradient scaling in turbulence: A joint velocity-scalar multifractal view** _(prediction market)_
  [2026-06-12](https://arxiv.org/abs/2606.14696v1)
  We revisit the problem of scalar dissipation anomaly and scaling of scalar gradients in passive scalar turbulence using theory and data from well-resolved direct numerical simulations (DNS) on grid sizes of up to $8192^3$, spanning Taylor-scale Reynolds numbers $Re_λ=140-1000$ and Schmidt numbers $Sc = 1-512$. The theory is based on a joint multifractal description of longitudinal velocity increme

- **Implications of hierarchical Markov models of behavior: on irreversibility, predictability, and dimensionality** _(prediction market)_
  [2026-06-12](https://arxiv.org/abs/2606.14692v1)
  The maturation of quantitative tools for studying the high-level structure of animal behavior, and especially tools which represent spontaneous behavior as a sequence of stereotyped and neurally well-defined 'syllables', demands that the field revisit a fundamental theoretical question: if the coarse structure of behavior can be accurately described by Markov models, what do these models really te

- **The Edges of Planetary Systems: Falling Off the Kuiper Cliff in a Dissipating Gas Disk** _(binary option pricing convergence)_
  [2026-06-12](https://arxiv.org/abs/2606.14704v1)
  Probably the last planetesimals to have formed from dust in the solar nebula are Cold Classical Kuiper belt objects (CCKBOs). To the extent that they are isolated and unchanged since birth, CCKBOs offer direct insights into nebular processes. Their population density drops abruptly beyond a heliocentric radius of $\sim$47 au, a feature known as the "Kuiper Cliff". We show with global, 1D (radial),

- **Instruct-Particulate: Scaling Feed-Forward 3D Object Articulation with Kinematic Control** _(binary option pricing convergence)_
  [2026-06-12](https://arxiv.org/abs/2606.14699v1)
  Reconstructing articulated 3D objects is important for animation, gaming, and robotic simulations. Recent neural networks can estimate the articulated structure of 3D objects, but their generalization remains limited by the scarcity of annotated data for this task. To address this gap, we introduce Instruct-Particulate, a model that takes a 3D mesh together with a target kinematic specification, i

- **AgentSpec: Understanding Embodied Agent Scaffolds Through Controlled Composition** _(binary option pricing convergence)_
  [2026-06-12](https://arxiv.org/abs/2606.14674v1)
  LLM agents are increasingly built not as single model calls, but as scaffolded systems that combine reasoning, memory, reflection, action execution, and learning. While such scaffolds often improve performance, they are often embedded in tightly coupled pipelines, making it difficult to isolate component contributions, compare alternative designs, or understand how module interactions shape agent 

- **Learning Coordinated Preference for Multi-Objective Multi-Agent Reinforcement Learning** _(event-driven trading)_
  [2026-06-12](https://arxiv.org/abs/2606.14693v1)
  Cooperative multi-objective multi-agent reinforcement learning (MOMARL) models team decision making under multiple, potentially conflicting objectives. In this setting, conflicts arise not only across objectives but also across agents with different observations, roles, and contributions. We propose Preference Coordinated Multi-agent Policy Optimization (PCMA), which learns coordinated agent-speci

- **AgentSpec: Understanding Embodied Agent Scaffolds Through Controlled Composition** _(event-driven trading)_
  [2026-06-12](https://arxiv.org/abs/2606.14674v1)
  LLM agents are increasingly built not as single model calls, but as scaffolded systems that combine reasoning, memory, reflection, action execution, and learning. While such scaffolds often improve performance, they are often embedded in tightly coupled pipelines, making it difficult to isolate component contributions, compare alternative designs, or understand how module interactions shape agent 

- **Private Information Retrieval for Large-Scale DNA-Based Data Storage** _(event-driven trading)_
  [2026-06-12](https://arxiv.org/abs/2606.14557v1)
  We investigate Private Information Retrieval (PIR) in the context of synthetic DNA-based data storage. While PIR is a well-studied primitive for digital databases, extending it to DNA-based databases presents unique challenges arising from biochemical query mechanisms and their complexity. We propose two approaches for adapting two-server PIR protocols to DNA-based storage, balancing privacy, effi

- **SED:Lightweight Saliency prediction for Event-based data via Distillation** _(sports betting arbitrage)_
  [2026-06-12](https://arxiv.org/abs/2606.14631v1)
  Event-based saliency prediction has gained attention recently, as combining event cameras with saliency estimation can act as an upstream stage that naturally improves the efficiency of downstream eventbased perception at the edge. However, current approaches are either neuromorphic, underperforming on event-based saliency benchmarks, or too heavy for resource-constrained edge applications due to 

- **Poker Arena: Multi-Axis Profiling of Strategic Reasoning and Memory in LLMs** _(sports betting arbitrage)_
  [2026-06-11](https://arxiv.org/abs/2606.13815v1)
  Strategic reasoning under uncertainty underpins consequential decisions in negotiation, finance, and policy, but prevailing game-play benchmarks collapse heterogeneous reasoning dimensions into a single scalar, leaving the capability structure of frontier LLMs unexamined. We introduce Poker Arena, a no-limit Texas Hold'em tournament platform that couples a three-layer memory architecture (within-h

- **Neural Slack Variables for Shape Constraints** _(sports betting arbitrage)_
  [2026-06-11](https://arxiv.org/abs/2606.13803v1)
  Enforcing functional inequality constraints such as monotonicity and convexity in neural networks is a fundamental challenge in many industrial and scientific applications. Classical one-sided penalty methods, along with primal-dual methods gated by complementary slackness, provide constraint gradients only at violated locations, resulting in fragile satisfaction. Architectures that guarantee feas

- **Gaze Heads: How VLMs Look at What They Describe** _(Kelly criterion small bankroll)_
  [2026-06-12](https://arxiv.org/abs/2606.14703v1)
  How a vision-language model internally solves the task of describing an image is far from obvious. We find that the model develops a specific mechanism for this: a small set of attention heads in its language-model backbone, which we call gaze heads, whose attention tracks the image region the model is currently describing. We find them with a simple correlation score from a few forward passes, us

- **Discontinuous Galerkin approximations of the Jordan-Moore-Gibson-Thompson equation in the vanishing relaxation limit** _(Kelly criterion small bankroll)_
  [2026-06-12](https://arxiv.org/abs/2606.14655v1)
  The Jordan-Moore-Gibson-Thompson (JMGT) equation models nonlinear acoustic wave propagation in thermally relaxing media and in the vanishing relaxation limit approaches the damped Westervelt equation. We investigate discontinuous Galerkin spatial discretizations of the JMGT equation on simplicial meshes and analyze their behavior uniformly with respect to the relaxation parameter. Under practicall

- **Open Wilson chain numerical renormalization group approach to steady-state non-equilibrium quantum transport** _(Kelly criterion small bankroll)_
  [2026-06-12](https://arxiv.org/abs/2606.14635v1)
  The numerical renormalization group (NRG) approach was developed to identify and quantify different equilibrium regimes of quantum impurity systems (QISs) with unprecedented accuracy by a tailored finite size representation. Out of equilibrium, the steady-state density operator is not of the Boltzmannian form but one that is determined by the imposed boundary conditions. We extend the NRG to the n

- **A Complexity Measure for Active Learning in Multi-group Mean Estimation** _(tail risk harvesting)_
  [2026-06-12](https://arxiv.org/abs/2606.14690v1)
  We study a \emph{max-risk} objective for active learning in a multi-group mean estimation $d$-armed bandits: a learner adaptively allocates a budget of $T$ samples across $d$ groups to minimize the worst-case uncertainty index $\max_{k\in[d]}σ_k^2/n_k$, where $σ_k$ is the standard deviation of the distribution of arm $d$, and $n_k$ is the number of times arm $d$ is sampled. We develop a local mini

- **Flood and Harvest: The Provable Necessity of Trivia for Generating Valuable Mathematics via the Lens of Language Generation in the Limit** _(tail risk harvesting)_
  [2026-06-12](https://arxiv.org/abs/2606.14688v1)
  AI systems coupled to proof assistants now generate formal mathematics at scale, and the gap between what a checker can verify and what a mathematician would value has become the binding constraint. We model the generation of valuable mathematics as nested language generation in the limit: a verifiable formal language $F$, accessed through a membership oracle (the proof checker), contains an unkno

- **Enigmatic Line Broadening During Solar Flares: Magnetic Field Broadening?** _(tail risk harvesting)_
  [2026-06-12](https://arxiv.org/abs/2606.14681v1)
  The origin of the extreme broadening observed in chromospheric metal lines during solar and stellar flares, particularly Mg II h&amp;k and Ca II H&amp;K, remains poorly understood. These lines often display Lorentzian like wings whose widths exceed standard Stark broadening predictions by factors of approx. 30, with no known collisional mechanism capable of producing such enhancements. We posit th

## 3. GitHub Repos (Recently Updated)
- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1888 · TypeScript _(updated 2026-06-15)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[oleksandrbannick/Meridian](https://github.com/oleksandrbannick/Meridian)** ⭐ 2 · Python _(updated 2026-06-15)_
  kalshi automated trading bot with custom UI

- **[dcamco/kalshi-snapshots](https://github.com/dcamco/kalshi-snapshots)** ⭐ 0 · HTML _(updated 2026-06-15)_
  Public read-only snapshots of the Kalshi paper-trading dashboard (main repo private)

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 1 · None _(updated 2026-06-15)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-15)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[TexasCoding/kalshi-python-sdk](https://github.com/TexasCoding/kalshi-python-sdk)** ⭐ 0 · Python _(updated 2026-06-15)_
  Professional Python SDK for the Kalshi prediction markets API

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 1 · Python _(updated 2026-06-15)_
  Polymarket Trade Bot

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 98 · Solidity _(updated 2026-06-15)_
  Easy setup and creation of a bot

- **[bit-nexusxtitmtdsuy/Polymarket_Bot](https://github.com/bit-nexusxtitmtdsuy/Polymarket_Bot)** ⭐ 32 · None _(updated 2026-06-15)_
  Polymarket Bot is a tool for interacting with Polymarket, a decentralized prediction market platform where users trade shares representing the probability of real-world events using cryptocurrency (pr

- **[pmxt-dev/pmxt](https://github.com/pmxt-dev/pmxt)** ⭐ 1888 · TypeScript _(updated 2026-06-15)_
  CCXT for prediction markets. PMXT is a unified API for trading on Polymarket, Kalshi, and more.

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-06-15)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant)** ⭐ 2 · Python _(updated 2026-06-15)_
  Trade Kalshi prediction markets with a quantitative system designed for fee-aware position sizing and statistical arbitrage.

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-12)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[talirabban/prediction-markets-thesis](https://github.com/talirabban/prediction-markets-thesis)** ⭐ 0 · Python _(updated 2026-06-10)_
  Quantitative analysis of Polymarket event contracts: calibration, ML-based pricing-error prediction, and out-of-sample strategy backtesting.

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

## 4. Perplexity Strategy Synthesis
The most actionable edges on **Kalshi** and **Polymarket** in 2026 are still the boring ones: **late-stage mispricing**, **cross-venue arbitrage**, and **convergence trades** where a market drifts toward a more liquid reference price as the event nears.[1][4] For small accounts, the most realistic profits come from **tiny, high-conviction dislocations** rather than broad arbitrage, because fees, minimum order sizes, and bankroll limits matter a lot more when you have only $50–$500.[1][5]

## 1) Tail-decay harvesting

This is the strategy of repeatedly selling overpriced **longshots** or buying underpriced **favorites** as time decay compresses the remaining uncertainty. QuantPedia notes that prediction markets exhibit systematic edges from behavioral biases such as **longshot bias**, and that prices often become more informative in the **last hours**, especially on more liquid venues like Polymarket.[1]

**How to trade it**
- Target markets with **10–72 hours** to resolution, where the event is still uncertain but the crowd has not fully re-priced the tail.
- Prefer contracts trading around **5%–25%** or **75%–95%** if you are fading excess optimism/pessimism.
- The cleanest setup is when one venue implies a materially different probability than the other, or when the market is far from an obvious external anchor such as polling, official data, or betting odds.[1][5]

**Concrete thresholds**
- If a “Yes” contract is at **$0.08–$0.15** and your outside estimate is below **3%–5%**, the edge is usually in *not* buying the longshot; if you can short via the platform mechanics, that is even better.
- If a favorite is at **$0.85–$0.95** and the true probability looks closer to **95%+**, buying the favorite or the complementary “No” can be a decent decay trade.
- For small accounts, size at **5%–15% of bankroll per trade** and avoid averaging down unless the market is still clearly mispriced and liquidity is sufficient.[1][5]

**Why it works**
- Longshot bias means traders often overpay for lottery-ticket outcomes, which creates a repeated source of negative expected value for crowded tails.[1]
- As expiry approaches, mispricings can collapse quickly, so a patient trader can often exit early once the contract converges partway to fair value.[1]

## 2) Cross-venue arbitrage

This is the most direct “real” edge: compare the same event on **Kalshi vs Polymarket**, and also compare the event against third-party betting lines or other prediction markets. QuantPedia explicitly highlights **inter- and intra-market arbitrage** and notes that if the sum of opposing positions across markets is below 1 minus costs, it can be profitable.[1]

**How to trade it**
- Look for the same event quoted on both venues with a gap of at least **2%–5% after fees**.
- For binary markets, a useful rule is: if you can buy the cheaper side on one venue and hedge the opposite exposure on the other so the worst-case payout exceeds total cost by at least **1.5%–3%**, it is worth considering.
- On sports and political markets, use the other venue or a sharp reference line as the anchor; on macro markets, use official futures-implied probabilities or data releases when available.[1][5]

**Concrete thresholds**
- Don’t bother with anything under roughly **1% net edge** unless your execution is extremely good.
- For small accounts, prioritize **fully funded, near-lock** structures only when the capital required is low enough that you can deploy at least *

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-15 via Conway's auto-publisher.*
