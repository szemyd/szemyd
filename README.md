# Daniel Szemerey

I build real-time data infrastructure for quantitative crypto research at **[Unravel Finance](https://unravel.finance)**.

Two things we do: we license **cross-sectional alpha factors and multi-factor portfolios** to systematic traders — with point-in-time reconstruction, risk overlays, and full transparency. And we're now opening up the **data infrastructure layer** underneath: accurate aggregate market metrics from terabytes of reconstructed orderbook and alternative data, served via API with sub-10s latency. The data product is currently in closed beta — [request access here](https://docs.google.com/forms/d/e/1FAIpQLSe1x7ZT6UcMocHyllbjrc3yf7pADoh0py2vJNFwr9dQS91cag/viewform?usp=dialog).

We also manage external capital via separately managed accounts.

Before this, I spent years in ML research (adaptive time series models, graph neural networks, reinforcement learning), ran an EU-wide healthcare accelerator backed by GE Healthcare and MIT, and studied computational architecture — where I wrote genetic algorithms that evolved building forms and simulated morphogenetic systems. The through-line is an obsession with modeling complex systems and making them usable.

<p>
  <a href="https://unravel.finance"><img src="https://img.shields.io/badge/Unravel_Finance_%E2%80%BA-000?style=for-the-badge" alt="Unravel Finance" /></a>
  <a href="https://docs.google.com/forms/d/e/1FAIpQLSe1x7ZT6UcMocHyllbjrc3yf7pADoh0py2vJNFwr9dQS91cag/viewform?usp=dialog"><img src="https://img.shields.io/badge/Request_Data_Access_%E2%80%BA-000?style=for-the-badge" alt="Aggregate Data Access" /></a>
  <a href="https://www.linkedin.com/in/daniel-szemerey/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

### Unravel — Product & Open Source

<p>
  <a href="https://unravel.finance/factors/40"><img src="https://img.shields.io/badge/Factor_Catalog_%E2%80%BA-000?style=for-the-badge" alt="Factor Catalog" /></a>&nbsp;
  <a href="https://unravel.finance/portfolios/40"><img src="https://img.shields.io/badge/Portfolio_Catalog_%E2%80%BA-000?style=for-the-badge" alt="Portfolio Catalog" /></a>&nbsp;
  <a href="https://unravel.finance/risk/spectra/40"><img src="https://img.shields.io/badge/Risk_Overlays_%E2%80%BA-000?style=for-the-badge" alt="Risk Overlays" /></a>&nbsp;
  <a href="https://unravel.finance/about"><img src="https://img.shields.io/badge/Team_%E2%80%BA-000?style=for-the-badge" alt="Team" /></a>
</p>

<p>

</p>

**Featured:**

> **[Spectra](https://unravel.finance/portfolio/spectra.40)** — Our flagship licensable multi-factor portfolio.
>
> **[Retail Flow](https://unravel.finance/portfolio/retail_flow.40)** — Cross-sectional factor designed to measure and respond to retail investor activity. By analyzing individual executed trades sourced from exchanges, the strategy identifies assets heavily influenced by retail participation. It then takes systematically contrarian positions, seeking to exploit predictable patterns of overreaction and herding behavior.



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

**Unravel Finance** (Co-Founder & CTO) — Factor portfolios, cross-sectional signals, and risk overlays for institutional crypto. Python & Rust ingestion, TimescaleDB, Cloudflare Workers, React frontend. Serving data with sub-10s latency to systematic funds.

**Myalo** — Quantitative research infrastructure for adaptive time series forecasting. Open-sourced `fold` and `krisi` from this work.

**Health Venture Lab** (Co-Founder & CEO) — EU-wide healthcare accelerator powered by GE Healthcare, in partnership with EIT Health. Faculty at MIT Linq Catalyst Europe.

**UCL Bartlett** (MSc Architectural Computation) — Genetic algorithms, morphogenetic simulation, L-systems, neural network–accelerated visibility graph analysis. Where I learned to think about emergent systems — it turns out markets are one.

**Full-stack** — Shipped products end-to-end in React/TypeScript, Python, Rust, Node.js. From SaaS platforms to VS Code extensions to data pipelines.

---

Berlin · Previously London & Budapest · English, German, Hungarian · [Founders Pledge](https://founderspledge.com) member

*If you work in systematic trading, quantitative research, or crypto market microstructure — I'm always happy to talk. I follow back people who build interesting things.*
