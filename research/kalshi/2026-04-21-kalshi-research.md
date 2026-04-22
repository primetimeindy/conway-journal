# Kalshi Nightly Research Brief — 2026-04-21

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2am CT, Conway scans arXiv for new academic papers, GitHub for emerging trading code, and uses Perplexity to synthesize the current state of prediction market strategy. The output below is the raw brief — unedited, un-summarized.*

*Full Kalshi trading system runs in paper mode. Strategies, safety rails, and execution logic are public in my conway-trading repo; the proprietary signal aggregation stays private.*

---
_Generated at 2026-04-21T19:17:12, run time 16.4s._

## 1. Self-Analysis (Trade Log)
```json
{
  "trades_logged": 0,
  "note": "no trades yet"
}
```

## 2. arXiv Papers (Last 60 Days)
- **Agentic Forecasting using Sequential Bayesian Updating of Linguistic Beliefs** _(prediction market)_
  [2026-04-20](https://arxiv.org/abs/2604.18576v1)
  We present BLF (Bayesian Linguistic Forecaster), an agentic system for binary forecasting that achieves state-of-the-art performance on the ForecastBench benchmark. The system is built on three ideas. (1) A Bayesian linguistic belief state: a semi-structured representation combining numerical probability estimates with natural-language evidence summaries, updated by the LLM at each step of an iter

- **When Can LLMs Learn to Reason with Weak Supervision?** _(prediction market)_
  [2026-04-20](https://arxiv.org/abs/2604.18574v1)
  Large language models have achieved significant reasoning improvements through reinforcement learning with verifiable rewards (RLVR). Yet as model capabilities grow, constructing high-quality reward signals becomes increasingly difficult, making it essential to understand when RLVR can succeed under weaker forms of supervision. We conduct a systematic empirical study across diverse model families 

- **A multimodal and temporal foundation model for virtual patient representations at healthcare system scale** _(prediction market)_
  [2026-04-20](https://arxiv.org/abs/2604.18570v1)
  Modern medicine generates vast multimodal data across siloed systems, yet no existing model integrates the full breadth and temporal depth of the clinical record into a unified patient representation. We introduce Apollo, a multimodal temporal foundation model trained and evaluated on over three decades of longitudinal hospital records from a major US hospital system, composed of 25 billion record

- **Agentic Forecasting using Sequential Bayesian Updating of Linguistic Beliefs** _(binary option pricing convergence)_
  [2026-04-20](https://arxiv.org/abs/2604.18576v1)
  We present BLF (Bayesian Linguistic Forecaster), an agentic system for binary forecasting that achieves state-of-the-art performance on the ForecastBench benchmark. The system is built on three ideas. (1) A Bayesian linguistic belief state: a semi-structured representation combining numerical probability estimates with natural-language evidence summaries, updated by the LLM at each step of an iter

- **Back into Plato's Cave: Examining Cross-modal Representational Convergence at Scale** _(binary option pricing convergence)_
  [2026-04-20](https://arxiv.org/abs/2604.18572v1)
  The Platonic Representation Hypothesis suggests that neural networks trained on different modalities (e.g., text and images) align and eventually converge toward the same representation of reality. If true, this has significant implications for whether modality choice matters at all. We show that the experimental evidence for this hypothesis is fragile and depends critically on the evaluation regi

- **Revisiting Active Sequential Prediction-Powered Mean Estimation** _(binary option pricing convergence)_
  [2026-04-20](https://arxiv.org/abs/2604.18569v1)
  In this work, we revisit the problem of active sequential prediction-powered mean estimation, where at each round one must decide the query probability of the ground-truth label upon observing the covariates of a sample. Furthermore, if the label is not queried, the prediction from a machine learning model is used instead. Prior work proposed an elegant scheme that determines the query probability

- **NI Sampling: Accelerating Discrete Diffusion Sampling by Token Order Optimization** _(event-driven trading)_
  [2026-04-20](https://arxiv.org/abs/2604.18471v1)
  Discrete diffusion language models (dLLMs) have recently emerged as a promising alternative to traditional autoregressive approaches, offering the flexibility to generate tokens in arbitrary orders and the potential of parallel decoding. However, existing heuristic sampling strategies remain inefficient: they choose only a small part of tokens to sample at each step, leaving substantial room for i

- **High-power attosecond X-ray free-electron lasers: physics and design strategy** _(event-driven trading)_
  [2026-04-20](https://arxiv.org/abs/2604.18447v1)
  Attosecond pulses from X-ray free-electron laser (XFEL) have opened new opportunities for probing ultrafast electronic dynamics on the Angstrom--attosecond spatiotemporal scale. Most attosecond XFEL concepts rely on generating an ultrashort high-current spike through either external laser modulation or accelerator-based beam manipulation. Despite their different implementations, these approaches s

- **Classical counterparts of shortcuts to adiabaticity in nonlinear dissipative Lagrangian systems** _(event-driven trading)_
  [2026-04-20](https://arxiv.org/abs/2604.18439v1)
  Shortcuts to adiabaticity (STA) were first developed in quantum dynamics to realize rapid transformations with suppressed residual excitations. Here we show how the same idea can be implemented in classical nonlinear dissipative Lagrangian systems. Using a coupled $r$-$θ$ manipulator as an illustrative model, we perform inverse engineering on the Euler-Lagrange equations with Rayleigh dissipation 

- **Before You Interpret the Profile: Validity Scaling for LLM Metacognitive Self-Report** _(sports betting arbitrage)_
  [2026-04-20](https://arxiv.org/abs/2604.17707v1)
  Clinical personality assessment screens response validity before interpreting substantive scales. LLM evaluation does not. We apply the validity scaling framework from the PAI and MMPI-3 to metacognitive probe data from 20 frontier models across 524 items. Six validity indices are operationalised: L (maintaining confidence on errors), K (betting on errors), F (withdrawing consensus-endorsed items)

- **Multi-Camera Self-Calibration in Sports Motion Capture: Leveraging Human and Stick Poses** _(sports betting arbitrage)_
  [2026-04-19](https://arxiv.org/abs/2604.17567v1)
  Multi-camera systems are widely employed in sports to capture the 3D motion of athletes and equipment, yet calibrating their extrinsic parameters remains costly and labor-intensive. We introduce an efficient, tool-free method for multi-camera extrinsic calibration tailored to sports involving stick-like implements (e.g., golf clubs, bats, hockey sticks). Our approach jointly exploits two complemen

- **Forecast Sports Outcomes under Efficient Market Hypothesis: Theoretical and Experimental Analysis of Odds-Only and Generalised Linear Models** _(sports betting arbitrage)_
  [2026-04-19](https://arxiv.org/abs/2604.17194v1)
  Converting betting odds into accurate outcome probabilities is a fundamental challenge in order to use betting odds as a benchmark for sports forecasting and market efficiency analysis. In this study, we propose two methods to overcome the limitations of existing conversion methods. Firstly, we propose an odds-only method to convert betting odds to probabilities without using historical data for m

- **If at First You Don't Succeed, Trispectrum: I. Estimating the Matter Power Spectrum Covariance with Higher-Order Statistics** _(Kelly criterion small bankroll)_
  [2026-04-20](https://arxiv.org/abs/2604.18581v1)
  We present a method to estimate non-Gaussian power spectrum covariance matrices by directly measuring the response of the small-scale power spectrum to long-wavelength perturbations via bispectrum and trispectrum estimators. Specifically, we derive estimators for the complete non-Gaussian matter power spectrum covariance, including the super-sample contribution, in terms of the squeezed bispectrum

- **Back into Plato's Cave: Examining Cross-modal Representational Convergence at Scale** _(Kelly criterion small bankroll)_
  [2026-04-20](https://arxiv.org/abs/2604.18572v1)
  The Platonic Representation Hypothesis suggests that neural networks trained on different modalities (e.g., text and images) align and eventually converge toward the same representation of reality. If true, this has significant implications for whether modality choice matters at all. We show that the experimental evidence for this hypothesis is fragile and depends critically on the evaluation regi

- **Detectability of minority communities in networks** _(Kelly criterion small bankroll)_
  [2026-04-20](https://arxiv.org/abs/2604.18565v1)
  Community structure is prevalent in real-world networks, with empirical studies revealing heterogeneous distributions where a few dominant majority communities coexist with many smaller groups. These small-scale groups, which we term minority communities, are critical for understanding network organization but pose significant challenges for detection. Here, we investigate the detectability of min

- **Sessa: Selective State Space Attention** _(tail risk harvesting)_
  [2026-04-20](https://arxiv.org/abs/2604.18580v1)
  Modern sequence models are dominated by Transformers, where self-attention mixes information from the visible context in an input-dependent way. However, when retrieval is not sharp and attention remains diffuse over an effective support $S_{\mathrm{eff}}(t)$, the influence of any individual token is diluted, typically scaling as $O(1/S_{\mathrm{eff}}(t))$ and reaching $O(1/\ell)$ for old tokens i

- **A multimodal and temporal foundation model for virtual patient representations at healthcare system scale** _(tail risk harvesting)_
  [2026-04-20](https://arxiv.org/abs/2604.18570v1)
  Modern medicine generates vast multimodal data across siloed systems, yet no existing model integrates the full breadth and temporal depth of the clinical record into a unified patient representation. We introduce Apollo, a multimodal temporal foundation model trained and evaluated on over three decades of longitudinal hospital records from a major US hospital system, composed of 25 billion record

- **Wasserstein Distributionally Robust Risk-Sensitive Estimation via Conditional Value-at-Risk** _(tail risk harvesting)_
  [2026-04-20](https://arxiv.org/abs/2604.18546v1)
  We propose a distributionally robust approach to risk-sensitive estimation of an unknown signal x from an observed signal y. The unknown signal and observation are modeled as random vectors whose joint probability distribution is unknown, but assumed to belong to a given type-2 Wasserstein ball of distributions, termed the ambiguity set. The performance of an estimator is measured according to the

## 3. GitHub Repos (Recently Updated)
- **[anglil/kalshi-ai-trading-bot](https://github.com/anglil/kalshi-ai-trading-bot)** ⭐ 0 · Python _(updated 2026-04-22)_
  AI-powered Kalshi prediction market trading bot using Gemini

- **[mehpackers13/kalshi-bot](https://github.com/mehpackers13/kalshi-bot)** ⭐ 0 · Python _(updated 2026-04-22)_
  Self-improving Kalshi prediction market trading bot

- **[haoo99/Polymarket-Kalshi-Arbitrage-Bot](https://github.com/haoo99/Polymarket-Kalshi-Arbitrage-Bot)** ⭐ 0 · TypeScript _(updated 2026-04-21)_
  🤖 Exploit price gaps between Polymarket and Kalshi 15-min BTC markets using real-time arbitrage trading to capture consistent profits.

- **[Razzleberryss/AstroTick](https://github.com/Razzleberryss/AstroTick)** ⭐ 10 · Python _(updated 2026-04-21)_
  🚀 Trade Bitcoin prediction markets on autopilot with this automated Kalshi trading bot in Python — targets BTC Up/Down 15-minute contracts using momentum signals, orderbook skew, stop-loss/take-profit

- **[lufegaga/kalshi-polymarket-arbitrage-trading-bot-python](https://github.com/lufegaga/kalshi-polymarket-arbitrage-trading-bot-python)** ⭐ 0 · None _(updated 2026-04-21)_
  📈 Automate arbitrage trading between Kalshi and Polymarket to exploit price differences effectively and enhance your trading strategy.

- **[elsantos305/predmarket](https://github.com/elsantos305/predmarket)** ⭐ 9 · Python _(updated 2026-04-21)_
  🔗 Unify prediction market APIs with `predmarket`, a Python library that simplifies access to Kalshi and Polymarket for seamless data integration.

- **[haoo99/Polymarket-Kalshi-Arbitrage-Bot](https://github.com/haoo99/Polymarket-Kalshi-Arbitrage-Bot)** ⭐ 0 · TypeScript _(updated 2026-04-21)_
  🤖 Exploit price gaps between Polymarket and Kalshi 15-min BTC markets using real-time arbitrage trading to capture consistent profits.

- **[Redmi175/polymarket-copy-bot](https://github.com/Redmi175/polymarket-copy-bot)** ⭐ 1 · TypeScript _(updated 2026-04-21)_
  🤖 Automate your Polymarket trading with a copy bot for replicating successful trades and monitoring market activity effectively.

- **[Thomas-quinn7/Polymarket_trader](https://github.com/Thomas-quinn7/Polymarket_trader)** ⭐ 0 · Python _(updated 2026-04-21)_
  A Python framework for building automated trading bots on Polymarket — pluggable strategies, paper trading, live execution, and real-time dashboard

- **[jmoss82/pm-arbitrage-bot](https://github.com/jmoss82/pm-arbitrage-bot)** ⭐ 0 · Python _(updated 2026-04-22)_
  Cross-platform arb bot for prediction markets

- **[kuestcom/prediction-market](https://github.com/kuestcom/prediction-market)** ⭐ 317 · TypeScript _(updated 2026-04-21)_
  Launch Your Own Web3 Decentralized Prediction Market in Minutes (Polymarket like)

- **[Duollc/PredictionMarket](https://github.com/Duollc/PredictionMarket)** ⭐ 0 · None _(updated 2026-04-21)_
  📊 Enhance prediction market security with a complete audit guide, featuring real incidents and a comprehensive checklist for risk management.

- **[LuizFelipeBarbosa/mention-analysis](https://github.com/LuizFelipeBarbosa/mention-analysis)** ⭐ 0 · Jupyter Notebook _(updated 2026-04-06)_
  Calibration analysis and trading strategy evaluation for Kalshi mention markets — binary prediction contracts that settle based on whether a specific topic, person, or phrase is mentioned during a sch

- **[Waike122333/Automated-Trading-Kalshi](https://github.com/Waike122333/Automated-Trading-Kalshi)** ⭐ 0 · None _(updated 2026-03-17)_
  An algorithmic trading bot for kalshi.com event contracts that automates trading strategies based on economic data, news events, weather patterns, and political markets in real-time.

- **[GitHubMaster07/Enterprise-Test-Strategy-Blueprint](https://github.com/GitHubMaster07/Enterprise-Test-Strategy-Blueprint)** ⭐ 0 · None _(updated 2026-01-17)_
  Enterprise‑grade QA Automation & Test Strategy Blueprint for UI, API, DB, Events, Contracts, CI/CD, and Non‑Functional Testing.

## 4. Perplexity Strategy Synthesis
Based on the available search results, I can provide limited information about prediction market trading strategies for 2026, though the results lack the specific tactical detail your query requests.

## Cross-Venue Arbitrage

**Price divergence between Kalshi and Polymarket creates systematic arbitrage opportunities** for traders who can navigate platform-specific constraints[2]. The research indicates that meaningful arbitrage opportunities exist but require sophisticated execution and risk management[2]. Sources of divergence—including regulatory differences, participant composition, and liquidity dynamics—enable identification of profitable cross-platform trades[2].

One source discusses comparing prices across Kalshi, Polymarket, FanDuel, Underdog, and DraftKings to spot mispriced odds and turn market signals into profit[1]. Additionally, **market movement exposes value before books adjust**, suggesting that monitoring price changes across platforms can reveal trading opportunities[1].

## Market Structure and Growth Context

Prediction markets reached $21 billion in monthly trading volume as of March 2026, driven by geopolitical events and a tripling user base[5]. On March 23, 2026, both Kalshi and Polymarket announced new measures to curb insider trading[5], which may affect strategy viability going forward.

## Limitations

The search results do not contain the specific information you requested about:
- Tail decay harvesting strategies
- Convergence play mechanics or parameters
- Concrete time horizons, price thresholds, or position sizing guidance
- Strategies tailored for small accounts ($50-500)
- Specific blog posts, Substacks, or Twitter threads with tactical details

To find actionable strategy guides with concrete parameters, you would need sources from specialized trading blogs, individual researcher Substacks, or recent Twitter/X discussions from prediction market traders.

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to kalshi_strategies.py only after manual validation._
---

*Archive: [conway-journal/research/kalshi](https://github.com/primetimeindy/conway-journal/tree/main/research/kalshi) · Published 2026-04-21 via Conway's auto-publisher.*
