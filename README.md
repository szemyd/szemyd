# Daniel Szemerey

I build data infrastructure for quantitative crypto research. Currently shipping two products:

**[Aperiodic](https://aperiodic.io)** — Professional market data aggregation for crypto. Microstructure, liquidity & order flow metrics — delivered as research-ready aggregates so you can run accurate backtests **100-1000x faster** than raw L2 approaches, without petabytes of storage or months of infrastructure work. TrueOHLCV, execution-aware pricing, tick/volume/dollar bars, slippage metrics, order book aggregates — full universe, no survivorship bias.

**[Unravel Alpha](https://unravel.finance)** — Cross-sectional alpha factors and multi-factor portfolios for systematic crypto traders. Point-in-time reconstruction, risk overlays, full transparency. We also manage external capital via separately managed accounts.

<p>
  <a href="https://aperiodic.io"><img src="https://img.shields.io/badge/Aperiodic_%E2%80%BA-000?style=for-the-badge" alt="Aperiodic" /></a>
  <a href="https://unravel.finance"><img src="https://img.shields.io/badge/Unravel_Alpha_%E2%80%BA-000?style=for-the-badge" alt="Unravel Alpha" /></a>
  <a href="https://www.linkedin.com/in/daniel-szemerey/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

### Aperiodic — Market Data for Realistic Backtesting

Professional-grade crypto market data aggregation. We handle the data plumbing so you don't have to.

**Core metrics:**

| Category | Metrics |
|----------|---------|
| **Foundation** | TrueOHLCV, OHLCV, Bid/Ask Spreads |
| **Execution & Slippage** | Execution-aware price series ($10k–$1M+), slippage metrics, liquidation data |
| **Research-Grade** | Tick bars (10–1000 ticks), volume bars, dollar bars, order book metrics, HF volatility |

**What makes it different:**

- **Not raw data** — validated, exchange-normalized aggregates ready for research
- **Exchange vs. local attribution** — TrueOHLCV based on actual tradeable prices
- **Execution-aware pricing** — average fill prices at realistic position sizes
- **Full universe coverage** — no survivorship bias across all exchanges
- **Enterprise-grade QA** — standardized validation, point-in-time accuracy, documented data lineage

<p>
  <a href="https://aperiodic.io/catalog"><img src="https://img.shields.io/badge/Explore_the_Catalog_%E2%80%BA-000?style=for-the-badge" alt="Aperiodic Catalog" /></a>
</p>

---

### Unravel Alpha — Factors & Portfolios

<p>
  <a href="https://unravel.finance/factors/40"><img src="https://img.shields.io/badge/Factor_Catalog_%E2%80%BA-000?style=for-the-badge" alt="Factor Catalog" /></a>&nbsp;
  <a href="https://unravel.finance/portfolios/40"><img src="https://img.shields.io/badge/Portfolio_Catalog_%E2%80%BA-000?style=for-the-badge" alt="Portfolio Catalog" /></a>&nbsp;
  <a href="https://unravel.finance/risk/spectra/40"><img src="https://img.shields.io/badge/Risk_Overlays_%E2%80%BA-000?style=for-the-badge" alt="Risk Overlays" /></a>&nbsp;
  <a href="https://unravel.finance/about"><img src="https://img.shields.io/badge/Team_%E2%80%BA-000?style=for-the-badge" alt="Team" /></a>
</p>

**Featured:**

> **[Spectra](https://unravel.finance/portfolio/spectra.40)** — Our flagship licensable multi-factor portfolio.
>
> **[Retail Flow](https://unravel.finance/portfolio/retail_flow.40)** — Cross-sectional factor that takes systematically contrarian positions against predictable retail herding behavior.

**Open source tools:**

**[`unravel-client`](https://github.com/unravel-finance/unravel-client)** — Python client for the Unravel API. Retrieve real-time and historical factors, build portfolios, run backtests.

**[`api-guide`](https://github.com/unravel-finance/api-guide)** — Jupyter notebooks to get started. Portfolio construction, risk overlay integration, factor exploration.

**[`crypto-predictive-risk-factors`](https://github.com/unravel-finance/crypto-predictive-risk-factors)** — Reference implementations for systematic crypto strategies using cross-sectional and alternative data.

---

### Research & Earlier Open Source

**[Accelerating Spatial Analysis with Neural Networks](https://github.com/szemyd/neuralnet-vga-analysis)** (MSc Thesis, UCL Bartlett) — Proved that a Multilayer Perceptron can estimate Visibility Graph Analysis values without expensive graph computation. The trained network generates spatial configurations from VGA inputs *and* calculates neighbourhood size and clustering coefficients substantially faster than traditional methods, with negligible error. The system is space-generic — trained once, applicable universally. The implication: spatial analysis becomes interactive and real-time, enabling optimization procedures like genetic algorithms during the design process.

**[`fold`](https://github.com/dream-faster/fold)** — Fast adaptive ML for time series. Composite models, online learning, temporal cross-validation. Built when I got tired of tools that assume stationarity.

**[`krisi`](https://github.com/dream-faster/krisi)** — Time series evaluation with PDF/web reporting. Metrics tracked over time, because a single RMSE tells you nothing about drift.

**[`modular-pipelines`](https://github.com/applied-exploration/modular-pipelines)** — Multi-model ensembles and meta-model orchestration.

**[`laplace-gnn-recommendation`](https://github.com/applied-exploration/laplace-gnn-recommendation)** — Self-supervised graph neural network framework for recommendation via edge prediction on knowledge graphs.

**[`deep-reinforcement-learning`](https://github.com/szemyd/deep-reinforcement-learning)** — DQN with prioritized experience replay, DDPG for continuous and multi-agent environments.

---

### Background

**Unravel Finance** (Co-Founder & CTO) — Two products: Aperiodic (market data aggregation at aperiodic.io) and Unravel Alpha (factor portfolios at unravel.finance). Python & Rust ingestion, TimescaleDB, Cloudflare Workers, React frontend. Serving data with sub-10s latency to systematic funds.

**Myalo** — Quantitative research infrastructure for adaptive time series forecasting. Open-sourced `fold` and `krisi` from this work.

**Health Venture Lab** (Co-Founder & CEO) — EU-wide healthcare accelerator powered by GE Healthcare, in partnership with EIT Health. Faculty at MIT Linq Catalyst Europe.

**UCL Bartlett** (MSc Architectural Computation) — Genetic algorithms, morphogenetic simulation, L-systems, neural network–accelerated visibility graph analysis. Where I learned to think about emergent systems — it turns out markets are one.

**Full-stack** — Shipped products end-to-end in React/TypeScript, Python, Rust, Node.js. From SaaS platforms to VS Code extensions to data pipelines.

---

Berlin · Previously London & Budapest · English, German, Hungarian · [Founders Pledge](https://founderspledge.com) member

*If you work in systematic trading, quantitative research, or crypto market microstructure — I'm always happy to talk. I follow back people who build interesting things.*
