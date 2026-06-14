# Kalshi Nightly Research Brief — 2026-06-14

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-14T02:01:21, run time 19.3s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **Modality Forcing for Scalable Spatial Generation** _(prediction market)_
  [2026-06-11](https://arxiv.org/abs/2606.13676v1)
  Text-to-image (T2I) models contain rich spatial priors. Synthesizing photorealistic, cluttered scenes requires an understanding of geometry, including perspective and relative scale. Prior works adapt T2I models to leverage this prior for depth prediction, but they require dense depth data and involve complex recipes. We propose Modality Forcing, a simple, scalable post-training recipe for joint i

- **RepWAM: World Action Modeling with Representation Visual-Action Tokenizers** _(prediction market)_
  [2026-06-11](https://arxiv.org/abs/2606.13674v1)
  This work presents RepWAM, a representation-centric world action model (WAM) built on representation visual-action tokenizers. Existing WAMs typically inherit reconstruction-oriented video tokenizers from pretrained video generation models. Although these tokenizers preserve visual fidelity, pixel reconstruction alone provides limited guidance for learning instruction-following dynamics that conne

- **$\texttt{WEAVER}$, Better, Faster, Longer: An Effective World Model for Robotic Manipulation** _(prediction market)_
  [2026-06-11](https://arxiv.org/abs/2606.13672v1)
  The potential impacts of world models (WMs, i.e., learned simulators) on robotics are far-reaching -- policy evaluation, policy improvement, and test-time planning -- all with limited real-world interaction. To unlock these downstream capabilities, a WM needs to jointly satisfy three desiderata: $\textit{(i)}$ fidelity (i.e., producing simulated trajectories that correlate with reality), $\textit{

- **Observable Dependence of Viscous Corrections in QGP: Heavy Quarks and Dileptons in Chapman--Enskog Theory** _(binary option pricing convergence)_
  [2026-06-11](https://arxiv.org/abs/2606.13646v1)
  We calculate, for the first time, heavy quark transport and thermal dilepton production from QGP using viscous correction up to second order in gradients. We use the form of viscous correction obtained from Chapman-Enskog like expansion of the Boltzmann transport equation in relaxation time approximation, and compare our results with that of Grad's 14-moment approximation. By employing the tempera

- **Aerial Wildfire Suppression Planning with a Hybrid CNN-Cellular Automata Fire Model** _(binary option pricing convergence)_
  [2026-06-11](https://arxiv.org/abs/2606.13633v1)
  Aerial wildfire suppression requires not only predicting fire spread, but also designing effective intervention strategies under operational and environmental uncertainty. We present a modeling and optimization framework for aerial wildfire suppression that combines a hybrid neural-cellular automaton wildfire model with gradient-based design of targeted aerial drops. The wildfire model predicts sp

- **Beyond Runtime Enforcement: Shield Synthesis as Defensibility Analysis for Adversarial Networks** _(binary option pricing convergence)_
  [2026-06-11](https://arxiv.org/abs/2606.13621v1)
  Shielded reinforcement learning is typically presented as a runtime safety mechanism that compiles temporal-logic specifications into automata restricting an agent's actions. We argue this is the wrong product. The same automata-theoretic machinery -- specification compilation, product game construction, attractor computation, and winning-region extraction -- is better read as a design-time analyt

- **World Tracing: Generative Pixel-Aligned Geometry Beyond the Visible** _(event-driven trading)_
  [2026-06-11](https://arxiv.org/abs/2606.13652v1)
  Image-to-3D methods often trade off faithfulness and completeness: depth estimators are anchored to input pixels but stop at the visible surface, while image-to-3D models generate complete shapes that are often misaligned with the input. We introduce World Tracing, a generative pixel-aligned geometry representation that predicts 3D points aligned with observed pixels while completing geometry beyo

- **Balancing label resolution and computational cost in dynamical models of lipid metabolism** _(event-driven trading)_
  [2026-06-11](https://arxiv.org/abs/2606.13620v1)
  Lipid metabolism is a central biological process that is commonly studied using destructive mass-spectrometry experiments. A recently proposed strategy, uses multiple labels to extract temporal information about lipid metabolism from a single destructive measurement. However, the computational complexity of the model-based data analysis increases rapidly with the number of labels, creating a funda

- **EvTexture++: Event-Driven Texture Enhancement for Video Super-Resolution** _(event-driven trading)_
  [2026-06-11](https://arxiv.org/abs/2606.13580v1)
  Event-based vision has drawn increasing attention owing to its distinctive properties, including ultra-high temporal resolution and extreme dynamic range. Recent works have introduced it to video super-resolution (VSR) to enhance flow estimation and temporal alignment. In contrast, this paper shifts the focus of event signals from motion refinement to texture enhancement in VSR. We propose EvTextu

- **SAM-Deep-EIoU: Selective Mask Propagation for Multi-Object Tracking** _(sports betting arbitrage)_
  [2026-06-11](https://arxiv.org/abs/2606.13033v1)
  Multi-object tracking has a heavy-tailed difficulty distribution: most frames are easy for a lightweight base tracker, while a small fraction are intrinsically hard. Video object segmentation (VOS) models can often preserve identity through the hard frames where the base tracker fails, but they are much more expensive in compute and memory. We propose selective mask propagation, a tracking algorit

- **In-Family Arbitrage-Free Interpolation of Mixture Densities Across Expirations** _(sports betting arbitrage)_
  [2026-06-10](https://arxiv.org/abs/2606.12717v1)
  Given risk-neutral densities of a tradeable forward, fitted as $N$-component mixtures at a finite set of expiration pillars, we look for a continuous-time interpolation that (i) stays inside the mixture family (it remains a mixture of the same kernel, though generically with more components than either pillar), and (ii) is the marginal flow of a Markov martingale, equivalently carries a non-negati

- **Cross-Validation Equilibrium** _(sports betting arbitrage)_
  [2026-06-10](https://arxiv.org/abs/2606.12571v1)
  We study strategic interaction when players delegate belief formation to predictive machine learning (ML). In a static Bayesian game, each player's ML agent predicts a payoff-relevant outcome variable as a function of the player's type. The ML agent's training sample is endogenous: it is drawn from the outcome distribution generated by players' ML-guided behavior. In Cross-Validation Equilibrium (

- **A model of local and global reciprocity** _(Kelly criterion small bankroll)_
  [2026-06-11](https://arxiv.org/abs/2606.13678v1)
  We often decide how to treat friends based on observations of their past behavior, whereas actions toward strangers are typically guided by their public reputations. These two kinds of information underlie two classical mechanisms for the evolution of cooperation$\unicode{x2014}$direct and indirect reciprocity$\unicode{x2014}$which have largely been studied in isolation. They are not interchangeab

- **Dense Supervision, Sparse Updates: On the Sparsity and Geometry of On-Policy Distillation** _(Kelly criterion small bankroll)_
  [2026-06-11](https://arxiv.org/abs/2606.13657v1)
  On-policy distillation (\textsc{OPD}) has recently become a prominent post-training recipe as it combines two desirable ingredients: on-policy student trajectories and dense teacher supervision, yet how this hybrid changes a model's parameters remains unclear. Across several language and vision-language model pairs and use cases, our analysis yields two main findings. On sparsity, \textsc{OPD}-sty

- **SkMTEB: Slovak Massive Text Embedding Benchmark and Model Adaptation** _(Kelly criterion small bankroll)_
  [2026-06-11](https://arxiv.org/abs/2606.13647v1)
  We introduce SkMTEB, the first comprehensive MTEB-style text embedding benchmark for Slovak, a low-resource West Slavic language, comprising 31 datasets across 7 task types -- nearly 4$\times$ the depth of existing multilingual benchmark coverage for Slovak. Our evaluation of 31 embedding models reveals that large instruction-tuned multilingual models achieve the strongest performance, while exist

- **Specifying Hardware Communication as Programs** _(tail risk harvesting)_
  [2026-06-11](https://arxiv.org/abs/2606.13659v1)
  To test and debug hardware modules, it is common to write two programs: a driver, which translates high-level transactions into interactions on the module's input and output signals, and a monitor, which analyzes a signal-level execution trace and recognizes a transaction. These two programs are commonly implemented separately for each hardware protocol, but this separation entails manual effort a

- **Revisiting Vehicle Color Recognition in Long-Tailed Surveillance Scenarios** _(tail risk harvesting)_
  [2026-06-11](https://arxiv.org/abs/2606.13625v1)
  Vehicle color recognition is an important cue for vehicle identification in surveillance systems, especially when license plates are illegible due to low resolution, occlusion, motion blur, or poor illumination. However, real-world vehicle color distributions are highly imbalanced, making overall accuracy insufficient to assess performance on rare but operationally relevant colors. This paper pres

- **A Declining CVaR Glidepath Framework for Target-Date Fund Design with an Application to the Chilean Pension System** _(tail risk harvesting)_
  [2026-06-11](https://arxiv.org/abs/2606.13618v1)
  We propose a framework for designing Target-Date Funds (TDFs) around an explicit return objective while controlling risk directly at the portfolio level through a declining Conditional Value-at-Risk (CVaR) constraint. In this approach, the regulator or sponsor specifies a CVaR glidepath that gives the portfolio manager enough flexibility to reach a target return with a reasonably high probability.

## 3. GitHub Repos (Recently Updated)
- **[Roughim/polymarket-trading-agent](https://github.com/Roughim/polymarket-trading-agent)** ⭐ 1 · Rust _(updated 2026-06-14)_
  Automate Polymarket trading with real-time market data, position tracking, exit logic, and a local dashboard in Rust

- **[Yury617/polymarket-impulse-monitoring-trading-bot](https://github.com/Yury617/polymarket-impulse-monitoring-trading-bot)** ⭐ 1 · TypeScript _(updated 2026-06-14)_
  Automate Polymarket momentum trading with impulse detection, trailing stops, hedging, and settlement tracking in real time

- **[UnitedStars111/polymarket-copy-trading-bot](https://github.com/UnitedStars111/polymarket-copy-trading-bot)** ⭐ 0 · HTML _(updated 2026-06-14)_
  Copy trades from Polymarket leader addresses across politics, sports, crypto, and more with config in trade.toml and secrets in .env

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-14)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-14)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[rockmundada/kalshi-weather-bot](https://github.com/rockmundada/kalshi-weather-bot)** ⭐ 0 · Python _(updated 2026-06-11)_
  Automated weather derivatives trading system for Kalshi — 5 API integrations, 10-chart analytics dashboard, data-driven strategy from 339 analyzed trades

- **[pr0m3th3usEx/pm-bot](https://github.com/pr0m3th3usEx/pm-bot)** ⭐ 0 · None _(updated 2026-06-14)_
  Polymarket Trading Bot

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 1 · Python _(updated 2026-06-14)_
  Polymarket Trade Bot

- **[Yury617/polymarket-impulse-monitoring-trading-bot](https://github.com/Yury617/polymarket-impulse-monitoring-trading-bot)** ⭐ 1 · TypeScript _(updated 2026-06-14)_
  Automate Polymarket momentum trading with impulse detection, trailing stops, hedging, and settlement tracking in real time

- **[Janiferintrinsical821/Kalshi-Trading-Bot](https://github.com/Janiferintrinsical821/Kalshi-Trading-Bot)** ⭐ 0 · None _(updated 2026-06-14)_
  Trade Kalshi prediction markets with a probability-based bot that analyzes odds, market moves, and probability shifts for structured decisions

- **[Mylantaprotiumguianense372/openclaw-cross-market-arbitrage-agent](https://github.com/Mylantaprotiumguianense372/openclaw-cross-market-arbitrage-agent)** ⭐ 0 · TypeScript _(updated 2026-06-14)_
  Detect price gaps in prediction markets across Kalshi and Polymarket, apply risk checks, and execute hedged trades with an event-driven system.

- **[RizkyDCuirass/Polymarket-Kalshi-arbitrage-bot](https://github.com/RizkyDCuirass/Polymarket-Kalshi-arbitrage-bot)** ⭐ 0 · TypeScript _(updated 2026-06-14)_
  Detect price gaps between Polymarket and Kalshi to make timely buy decisions using configurable arbitrage rules for efficient trading.

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-12)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[talirabban/prediction-markets-thesis](https://github.com/talirabban/prediction-markets-thesis)** ⭐ 0 · Python _(updated 2026-06-10)_
  Quantitative analysis of Polymarket event contracts: calibration, ML-based pricing-error prediction, and out-of-sample strategy backtesting.

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

## 4. Perplexity Strategy Synthesis
The most actionable edges in **2026 prediction markets** are still the boring ones: **sell overpriced tails near expiry, arbitrage price inconsistencies across venues, and trade convergence when a market becomes more informative late in the event cycle**. The strongest source in your results is QuantPedia, which explicitly highlights **inter- and intra-market arbitrage**, **buy-all arbitrage**, and the fact that **Polymarket often leads Kalshi in the last hours because of higher liquidity**.[1]

## 1) Tail decay harvesting: sell extreme prices that are too rich late in the cycle

This is the most practical “small account” edge when you can’t run large arb books. The idea is to sell **far-OTM yes contracts** or buy **far-OTM no contracts** when the event is close enough that the remaining information flow is low and the market has overpaid for a longshot.[1]

- **Best setup:** event is in the **final 24–72 hours** and the contract is trading at an extreme, especially **\(\ge 85\%\)** or **\(\le 15\%\)** where the market is thin and emotionally driven. This threshold is an inference from the longshot-bias and tail-mispricing logic described by QuantPedia, not a quoted hard rule.[1]
- **Trade shape:** prefer **defined-risk** positions:
  - sell a **YES** at 85–95 if you think the true probability is lower
  - buy a **NO** at 5–15 if you think the true probability is higher
- **Why it works:** as expiry nears, the remaining uncertainty collapses, so prices often move toward the final information rather than continue to overreact to narrative or low-liquidity flow.[1]
- **Small-account sizing:** with **$50–500**, keep each position to **5–20% of bankroll** and avoid event clusters that could all resolve the same way. On Kalshi, margin can be more capital-efficient than purchasing many tiny contracts; on Polymarket, small accounts often do better by concentrating into one or two mispriced tails rather than scattering size.[2][3]

A concrete rule set:
- **Enter** when a tail contract is mispriced by at least **8–12 cents** versus your estimate and there are **<72 hours** left.
- **Exit early** if the price reverts halfway to fair value; do not wait for perfect convergence.
- **Hold to expiry only** when the edge is clear and the event is binary with low ambiguity.

## 2) Cross-venue arbitrage: compare Kalshi vs Polymarket on the same event

QuantPedia notes that prices can be converted to probabilities and that an arbitrage exists when the sum of opposing probabilities across markets is below one after costs; it also states that **Polymarket generally leads Kalshi due to higher liquidity, particularly in the last hours**.[1]

### Practical version
- Track the same event on both venues.
- Convert prices to implied probabilities.
- Look for a gap of at least:
  - **3–5 cents** on liquid events
  - **5–10 cents** on thin events
- Only trade if the spread exceeds **fees, slippage, and transfer/settlement friction**.[1][2][3]

### Most actionable cross-venue patterns
| Pattern | What to do | Useful threshold |
|---|---|---|
| **Kalshi lags Polymarket** | Buy the cheaper venue, sell/short the richer one if you can hedge synthetically | Gap persists for **10–60 minutes** after a move on Polymarket |
| **Last-hour informational lead** | Use Polymarket as the “price discovery” venue and wait for Kalshi to catch up | Best in **final hour

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-14 via Conway's auto-publisher.*
