<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,100:7aa2f7&height=180&section=header&text=Charu%20Malik&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%C2%B7%20AI%20Systems%20%C2%B7%20Data%20Science&descAlignY=58&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=7AA2F7&center=true&vCenter=true&width=600&lines=Building+reliable+backend+systems...;Shipping+AI+infrastructure+and+LLM+pipelines...;Turning+data+into+decisions..." alt="Typing SVG"/>

[![Email](https://img.shields.io/badge/Email-charu.malik2210%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:charu.malik2210@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-charu--malik-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/charu-malik-56636733a)
[![GitHub](https://img.shields.io/badge/GitHub-charu2210-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/charu2210)
![Profile Views](https://komarev.com/ghpvc/?username=charu2210&color=7AA2F7&style=flat-square&label=Profile+Views)

</div>

---

## 🎯 About

B.Tech Computer Science & Engineering (Data Science), Manipal University Jaipur — CGPA 8.99/10, expected 2028.

I enjoy building software where reliable AI systems, intelligent applications, and data-driven decision making intersect.

---

## 🧰 Technical Skills

| Category | Skills |
|---|---|
| **Languages** | Python, Java, C, SQL (Window Functions, CTEs, Joins) |
| **AI / ML** | Scikit-learn, Multi-Agent LLM Orchestration, Claude API, Prompt Engineering, Anomaly Detection |
| **Data** | Pandas, NumPy, Matplotlib, Seaborn, Feature Engineering, Statistical Inference |
| **Tools** | Git, Linux/Bash, Docker, Postman, Wireshark |

<div align="center">

<img src="https://skillicons.dev/icons?i=python,java,c,scikitlearn,git,docker,linux,postman&theme=dark" />

</div>

---

## 💼 Experience

**AI & Data Science Intern — XYlofy AI** *(June 2026 – July 2026, Remote)*
- Built an end-to-end ETL pipeline in Python to ingest, transform, validate, and integrate multi-year retail datasets for downstream analytics.
- Automated reusable data-processing workflows using Pandas and NumPy, reducing manual preprocessing effort across experiments.
- Built modular data-transformation and anomaly-detection components consumed by an interactive analytics platform.
- Evaluated pipeline output quality using MAE, RMSE, and MAPE to improve data accuracy and support operational decision-making.
- Maintained pipeline code using Git-based version control and collaborative pull-request workflows.

---

## 🚀 Featured Projects

### `R-UDP` — Reliable Transport Protocol over UDP
**Backend / Systems** · Java, Socket Programming, Concurrent Systems, CRC32, ARQ
- Custom Layer-4 protocol over UDP with a 12-byte application header (sequence numbers, CRC32 checksum, payload length, Big-Endian).
- Selective Repeat ARQ using a thread-safe `ConcurrentHashMap` for the in-flight packet window — 90% goodput under 20% simulated packet loss, outperforming Go-Back-N.
- Configurable network emulation proxy for stress-testing packet drop, duplication, and reordering.

[→ Repository](https://github.com/charu2210/R-UDP-Project)

### `Telemetry Ingestion Service` — High-Throughput Backend
**Backend / SDE** · Java, Spring Boot, Multithreading, SQL
- High-throughput batch ingestion backend processing thousands of manufacturing telemetry events/minute under concurrent load, using atomic `compute()` for lock-free upserts.
- 4-state idempotent upsert logic (`NEW` / `DEDUPED` / `UPDATED` / `IGNORED`) with ingress timestamps to prevent clock-skew data corruption.
- Schema validation and boundary-check layers to intercept malformed packets before persistence.

[→ Repository](https://github.com/charu2210/telemetry-ingestion-backend)

### `Phantom Plan` — Multi-Agent LLM Backend
**AI / Backend** · Python, FastAPI, AsyncIO, Claude API
- 6-agent stateful LLM inference pipeline with a shared `PipelineState` dataclass and per-agent fallback recovery — zero HTTP 500s under simulated full agent outage.
- Behavioral Monte Carlo risk simulation (500 runs) stress-testing financial plans against user-specific spending variables.
- Pydantic-enforced JSON schema contracts across every agent boundary, eliminating downstream parsing failures.

[→ Repository](https://github.com/charu2210/phantom)

### `OpenCase` — AI Investigation Platform
**AI / Full-Stack** · Next.js, TypeScript, FastAPI, Gemini API
- Research-adjacent project exploring how LLMs reason over evidence: four investigation personas, an evidence board, theory comparison, and step-by-step reasoning traces.
- FastAPI backend serving prompt-engineered investigation modes to a Next.js/TypeScript frontend.

[→ Repository](https://github.com/charu2210/opencase)

### `FlowState` — Anomaly Detection on Behavioral Data
**AI / Data** · Python, Scikit-learn, Statistical Feature Engineering
- 7-dimensional feature space (Shannon Entropy, Hjorth Mobility, CoV, Skewness, Kurtosis) from keystroke timing data.
- Benchmarked Isolation Forest, LOF, and OC-SVM — LOF achieved ROC-AUC 0.8512, F1 0.7143.
- Leave-One-User-Out validation across 10 users (cross-user mean AUC 0.8031); privacy-by-design — discards key identity at the hardware level.

[→ Repository](https://github.com/charu2210/FlowState)

### `Demand Intelligence Engine` — Sales Forecasting & Business Analytics System
**Data Science / Full-Stack** · Python, Streamlit, SARIMA, Prophet, XGBoost, Scikit-learn
- End-to-end retail demand forecasting system on 4 years of transaction data: benchmarked SARIMA, Prophet, and XGBoost head-to-head, with SARIMA winning at 20.5% MAPE.
- Dual-method anomaly detection (Isolation Forest + Z-score) across 209 weeks of sales, plus KMeans/PCA-based product segmentation into four demand tiers, each mapped to a distinct inventory strategy.
- Shipped as a live, interactive 4-page Streamlit dashboard (Sales Overview, Forecast Explorer, Anomaly Report, Product Segments) — not just a notebook, an actual decision-support tool.

[→ Live Demo](https://salesforecasting-9sfccbfx2bdpah4h3fezql.streamlit.app/) · [→ Repository](https://github.com/charu2210/SalesForecasting)

### `House Price Prediction` — Regression Modeling
**Data Analyst** · Python, Scikit-learn, Pandas
- End-to-end regression workflow on residential property data: cleaning, EDA, one-hot encoding, 80/20 split.
- Compared Linear Regression and Random Forest; best model (Linear Regression) reached R² 0.653 (MAE ≈ 970K, RMSE ≈ 1.32M).
- Feature importance analysis (area, bathrooms, A/C, parking) translated into pricing recommendations.

[→ Repository](https://github.com/charu2210/house-price-prediction)

### `Employee Attrition Prediction` — Classification & HR Analytics
**Data Analyst** · Python, Scikit-learn, Pandas
- Predicted attrition on the IBM HR Analytics dataset (1,470 rows) using Logistic Regression, Random Forest, and Gradient Boosting.
- Best model (Gradient Boosting) reached ROC-AUC 0.805.
- Surfaced key drivers (monthly income, overtime, stock options, job involvement) as HR-facing recommendations.

[→ Repository](https://github.com/charu2210/employee-attrition-prediction)

---

## 🌱 Open Source — GirlScript Summer of Code 2026

Active contributor, currently ranked **#409 globally out of 43,587 participants (top 1%)**.

| Metric | Value |
|---|---|
| PRs Merged | 13 (across 13 projects) |
| Contribution Points | 1,033 (PRs) + 650 (bounty tasks) |
| Badges Earned | 12, including Elite, Power Contributor, Rising Star |
| Focus Areas | Bug fixes — security (XSS prevention), concurrency, data handling, UX |

Sample merged PRs: fixed an XSS vulnerability in skill-badge rendering, prevented concurrent-request race conditions in an AI dev assistant, and fixed EXIF orientation handling for uploaded images — contributing production-quality fixes across security, concurrency, image processing, and data correctness.

[→ GSSoC Profile](https://gssoc.girlscript.org/profile/5deeb7c6-21ca-4415-ae1d-da355c6db586)

---

## 🏆 Achievements & Leadership

- **Hackathon Finalist:** Offline National Finalist, IIT Bombay Upskill India Hackathon · Finalist, India Innovates 2026 (presented at Bharat Mandapam, New Delhi) · Round 2 Qualifier, EY Techathon
- **Global Delegate:** Selected Delegate, HPAIR 2026 (Harvard Project for Asian & International Relations)
- **Certifications:** NPTEL Programming in Java — Elite Gold (Top 90th percentile)
- **Leadership:** Joint Head of Corporate Affairs, IEEE Computer Society MUJ — secured 5+ industry sponsorships for Genesis 5.0 (20,000+ attendees)

---

## 📊 GitHub Stats

> Consistently building backend systems, AI infrastructure, and open-source software.

<div align="center">

![GitHub Stats](https://github-readme-stats-one-bice.vercel.app/api?username=charu2210&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats-one-bice.vercel.app/api/top-langs/?username=charu2210&layout=compact&theme=tokyonight&hide_border=true)
</div>


<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=charu2210&theme=tokyo-night&hide_border=true"/>
</p>


<!--
Optional next step — a contribution snake animation (purely cosmetic, signals an actively maintained profile):
1. In this repo (charu2210/charu2210), add .github/workflows/snake.yml using the platane/snk GitHub Action.
2. Once the workflow runs once, uncomment and add this line here:
<img src="https://raw.githubusercontent.com/charu2210/charu2210/output/github-contribution-grid-snake.svg" width="100%" />
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,100:1a1b27&height=100&section=footer" width="100%"/>

</div>

---

<div align="center">

*"I enjoy building systems that remain reliable long after the happy path disappears."*

**charu.malik2210@gmail.com** · [LinkedIn](https://linkedin.com/in/charu-malik-56636733a) · [GitHub](https://github.com/charu2210)

</div>
