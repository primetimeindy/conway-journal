# Kalshi Nightly Research Brief — 2026-06-09

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-09T02:02:04, run time 20.3s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **MemoryVLA++: Temporal Modeling via Memory and Imagination in Vision-Language-Action Models** _(prediction market)_
  [2026-06-08](https://arxiv.org/abs/2606.09827v1)
  Temporal modeling is essential for robotic manipulation, as effective control requires both memory of past interactions and imagination of future states. However, most VLA models rely primarily on the current observation and therefore struggle with long-horizon, temporally dependent tasks. Cognitive science suggests that humans rely on working memory to buffer short-lived context, the hippocampal 

- **PTL-Diffusion: Manifold-Aware Diffusion with Periodic Terminal Laws** _(prediction market)_
  [2026-06-08](https://arxiv.org/abs/2606.09816v1)
  Standard diffusion models typically use a single time-homogeneous Gaussian terminal distribution as the reference law for generation. While this choice is analytically convenient and empirically powerful, it provides little explicit structure for data concentrated near low-dimensional manifolds, where different regions of the data distribution may correspond to distinct local geometric or semantic

- **iMaC: Translating Actions into Motion and Contact Images for Embodied World Models** _(prediction market)_
  [2026-06-08](https://arxiv.org/abs/2606.09813v1)
  Embodied world models have emerged as a pivotal paradigm for visual robotic decision-making and interactive environment simulation. However, conventional embodied frameworks rely on low-dimensional structured action vectors (e.g., joint angles and end-effector poses), which suffer from limited expressive capacity, poor generalization across diverse embodiments, and unnatural dynamic modeling for c

- **PTL-Diffusion: Manifold-Aware Diffusion with Periodic Terminal Laws** _(binary option pricing convergence)_
  [2026-06-08](https://arxiv.org/abs/2606.09816v1)
  Standard diffusion models typically use a single time-homogeneous Gaussian terminal distribution as the reference law for generation. While this choice is analytically convenient and empirically powerful, it provides little explicit structure for data concentrated near low-dimensional manifolds, where different regions of the data distribution may correspond to distinct local geometric or semantic

- **Limit Theory for $N$-Player $α$-Potential Games** _(binary option pricing convergence)_
  [2026-06-08](https://arxiv.org/abs/2606.09815v1)
  The framework of $α$-potential games has recently been introduced as a tool to analyze finite-player dynamic games, reducing the challenging task of finding approximate Nash equilibria to a control problem of minimizing a single function called $α$-potential function. In this work, we investigate the limiting behavior of $α$-potential games as the number of players $N$ tends to infinity. We show t

- **ALMA measurements of mass loss and wind clumping in the massive stars of the Arches cluster** _(binary option pricing convergence)_
  [2026-06-08](https://arxiv.org/abs/2606.09814v1)
  We present the first Atacama Large Millimeter/submillimeter Array (ALMA) Band 3 (100 GHz) and Band 6 (243 GHz) continuum observations of the Arches cluster, one of the youngest and most massive stellar clusters in the Milky Way. We detect and characterise millimetre emission from 23 massive stars, including WN7-9h Wolf-Rayet stars, O-type supergiants and hypergiants. By combining our ALMA measurem

- **A fast and consistent sharp-interface immersed boundary method for moving bodies of arbitrary thicknes** _(event-driven trading)_
  [2026-06-08](https://arxiv.org/abs/2606.09799v1)
  Immersed boundary methods (IBMs) are widely used to simulate flows around complex geometries and moving bodies, but they often involve a trade-off between precision and computational efficiency. Eulerian formulations require special treatments for moving walls and may generate spurious force oscillations, whereas Lagrangian formulations can suffer from slip errors at the immersed surfaces. We prop

- **PsychoSafe: Eliciting Psychologically-Informed Refusals in Large Language Models** _(event-driven trading)_
  [2026-06-08](https://arxiv.org/abs/2606.09697v1)
  Large language models (LLMs) routinely face requests that should be refused, creating a trade-off between helpfulness and harm prevention. However, refusals themselves can be helpful. In high-risk interactions involving crisis, coercion, or escalating intent, blunt non-compliance may prevent direct harm while still failing to support the needs of the person behind the request. We present PsychoSaf

- **Powering the Future of AI: Navigating the Trade-offs for Europe's Energy Transition and Net-Zero Goals** _(event-driven trading)_
  [2026-06-08](https://arxiv.org/abs/2606.09617v1)
  The rapid expansion of AI globally has led to the proliferation of energy-intensive hyperscale data centres (DCs), making them as a structurally challenging component in power system planning and operation. Using a spatially explicit optimisation model of Europe across 21 AI growth scenarios, we systematically quantify additional demand, capacity requirements, emissions, and operational impacts of

- **A Universal Dense Football Event Representation Based on TabTransformer** _(sports betting arbitrage)_
  [2026-06-08](https://arxiv.org/abs/2606.09327v1)
  Football event data constitute a rich spatiotemporal source for quantitative analysis of player actions in team sports. These datasets contain heterogeneous features, combining continuous location coordinates with categorical variables such as action type, action outcome, and body part. Such data have been applied in sports analytics for match outcome forecasting, player evaluation, and tactical p

- **Pseudocompact Topological \(MV\)-Algebras** _(sports betting arbitrage)_
  [2026-06-08](https://arxiv.org/abs/2606.09259v1)
  Recently, topological MV-algebras have been investigated by several mathematicians. In this paper, we find that every topological \(MV\)-algebra is a Mal'tsev space introduced by Mal'tsev in 1954. Hence, applying the theorem of Reznichenko and Uspenskij on pseudocompact Mal'tsev spaces, we show that the product of arbitrary family of pseudocompact topological \(MV\)-algebras are pseudocompact. We 

- **SOMA: From Surface Observations to Muscle Anatomy** _(sports betting arbitrage)_
  [2026-06-08](https://arxiv.org/abs/2606.09246v1)
  With the growing demand for realistic virtual humans, parametric body models have become a cornerstone of modern medicine, sports, and entertainment applications. However, most of these models are inherently limited: they only capture the 3D surface of the skin, offering no insight into the complex bio-mechanical structures that generate motion. As more applications expand towards biomechanics, th

- **High Mach number limit of the compressible Navier--Stokes equations in critical Besov spaces** _(Kelly criterion small bankroll)_
  [2026-06-08](https://arxiv.org/abs/2606.09808v1)
  We investigate the high Mach number limit for the scaled compressible Navier--Stokes system in the critical Besov framework. In the scaled momentum equation, the pressure force is represented by the term \(\varepsilon^2\nabla a^\varepsilon\), where $\varepsilon$ is the inverse Mach number; as \(\varepsilon\to0\), the formal limiting system is the compressible pressureless Navier--Stokes system. Th

- **A fast and consistent sharp-interface immersed boundary method for moving bodies of arbitrary thicknes** _(Kelly criterion small bankroll)_
  [2026-06-08](https://arxiv.org/abs/2606.09799v1)
  Immersed boundary methods (IBMs) are widely used to simulate flows around complex geometries and moving bodies, but they often involve a trade-off between precision and computational efficiency. Eulerian formulations require special treatments for moving walls and may generate spurious force oscillations, whereas Lagrangian formulations can suffer from slip errors at the immersed surfaces. We prop

- **Actions, semidirect products and crossed semimodules in the category of small categories with a fixed set of objects** _(Kelly criterion small bankroll)_
  [2026-06-08](https://arxiv.org/abs/2606.09796v1)
  We generalize to the fibres of the fibration $\mathcal{O}\colon\mathbf{Cat}\rightarrow\mathbf{Set},$ defined by mapping a small category $\mathbb{X}$ to its set of objects $X_0=ob(\mathbb{X}),$ the classical notions of action and semidirect product of monoids. We prove that the equivalence between monoid actions of a monoid $Y$ and Schreier split extensions on $Y,$ which is well known to generaliz

- **Adaptive Derivative Estimation via Stein's Unbiased Risk** _(tail risk harvesting)_
  [2026-06-08](https://arxiv.org/abs/2606.09829v1)
  Estimating derivatives from noisy sampled data is fundamental to control, human--computer interaction, and biomedical engineering. Causal FIR derivative filters offer a natural approach for this challenge, yet their performance depend on their length. While short filters amplify noise, long filters introduce smoothing bias. We present SURDE (SURE Derivative Estimator), which addresses this tradeof

- **Rethinking the Divergence Regularization in LLM RL** _(tail risk harvesting)_
  [2026-06-08](https://arxiv.org/abs/2606.09821v1)
  Reinforcement learning (RL) has become a key component of post-training large language models (LLMs). In practice, LLM RL is often off-policy because of training-inference mismatch and policy staleness, making trust-region control essential for stable optimization. Mainstream methods such as PPO and GRPO approximate this control with a ratio-clipping mechanism, but the importance ratio can be a po

- **Evaluation Cards: An Interpretive Layer for AI Evaluation Reporting** _(tail risk harvesting)_
  [2026-06-08](https://arxiv.org/abs/2606.09809v1)
  AI evaluation results are produced at scale but reported inconsistently across leaderboards, model cards, benchmark papers, and company blogs. The cost is interpretive: readers cannot reliably compare results across sources, identify what a report omits, or trace an aggregate claim to its underlying evidence. Recent efforts address isolated components but leave three gaps: they cover only narrow s

## 3. GitHub Repos (Recently Updated)
- **[SpartanLabsXyz/simmer-sdk](https://github.com/SpartanLabsXyz/simmer-sdk)** ⭐ 45 · Python _(updated 2026-06-09)_
  Python SDK for Agentic Prediction Market trading

- **[haoo99/Polymarket-Kalshi-Arbitrage-Bot](https://github.com/haoo99/Polymarket-Kalshi-Arbitrage-Bot)** ⭐ 1 · TypeScript _(updated 2026-06-09)_
  🤖 Exploit price gaps between Polymarket and Kalshi 15-min BTC markets using real-time arbitrage trading to capture consistent profits.

- **[dcamco/kalshi-snapshots](https://github.com/dcamco/kalshi-snapshots)** ⭐ 0 · HTML _(updated 2026-06-09)_
  Public read-only snapshots of the Kalshi paper-trading dashboard (main repo private)

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-09)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[lweiss01/pmwatch](https://github.com/lweiss01/pmwatch)** ⭐ 1 · Python _(updated 2026-06-09)_
  Open-source anomaly detector for politically-sensitive Kalshi prediction markets. Flags unusual trading patterns that may precede public announcements. Public API only, no auth required.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-09)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[Casiniza/polymarket-bot](https://github.com/Casiniza/polymarket-bot)** ⭐ 1 · Python _(updated 2026-06-09)_
  Automated Polymarket trading bot with GitHub Actions

- **[rexlau-prog/pm-crypto-trend-dashboard](https://github.com/rexlau-prog/pm-crypto-trend-dashboard)** ⭐ 0 · HTML _(updated 2026-06-09)_
  Report dashboard for the pm_crypto_trend Polymarket 5-min trading bot

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 97 · Solidity _(updated 2026-06-09)_
  Easy setup and creation of a bot

- **[Duollc/PredictionMarket](https://github.com/Duollc/PredictionMarket)** ⭐ 0 · None _(updated 2026-06-09)_
  📊 Enhance prediction market security with a complete audit guide, featuring real incidents and a comprehensive checklist for risk management.

- **[Crayz916/prediction-market-arbitrage-bot](https://github.com/Crayz916/prediction-market-arbitrage-bot)** ⭐ 1 · JavaScript _(updated 2026-06-09)_
  🎯 Execute synthetic arbitrage between Polymarket and Kalshi to capitalize on price differences instantly with our educational bot.

- **[kmjjjj/polymarket-arbitrage-bot-btc-sol-15m](https://github.com/kmjjjj/polymarket-arbitrage-bot-btc-sol-15m)** ⭐ 2 · Rust _(updated 2026-06-09)_
  🚀 Execute profitable trades with this Rust-based arbitrage bot for Polymarket, monitoring BTC and SOL 15-minute price prediction markets.

- **[talirabban/prediction-markets-thesis](https://github.com/talirabban/prediction-markets-thesis)** ⭐ 0 · Python _(updated 2026-06-08)_
  Quantitative analysis of Polymarket event contracts: calibration, ML-based pricing-error prediction, and out-of-sample strategy backtesting.

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

- **[Waike122333/Automated-Trading-Kalshi](https://github.com/Waike122333/Automated-Trading-Kalshi)** ⭐ 0 · None _(updated 2026-03-17)_
  An algorithmic trading bot for kalshi.com event contracts that automates trading strategies based on economic data, news events, weather patterns, and political markets in real-time.

## 4. Perplexity Strategy Synthesis
The most actionable edges in **2026** are still the boring ones: **late-line convergence**, **cross-venue price gaps**, and **short-dated “tail decay” sells** in thin markets where attention fades faster than the odds do.[1][2] For **small accounts ($50–500)**, the best opportunities are usually **1–10 contract clips** in markets with wide spreads, weak liquidity, or a clear catalyst window, not large-scale arb.[1][2]

## 1) **Tail decay harvesting**
This is the most repeatable edge for small accounts because you are betting on the *collapse of stale hype* rather than needing a perfect event forecast.[1]

- **Best setup:** markets where the headline is exciting but the actual resolution is narrow, technical, or slow-moving.
- **Time horizon:** enter **days to hours before resolution** if the market is still above a “hype premium” that is unsupported by fresh information.[1]
- **Price thresholds:** look for contracts that are still trading at roughly **0.65–0.90** when the true event probability has clearly weakened; the exact cutoff is market-specific, but the goal is to sell into exaggerated optimism or buy stale fear.[1]
- **Position sizing:** for a $50–$500 account, risk **1–5% of bankroll per idea** and use several small clips rather than one large entry.
- **Why it works:** QuantPedia’s review highlights systematic inefficiencies, including behavioral bias and the tendency for mispricings to persist until close, while noting that Polymarket’s higher liquidity often makes it especially informative in the final hours.[1]

Practical version: if a market is still priced aggressively despite no new evidence, **fade the continuation of the move**, not the event itself. The edge is strongest when a market has a “story” but the underlying settlement rule is binary and strict.[1]

## 2) **Cross-venue arbitrage**
This is the cleanest “math” trade when Kalshi and Polymarket disagree on the same event.[1][2]

- **Core rule:** convert prices to probabilities and compare the two venues after fees and slippage.[1]
- **Trigger:** when the combined cost of buying the winning side across venues is **meaningfully below 1.00** after transaction costs, or when a buy-all / sell-all basket is mispriced.[1]
- **Time horizon:** usually **minutes to hours**, because these dislocations often close quickly once one venue updates.
- **Position sizing:** small accounts should use **micro-arb** only when the spread is large enough to survive fees; in practice, that means skipping tiny theoretical edges and only acting when there is a visible cushion for fees, maker/taker costs, and partial fills.
- **Execution note:** QuantPedia states that Polymarket generally leads Kalshi because of higher liquidity, especially near the end, so if one venue is stale, the lagging venue is often the better leg to hit.[1]

Practical version: if Kalshi is at 0.58 and Polymarket is at 0.47 on the same yes/no contract, you do **not** assume free money unless the after-fee, after-slippage round-trip still leaves a buffer. The edge is real only when the gap is large enough to clear execution friction.[1]

## 3) **Convergence plays**
These are trades where you expect the price to drift toward a reference value as information gets absorbed.[1][2]

- **Best setup:** markets with a clear external anchor: polls, official data releases, sportsbook-like consensus, or a related market that is more liquid.
- **Time horizon:** **hours to days**; convergence is typically slower than pure arb but more forgiving on execution.
- **Price thresholds:** enter when the market dive

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-09 via Conway's auto-publisher.*
