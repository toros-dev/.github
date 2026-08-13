# toros-dev

---

## Overview

**toros-dev** is a research-oriented engineering group focused on building high-quality, open-source infrastructure for financial data acquisition, transformation, and analysis.

The organization's primary objective is to develop **reliable, reproducible, and model-ready data systems** that turn heterogeneous financial disclosures into consistent, analyzable structures — covering structured data extraction, XBRL parsing, and the reconstruction of financial time series across filings, companies, and reporting regimes.

The flagship project, **toros**, is a modular Python toolkit that represents complex financial objects as first-class typed structures on top of a clean, extensible dataframe interface. It abstracts the complexity of XBRL and related disclosure formats, giving researchers, developers, and quantitative analysts a stable representation layer to compute on rather than a pile of nested filing data. The system emphasizes:

* Deterministic data pipelines and reproducibility
* Robust API and SDK design
* Cross-filing normalization and entity resolution
* Time-series reconstruction from financial disclosures
* Integration with modern data workflows (pandas, polars, dask)

Surrounding toros is a set of source-specific acquisition libraries, beginning with **edgar-sec**, a client for the U.S. Securities and Exchange Commission (SEC) EDGAR API. edgar-sec handles retrieval, rate limiting, and parsing of SEC filings; toros handles what those filings become. Together they form an end-to-end path from raw ingestion to model-ready datasets, with the same pattern extensible to additional data sources.

The broader development philosophy aligns with **research-grade software engineering**, combining principles from econometrics, machine learning, and systems design to produce tools suitable for both academic research and production-grade analytics.

---

## Projects

[![edgar-sec](https://github-readme-stats.vercel.app/api/pin/?username=toros-dev&repo=edgar-sec)](https://github.com/toros-dev/edgar-sec)

[![toros](https://github-readme-stats.vercel.app/api/pin/?username=toros-dev&repo=toros)](https://github.com/toros-dev/toros)

---

## Developers

### Nikhil Sunder
<img src="https://github.com/toros-dev/.github/blob/338420e9fb1ba91ca0b431b39dbdd300e82bdc23/profile/assets/1771534042338.png" width="150" alt="Profile Photo">\
**Undergraduate Researcher @ The University of Miami, Herbert Business School**

- **Role:**  
  Founder & Lead Developer

- **Focus:**
  Data Engineering, Design & Architecture

- **Education & Experience:**  
  - BSBA Quantitative Economics, BSBA Finance (Minor in Mathematics) — University of Miami Herbert Business School  
  - Research Fellow — Intelligent Computer Systems Research Institute (ICSRI) @ University of Miami Herbert Business School

- **Featured Work:**  
  - [`fedfred`](https://github.com/nikhilxsunder/fedfred) — A feature-rich python package for interacting with the Federal Reserve Bank of St. Louis Economic Database: FRED.
  - [`cultivars`](https://github.com/nikhilxsunder/fedfred) - A modern computing library in python for providing vector autoregressions and other autoregressive economic models.

- **Research:**  
  - ORCID: https://orcid.org/0009-0007-3323-1760

---

### John Bernardin
<img src="https://github.com/toros-dev/.github/blob/338420e9fb1ba91ca0b431b39dbdd300e82bdc23/profile/assets/1651668154585.jpeg" width="150" alt="Profile Photo">\
**Generative AI Engineer @ Air Products**

- **Role:**  
  Developer & Researcher

- **Focus:**  
  Machine learning & Data Engineering

- **Education & Experience:**   
  - MS Artificial Intelligence and Innovation - Carnegie Mellon University
  - BS Applied Mathematics, BS Computer Science - Temple University
  - Research Assistant - Human-Computer Interaction Lab (HCI) @ Temple University
  - Generative AI Engineer - Air Products
  - AI Engineer - PS Technology

---

### Rayhan Rahman
<img src="https://github.com/toros-dev/.github/blob/338420e9fb1ba91ca0b431b39dbdd300e82bdc23/profile/assets/1611510883839.jpeg" width="150" alt="Profile Photo">\
**Software Engineer II @ Vanguard**

- **Role:**  
  Developer & Researcher

- **Focus:**  
  API Design & Development

- **Education & Experience:**  
  - BS Computer Engineering (Minor in Economics) - Penn State Schreyer Honors College
  - AWS Certified Cloud Practicioner - Amazon Web Services

---

### Jake Schultz
**Undergraduate Student @ Penn State**

- **Role:**  
  Developer & Maintainer

- **Focus:**  
  Cyber Security, Documentation & Analytics

- **Education & Experience:**
  - BS Cyber/Electronic Operations & Warfare - Penn State
  - Financial Management Resource Analyst - Marine Corps University
  - Comptroller Chief - MCAS Iwakuni Comptroller's Officer
  - Cyber Security Specialist - 3rd Network Batallion Det. Iwakuni
 
---

### Other work from our developers

[![fedfred](https://github-readme-stats.vercel.app/api/pin/?username=nikhilxsunder&repo=fedfred)](https://github.com/nikhilxsunder/fedfred)
