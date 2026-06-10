# Kalshi Nightly Research Brief — 2026-06-10

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging prediction-market code, and uses Perplexity to synthesize the current state of Kalshi/Polymarket strategy. The brief below is raw — unedited, un-summarized.*

*Kalshi trading runs in paper mode with strict safety rails. Strategies and execution logic are public in conway-trading; proprietary signal aggregation stays private.*

---
_Generated at 2026-06-10T02:02:21, run time 21.6s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **When to Align, When to Predict: A Phase Diagram for Multimodal Learning** _(prediction market)_
  [2026-06-09](https://arxiv.org/abs/2606.11190v1)
  Cross-modal alignment (CA) and cross-modal prediction (CP) are the dominant paradigms for multimodal representation learning, yet there is no systematic understanding of when each succeeds, when each fails, and when cross-modal training helps at all -- a gap that leaves practitioners, especially in scientific domains like biomedicine or astrophysics, with heterogeneous instruments and multiple lev

- **ARM: An AutoRegressive Large Multimodal Model with Unified Discrete Representations** _(prediction market)_
  [2026-06-09](https://arxiv.org/abs/2606.11188v1)
  This paper introduces ARM, a discrete representation-based AutoRegressive Model that unifies image understanding, generation, and editing within a next-token prediction framework. ARM is built on three efforts: first, we train a discrete semantic visual tokenizer that maps images into compact token sequences. Our tokenizer is supervised with multiple objectives that jointly promote semantic discri

- **Next Forcing: Causal World Modeling with Multi-Chunk Prediction** _(prediction market)_
  [2026-06-09](https://arxiv.org/abs/2606.11187v1)
  Autoregressive video generation has emerged as a powerful paradigm for World Action Models (WAMs). However, existing approaches suffer from slow training convergence and limited converged accuracy, particularly at high frame rates, as the training supervision is confined to the current chunk without explicit signals about future dynamics; they also suffer from slow inference due to iterative video

- **Next Forcing: Causal World Modeling with Multi-Chunk Prediction** _(binary option pricing convergence)_
  [2026-06-09](https://arxiv.org/abs/2606.11187v1)
  Autoregressive video generation has emerged as a powerful paradigm for World Action Models (WAMs). However, existing approaches suffer from slow training convergence and limited converged accuracy, particularly at high frame rates, as the training supervision is confined to the current chunk without explicit signals about future dynamics; they also suffer from slow inference due to iterative video

- **Nonparametric Riemannian Empirical Bayes, and Denoising Measurements on Manifolds** _(binary option pricing convergence)_
  [2026-06-09](https://arxiv.org/abs/2606.11183v1)
  We initiate the study of nonparametric empirical Bayes denoising methods in the setting where both the latent variables and their measurements lie on a compact Riemannian manifold, and where the likelihood is a Riemannian Gaussian distribution. Our starting point is a novel Tweedie-Eddington formula for Riemannian Gaussian mixture models which identifies a certain surrogate oracle denoiser in term

- **The Role of Feedback Alignment in Self-Distillation** _(binary option pricing convergence)_
  [2026-06-09](https://arxiv.org/abs/2606.11173v1)
  Conditioning a language model on additional context, such as feedback on a previous attempt, typically improves its response. Self-distillation trains the model to retain this improvement when the context is not present. The method works by matching the model's output distribution under two settings: a student that sees only the question, and a self-teacher that also sees the context. What the mod

- **Data assimilation for subsurface flow using latent diffusion model parameterization: performance of ensemble-Kalman and Monte Carlo techniques** _(event-driven trading)_
  [2026-06-09](https://arxiv.org/abs/2606.11140v1)
  Data assimilation (DA) in subsurface flow entails calibrating model parameters to match observed data, typically at wells, while preserving geological realism. Latent diffusion models (LDMs) provide efficient mappings from high-dimensional geological model space to a low-dimensional latent variable, reducing the dimensionality of the inverse problem while maintaining plausibility in posterior geom

- **Towards Autonomous Accelerator Design: FPGA Accelerator Generation with SECDA** _(event-driven trading)_
  [2026-06-09](https://arxiv.org/abs/2606.11117v1)
  Designing FPGA-based accelerators for modern artificial intelligence workloads requires exploring a large and complex hardware design space that involves architectural parameters, data flow strategies, and memory hierarchies, making the process very time consuming. While existing methodologies such as SECDA enable rapid hardware-software co-design through SystemC simulation and FPGA execution, ide

- **Toward a Full-Stack Framework for Industrial Augmented Reality: Benefits, Risks, and Design Considerations for Dependable Deployment in Manufacturing** _(event-driven trading)_
  [2026-06-09](https://arxiv.org/abs/2606.11112v1)
  Industrial Augmented Reality (AR) has progressed from laboratory demonstrations to operational pilots across design, training, assembly, maintenance and quality assurance, yet broad, dependable deployment in manufacturing remains the exception. We synthesise existing evidence into a full-stack deployment framework structured along six distinct but coupled decision axes: (i) value and benefits, (ii

- **Arbitrage-free Data Pricing** _(sports betting arbitrage)_
  [2026-06-09](https://arxiv.org/abs/2606.10451v1)
  Driven by the rising value of data in applications such as advertising, finance, and machine learning, markets for data products have become increasingly important. Data markets mainly sell two kinds of products: datasets and machine learning models. Since these products can be replicated at negligible marginal cost, sellers naturally version them through query access and noisy model releases. Ver

- **A Universal Dense Football Event Representation Based on TabTransformer** _(sports betting arbitrage)_
  [2026-06-08](https://arxiv.org/abs/2606.09327v1)
  Football event data constitute a rich spatiotemporal source for quantitative analysis of player actions in team sports. These datasets contain heterogeneous features, combining continuous location coordinates with categorical variables such as action type, action outcome, and body part. Such data have been applied in sports analytics for match outcome forecasting, player evaluation, and tactical p

- **Pseudocompact Topological \(MV\)-Algebras** _(sports betting arbitrage)_
  [2026-06-08](https://arxiv.org/abs/2606.09259v1)
  Recently, topological MV-algebras have been investigated by several mathematicians. In this paper, we find that every topological \(MV\)-algebra is a Mal'tsev space introduced by Mal'tsev in 1954. Hence, applying the theorem of Reznichenko and Uspenskij on pseudocompact Mal'tsev spaces, we show that the product of arbitrary family of pseudocompact topological \(MV\)-algebras are pseudocompact. We 

- **When to Align, When to Predict: A Phase Diagram for Multimodal Learning** _(Kelly criterion small bankroll)_
  [2026-06-09](https://arxiv.org/abs/2606.11190v1)
  Cross-modal alignment (CA) and cross-modal prediction (CP) are the dominant paradigms for multimodal representation learning, yet there is no systematic understanding of when each succeeds, when each fails, and when cross-modal training helps at all -- a gap that leaves practitioners, especially in scientific domains like biomedicine or astrophysics, with heterogeneous instruments and multiple lev

- **Anchors that Don't Lift: Understanding Supply Chain Driven Kernel Lock-In and Governance-Mediated Mitigation Strategies in SOHO Devices** _(Kelly criterion small bankroll)_
  [2026-06-09](https://arxiv.org/abs/2606.11175v1)
  Small Office/Home Office (SOHO) devices are widely popular, yet often attacked due to security vulnerabilities in their firmware, affecting thousands of devices. These security vulnerabilities often stem from outdated Linux kernel versions included in SOHO device firmware. Naturally, prior work audited the extent and impact of this issue by simple Linux version extraction and version number based 

- **Piper: A Programmable Distributed Training System** _(Kelly criterion small bankroll)_
  [2026-06-09](https://arxiv.org/abs/2606.11169v1)
  Large-scale model training increasingly relies on composing multiple parallelism strategies, such as data, pipeline, and expert parallelism, together with memory-saving optimizations like ZeRO. Deployed systems for foundation model pretraining often rely on human experts to manually design a high-level parallelism strategy then implement the corresponding low-level execution strategy, making it di

- **Nonparametric Riemannian Empirical Bayes, and Denoising Measurements on Manifolds** _(tail risk harvesting)_
  [2026-06-09](https://arxiv.org/abs/2606.11183v1)
  We initiate the study of nonparametric empirical Bayes denoising methods in the setting where both the latent variables and their measurements lie on a compact Riemannian manifold, and where the likelihood is a Riemannian Gaussian distribution. Our starting point is a novel Tweedie-Eddington formula for Riemannian Gaussian mixture models which identifies a certain surrogate oracle denoiser in term

- **Unidirectional Entropic Solutions of the Pressureless Euler Alignment System** _(tail risk harvesting)_
  [2026-06-09](https://arxiv.org/abs/2606.11159v1)
  We study the pressureless Euler Alignment system with unidirectional velocity (u,0,...,0). By re-casting the system as a family of coupled scalar balance laws, one for each horizontal slice of R^d, we are able to prove existence, uniqueness, and stability within the class of unidirectional solutions, under the assumption of a bounded Lipschitz communication protocol. The nonlocal coupling between 

- **ABC-Bench: An Agentic Bio-Capabilities Benchmark for Biosecurity** _(tail risk harvesting)_
  [2026-06-09](https://arxiv.org/abs/2606.11150v1)
  Large language models (LLMs) are rapidly acquiring capabilities relevant to biological research, from literature synthesis to interpretation of experimental data. Increasingly, LLM agents can also perform in silico biology tasks that previously required experienced human biologists. These emerging AI capabilities offer new opportunities for scientific discovery and biomedical advances, but they al

## 3. GitHub Repos (Recently Updated)
- **[anglil/kalshi-ai-trading-bot](https://github.com/anglil/kalshi-ai-trading-bot)** ⭐ 4 · Python _(updated 2026-06-10)_
  AI-powered Kalshi prediction market trading bot using Gemini

- **[oleksandrbannick/Meridian](https://github.com/oleksandrbannick/Meridian)** ⭐ 1 · Python _(updated 2026-06-10)_
  kalshi automated trading bot with custom UI

- **[agung65122-byte/crypto-arbitrage-bot-automated-trading](https://github.com/agung65122-byte/crypto-arbitrage-bot-automated-trading)** ⭐ 0 · None _(updated 2026-06-10)_
  Scan multi-chain markets and execute automated crypto arbitrage trades across TON, Solana, and EVM networks.

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-06-10)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-06-10)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[TexasCoding/kalshi-python-sdk](https://github.com/TexasCoding/kalshi-python-sdk)** ⭐ 0 · Python _(updated 2026-06-10)_
  Professional Python SDK for the Kalshi prediction markets API

- **[onur-tech/KongTradeBot](https://github.com/onur-tech/KongTradeBot)** ⭐ 0 · Python _(updated 2026-06-10)_
  Polymarket Trade Bot

- **[Casiniza/polymarket-bot](https://github.com/Casiniza/polymarket-bot)** ⭐ 1 · Python _(updated 2026-06-10)_
  Automated Polymarket trading bot with GitHub Actions

- **[RiekertQuant/polymarket-weather-bot-poc](https://github.com/RiekertQuant/polymarket-weather-bot-poc)** ⭐ 21 · Python _(updated 2026-06-10)_
  Paper trading bot for Polymarket weather temperature markets (POC)

- **[Aidenb2931/polymarket-bot](https://github.com/Aidenb2931/polymarket-bot)** ⭐ 0 · None _(updated 2026-06-10)_
  Automate trades and identify arbitrage opportunities on Polymarket using this execution tool for prediction markets.

- **[Pearlfisheryjersey8695/kalshiquant](https://github.com/Pearlfisheryjersey8695/kalshiquant)** ⭐ 2 · Python _(updated 2026-06-10)_
  Trade Kalshi prediction markets with a quantitative system designed for fee-aware position sizing and statistical arbitrage.

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-06-10)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[talirabban/prediction-markets-thesis](https://github.com/talirabban/prediction-markets-thesis)** ⭐ 0 · Python _(updated 2026-06-08)_
  Quantitative analysis of Polymarket event contracts: calibration, ML-based pricing-error prediction, and out-of-sample strategy backtesting.

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

- **[Waike122333/Automated-Trading-Kalshi](https://github.com/Waike122333/Automated-Trading-Kalshi)** ⭐ 0 · None _(updated 2026-03-17)_
  An algorithmic trading bot for kalshi.com event contracts that automates trading strategies based on economic data, news events, weather patterns, and political markets in real-time.

## 4. Perplexity Strategy Synthesis
The most actionable strategies for **Kalshi** and **Polymarket** in 2026 are: **(1) tail-decay harvesting** in binary markets with fast mean reversion, **(2) cross-venue arbitrage** between venue-implied probabilities and external reference prices, **(3) convergence plays** on markets that become mechanically closer to resolution as information accumulates, and **(4) tiny-account niche edges** where fee structure, order-book frictions, or stale quotes still leave room for $50–$500 accounts.[1][3][5][7]

Because your request asks for *recent posts/threads*, I should be explicit: the search results here include general explainers and a YouTube tutorial, but not a rich set of recent trading-strategy blog posts or X threads specifically about 2026 prediction-market alpha.[1][2][5][7] So below I’m combining the sourced platform/market facts with practical strategy design that follows from how these venues work.[1][3][5][7]

| Strategy | Best on | Core edge | Typical time horizon | Practical entry rules | Position sizing for small accounts |
|---|---|---|---|---|---|
| Tail-decay harvesting | Both, especially thin Kalshi contracts | Selling overpriced “far tails” that decay as the event becomes less uncertain | Hours to weeks | Short volatility after hype spikes; target events with many information updates | 2%–10% of bankroll per name, smaller if binary gap is wide |
| Cross-venue arbitrage | Both | Price mismatch vs another venue or external market | Minutes to days | Buy the underpriced side, sell/avoid the overpriced side when spread exceeds costs | Very small per-trade size; scale only after fills are reliable |
| Convergence plays | Both | Markets converge as date approaches and ambiguity disappears | Days to weeks | Enter when resolution path is becoming clearer, but price still lags fundamentals | Ladder entries; reserve half bankroll for later adds |
| Small-account edge cases | Kalshi often, some Polymarket niches | Low fees/stale books/small contest markets | Intraday to weeks | Focus on illiquid names, event-driven mispricings, and contract ranges where $50–$500 can actually move the book | 1–5 active positions max; avoid concentration in one event |

**1) Tail-decay harvesting**

This is the most realistic “systematic” edge for small accounts on binary prediction markets: you fade overreaction in contracts that temporarily become too extreme, then wait for the probability to drift back as the market digests new information.[1][3][7]

- On Kalshi and Polymarket, the basic price mechanism is a probability market: the contract price is tied to the market’s implied chance of the event, and both platforms support event-contract trading.[1][3]
- The practical setup is to look for contracts that move sharply on headline risk, then enter *against* the move only when the new information is not actually decisive.
- Good candidates are markets with frequent updates but no resolution yet: elections, macro releases, legal events, sports injury news, or policy timelines.
- A useful rule of thumb is to target **50–150 bps of temporary overreaction** on liquid contracts, and **1–3 cents** of mispricing on thinner ones if the order book is sparse.
- Time horizon: **same day to 2 weeks** is usually the sweet spot; the edge decays once the market fully incorporates the news.
- For a small account, keep each tail-decay trade to **\$10–\$50 notional** on a \$50 account and **\$25–\$100** on a \$500 account unless liquidity is excellent.
- Avoid holding into a true binary catalyst if the event can actually resolve the market against yo

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-06-10 via Conway's auto-publisher.*
