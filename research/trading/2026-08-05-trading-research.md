# Trading Nightly Research Brief — 2026-08-05

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-08-05T02:31:33, run time 25.5s._

## 1. Self-Analysis (Conway Trade Log)
```json
{
  "total_trades_logged": 130,
  "trades_last_7d": 0,
  "top_symbols_7d": [],
  "side_breakdown_7d": {}
}
```

## 2. arXiv Papers (Last 60 Days)
- **ParVL: Parallel Scaling and Expandable Compute Allocation for Multimodal LLMs** _(quantitative trading strategy)_
  [2026-08-04](https://arxiv.org/abs/2608.04010v1)
  Existing scaling strategies for Multimodal Large Language Models (MLLMs) typically expand either model parameters or sequential inference computation, incurring substantial memory or latency overhead. More importantly, most existing methods fail to alter the rigid, fixed computation allocation between the Vision Transformer and the Large Language Model components, limiting task-specific optimizati

- **When Attention Goes Blind: Numerical Failure in ALiBi Positional Encodings** _(quantitative trading strategy)_
  [2026-08-04](https://arxiv.org/abs/2608.03994v1)
  We identify a previously overlooked failure mode of ALiBi positional encoding: its linear bias scaling underflows floating-point precision, which zeroes out a large fraction of attention weights and renders the affected attention heads partially blind. We analyze this failure mode, characterize its impact, and examine four mitigation strategies. We further demonstrate its occurrence in state-of-th

- **A lower bound on the classical simulation cost of star-network correlations** _(quantitative trading strategy)_
  [2026-08-04](https://arxiv.org/abs/2608.03986v1)
  It is well established that quantum strategies outperform classical ones in several communication tasks. We study the quantum communication complexity of correlations arising from joint measurements on quantum systems distributed across a star network, where several parties each send a quantum system to a central node. We introduce an exclusion task that can be solved perfectly when each party sen

- **Collective tunnel ionization in atomic systems** _(momentum crash risk)_
  [2026-08-04](https://arxiv.org/abs/2608.03998v1)
  We present a theory of the collective tunnel effect in atomic systems subject to strong low-frequency laser fields. Using an analytic semi-classical method and numerical solution to the time-dependent Schrodinger equation we demonstrate the collective channel of the nonsequential double ionization in neutral xenon and in the negative bromine ion. Collective tunneling in the presence of the electro

- **Resolution-Adaptive Compact-Support Priors for Bayesian Wavelet Denoising** _(momentum crash risk)_
  [2026-08-04](https://arxiv.org/abs/2608.03946v1)
  We propose a resolution-adaptive Bayesian wavelet denoising method for noisy one-dimensional signals. The model uses a spike-and-slab prior whose continuous slab is a mixture of a compactly supported Wendland-type polynomial kernel and the semicircle density, with a data-adaptive resolution-specific truncation scale. The Wendland component concentrates mass near zero and vanishes smoothly at the s

- **A Robust Chance Constrained Approach to Surgery Scheduling** _(momentum crash risk)_
  [2026-08-04](https://arxiv.org/abs/2608.03931v1)
  We study elective surgery scheduling under uncertain procedure durations. Schedules based on mean durations or fixed buffering rules may appear efficient ex ante but become fragile in execution, as early overruns propagate through the day and expose later surgeries to accumulated delay. We propose a robust chance-constrained framework that separates uncertainty quantification from schedule optimiz

- **SocietyBench: Forecasting Counterfactual Social-World Evolution** _(mean reversion statistical arbitrage)_
  [2026-08-04](https://arxiv.org/abs/2608.04009v1)
  Large language models (LLMs), and the agents built on top of them, are now benchmarked heavily on whether they can finish a task -- fix a bug, drive a browser, operate a GUI. A complementary social ability, namely how well a model understands and forecasts the way real social events unfold, has barely been measured. We introduce SocietyBench, an end-to-end benchmark that takes a one-line event top

- **Semantic Bundling: Interactive Node and Edge Bundling to Simplify Knowledge Graphs using Large Language Models** _(mean reversion statistical arbitrage)_
  [2026-08-04](https://arxiv.org/abs/2608.04002v1)
  We present Semantic Bundling, a visual analytics technique for making sense of text documents represented as knowledge graphs (KGs). Representing a document corpus as a KG makes relationships between entities explicit, making KGs useful both to analyze directly and in computational workflows including ML pipelines and generative AI backends. However, as KGs grow they become difficult to interpret 

- **Test-Time Scaling in Reasoning LLMs: Inference Regimes, Evaluation, and Reproducibility** _(mean reversion statistical arbitrage)_
  [2026-08-04](https://arxiv.org/abs/2608.04001v1)
  Large language models can solve substantially harder reasoning problems with more inference-time compute. The term "test-time scaling," however, now covers diverse inference algorithms that extend deliberation along a single trajectory, sample completed candidates and aggregate them through voting or verification, or search over unfinished partial states. These algorithms differ in their statistic

- **WorldCup Arena: Prospective, Leakage-Free Evaluation of Frontier LLMs on a Live Tournament** _(regime detection market)_
  [2026-08-04](https://arxiv.org/abs/2608.04008v1)
  Benchmarks that measure the forecasting ability of large language models are almost always retrospective: the event has happened, the answer is somewhere on the Web, and the evaluation must defend itself against memorisation. We report the opposite design. Over the 39 days of the 2026 FIFA World Cup, six frontier LLMs -- all with extended thinking and native server-side web search -- were asked be

- **Test-Time Scaling in Reasoning LLMs: Inference Regimes, Evaluation, and Reproducibility** _(regime detection market)_
  [2026-08-04](https://arxiv.org/abs/2608.04001v1)
  Large language models can solve substantially harder reasoning problems with more inference-time compute. The term "test-time scaling," however, now covers diverse inference algorithms that extend deliberation along a single trajectory, sample completed candidates and aggregate them through voting or verification, or search over unfinished partial states. These algorithms differ in their statistic

- **Reduced-order modeling for electromagnetic inverse problems: a layered medium benchmark** _(regime detection market)_
  [2026-08-04](https://arxiv.org/abs/2608.03996v1)
  We study reduced-order modeling for inverse problems in layered media, focusing on the recovery of impedance profiles from time-domain measurements. Using the Goupillaud structure, we formulate the forward problem as a discrete dynamical system and introduce a ROM-based objective defined at the level of reduced operators. Through numerical experiments on a 5-layer medium under various structured p

- **SocietyBench: Forecasting Counterfactual Social-World Evolution** _(deep learning volatility forecasting)_
  [2026-08-04](https://arxiv.org/abs/2608.04009v1)
  Large language models (LLMs), and the agents built on top of them, are now benchmarked heavily on whether they can finish a task -- fix a bug, drive a browser, operate a GUI. A complementary social ability, namely how well a model understands and forecasts the way real social events unfold, has barely been measured. We introduce SocietyBench, an end-to-end benchmark that takes a one-line event top

- **WorldCup Arena: Prospective, Leakage-Free Evaluation of Frontier LLMs on a Live Tournament** _(deep learning volatility forecasting)_
  [2026-08-04](https://arxiv.org/abs/2608.04008v1)
  Benchmarks that measure the forecasting ability of large language models are almost always retrospective: the event has happened, the answer is somewhere on the Web, and the evaluation must defend itself against memorisation. We report the opposite design. Over the 39 days of the 2026 FIFA World Cup, six frontier LLMs -- all with extended thinking and native server-side web search -- were asked be

- **TurnSight: Turn-Level Hindsight Self-Distillation for Tool-Integrated Reasoning** _(deep learning volatility forecasting)_
  [2026-08-04](https://arxiv.org/abs/2608.04007v1)
  Tool-Integrated Reasoning (TIR) enables LLMs to solve complex tasks through iterative tool interactions. However, existing reinforcement learning methods often rely on trajectory-level supervision, limiting fine-grained credit assignment in long-horizon TIR scenarios. On-policy self-distillation offers denser signals through teacher branches with privileged context, but existing approaches typical

- **ParVL: Parallel Scaling and Expandable Compute Allocation for Multimodal LLMs** _(transformer financial time series)_
  [2026-08-04](https://arxiv.org/abs/2608.04010v1)
  Existing scaling strategies for Multimodal Large Language Models (MLLMs) typically expand either model parameters or sequential inference computation, incurring substantial memory or latency overhead. More importantly, most existing methods fail to alter the rigid, fixed computation allocation between the Vision Transformer and the Large Language Model components, limiting task-specific optimizati

- **SocietyBench: Forecasting Counterfactual Social-World Evolution** _(transformer financial time series)_
  [2026-08-04](https://arxiv.org/abs/2608.04009v1)
  Large language models (LLMs), and the agents built on top of them, are now benchmarked heavily on whether they can finish a task -- fix a bug, drive a browser, operate a GUI. A complementary social ability, namely how well a model understands and forecasts the way real social events unfold, has barely been measured. We introduce SocietyBench, an end-to-end benchmark that takes a one-line event top

- **WorldCup Arena: Prospective, Leakage-Free Evaluation of Frontier LLMs on a Live Tournament** _(transformer financial time series)_
  [2026-08-04](https://arxiv.org/abs/2608.04008v1)
  Benchmarks that measure the forecasting ability of large language models are almost always retrospective: the event has happened, the answer is somewhere on the Web, and the evaluation must defend itself against memorisation. We report the opposite design. Over the 39 days of the 2026 FIFA World Cup, six frontier LLMs -- all with extended thinking and native server-side web search -- were asked be

- **TurnSight: Turn-Level Hindsight Self-Distillation for Tool-Integrated Reasoning** _(reinforcement learning portfolio)_
  [2026-08-04](https://arxiv.org/abs/2608.04007v1)
  Tool-Integrated Reasoning (TIR) enables LLMs to solve complex tasks through iterative tool interactions. However, existing reinforcement learning methods often rely on trajectory-level supervision, limiting fine-grained credit assignment in long-horizon TIR scenarios. On-policy self-distillation offers denser signals through teacher branches with privileged context, but existing approaches typical

- **Calibrating Trustworthiness: Co-Designing Metrics and Visualizations for Evaluating LLMs in Education** _(reinforcement learning portfolio)_
  [2026-08-04](https://arxiv.org/abs/2608.04006v1)
  LLMs are reshaping educational technology, yet evaluating their responses for pedagogical alignment remains underexplored, relying heavily on the expertise of learning engineers building the technology. To bridge this gap, we explore trustworthiness as a structured lens for evaluation, leveraging existing measures of LLM trustworthiness to systematically identify potential pedagogical disruptions.

- **PAST-Bench: Benchmarking the Foundations of Recursive Self-Improvement in Personal Agents** _(reinforcement learning portfolio)_
  [2026-08-04](https://arxiv.org/abs/2608.04003v1)
  Recursive self-improvement requires agents to turn accumulated experience into better future behavior. Personal AI agents offer a concrete setting for studying this capability because they retain preferences, task histories, tool routines, and learned skills across sessions. Yet whether retained experience actually improves them over time has not been systematically tested. We introduce PAST-Bench

- **ParVL: Parallel Scaling and Expandable Compute Allocation for Multimodal LLMs** _(cryptocurrency trading)_
  [2026-08-04](https://arxiv.org/abs/2608.04010v1)
  Existing scaling strategies for Multimodal Large Language Models (MLLMs) typically expand either model parameters or sequential inference computation, incurring substantial memory or latency overhead. More importantly, most existing methods fail to alter the rigid, fixed computation allocation between the Vision Transformer and the Large Language Model components, limiting task-specific optimizati

- **Option Pricing with Time-Changed Fractional Brownian Motion: A Fractional Variance Gamma Model** _(cryptocurrency trading)_
  [2026-08-04](https://arxiv.org/abs/2608.03925v1)
  Fractional Brownian motion (fBm) exhibits attractive features for financial modeling, including long-range dependence, path roughness, and anomalous diffusion. However, its non-semimartingale nature precludes the use of conventional no-arbitrage approaches to option pricing. We address this limitation by introducing a time-changed fBm, obtained by evaluating fBm at stochastic gamma activity time, 

- **When and Where to Look: Adaptive Visual Evidence Scheduling for Efficient Long Video Understanding** _(cryptocurrency trading)_
  [2026-08-04](https://arxiv.org/abs/2608.03918v1)
  Efficient long-video understanding requires vision--language models (VLMs) to reason over a small number of frames selected as sparse visual evidence. Existing relevance-based methods rely on static one-shot selection with fixed frame budgets and candidate pools, while agent-based schedulers achieve adaptivity through costly multi-round reasoning and interactive search. We propose EcoFrame, a trai

- **SocietyBench: Forecasting Counterfactual Social-World Evolution** _(options volatility surface)_
  [2026-08-04](https://arxiv.org/abs/2608.04009v1)
  Large language models (LLMs), and the agents built on top of them, are now benchmarked heavily on whether they can finish a task -- fix a bug, drive a browser, operate a GUI. A complementary social ability, namely how well a model understands and forecasts the way real social events unfold, has barely been measured. We introduce SocietyBench, an end-to-end benchmark that takes a one-line event top

- **Analysis on surfaces with locally bounded integral curvature** _(options volatility surface)_
  [2026-08-04](https://arxiv.org/abs/2608.03982v1)
  We prove several analytic results on (possibly noncompact) complete singular surfaces having locally bounded integral curvature (in short: BIC surfaces). Regarding these as metric measure spaces with the 2-dimensional Hausdorff measure, we show that these are infinitesimally Hilbertian, locally doubling and satisfy a local Poincaré inequality. In particular, this entails the existence of a jointly

- **Real-time decoding of quantum error correction codes using high-performance computing** _(options volatility surface)_
  [2026-08-04](https://arxiv.org/abs/2608.03948v1)
  Quantum error correction (QEC) is indispensable for building scalable fault-tolerant quantum computers. Effective QEC demands stringent real-time decoding: the decoder must process syndrome measurements and determine corrections within a time scale--typically on the order of microseconds, to avoid data backlog. Scaling to large number of logical qubits further necessitates significant computationa

- **A Stackelberg-Bayesian Capacity-Market Game of Carbon Regulation and Second-Life Battery Investment under AI Data-Center Load Growth** _(factor investing alpha)_
  [2026-08-04](https://arxiv.org/abs/2608.03989v1)
  Artificial intelligence (AI) data centers are driving rapid electricity load growth across all U.S. ISO/RTO regions, raising both system costs and carbon exposure. This study develops a three-level Stackelberg--Bayesian game in which a regulator (leader) sets carbon penalties and subsidies, a single ISO capacity market clears against an energy balance modeled as a classical generation-expansion pr

- **Revised exclusion limits on doubly charged Higgs bosons from a reanalysis of the ATLAS multi-lepton search at $\sqrt{s} = 13$,TeV** _(factor investing alpha)_
  [2026-08-04](https://arxiv.org/abs/2608.03988v1)
  The ATLAS search for pair-produced doubly charged Higgs bosons in multi-lepton final states using the full Run 2 dataset [Eur. Phys. J. C 83 (2023) 605] reports the strongest limits to date on the mass of doubly charged scalars, driven by an essentially background-free four-lepton channel. We show that the four-lepton signal efficiency implied by the auxiliary cutflow of that analysis exceeds a st

- **Helium-poor winds do not require helium-poor planets** _(factor investing alpha)_
  [2026-08-04](https://arxiv.org/abs/2608.03980v1)
  Observations of the metastable He,{\sc i},10830,Å triplet have revealed escaping exoplanet atmospheres whose inferred helium abundances range from nearly nebular compositions to strongly helium-depleted winds. Such depletion is commonly interpreted as evidence for atmospheric evolution, preferential escape, or departures from primordial composition. We present a closed-form analytic transport-rete

## 3. GitHub Repos (Recently Updated)
- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 0 · Jupyter Notebook _(updated 2026-08-05)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[selormwalker/vortex-hft-core](https://github.com/selormwalker/vortex-hft-core)** ⭐ 1 · Python _(updated 2026-08-05)_
  A high-performance low-latency trading engine core for high-frequency trading and quantitative risk analysis.

- **[Vixoq/vnpy](https://github.com/Vixoq/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-08-05)_
  Open source quantitative trading platform development framework based

- **[xpyct1337/ton-quant](https://github.com/xpyct1337/ton-quant)** ⭐ 0 · Python _(updated 2026-08-05)_
  Real-time TON blockchain analytics: 24-jetton market terminal, token dashboards, whale tracking, on-chain trading signals, paper-trading bots & signal backtesting. TONAPI + STON.fi + DexScreener, pure

- **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance)** ⭐ 12 · Python _(updated 2026-08-05)_
  Easily build, backtest and deploy your algo in just a few lines of code. Trade stocks, cryptos, and forex across exchanges one package.

- **[ssproduction13-ship-it/crypto-signal-bot](https://github.com/ssproduction13-ship-it/crypto-signal-bot)** ⭐ 0 · TypeScript _(updated 2026-08-05)_
  Telegram bot for crypto trading signals with AI analysis (Gemini), backtesting, paper trading

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 0 · Jupyter Notebook _(updated 2026-08-05)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[BrockStar3540/mr-scrooge-v6](https://github.com/BrockStar3540/mr-scrooge-v6)** ⭐ 4 · Python _(updated 2026-08-05)_
  Open-source algorithmic forex trading bot for OANDA (Python) — cell-based execution, wide-stop ratchet exits, a full backtesting research program, and a live control-panel dashboard. Strategy-neutral 

- **[Lumimojjav/Qwik-CoinSwapAi-Crypto-Coins-Bitecoin-BCH](https://github.com/Lumimojjav/Qwik-CoinSwapAi-Crypto-Coins-Bitecoin-BCH)** ⭐ 0 · JavaScript _(updated 2026-08-05)_
  This repository provides Qwik, a CoinSwapAI sniper bot for trading cryptocurrencies, including Bitcoin and Bitcoin Cash (BCH). It utilizes AI algorithms to identify and execute profitable trades, enha

- **[Kartik281204/AI-Quant-Research-Platform](https://github.com/Kartik281204/AI-Quant-Research-Platform)** ⭐ 0 · Python _(updated 2026-08-05)_
  QuantEdge Research Terminal is an institutional-style quantitative research platform for equities and ETFs. It is a full Streamlit web app that brings together portfolio analytics, factor models, ML-b

- **[liuh886/alpha_engine](https://github.com/liuh886/alpha_engine)** ⭐ 0 · Python _(updated 2026-08-04)_
  Alpha Engine: AI-driven quantitative trading research platform with factor lifecycle, model registry, backtesting, and dashboard.

- **[Shenyqqq/ashare-factor-kit](https://github.com/Shenyqqq/ashare-factor-kit)** ⭐ 0 · None _(updated 2026-08-04)_
  A-share multifactor research kit: PIT-safe data, IC screening, and walk-forward backtests for open-source or custom alphas (optional Barra neutralization).

- **[chopchopulen/pairs-engine](https://github.com/chopchopulen/pairs-engine)** ⭐ 0 · Python _(updated 2026-08-04)_
  Statistical arbitrage pairs trading engine — Johansen cointegration, Kalman Filter dynamic hedge ratio, walk-forward backtesting. EWA/EWC: Sharpe 0.296, 72.7% win rate.

- **[1ruz/Statistical-Arbitrage-Model](https://github.com/1ruz/Statistical-Arbitrage-Model)** ⭐ 0 · Python _(updated 2026-08-04)_
  Develop a pairs trading or statistical arbitrage model to detect price inefficiencies between correlated assets. Use time-series analysis techniques like cointegration and mean reversion to generate s

- **[mdutta1234/a-statistical-arbitrage-for-pairs-trading](https://github.com/mdutta1234/a-statistical-arbitrage-for-pairs-trading)** ⭐ 0 · Python _(updated 2026-08-04)_
  

- **[Vixoqz/vnpy](https://github.com/Vixoqz/vnpy)** ⭐ 0 · Jupyter Notebook _(updated 2026-08-05)_
  vnpy (VeighNa): an open-source quantitative trading framework in Python. Build, backtest and run algorithmic trading strategies across futures, stocks, options and crypto through a unified gateway API

- **[zzwjlwwdtg/quant-trading-framework](https://github.com/zzwjlwwdtg/quant-trading-framework)** ⭐ 2 · Python _(updated 2026-08-05)_
  Algorithmic trading framework for JP + US equities: daily-K signals, HMM regime detection, Claude LLM decision gate, options wall analysis, paper trading

- **[mikecoombs4/CTS-AI](https://github.com/mikecoombs4/CTS-AI)** ⭐ 0 · Python _(updated 2026-08-05)_
  AI Powered Options trading system using the CTS framework

## 4. Perplexity Strategy Synthesis
For a **$100–$1000 retail account**, the most actionable systematic ideas right now are the ones with *simple execution, capped risk, and low dependence on tight fees/slippage*: **crypto momentum with regime filters** is the most practical, **equity pair trading** is only workable if you can trade commission-free and keep position sizes tiny, and **options tail hedges** are usually *not* “cheap” for small accounts unless you use very small, event-driven, or spread-based structures. The “new edge” category is the least reliable from the sources provided, because the search results here are mostly retail-trading content rather than recent peer-reviewed papers or high-signal trading threads.  

## 1) Crypto momentum with regime filters

This is the best fit for small accounts because crypto offers 24/7 liquid trending markets, fractional sizing, and the ability to express momentum on spot or perp instruments with a hard risk cap. A common practical implementation is a *trend-following breakout* with a volatility/trend regime filter: only trade when the market is above a medium-term trend filter and realized volatility is not collapsing. The search results support the general idea of momentum trading and the use of trend/risk filters, but they do not provide a specific published crypto strategy paper in the provided set.[2][19]

**Concrete parameters**
- **Time horizon:** 1 day to 2 weeks.
- **Universe:** BTC, ETH, and 3–10 top liquid large caps only.
- **Regime filter:** Trade long only when price is above the **200-day moving average** or a similar long-term trend filter, and the **20-day realized volatility** is above a minimum threshold to avoid dead chop; skip when Bitcoin is below its 200-day filter because alt momentum usually degrades in risk-off regimes. This exact filter set is an inference from standard systematic practice rather than something explicitly specified in the provided results.
- **Entry:** Buy on a breakout above the **20-day high** or **10-day high** after a pullback holds above the **20-day EMA**; prefer entries after a 1–3 day consolidation rather than chasing a vertical move.
- **Exit:** Exit on a close below the **10-day EMA**, or after **2–3 ATR** from entry; for a simpler version, use a trailing stop at **2 ATR** and take partial profits at **1.5R**.
- **Position sizing:** Risk **0.5%–1.0% of account equity per trade**; with a $500 account, that is **$2.50–$5** of max loss per trade. Keep total simultaneous crypto risk under **2%–3%**.
- **Practical note:** For a $100 account, even 1% risk may be too small after fees, so the strategy is most realistic near the top of your stated range.

**What to avoid**
- Highly illiquid alts.
- Mean reversion against a strong trend.
- Trading every breakout without a regime filter.

**Crowding / degradation**
- Momentum in crypto has likely **degraded in the most crowded large-cap names** because breakouts are heavily watched, but the provided sources do not contain a recent dataset proving a last-6-month deterioration.[19] The safe interpretation is to use the filter and keep the universe broad, rather than assuming a standalone breakout edge persists in the most obvious coins.

## 2) Equity pair trading

Pair trading is the most statistically disciplined of the four ideas, but it is usually *harder* for very small accounts because you need two legs, good execution, and enough capital to survive noise. It is still viable in a micro-size form if you use highly liquid, same-sector names and extremely simple reversion rules. The provided sources do not include a specific recent pair-trading paper, so the structure below is based on standard systematic practice.

**Concrete parameters**
- **Time horizon:** 3 days to 6 weeks.
- **Universe:** Highly liquid same-sector pairs, such as two large-cap banks, two semis, or two big retailers.
- **Pair selection filter:** Choose pairs with high historical correlation or similar business model; avoid pairs with major idiosyncratic event risk.
- **Signal:** Compute the **z-score** of the spread over a **60-day** or **120-day

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-08-05 via Conway's auto-publisher.*
