<h1 align="center">toros-dev</h1>
<h3 align="center">Open-Source Infrastructure for Financial Data</h3>
<p align="center">
  <a href="https://github.com/toros-dev/toros"><img src="https://img.shields.io/badge/toros-in%20development-orange?style=flat" alt="toros"></a>
  <a href="https://pypi.org/project/edgar-sec/"><img src="https://img.shields.io/pypi/v/edgar-sec.svg?style=flat&label=edgar-sec" alt="edgar-sec on PyPI"></a>
  <a href="https://pepy.tech/projects/edgar-sec"><img src="https://static.pepy.tech/badge/edgar-sec" alt="edgar-sec downloads"></a>
</p>

---

**toros-dev** is a research-oriented engineering group building open-source infrastructure for financial data acquisition, representation, and analysis.

Financial disclosure data is public, structured in principle, and nearly unusable in practice. Comparable facts sit buried under inconsistent XBRL taxonomies, reporting regimes shift across filings and companies, and most research code that touches this data is written once per paper and thrown away. We build the alternative: installable, typed, tested, documented packages that turn heterogeneous disclosures into reliable, reproducible, model-ready structures — a stable representation layer to compute on rather than a pile of nested filing data.

The stack separates concerns by layer. **Acquisition** libraries handle retrieval, rate limiting, and parsing from primary sources; **representation** gives that data enforced semantics. The flagship, **toros**, represents complex financial objects as first-class typed structures on a clean, extensible dataframe interface (pandas, polars, dask), with cross-filing normalization, entity resolution, and time-series reconstruction built in. **edgar-sec** feeds it from SEC EDGAR, and the same pattern extends to additional sources.

### The stack

| Layer | Project | | Status |
|---|---|---|---|
| Acquisition | **[edgar-sec](https://github.com/toros-dev/edgar-sec)** | SEC EDGAR REST API client | [![PyPI](https://img.shields.io/pypi/v/edgar-sec.svg?label=)](https://pypi.org/project/edgar-sec/) [![Downloads](https://static.pepy.tech/badge/edgar-sec)](https://pepy.tech/projects/edgar-sec) |
| Representation | **[toros](https://github.com/toros-dev/toros)** | Self-validating financial DataFrames | ![In development](https://img.shields.io/badge/-in%20development-orange.svg) |

### How we build

**Correctness over convenience.** Full type annotations, `mypy`-clean, explicit key-existence checks, specific exception classes, no silent failure. If a response shape is wrong, the library says so rather than returning `None`.

**Sync and async as first-class peers.** Strict parity between clients — the async surface is never a second-class citizen with missing endpoints.

**Reproducibility as a deliverable.** OpenSSF Best Practices, Codecov coverage gates, conda-forge distribution alongside PyPI, and DOI-archived releases, so a paper can cite an exact version that will still resolve in ten years.

**Design before code.** Every package starts as a specification argument — what the public surface should be, what belongs in private internals, where the layer boundaries fall — before any implementation exists.

---

## Team

### Nikhil Sunder

<img src="https://raw.githubusercontent.com/toros-dev/.github/main/profile/assets/1771534042338.png" width="150" alt="Nikhil Sunder">

**Founder & Lead Developer** · Data Engineering, Design & Architecture

Undergraduate researcher at the University of Miami Herbert Business School, working on state-space models, spectral decomposition, and reinforcement learning for monetary policy. Sets the architecture for the stack and maintains its acquisition and modeling ends.

- BSBA Quantitative Economics, BSBA Finance (Minor in Mathematics) — University of Miami, Herbert Business School
- Research Fellow — Intelligent Computer Systems Research Institute (ICSRI), University of Miami
- Author of [`fedfred`](https://github.com/nikhilxsunder/fedfred) and [`cultivars`](https://github.com/nikhilxsunder/cultivars)
- ORCID: [0009-0007-3323-1760](https://orcid.org/0009-0007-3323-1760)

---

### John Bernardin

<img src="https://raw.githubusercontent.com/toros-dev/.github/main/profile/assets/1651668154585.jpeg" width="150" alt="John Bernardin">

**Developer & Researcher** · Machine Learning & Data Engineering

Generative AI Engineer at Air Products.

- MS Artificial Intelligence and Innovation — Carnegie Mellon University
- BS Applied Mathematics, BS Computer Science — Temple University
- Previously: Research Assistant, Human-Computer Interaction Lab @ Temple University · AI Engineer, PS Technology

---

### Rayhan Rahman

<img src="https://raw.githubusercontent.com/toros-dev/.github/main/profile/assets/1611510883839.jpeg" width="150" alt="Rayhan Rahman">

**Developer & Researcher** · API Design & Development

Software Engineer II at Vanguard.

- BS Computer Engineering (Minor in Economics) — Penn State Schreyer Honors College
- AWS Certified Cloud Practitioner

---

### Jake Schultz

**Developer & Maintainer** · Cyber Security, Documentation & Analytics

Undergraduate at Penn State with a background in defense financial management and network security.

- BS Cyber/Electronic Operations & Warfare — Penn State
- Financial Management Resource Analyst — Marine Corps University · Comptroller Chief — MCAS Iwakuni Comptroller's Office
- Cyber Security Specialist — 3rd Network Battalion, Det. Iwakuni

---

## From our developers

[![fedfred](https://github-readme-stats.vercel.app/api/pin/?username=nikhilxsunder&repo=fedfred)](https://github.com/nikhilxsunder/fedfred)

[![cultivars](https://github-readme-stats.vercel.app/api/pin/?username=nikhilxsunder&repo=cultivars)](https://github.com/nikhilxsunder/cultivars)

---

<p align="center">
  Open to research collaboration and contributions — start with an issue on <a href="https://github.com/toros-dev/toros">toros</a> or <a href="https://github.com/toros-dev/edgar-sec">edgar-sec</a>.
</p>
