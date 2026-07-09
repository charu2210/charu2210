<div align="center">

# Charu Malik

### Backend & AI Systems Engineer · Data Science Undergrad

Building reliable backend systems, AI pipelines, and data-driven products — from raw sockets to LLM orchestration to predictive models.

[![Email](https://img.shields.io/badge/Email-charu.malik2210%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:charu.malik2210@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-charu--malik-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/charu-malik-56636733a)
[![GitHub](https://img.shields.io/badge/GitHub-charu2210-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/charu2210)

</div>

---

## About

B.Tech Computer Science & Engineering (Data Science), Manipal University Jaipur — CGPA 8.99/10, expected 2028.

I work across three overlapping areas and I'm open to roles in any of them:

- **Backend / SDE** — concurrent systems, custom network protocols, REST APIs, thread-safe data structures
- **AI / ML Engineering** — multi-agent LLM pipelines, structured output enforcement, anomaly detection
- **Data Analytics** — EDA, predictive modeling, feature engineering, business-facing reporting

Currently a **Data Science Intern at XYlofy AI**, building forecasting and classification pipelines end-to-end.

---

## Technical Skills

| Category | Skills |
|---|---|
| **Languages** | Python, Java, C++, SQL (Window Functions, CTEs, Joins) |
| **Backend** | FastAPI, AsyncIO, Spring Boot, REST API design, Pydantic |
| **Systems** | Multithreading, Concurrency, Socket Programming, TCP/UDP, ConcurrentHashMap, Thread-Safe Design |
| **AI / ML** | Scikit-learn, Multi-Agent LLM Orchestration, Claude API, Prompt Engineering, Anomaly Detection |
| **Data** | Pandas, NumPy, Matplotlib, Seaborn, Feature Engineering, Statistical Inference |
| **Tools** | Git, Linux/Bash, Docker, Postman, Wireshark |

---

## Experience

**AI & Data Science Intern — XYlofy AI** *(June 2026 – Present, Remote)*
- Built an employee attrition prediction system in Scikit-learn, comparing Logistic Regression, Random Forest, and Gradient Boosting on Precision/Recall/F1/ROC-AUC.
- Built end-to-end ML pipelines: data cleaning, feature engineering, encoding, scaling on structured HR datasets.
- Extracted feature importance and translated model output into business recommendations for stakeholders.

---

## Featured Projects

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

### `FlowState` — Anomaly Detection on Behavioral Data
**AI / Data** · Python, Scikit-learn, Statistical Feature Engineering
- 7-dimensional feature space (Shannon Entropy, Hjorth Mobility, CoV, Skewness, Kurtosis) from keystroke timing data.
- Benchmarked Isolation Forest, LOF, and OC-SVM — LOF achieved ROC-AUC 0.8512, F1 0.7143.
- Leave-One-User-Out validation across 10 users (cross-user mean AUC 0.8031); privacy-by-design — discards key identity at the hardware level.

[→ Repository](https://github.com/charu2210/FlowState)

### `OpenCase` — AI Investigation Platform
**AI / Full-Stack** · Next.js, TypeScript, FastAPI, Gemini API
- Research project (under a university professor) exploring how LLMs reason over evidence: four investigation personas, an evidence board, theory comparison, and step-by-step reasoning traces.
- FastAPI backend serving prompt-engineered investigation modes to a Next.js/TypeScript frontend.

[→ Repository](https://github.com/charu2210/opencase)

### `House Price Prediction` — Regression Modeling
**Data Analyst** · Python, Scikit-learn, Pandas
- End-to-end regression workflow on residential property data: cleaning, EDA, one-hot encoding, 80/20 split.
- Compared Linear Regression and Random Forest; best model R² 0.653 (MAE ~970K, RMSE ~1.32M).
- Feature importance analysis translated into business recommendations.

[→ Repository](https://github.com/charu2210/house-price-prediction)

### `Employee Attrition Prediction` — Classification & HR Analytics
**Data Analyst** · Python, Scikit-learn, Pandas
- Predicted attrition on the IBM HR Analytics dataset (1,470 rows) using Logistic Regression, Random Forest, and Gradient Boosting.
- Best model (Gradient Boosting) reached ROC-AUC 0.805.
- Surfaced key drivers (monthly income, overtime, stock options, job involvement) as HR-facing recommendations.

[→ Repository](https://github.com/charu2210/employee-attrition-prediction)

---

## Achievements & Leadership

- **Hackathon Finalist:** Offline National Finalist, IIT Bombay Upskill India Hackathon · Finalist, India Innovates 2026 (presented at Bharat Mandapam, New Delhi) · Round 2 Qualifier, EY Techathon
- **Global Delegate:** Selected Delegate, HPAIR 2026 (Harvard Project for Asian & International Relations)
- **Certifications:** NPTEL Programming in Java — Elite Gold (Top 90th percentile) · GirlScript Summer of Code 2025 — Selected Participant
- **Leadership:** Joint Head of Corporate Affairs, IEEE Computer Society MUJ — secured 5+ industry sponsorships for Genesis 5.0 (20,000+ attendees)

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=charu2210&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=charu2210&layout=compact&theme=tokyonight&hide_border=true)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=charu2210&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

**charu.malik2210@gmail.com** · [LinkedIn](https://linkedin.com/in/charu-malik-56636733a) · [GitHub](https://github.com/charu2210)

</div>
