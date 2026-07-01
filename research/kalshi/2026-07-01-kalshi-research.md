# Kalshi Nightly Research Brief — 2026-07-01

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-07-01T02:01:09, run time 19.6s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **GEAR: Guided End-to-End AutoRegression for Image Synthesis** _(prediction market)_
  [2026-06-30](https://arxiv.org/abs/2606.32039v1)
  Visual generative models are typically trained in two stages. A tokenizer is first trained for reconstruction and then frozen, after which a generator is trained on its discrete indices or continuous latents. This decoupling leaves the tokenizer unaware of what the generator finds easy to model. We present GEAR (Guided End-to-end AutoRegression), which trains a vector-quantized (VQ) tokenizer and 

- **Introspective Coupling: Self-Explanation Training Tracks Behavioral Change Despite Fixed Supervision** _(prediction market)_
  [2026-06-30](https://arxiv.org/abs/2606.32038v1)
  When does training language models (LMs) to generate explanations of their predictions yield faithful introspection, rather than superficial imitation? We study LMs trained to explain which features of their inputs influenced their behavior, using models' counterfactual behavior on modified inputs as supervision. Surprisingly, we find that LMs trained on fixed counterfactual explanations derived f

- **Finite-range EFT for the $E1$ strength distribution of ${}^6$He** _(prediction market)_
  [2026-06-30](https://arxiv.org/abs/2606.32037v1)
  Halo effective field theory (Halo EFT) is a powerful tool to describe halo nuclei and predict low-energy observables with quantified uncertainties. However, in the case that there is a leading-order interaction determined by two or more effective-range parameters, such as the $^2P_{3/2}$ $nα$ interaction in $^6$He, the standard implementation in the dimer formalism leads to an energy-dependent int

- **GEAR: Guided End-to-End AutoRegression for Image Synthesis** _(binary option pricing convergence)_
  [2026-06-30](https://arxiv.org/abs/2606.32039v1)
  Visual generative models are typically trained in two stages. A tokenizer is first trained for reconstruction and then frozen, after which a generator is trained on its discrete indices or continuous latents. This decoupling leaves the tokenizer unaware of what the generator finds easy to model. We present GEAR (Guided End-to-end AutoRegression), which trains a vector-quantized (VQ) tokenizer and 

- **Freeform Preference Learning for Robotic Manipulation** _(binary option pricing convergence)_
  [2026-06-30](https://arxiv.org/abs/2606.32027v1)
  Reward design remains a central bottleneck for autonomous robot policy improvement, especially in long-horizon manipulation tasks where sparse success labels provide too little signal and binary preferences collapse many competing notions of quality into one ambiguous signal. We introduce Freeform Preference Learning (FPL), a method for learning robot policies from freeform human preferences. Rath

- **Competition and Anomalies Redux: Evidence from U.S. Auto Dealers** _(binary option pricing convergence)_
  [2026-06-30](https://arxiv.org/abs/2606.32011v1)
  We examine a choice between bonus contracts offered to dealers of a U.S. auto manufacturer. In our data, dealers select the non-profit-maximizing option in 20 percent of observations, costing the mistaken dealers $18,453 per year on average. We examine how the propensity to make this mistake varies with competition, identified both cross-sectionally and within dealers over time. Both analyses show

- **On the Comparison of Reinforcement Learning and Adaptive Control for Linear Systems under Packet Loss and Uncertainty** _(event-driven trading)_
  [2026-06-30](https://arxiv.org/abs/2606.32003v1)
  This paper presents a comparative study between Adaptive Quantized Control (AQC) and Deep Deterministic Policy Gradient (DDPG) reinforcement learning for uncertain linear systems with input quantization over communication channels subject to packet loss. The considered setting also includes dynamic switching from a nominal unstable system to a more unstable one during operation. The AQC is designe

- **Accelerating Conformal Prediction via Approximate Leave-One-Out** _(event-driven trading)_
  [2026-06-30](https://arxiv.org/abs/2606.31915v1)
  While conformal prediction provides a general framework for uncertainty quantification in predictive inference, its application is often limited by computational cost. Recent methods, including Jackknife+ and Jackknife-minmax, achieve faster computation by trading a slight loss of efficiency relative to full conformal prediction, but still requires computing leave-one-out refits for all observatio

- **Trade-Offs in Decentralized Gigantic MIMO with Hard-Boundary Constraints** _(event-driven trading)_
  [2026-06-30](https://arxiv.org/abs/2606.31911v1)
  To maintain the antenna apertures offered by 5G massive MIMO systems operating at the sub-6GHz band, known as FR1, 6G base stations (BSs) using the upper-mid band, FR3, should increase the number of antennas by a factor 4-8, giving rise to gigantic MIMO. This poses challenges in terms of processing complexity and interconnection bandwidth. The WAX framework, previously introduced for exploring tra

- **Planar-SfM: Camera Pose Estimation via Homography Graph Embeddings** _(sports betting arbitrage)_
  [2026-06-30](https://arxiv.org/abs/2606.31979v1)
  Structure from Motion (SfM) systems traditionally struggle with planar scenes, where standard epipolar geometry-based methods become degenerate. Rather than viewing planar surfaces as a limitation, we propose a unified framework that leverages them as a source of geometric constraints. Our key insight is that each planar surface visible across multiple views provides an independent estimate of rel

- **FinPersona-Bench: A Benchmark for Longitudinal Psychometric Stability of Autonomous Financial Agents** _(sports betting arbitrage)_
  [2026-06-30](https://arxiv.org/abs/2606.31522v1)
  Large Language Models (LLMs) are increasingly deployed as autonomous financial agents initialized with explicit behavioral mandates such as "preserve capital" or "avoid speculative bets" that are meant to govern every decision throughout deployment. In practice, however, as market context accumulates over long horizons, these mandates gradually lose their behavioral influence, a phenomenon we form

- **Signature-Based Optimal Execution for Statistical Arbitrage with Path-Dependent Trading Signals** _(sports betting arbitrage)_
  [2026-06-30](https://arxiv.org/abs/2606.31387v1)
  We develop a signature-based framework for optimal execution in statistical arbitrage strategies with path-dependent predictive signals. Both the alpha process and the trading speed are modelled as linear functionals of the truncated signature of a time-augmented market path, placing signal generation and execution on the same truncated signature basis. This allows the trading rule to react to the

- **When LLMs Read Tables Carelessly: Measuring and Reducing Data Referencing Errors** _(Kelly criterion small bankroll)_
  [2026-06-30](https://arxiv.org/abs/2606.32029v1)
  While large language models (LLMs) perform well on table tasks, they still make data referencing errors (DREs), i.e., incorrectly citing or omitting table values, despite understanding the table structure. Beyond final-answer accuracy, DREs directly compromise the correctness and reliability of intermediate reasoning steps. Yet prior studies have only offered limited, small-scale analyses. In this

- **SemRF: A Semantic Reference Frame for Residual-Stream Dynamics in Language Models** _(Kelly criterion small bankroll)_
  [2026-06-30](https://arxiv.org/abs/2606.32022v1)
  Residual-stream analysis asks how language-model computation evolves across depth, but intermediate decoding requires comparable readout coordinates across layers. If embedding anchors and unembedding readout disagree on the chosen span, apparent motion may reflect measurement drift rather than computation. We introduce \emph{Semantic Reference Frames} (SemRF), an anchor-based formalism separating

- **GQL-Based Physical-Constraint-Preserving High-Order Finite Difference Schemes for Special Relativistic Hydrodynamics in Arbitrary Dimensions** _(Kelly criterion small bankroll)_
  [2026-06-30](https://arxiv.org/abs/2606.31992v1)
  High-order accurate simulations of special relativistic hydrodynamics (RHD) are prone to numerical breakdown if intrinsic physical constraints (positive rest-mass density/pressure and subluminal velocity) are violated near strong discontinuities. In this work, we develop a robust and efficient physical-constraint-preserving (PCP) flux-limiting framework for high-order schemes, using finite-differe

- **Stationary covariance spectra of discrete-time non-normal random recurrent dynamics** _(tail risk harvesting)_
  [2026-06-30](https://arxiv.org/abs/2606.31944v1)
  Principal component analysis is widely used to characterize structure in the dynamics of recurrent neural networks. For stationary noise-driven dynamics, the distribution of variance among the principal components is determined by the spectrum of the stationary covariance matrix. While the spectral properties of this matrix are well-understood for linear networks with normal synaptic weight matric

- **Delegation Rights: Property, Agency, and Investment Incentives in the Age of AI Agents** _(tail risk harvesting)_
  [2026-06-30](https://arxiv.org/abs/2606.31935v1)
  AI agents increasingly operate inside digital accounts by exercising privileges that users already hold, raising a new control question: whether an existing account entitlement must be exercised manually or may be exercised through a user-authorized automated proxy. We define \emph{delegation rights} as the revocable, identity-preserving, scope-limited, and mode-specific authority of an account ho

- **Theory of Mind and Persuasion Beyond Conversation: Assessing the Capacity of LLMs to Induce Belief States via Planning and Action** _(tail risk harvesting)_
  [2026-06-30](https://arxiv.org/abs/2606.31916v1)
  Theory of Mind (ToM) benchmarks for Large Language Models (LLMs) typically rely on passive question-answering formats, but the deployment of LLMs in increasingly agentic and autonomous forms demands new evaluations. In this paper we evaluate an agent's ability to induce specific belief states in other agents by taking actions rather than using conversational persuasion, a capability we call Non-Co

## 3. GitHub Repos (Recently Updated)
- **[samuel483/poly-kalshi-arb](https://github.com/samuel483/poly-kalshi-arb)** ⭐ 5 · Rust _(updated 2026-07-01)_
  🎯 Automate cross-platform arbitrage trading between Kalshi and Polymarket with this easy-to-use bot designed for optimal profit.

- **[oleksandrbannick/Meridian](https://github.com/oleksandrbannick/Meridian)** ⭐ 3 · Python _(updated 2026-07-01)_
  kalshi automated trading bot with custom UI

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-07-01)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-07-01)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-07-01)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[rockmundada/kalshi-weather-bot](https://github.com/rockmundada/kalshi-weather-bot)** ⭐ 0 · Python _(updated 2026-06-29)_
  Automated weather derivatives trading system for Kalshi — 5 API integrations, 10-chart analytics dashboard, data-driven strategy from 339 analyzed trades

- **[quipmnxailcrrgky/tradingbot](https://github.com/quipmnxailcrrgky/tradingbot)** ⭐ 98 · Solidity _(updated 2026-07-01)_
  Easy setup and creation of a bot

- **[rexlau-prog/pm-crypto-trend-dashboard](https://github.com/rexlau-prog/pm-crypto-trend-dashboard)** ⭐ 0 · HTML _(updated 2026-07-01)_
  Report dashboard for the pm_crypto_trend Polymarket 5-min trading bot

- **[bit-nexusxtitmtdsuy/Polymarket_Bot](https://github.com/bit-nexusxtitmtdsuy/Polymarket_Bot)** ⭐ 32 · None _(updated 2026-07-01)_
  Polymarket Bot is a tool for interacting with Polymarket, a decentralized prediction market platform where users trade shares representing the probability of real-world events using cryptocurrency (pr

- **[sehyunVan/Poly-model](https://github.com/sehyunVan/Poly-model)** ⭐ 0 · Python _(updated 2026-07-01)_
  A 24/7 Python trading stack for Polymarket prediction markets, paired with a Binance funding-rate arbitrage bot. Runs unattended on a Linux VM, makes real CLOB orders on Polygon, and exposes a local w

- **[Richardlai03/Prediction-Market-Arbitrage-Scanner](https://github.com/Richardlai03/Prediction-Market-Arbitrage-Scanner)** ⭐ 0 · Python _(updated 2026-07-01)_
  Real Time Arbitrage scanner across Polymarket, Kalshi, and sportsbooks with EV calculation and calibration analysis

- **[pjmerica/pred-arbitrage](https://github.com/pjmerica/pred-arbitrage)** ⭐ 0 · Python _(updated 2026-07-01)_
  Cross-market prediction market arbitrage scanner — Kalshi, Polymarket, PredictIt

- **[markl-a/phantom-quant](https://github.com/markl-a/phantom-quant)** ⭐ 0 · Python _(updated 2026-06-27)_
  Taiwan-stock backtest -> paper -> live trading engine on phantom-mesh. v1 (P0): fully-offline backtest with a real 台股 cost model, event-driven strategy contract, Decimal accounting. Apache-2.0.

- **[jhunter11/openclaw-kalshi-operator](https://github.com/jhunter11/openclaw-kalshi-operator)** ⭐ 0 · HTML _(updated 2026-06-26)_
  Autonomous AI agent operating an event-contract research & trading loop (Kalshi). Python research/orchestration harness + strategy gates + learning log.

- **[aasuper1/kalshi-alpha-strategies](https://github.com/aasuper1/kalshi-alpha-strategies)** ⭐ 0 · Python _(updated 2026-06-19)_
  Three independent Kalshi event-contract trading strategies: latency (sell-worthless), liquidity-incentive market making, and a cross-market/correlation engine.

## 4. Perplexity Strategy Synthesis
Small accounts ($50–$500) can profit on Kalshi and Polymarket in 2026 primarily through **domain-expertise trading** (buying undervalued outcomes in niches you understand) and **cross-venue arbitrage** on wide, slow-moving gaps, while **arbitrage** and **market-making** become viable only with capital splitting across venues or automated execution[2][3].

### Core Strategies & Concrete Parameters

#### 1. Tail Decay Harvesting (Domain-Expertise & "Obvious No")
This strategy exploits the market’s tendency to overprice low-probability events (tails) or underprice near-certain outcomes.
*   **Mechanism:** Focus on 2–3 categories where you possess a niche edge (e.g., specific sports leagues, technical crypto developments). Compare your research-based probability (e.g., 70%) against the market price (e.g., 50%) to identify undervaluation[2].
*   **"Obvious No" Play:** Identify markets where the outcome is near-certain (e.g., >90% probability) and buy the **NO** (or the losing side if the event is guaranteed) to collect the spread upon resolution[2].
*   **Parameters:**
    *   **Time Horizon:** Short-to-medium windows (resolve in days to weeks) to minimize tail risk exposure.
    *   **Position Sizing:** Strictly **1–5%** of your total bankroll per trade to manage volatility[2][3].
    *   **Entry Threshold:** Buy only if your edge > 15–20% (e.g., you see 70%, market sees 50%)[2].

#### 2. Cross-Venue Arbitrage (Kalshi vs. Polymarket)
Price gaps of **2–5%** exist between platforms on major events, allowing for guaranteed profit by locking in opposing positions[1].
*   **Mechanism:** Buy **YES** on the platform with the lower price (e.g., Kalshi at 50%) and **NO** on the higher price (e.g., Polymarket at 60%). The combined cost is <$1, guaranteeing a profit of the spread[2].
*   **Small Account Edge:** Manual arbitrage on **wide gaps (5¢+)** in slower markets is accessible to small accounts, whereas narrow spreads require automation and high-frequency bots[3].
*   **Parameters:**
    *   **Time Horizon:** Execute both legs within minutes to avoid price adjustment; hold until resolution.
    *   **Price Threshold:** Only trade if the spread > **5¢** (5%) to cover fees and slippage manually[3].
    *   **Critical Checks:** Verify **fee math** on both legs (Polymarket fees up to 1.8%, Kalshi fees vary) and ensure **matching resolution criteria** before entering[3][5].
    *   **Capital Requirement:** Minimum **$500 split** across venues recommended for efficient arbitrage, though smaller accounts can start with fewer, wider opportunities[3].

#### 3. Convergence Plays (Market Making)
Acting as a liquidity provider to earn the spread between buy and sell orders.
*   **Mechanism:** Place a limit **buy order at 49¢** and a **sell order at 51¢**. When both fill, you pocket the **2¢** spread per share[2].
*   **Small Account Edge:** While less capital-efficient than arbitrage for tiny accounts, it earns **liquidity rewards** on Polymarket and reduces transaction costs over time[2].
*   **Parameters:**
    *   **Spread Width:** Target **2–3¢

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-07-01 via Conway's auto-publisher.*
