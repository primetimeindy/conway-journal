# Kalshi Nightly Research Brief — 2026-06-13

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-13T02:01:53, run time 19.6s._

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
- **[raniisometric491/polymarket-kalshi-arbitrage-bot](https://github.com/raniisometric491/polymarket-kalshi-arbitrage-bot)** ⭐ 0 · TypeScript _(updated 2026-06-13)_
  Monitor and execute arbitrage trades between Kalshi and Polymarket Bitcoin 15-minute markets using an automated TypeScript toolkit.

- **[Mylantaprotiumguianense372/openclaw-cross-market-arbitrage-agent](https://github.com/Mylantaprotiumguianense372/openclaw-cross-market-arbitrage-agent)** ⭐ 0 · TypeScript _(updated 2026-06-13)_
  Detect price gaps in prediction markets across Kalshi and Polymarket, apply risk checks, and execute hedged trades with an event-driven system.

- **[alzei2269/polymarket-agent](https://github.com/alzei2269/polymarket-agent)** ⭐ 1 · None _(updated 2026-06-13)_
  Analyze Polymarket prediction markets using AI to identify mispriced opportunities and detect edges for informed decisions.

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-13)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-13)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[rockmundada/kalshi-weather-bot](https://github.com/rockmundada/kalshi-weather-bot)** ⭐ 0 · Python _(updated 2026-06-11)_
  Automated weather derivatives trading system for Kalshi — 5 API integrations, 10-chart analytics dashboard, data-driven strategy from 339 analyzed trades

- **[raniisometric491/polymarket-kalshi-arbitrage-bot](https://github.com/raniisometric491/polymarket-kalshi-arbitrage-bot)** ⭐ 0 · TypeScript _(updated 2026-06-13)_
  Monitor and execute arbitrage trades between Kalshi and Polymarket Bitcoin 15-minute markets using an automated TypeScript toolkit.

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 98 · Solidity _(updated 2026-06-13)_
  Easy setup and creation of a bot

- **[bit-nexusxtitmtdsuy/Polymarket_Bot](https://github.com/bit-nexusxtitmtdsuy/Polymarket_Bot)** ⭐ 32 · None _(updated 2026-06-13)_
  Polymarket Bot is a tool for interacting with Polymarket, a decentralized prediction market platform where users trade shares representing the probability of real-world events using cryptocurrency (pr

- **[Mylantaprotiumguianense372/openclaw-cross-market-arbitrage-agent](https://github.com/Mylantaprotiumguianense372/openclaw-cross-market-arbitrage-agent)** ⭐ 0 · TypeScript _(updated 2026-06-13)_
  Detect price gaps in prediction markets across Kalshi and Polymarket, apply risk checks, and execute hedged trades with an event-driven system.

- **[RizkyDCuirass/Polymarket-Kalshi-arbitrage-bot](https://github.com/RizkyDCuirass/Polymarket-Kalshi-arbitrage-bot)** ⭐ 0 · TypeScript _(updated 2026-06-13)_
  Detect price gaps between Polymarket and Kalshi to make timely buy decisions using configurable arbitrage rules for efficient trading.

- **[Duollc/PredictionMarket](https://github.com/Duollc/PredictionMarket)** ⭐ 0 · None _(updated 2026-06-13)_
  📊 Enhance prediction market security with a complete audit guide, featuring real incidents and a comprehensive checklist for risk management.

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-12)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[talirabban/prediction-markets-thesis](https://github.com/talirabban/prediction-markets-thesis)** ⭐ 0 · Python _(updated 2026-06-10)_
  Quantitative analysis of Polymarket event contracts: calibration, ML-based pricing-error prediction, and out-of-sample strategy backtesting.

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

## 4. Perplexity Strategy Synthesis
Based on the landscape of prediction markets in mid-2026, specifically for **Kalshi** (regulated, event contracts) and **Polymarket** (decentralized, crypto-native), the most actionable strategies for accounts between **$50–$500** focus on high-frequency inefficiencies rather than long-term directional bets. Large directional positions are often capital-inefficient for small accounts due to slippage and liquidity fragmentation.

Here are the four concrete strategies you requested, with specific parameters, followed by the most relevant recent sources.

### 1. Cross-Venue Arbitrage (The "Split-Price" Play)
With trading concentrating on Kalshi and Polymarket, price discrepancies frequently arise due to differing user bases (institutional vs. crypto degens) and settlement latency.

*   **Strategy Logic:** Buy the "No" contract on the venue where the price is lower (implied probability < 50%) and simultaneously buy the "Yes" contract on the venue where the price is higher (implied probability > 50%).
*   **Small Account Advantage:** You can execute this with very small capital ($50–$100) because the profit is risk-free (delta-neutral) and scales linearly.
*   **Concrete Parameters:**
    *   **Time Horizon:** Ultra-short (minutes to resolve).
    *   **Price Threshold:** Seek a spread where the sum of implied probabilities from opposing contracts is **< 98%** (e.g., 48% "Yes" on Kalshi + 49% "No" on Polymarket = 97% total). This creates an immediate arbitrage edge of ~3% minus fees.
    *   **Position Sizing:** Allocate 100% of available buying power to the lower-priced side. If the spread is 3%, a $100 bet yields ~$3 profit.
    *   **Execution:** Requires API access or fast manual execution. Use tools like *PredTools* or *Arkham* to monitor real-time splits.

### 2. Tail Decay Harvesting (The "Longshot" Fade)
This strategy exploits the **Longshot Bias** (traders overvaluing "No" outcomes on unlikely events). In 2026, this is most prevalent in Polymarket's "crypto news" categories and Kalshi's political super-majority events.

*   **Strategy Logic:** When a contract is priced at 90–95% (heavy "Yes" bias), the "No" tail is often priced at 5–10% but is actually worth less than 1% due to behavioral bias. You short the "No" (or buy the "Yes" if the price is depressed, but buying the "Yes" is safer for small accounts).
*   **Concrete Parameters:**
    *   **Time Horizon:** 1–7 days (waiting for the event to resolve or the tail to decay to 0%).
    *   **Price Threshold:** Target contracts where the "No" price is **> 8%** but the event outcome is objectively highly probable (e.g., a 99% certainty event where the market prices it at 92%).
    *   **Position Sizing:** For a $100 account, buy **$20–$30** of the "Yes" contract. If the probability corrects to 99%, the price moves from ~0.92 to ~0.99, yielding ~7-8% ROI.
    *   **Edge Case:** In "Crypto Bro" markets (Polymarket), where sentiment is extreme, "No" prices often stay artificially high (e.g., 12%) even when the event is 99.

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-13 via Conway's auto-publisher.*
