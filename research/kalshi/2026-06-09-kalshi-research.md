# Kalshi Nightly Research Brief — 2026-06-09

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-09T01:01:25, run time 30.1s._

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
- **[lweiss01/pmwatch](https://github.com/lweiss01/pmwatch)** ⭐ 1 · Python _(updated 2026-06-09)_
  Open-source anomaly detector for politically-sensitive Kalshi prediction markets. Flags unusual trading patterns that may precede public announcements. Public API only, no auth required.

- **[dcamco/kalshi-snapshots](https://github.com/dcamco/kalshi-snapshots)** ⭐ 0 · HTML _(updated 2026-06-09)_
  Public read-only snapshots of the Kalshi paper-trading dashboard (main repo private)

- **[oleksandrbannick/Meridian](https://github.com/oleksandrbannick/Meridian)** ⭐ 1 · Python _(updated 2026-06-09)_
  kalshi automated trading bot with custom UI

- **[lweiss01/pmwatch](https://github.com/lweiss01/pmwatch)** ⭐ 1 · Python _(updated 2026-06-09)_
  Open-source anomaly detector for politically-sensitive Kalshi prediction markets. Flags unusual trading patterns that may precede public announcements. Public API only, no auth required.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-09)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-09)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[Casiniza/polymarket-bot](https://github.com/Casiniza/polymarket-bot)** ⭐ 1 · Python _(updated 2026-06-09)_
  Automated Polymarket trading bot with GitHub Actions

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 0 · Python _(updated 2026-06-09)_
  Polymarket Trade Bot

- **[rexlau-prog/pm-crypto-trend-dashboard](https://github.com/rexlau-prog/pm-crypto-trend-dashboard)** ⭐ 0 · HTML _(updated 2026-06-09)_
  Report dashboard for the pm_crypto_trend Polymarket 5-min trading bot

- **[HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits](https://github.com/HarrierOnChain/Prediction-Markets-Trading-Bot-Toolkits)** ⭐ 269 · Rust _(updated 2026-06-09)_
  Trading bots on Prediction markets like Polymarket, Kalshi, Limitless etc. it is also available on Predict.fun predictdotfun. predict fun trading bot predict fun trading bot predict fun trading bot

- **[pjmerica/pred-arbitrage](https://github.com/pjmerica/pred-arbitrage)** ⭐ 0 · Python _(updated 2026-06-09)_
  Cross-market prediction market arbitrage scanner — Kalshi, Polymarket, PredictIt

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-06-09)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[talirabban/prediction-markets-thesis](https://github.com/talirabban/prediction-markets-thesis)** ⭐ 0 · Python _(updated 2026-06-08)_
  Quantitative analysis of Polymarket event contracts: calibration, ML-based pricing-error prediction, and out-of-sample strategy backtesting.

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

- **[Waike122333/Automated-Trading-Kalshi](https://github.com/Waike122333/Automated-Trading-Kalshi)** ⭐ 0 · None _(updated 2026-03-17)_
  An algorithmic trading bot for kalshi.com event contracts that automates trading strategies based on economic data, news events, weather patterns, and political markets in real-time.

## 4. Perplexity Strategy Synthesis
The most actionable edges in **2026 prediction markets** are still: **tail-decay harvesting near resolution**, **cross-venue mispricing/arbitrage between Kalshi and Polymarket**, and **convergence trades in markets that have a clear external benchmark**. The best small-account setups are usually *not* classic risk-free arb, but short-horizon mean reversion where you can size tiny and exit quickly; Polymarket tends to be more informative in the last hours because it is often more liquid, while Kalshi can still show isolated dislocations[1][2].

- **Tail-decay harvesting**: target “Yes” contracts that are trading too high relative to how much uncertainty is actually left, especially in the final hours to days before resolution. QuantPedia notes that prediction markets can exhibit systematic inefficiencies and that Polymarket tends to lead in the last hours, which makes late-stage price decay and convergence more tradable if you have a strong reference for the outcome[1].
- **Cross-venue arbitrage**: compare the same or economically equivalent event on Kalshi and Polymarket and trade when the implied probabilities diverge beyond fees and slippage. QuantPedia describes the basic rule: if the sum of the relevant opposing probabilities is below \(1\) minus transaction costs, there is an arbitrage; for a buy-all basket, if total contract prices sum to less than \(1\), you can buy the full set and lock in the payout[1].
- **Convergence plays**: trade when a prediction market price is far from a nearby “truth anchor” such as a polling average, election odds, scheduled macro release, court timetable, or event deadline, then fade into the anchor as the deadline approaches. This is often the cleanest edge for small accounts because you can define a hard exit rule and avoid holding through the final binary jump.
- **Small-account edge cases**: the best opportunities for \( \$50\text{–}500 \) accounts are usually single-contract, high-conviction, short-duration trades with limited downside, rather than multi-leg arbs that get eaten by minimum order sizes, fees, or inability to fully hedge. In practice, that means betting only when your estimated edge is large enough to overcome a few percentage points of friction, and using very small clip sizes so you can diversify across several dislocations.

Concrete trade framework:

| Strategy | Best horizon | Entry threshold | Typical sizing | What to look for |
|---|---:|---:|---:|---|
| Tail-decay harvest | 1–72 hours before resolution | Buy when contract is \(3\text{–}10\) points above your fair value estimate | 1–3% of bankroll per trade | Thin markets, stale prices, imminent catalyst |
| Cross-venue arb | Minutes to hours | Trade when venue gap exceeds fees + slippage, usually \(>2\text{–}4\) points in liquid markets | Size only what you can fully hedge | Same event listed on both venues, delayed repricing |
| Convergence fade | 1 day to several weeks | Enter when market is \(5\text{–}15\) points from your anchor and catalyst is known | 2–5% of bankroll | Polls, court dates, macro releases, sports injury news |
| Small-account dislocation trade | Same day to 1 week | Only when expected value is clearly positive after fees, often \(>8\text{–}10\) points of edge | \( \$5\text{–}25 \) clips | News overreaction, stale order books, low-liquidity tails |

A few practical rules matter more than the label of the strategy:

- **Do not chase tiny edges** on small accounts. If total friction is roughly 3–5% round trip, you generally need a bigger apparent mis

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-09 via Conway's auto-publisher.*
