<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b26,100:7aa2f7&height=180&section=header&text=Charu%20Malik&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Backend%20Engineer%20%E2%80%A2%20AI%20Researcher%20%E2%80%A2%20Systems%20Programmer&descAlignY=58&descSize=18" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=7AA2F7&center=true&vCenter=true&width=650&lines=Building+reliable+distributed+systems...;...and+interpretable+AI." alt="Typing SVG" />

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=charu2210&color=7AA2F7&style=flat-square&label=Profile+Views)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/charu-malik-56636733a)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:charu.malik2210@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/charu2210)

</div>

---

### 👋 About Me

| | |
|---|---|
| 🎓 **Education** | B.Tech, CSE (Data Science) — Manipal University Jaipur, Class of 2028 (CGPA 8.99/10) |
| 🏢 **Currently** | AI & Data Science Intern @ XYlofy AI (Remote) |
| 🔬 **Research** | Undergraduate research toward publication-track work on LLM reasoning & interpretability |
| ⚙️ **Interests** | AI safety, distributed systems, explainable AI |
| 🎯 **Focus** | Research internships in NLP / interpretability + production-grade backend systems |

### ✅ Engineering Focus

`Backend Systems` `Concurrent & Distributed Programming` `AI Infrastructure` `LLM Research` `Production APIs` `Systems Design`

---

### 🧪 Featured Projects

<table>
<tr>
<td width="50%">

**[R-UDP](https://github.com/charu2210/R-UDP-Project)**  
Custom Layer-4 reliable transport protocol built over UDP.
- 12-byte header with sequence numbers, CRC32 checksum, payload length (Big-Endian)
- Selective Repeat ARQ via thread-safe `ConcurrentHashMap` — 90% goodput at 20% simulated packet loss
- Configurable network emulation proxy for drop/duplication/reordering stress tests

```
Application → Packet Builder → Custom Header → UDP Socket
                    ── Network ──
UDP Socket → Packet Parser → CRC Verification → Application
```

`Java` `Socket Programming` `Concurrency` `ARQ`

</td>
<td width="50%">

**[Industrial Telemetry Ingestion Service](https://github.com/charu2210/telemetry-ingestion-backend)**  
High-throughput batch ingestion backend for manufacturing telemetry.
- Thread-safe, lock-free upserts via atomic `compute()` on `ConcurrentHashMap`
- 4-state idempotent reconciliation logic (NEW / DEDUPED / UPDATED / IGNORED)
- Schema validation and boundary checks ahead of persistence

`Java` `Spring Boot` `Multithreading` `SQL`

</td>
</tr>
<tr>
<td width="50%">

**[Phantom Plan](https://github.com/charu2210/phantom)**  
Multi-agent LLM backend for behavioral financial planning.
- 6-agent stateful pipeline with per-agent fallback recovery (zero HTTP 500s under full agent outage)
- Task-specific model routing across Claude tiers
- Monte Carlo risk simulation (500 runs) over psychological spending variables, with Pydantic-enforced schema contracts

`Python` `FastAPI` `AsyncIO` `Claude API`

</td>
<td width="50%">

**[FlowState](https://github.com/charu2210/FlowState)**  
Cognitive load estimation from keystroke dynamics.
- 7-dimensional feature space (Shannon Entropy, Hjorth Mobility, CoV, Skewness, Kurtosis)
- Benchmarked Isolation Forest, LOF, OC-SVM — LOF: ROC-AUC 0.8512, F1 0.7143
- Leave-One-User-Out validation across 10 users (mean AUC 0.8031); privacy-by-design key discarding

`Python` `Scikit-learn` `Anomaly Detection`

</td>
</tr>
<tr>
<td width="50%">

**[OpenCase](https://github.com/charu2210/opencase)**  
AI-powered investigative reasoning platform for unsolved-mystery case analysis.
- Four investigation modes (Detective/Scientist/Journalist/Historian) via distinct system prompts
- Interpretability view exposing evidence-importance rankings and reasoning traces
- FastAPI backend designed to swap in a fine-tuned local model with no interface changes

`Python` `FastAPI` `Gemini API` `Next.js`

</td>
<td width="50%">

**[Employee Attrition Prediction](https://github.com/charu2210/employee-attrition-prediction)** · **[House Price Prediction](https://github.com/charu2210/house-price-prediction)**  
Applied ML workflows on the IBM HR Analytics and Kaggle housing datasets.
- End-to-end pipelines: EDA → feature engineering → model comparison → evaluation
- Logistic Regression, Random Forest, Gradient Boosting (attrition); regression modeling (housing)
- Feature importance analysis translated into business recommendations

`Python` `Scikit-learn` `Pandas`

</td>
</tr>
</table>

---

### ⚡ Tech Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=python,java,cpp,fastapi,spring,docker,git,linux,postgres,postman&theme=dark" />
</div>

<sub>Also: AsyncIO · Pydantic · Scikit-learn · Pandas / NumPy · Anthropic Claude API · Wireshark</sub>

---

### 📊 GitHub Stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=charu2210&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=charu2210&layout=compact&theme=tokyonight&hide_border=true" width="30%" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=charu2210&theme=tokyonight&hide_border=true" width="60%" />
</div>

<!--
Optional: add a contribution snake animation via GitHub Actions.
1. Create .github/workflows/snake.yml in your profile repo (charu2210/charu2210) using platane/snk
2. Then embed it here:
<img src="https://raw.githubusercontent.com/charu2210/charu2210/output/github-contribution-grid-snake.svg" />
-->

---

### 🔬 Research Interests

Undergraduate research advised by a faculty mentor, oriented toward LLM interpretability and reasoning — currently working toward a first publication-track submission.

`Mechanistic Interpretability` `LLM Reasoning Under Uncertainty` `AI Safety` `Explainable AI` `Human-AI Interaction`

---

### 📈 Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=charu2210&theme=tokyo-night&hide_border=true" width="90%" />
</div>

<div align="center">
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=charu2210&theme=tokyonight" width="45%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=charu2210&theme=tokyonight" width="45%" />
</div>

---

### 🕰️ Timeline

```
2024  Started B.Tech, Manipal University Jaipur
  │
2025  GirlScript Summer of Code — selected participant
  │
2026  AI & Data Science Intern @ XYlofy AI
  │
2026  HPAIR — selected global delegate
  │
2026  Undergraduate research toward first ACL-track submission
```

---

### 🤝 Let's Connect

[![Email](https://img.shields.io/badge/Email-charu.malik2210%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:charu.malik2210@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Charu_Malik-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/charu-malik-56636733a)
[![GitHub](https://img.shields.io/badge/GitHub-charu2210-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/charu2210)

<div align="center">
<i>"I enjoy building systems that stay correct long after the happy path disappears."</i>
</div>
