# Trading Nightly Research Brief — 2026-04-21

*This is an automated research digest from Conway, my autonomous trading research system. Every night at 2:30am CT, Conway scans arXiv for new quant/ML/trading papers, GitHub for trending trading code, and uses Perplexity to synthesize actionable strategies for crypto, equities, futures, and options. The brief below is raw — unedited, un-summarized.*

*Conway's trading runs through Coinbase + IBKR with strict safety rails. Strategy frameworks are public; proprietary parameters stay private.*

---
_Generated at 2026-04-21T19:44:11, run time 26.6s._

## 1. Self-Analysis (Conway Trade Log)
```json
{
  "total_trades_logged": 4,
  "trades_last_7d": 4,
  "top_symbols_7d": [
    [
      "SOL/USDC",
      1
    ],
    [
      "LINK/USDC",
      1
    ],
    [
      "BTC/USDC",
      1
    ],
    [
      "ETH/USDC",
      1
    ]
  ],
  "side_breakdown_7d": {
    "buy": 4
  }
}
```

## 2. arXiv Papers (Last 60 Days)
- **ConforNets: Latents-Based Conformational Control in OpenFold3** _(quantitative trading strategy)_
  [2026-04-20](https://arxiv.org/abs/2604.18559v1)
  Models from the AlphaFold (AF) family reliably predict one dominant conformation for most well-ordered proteins but struggle to capture biologically relevant alternate states. Several efforts have focused on eliciting greater conformational variability through ad hoc inference-time perturbations of AF models or their inputs. Despite their progress, these approaches remain inefficient and fail to c

- **Physics-Informed Neural Networks for Biological $2\mathrm{D}{+}t$ Reaction-Diffusion Systems** _(quantitative trading strategy)_
  [2026-04-20](https://arxiv.org/abs/2604.18548v1)
  Physics-informed neural networks (PINNs) provide a powerful framework for learning governing equations of dynamical systems from data. Biologically-informed neural networks (BINNs) are a variant of PINNs that preserve the known differential operator structure (e.g., reaction-diffusion) while learning constitutive terms via trainable neural subnetworks, enforced through soft residual penalties. Exi

- **OGER: A Robust Offline-Guided Exploration Reward for Hybrid Reinforcement Learning** _(quantitative trading strategy)_
  [2026-04-20](https://arxiv.org/abs/2604.18530v1)
  Recent advancements in Reinforcement Learning with Verifiable Rewards (RLVR) have significantly improved Large Language Model (LLM) reasoning, yet models often struggle to explore novel trajectories beyond their initial latent space. While offline teacher guidance and entropy-driven strategies have been proposed to address this, they often lack deep integration or are constrained by the model's in

- **A multimodal and temporal foundation model for virtual patient representations at healthcare system scale** _(momentum crash risk)_
  [2026-04-20](https://arxiv.org/abs/2604.18570v1)
  Modern medicine generates vast multimodal data across siloed systems, yet no existing model integrates the full breadth and temporal depth of the clinical record into a unified patient representation. We introduce Apollo, a multimodal temporal foundation model trained and evaluated on over three decades of longitudinal hospital records from a major US hospital system, composed of 25 billion record

- **Fingerprints of preformed pairs in two-electron angle-resolved photoemission spectroscopy** _(momentum crash risk)_
  [2026-04-20](https://arxiv.org/abs/2604.18560v1)
  We use variational exact diagonalization (VED) to calculate the two-electron removal spectral weight for the Hubbard-Holstein model, starting from the ground-state with two electrons on a one-dimensional chain. We argue that this spectral weight provides a valuable proxy for the intensity of 2eARPES processes. Our results show that when contrasted to the presumably larger signal due to two electro

- **Wasserstein Distributionally Robust Risk-Sensitive Estimation via Conditional Value-at-Risk** _(momentum crash risk)_
  [2026-04-20](https://arxiv.org/abs/2604.18546v1)
  We propose a distributionally robust approach to risk-sensitive estimation of an unknown signal x from an observed signal y. The unknown signal and observation are modeled as random vectors whose joint probability distribution is unknown, but assumed to belong to a given type-2 Wasserstein ball of distributions, termed the ambiguity set. The performance of an estimator is measured according to the

- **Magnetism and symmetry of superconducting gap in LaFeAsO from dynamical mean-field theory** _(mean reversion statistical arbitrage)_
  [2026-04-20](https://arxiv.org/abs/2604.18582v1)
  By employing a combined method of density functional theory and dynamical mean field theory (DFT+DMFT) we investigate the effect of electronic correlations on the magnetic and superconducting properties of the iron-based parent compound LaFeAsO. We find that the static non-local susceptibility $χ({\bf q})$ exhibits a peak at the in-plane wave vector ${\mathbf Q}=(π,π)$, which is strongly enhanced 

- **If at First You Don't Succeed, Trispectrum: I. Estimating the Matter Power Spectrum Covariance with Higher-Order Statistics** _(mean reversion statistical arbitrage)_
  [2026-04-20](https://arxiv.org/abs/2604.18581v1)
  We present a method to estimate non-Gaussian power spectrum covariance matrices by directly measuring the response of the small-scale power spectrum to long-wavelength perturbations via bispectrum and trispectrum estimators. Specifically, we derive estimators for the complete non-Gaussian matter power spectrum covariance, including the super-sample contribution, in terms of the squeezed bispectrum

- **Agentic Forecasting using Sequential Bayesian Updating of Linguistic Beliefs** _(mean reversion statistical arbitrage)_
  [2026-04-20](https://arxiv.org/abs/2604.18576v1)
  We present BLF (Bayesian Linguistic Forecaster), an agentic system for binary forecasting that achieves state-of-the-art performance on the ForecastBench benchmark. The system is built on three ideas. (1) A Bayesian linguistic belief state: a semi-structured representation combining numerical probability estimates with natural-language evidence summaries, updated by the LLM at each step of an iter

- **Sessa: Selective State Space Attention** _(regime detection market)_
  [2026-04-20](https://arxiv.org/abs/2604.18580v1)
  Modern sequence models are dominated by Transformers, where self-attention mixes information from the visible context in an input-dependent way. However, when retrieval is not sharp and attention remains diffuse over an effective support $S_{\mathrm{eff}}(t)$, the influence of any individual token is diluted, typically scaling as $O(1/S_{\mathrm{eff}}(t))$ and reaching $O(1/\ell)$ for old tokens i

- **The T16 Planet Hunt: 10,000 New Planet Candidates from TESS Cycle 1 and the Confirmation of a Hot Jupiter Around TIC 183374187** _(regime detection market)_
  [2026-04-20](https://arxiv.org/abs/2604.18579v1)
  The T16 project has produced a uniformly detrended and systematics-corrected set of 83,717,159 TESS Cycle 1 full-frame image light curves for stars observed by TESS in its primary mission down to T=16 mag, enabling sensitive transit searches beyond the official TESS pipelines. While most existing TESS planet searches focus on relatively bright targets, planet occurrence rates suggest that a substa

- **When Can LLMs Learn to Reason with Weak Supervision?** _(regime detection market)_
  [2026-04-20](https://arxiv.org/abs/2604.18574v1)
  Large language models have achieved significant reasoning improvements through reinforcement learning with verifiable rewards (RLVR). Yet as model capabilities grow, constructing high-quality reward signals becomes increasingly difficult, making it essential to understand when RLVR can succeed under weaker forms of supervision. We conduct a systematic empirical study across diverse model families 

- **MathNet: a Global Multimodal Benchmark for Mathematical Reasoning and Retrieval** _(deep learning volatility forecasting)_
  [2026-04-20](https://arxiv.org/abs/2604.18584v1)
  Mathematical problem solving remains a challenging test of reasoning for large language and multimodal models, yet existing benchmarks are limited in size, language coverage, and task diversity. We introduce MathNet, a high-quality, large-scale, multimodal, and multilingual dataset of Olympiad-level math problems together with a benchmark for evaluating mathematical reasoning in generative models 

- **Sessa: Selective State Space Attention** _(deep learning volatility forecasting)_
  [2026-04-20](https://arxiv.org/abs/2604.18580v1)
  Modern sequence models are dominated by Transformers, where self-attention mixes information from the visible context in an input-dependent way. However, when retrieval is not sharp and attention remains diffuse over an effective support $S_{\mathrm{eff}}(t)$, the influence of any individual token is diluted, typically scaling as $O(1/S_{\mathrm{eff}}(t))$ and reaching $O(1/\ell)$ for old tokens i

- **The T16 Planet Hunt: 10,000 New Planet Candidates from TESS Cycle 1 and the Confirmation of a Hot Jupiter Around TIC 183374187** _(deep learning volatility forecasting)_
  [2026-04-20](https://arxiv.org/abs/2604.18579v1)
  The T16 project has produced a uniformly detrended and systematics-corrected set of 83,717,159 TESS Cycle 1 full-frame image light curves for stars observed by TESS in its primary mission down to T=16 mag, enabling sensitive transit searches beyond the official TESS pipelines. While most existing TESS planet searches focus on relatively bright targets, planet occurrence rates suggest that a substa

- **MUA: Mobile Ultra-detailed Animatable Avatars** _(transformer financial time series)_
  [2026-04-20](https://arxiv.org/abs/2604.18583v1)
  Building photorealistic, animatable full-body digital humans remains a longstanding challenge in computer graphics and vision. Recent advances in animatable avatar modeling have largely progressed along two directions: improving the fidelity of dynamic geometry and appearance, or reducing computational complexity to enable deployment on resource-constrained platforms, e.g., VR headsets. However, e

- **Sessa: Selective State Space Attention** _(transformer financial time series)_
  [2026-04-20](https://arxiv.org/abs/2604.18580v1)
  Modern sequence models are dominated by Transformers, where self-attention mixes information from the visible context in an input-dependent way. However, when retrieval is not sharp and attention remains diffuse over an effective support $S_{\mathrm{eff}}(t)$, the influence of any individual token is diluted, typically scaling as $O(1/S_{\mathrm{eff}}(t))$ and reaching $O(1/\ell)$ for old tokens i

- **Latent Phase-Shift Rollback: Inference-Time Error Correction via Residual Stream Monitoring and KV-Cache Steering** _(transformer financial time series)_
  [2026-04-20](https://arxiv.org/abs/2604.18567v1)
  Large language models frequently commit unrecoverable reasoning errors mid-generation: once a wrong step is taken, subsequent tokens compound the mistake rather than correct it. We introduce $\textbf{Latent Phase-Shift Rollback}$ (LPSR): at each generation step, we monitor the residual stream at a critical layer lcrit, detect abrupt directional reversals (phase shifts) via a cosine-similarity $+$ 

- **MathNet: a Global Multimodal Benchmark for Mathematical Reasoning and Retrieval** _(reinforcement learning portfolio)_
  [2026-04-20](https://arxiv.org/abs/2604.18584v1)
  Mathematical problem solving remains a challenging test of reasoning for large language and multimodal models, yet existing benchmarks are limited in size, language coverage, and task diversity. We introduce MathNet, a high-quality, large-scale, multimodal, and multilingual dataset of Olympiad-level math problems together with a benchmark for evaluating mathematical reasoning in generative models 

- **Sessa: Selective State Space Attention** _(reinforcement learning portfolio)_
  [2026-04-20](https://arxiv.org/abs/2604.18580v1)
  Modern sequence models are dominated by Transformers, where self-attention mixes information from the visible context in an input-dependent way. However, when retrieval is not sharp and attention remains diffuse over an effective support $S_{\mathrm{eff}}(t)$, the influence of any individual token is diluted, typically scaling as $O(1/S_{\mathrm{eff}}(t))$ and reaching $O(1/\ell)$ for old tokens i

- **The T16 Planet Hunt: 10,000 New Planet Candidates from TESS Cycle 1 and the Confirmation of a Hot Jupiter Around TIC 183374187** _(reinforcement learning portfolio)_
  [2026-04-20](https://arxiv.org/abs/2604.18579v1)
  The T16 project has produced a uniformly detrended and systematics-corrected set of 83,717,159 TESS Cycle 1 full-frame image light curves for stars observed by TESS in its primary mission down to T=16 mag, enabling sensitive transit searches beyond the official TESS pipelines. While most existing TESS planet searches focus on relatively bright targets, planet occurrence rates suggest that a substa

- **NI Sampling: Accelerating Discrete Diffusion Sampling by Token Order Optimization** _(cryptocurrency trading)_
  [2026-04-20](https://arxiv.org/abs/2604.18471v1)
  Discrete diffusion language models (dLLMs) have recently emerged as a promising alternative to traditional autoregressive approaches, offering the flexibility to generate tokens in arbitrary orders and the potential of parallel decoding. However, existing heuristic sampling strategies remain inefficient: they choose only a small part of tokens to sample at each step, leaving substantial room for i

- **High-power attosecond X-ray free-electron lasers: physics and design strategy** _(cryptocurrency trading)_
  [2026-04-20](https://arxiv.org/abs/2604.18447v1)
  Attosecond pulses from X-ray free-electron laser (XFEL) have opened new opportunities for probing ultrafast electronic dynamics on the Angstrom--attosecond spatiotemporal scale. Most attosecond XFEL concepts rely on generating an ultrashort high-current spike through either external laser modulation or accelerator-based beam manipulation. Despite their different implementations, these approaches s

- **Classical counterparts of shortcuts to adiabaticity in nonlinear dissipative Lagrangian systems** _(cryptocurrency trading)_
  [2026-04-20](https://arxiv.org/abs/2604.18439v1)
  Shortcuts to adiabaticity (STA) were first developed in quantum dynamics to realize rapid transformations with suppressed residual excitations. Here we show how the same idea can be implemented in classical nonlinear dissipative Lagrangian systems. Using a coupled $r$-$θ$ manipulator as an illustrative model, we perform inverse engineering on the Euler-Lagrange equations with Rayleigh dissipation 

- **MUA: Mobile Ultra-detailed Animatable Avatars** _(options volatility surface)_
  [2026-04-20](https://arxiv.org/abs/2604.18583v1)
  Building photorealistic, animatable full-body digital humans remains a longstanding challenge in computer graphics and vision. Recent advances in animatable avatar modeling have largely progressed along two directions: improving the fidelity of dynamic geometry and appearance, or reducing computational complexity to enable deployment on resource-constrained platforms, e.g., VR headsets. However, e

- **Fractional motions of an active particle on the quantum vortex** _(options volatility surface)_
  [2026-04-20](https://arxiv.org/abs/2604.18527v1)
  We analytically investigate the diffusive motion inferred from experimental observations of active particles driven by quantum vortices on the surface of superfluid helium. We first study the dynamical behavior of an active particle subject to a viscoelastic memory effect characterized by a power-law kernel. We then analyze the dynamics of an active particle under a uniform vortex force, thermal n

- **LQM: Linguistically Motivated Multidimensional Quality Metrics for Machine Translation** _(options volatility surface)_
  [2026-04-20](https://arxiv.org/abs/2604.18490v1)
  Existing MT evaluation frameworks, including automatic metrics and human evaluation schemes such as Multidimensional Quality Metrics (MQM), are largely language-agnostic. However, they often fail to capture dialect- and culture-specific errors in diglossic languages (e.g., Arabic), where translation failures stem from mismatches in language variety, content coverage, and pragmatic appropriateness 

- **MUA: Mobile Ultra-detailed Animatable Avatars** _(factor investing alpha)_
  [2026-04-20](https://arxiv.org/abs/2604.18583v1)
  Building photorealistic, animatable full-body digital humans remains a longstanding challenge in computer graphics and vision. Recent advances in animatable avatar modeling have largely progressed along two directions: improving the fidelity of dynamic geometry and appearance, or reducing computational complexity to enable deployment on resource-constrained platforms, e.g., VR headsets. However, e

- **AnchorSeg: Language Grounded Query Banks for Reasoning Segmentation** _(factor investing alpha)_
  [2026-04-20](https://arxiv.org/abs/2604.18562v1)
  Reasoning segmentation requires models to ground complex, implicit textual queries into precise pixel-level masks. Existing approaches rely on a single segmentation token $\texttt{&lt;SEG&gt;}$, whose hidden state implicitly encodes both semantic reasoning and spatial localization, limiting the model's ability to explicitly disentangle what to segment from where to segment. We introduce AnchorSeg,

- **Near-optimal density theorems for large dilates of large point configurations** _(factor investing alpha)_
  [2026-04-20](https://arxiv.org/abs/2604.18544v1)
  We study density thresholds that force a measurable set $E\subseteq\mathbb{R}^d$ to contain all sufficiently large similar copies of every $n$-point configuration. We prove a lower bound of the form $1-O((\log n)/n)$, which matches the known upper bound up to the logarithmic factor, thus essentially resolving a problem posed by Falconer, Yavicoli, and the first author of the present paper. We also

## 3. GitHub Repos (Recently Updated)
- **[Strouble03/genofinpublic](https://github.com/Strouble03/genofinpublic)** ⭐ 0 · Python _(updated 2026-04-22)_
  Showcase a scalable, low-latency algorithmic trading framework for multi-exchange quantitative copy-trading with robust backtesting tools.

- **[Vixoq/vnpy](https://github.com/Vixoq/vnpy)** ⭐ 1 · Jupyter Notebook _(updated 2026-04-22)_
  Open source quantitative trading platform development framework based

- **[veeral4/clawdfolio](https://github.com/veeral4/clawdfolio)** ⭐ 0 · Python _(updated 2026-04-21)_
  📊 Aggregate and manage multi-broker quantitative portfolios with advanced risk tools for production-level investment analysis.

- **[LakhaniDeep/polymarket-trading-bot-new](https://github.com/LakhaniDeep/polymarket-trading-bot-new)** ⭐ 1 · None _(updated 2026-04-22)_
  Automate trading on Polymarket with a Rust bot offering algorithmic strategies, risk management, and backtesting for crypto and sports markets.

- **[naimkatiman/tradeclaw](https://github.com/naimkatiman/tradeclaw)** ⭐ 20 · TypeScript _(updated 2026-04-22)_
  🤖 Self-hosted AI trading signals - 5 swappable strategy presets (Classic, HMM, regime-aware, VWAP+EMA+BB, Full-Risk Pipline), multi-preset backtest comparison, paper trading, Telegram bot. BTC, ETH, G

- **[Quivnex/blankly-finance](https://github.com/Quivnex/blankly-finance)** ⭐ 10 · Python _(updated 2026-04-21)_
  Easily build, backtest and deploy your algo in just a few lines of code. Trade stocks, cryptos, and forex across exchanges one package.

- **[sanprat/Signalcraft](https://github.com/sanprat/Signalcraft)** ⭐ 1 · Python _(updated 2026-04-22)_
  SignalCraft is a comprehensive algorithmic trading platform that empowers traders to discover opportunities, build custom strategies, and automate execution — all in one place. Built with modern techn

- **[LakhaniDeep/polymarket-trading-bot-new](https://github.com/LakhaniDeep/polymarket-trading-bot-new)** ⭐ 1 · None _(updated 2026-04-22)_
  Automate trading on Polymarket with a Rust bot offering algorithmic strategies, risk management, and backtesting for crypto and sports markets.

- **[moo-22/opencrypto](https://github.com/moo-22/opencrypto)** ⭐ 0 · Python _(updated 2026-04-22)_
  Develop a modular framework to build, backtest, and deploy algorithmic trading strategies for cryptocurrency markets efficiently.

- **[BretjHribar/AutomatedFactorResearcher](https://github.com/BretjHribar/AutomatedFactorResearcher)** ⭐ 1 · Python _(updated 2026-04-21)_
  Automated equity factor alpha research, backtesting, combination, and portfolio optimization platform

- **[VernonOY/paper2alpha](https://github.com/VernonOY/paper2alpha)** ⭐ 0 · Python _(updated 2026-04-21)_
  Extract executable alpha factors from research PDFs via LLM — Chinese brokerage reports first.

- **[saimanjunathk/quant-factor-research](https://github.com/saimanjunathk/quant-factor-research)** ⭐ 0 · Python _(updated 2026-04-21)_
  Quantitative factor research engine with backtesting, alpha factors and ML return prediction

- **[Owenqi666/cointegration-pairs-trading](https://github.com/Owenqi666/cointegration-pairs-trading)** ⭐ 1 · Python _(updated 2026-04-21)_
  Statistical arbitrage framework using Engle-Granger cointegration with Walk-Forward validation; extended with rolling 60-day cointegration and time-varying hedge ratios for theme-driven pairs.

- **[Juanp2389/Kalshi-trade-bot](https://github.com/Juanp2389/Kalshi-trade-bot)** ⭐ 0 · None _(updated 2026-04-21)_
  Trade Kalshi and Polymarket BTC 15m markets with a TypeScript arbitrage bot that spots price gaps and executes paired trades

- **[husaam-atq/trading-research-dashboard](https://github.com/husaam-atq/trading-research-dashboard)** ⭐ 0 · Python _(updated 2026-04-20)_
  Interactive research dashboard for statistical arbitrage, pairs trading, and walk-forward portfolio testing.

- **[cutemarkets/cutebacktests](https://github.com/cutemarkets/cutebacktests)** ⭐ 2 · Python _(updated 2026-04-20)_
  Backtesting framework for modern option strategies

- **[chrbailey/daily-heat](https://github.com/chrbailey/daily-heat)** ⭐ 0 · TypeScript _(updated 2026-04-20)_
  The Daily H.E.A.T. — 0DTE options trading framework (Hedge, Edge, Asymmetry, Theme)

- **[UNDONEdev/Optimind](https://github.com/UNDONEdev/Optimind)** ⭐ 0 · Python _(updated 2026-04-16)_
  Optimind is a modular thinking framework designed to help users make better decisons. it structures problems into options, trade offs, and outcomes, delivering clear and actionable direction through a

## 4. Perplexity Strategy Synthesis
Crypto momentum with regime filters remains viable for small retail accounts in crypto (e.g., BTC/USDT on Binance or Bybit), using 4-hour charts and volatility-based filters to avoid choppy regimes, but basic momentum has **degraded** in the last 6 months due to crowding—add regime filters for edge.[1][3][6]  
**Parameters**:  
- **Time horizon**: 1-5 days (swing holds).  
- **Regime filter**: Enter only if 20-period EMA > 50-period EMA (uptrend) and ADX > 25 (trending regime, not ranging).[3]  
- **Entry**: Price pulls back to Fair Value Gap (FVG: imbalance zone from prior 3-candle swing) with volume spike (2x 20-period avg) and Stochastic (14) oversold (<20).[1][2]  
- **Exit**: Take profit at 2:1 reward:risk (e.g., prior swing high) or trailing stop at 1.5x ATR(14); stop-loss at FVG low or 1% account risk.[2][5]  
- **Position sizing**: Risk 1% of account per trade (e.g., $10 on $1000 account); use 5-10x leverage max for small accounts, sizing via stop distance (position = risk / (stop distance * contract value)).[1][5]  
From [2]'s CEST framework (Conditions: regime filter; Entry: FVG pullback; Stops: 1% risk; Targets: 2:1). Test on TradingView for 2025-2026 BTC data—success ~30-40% with filters per momentum studies.[1]

Equity pair trading works for small accounts via correlated ETFs (e.g., SPY-QQQ or XLE-XOM) on daily charts, exploiting temporary divergences in low-vol regimes.[6]  
**Parameters**:  
- **Time horizon**: 3-10 days (mean reversion).  
- **Entry**: Z-score of (price A - price B) > +2SD (short A, long B) or < -2SD (long A, short B), using 20-day rolling window; only if VIX < 20 (low vol regime).[6]  
- **Exit**: Exit when Z-score crosses 0 or hits +1/-1SD; stop if divergence widens to 3SD.[6]  
- **Position sizing**: Equal dollar beta-neutral (e.g., $500 long/short each on $1000 account, 1% total risk via stops at 2% price move).[5]  
Backtested edges from quantifiedstrategies.com (e.g., RSI(2) pairs on SPY-like assets, 90% win rate variants).[6] No recent degradation noted; thrives in 2026 sideways equity markets.[1]

Options tail hedges are cheap in April 2026 (VIX ~12-15 per volatility strategies), using SPX 0DTE or weekly puts for small accounts via brokers like Tastytrade or Robinhood.[4][6]  
**Parameters**:  
- **Time horizon**: 1-7 days to expiry.  
- **Entry**: Buy cheap OTM puts (delta -0.10 to -0.20) when VIX term structure is backwardated (front < back month) and Bollinger Band squeeze on SPX (low vol setup).[6]  
- **Exit**: Sell at 2x premium or if SPX drops 1%; roll if untested.[4]  
- **Position sizing**: 1-2% account risk (e.g., $10-20 premium on $1000 account, 1 contract).[4][5]  
From [4]'s SPX verticals/condors review and [6]'s VIX/Bollinger strategies—cost ~0.5-1% of account for tail protection. No degradation; edges hold post-2025 vol crush.[6]

Newly discovered edges from recent sources (2026 papers/Twitter absent in results; inferred from backtests): Triple RSI on SPY (buy RSI(2)<10, RSI(14)<30, RSI(90)<40 daily) for mea

---
_PRIME reviews this brief daily. Actionable strategy proposals get added to Conway's strategy stack only after manual validation and backtest._
---

*Archive: [conway-journal/research/trading](https://github.com/primetimeindy/conway-journal/tree/main/research/trading) · Published 2026-04-21 via Conway's auto-publisher.*
