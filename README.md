
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,100:7aa2f7&height=180&section=header&text=Charu%20Malik&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%C2%B7%20LLM%20Research%20%C2%B7%20Intelligent%20Systems&descAlignY=58&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=7AA2F7&center=true&vCenter=true&width=750&lines=Building+reliable+AI+systems...;Researching+LLM+reasoning+and+interpretability...;Engineering+multimodal+and+agentic+AI...;Turning+research+ideas+into+working+systems..." alt="Typing SVG"/>

[![Email](https://img.shields.io/badge/Email-charu.malik2210%40gmail.com-D14836?style=flat-square\&logo=gmail\&logoColor=white)](mailto:charu.malik2210@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-charu--malik-0A66C2?style=flat-square\&logo=linkedin\&logoColor=white)](https://linkedin.com/in/charu-malik-56636733a)
[![GitHub](https://img.shields.io/badge/GitHub-charu2210-181717?style=flat-square\&logo=github\&logoColor=white)](https://github.com/charu2210)
![Profile Views](https://komarev.com/ghpvc/?username=charu2210\&color=7AA2F7\&style=flat-square\&label=Profile+Views)

</div>

---

## 🧠 About Me

I am a **Computer Science & Engineering (Data Science) undergraduate at Manipal University Jaipur**, interested in building and studying intelligent systems at the intersection of **AI engineering, large language models, multimodal learning, and machine learning research**.

My work spans both sides of AI:

* 🔬 **Research:** LLM reasoning, belief revision, mechanistic interpretability, evaluation, multimodal retrieval
* ⚙️ **AI Engineering:** agentic systems, inference pipelines, APIs, structured generation, fault-tolerant AI infrastructure
* 📊 **Machine Learning:** anomaly detection, forecasting, classification, statistical feature engineering
* 🧩 **Systems:** concurrent backends, networking, data pipelines, reliable distributed workflows

Currently, my research interests center around **how AI systems reason, update beliefs, represent information internally, and behave under changing or unreliable evidence**.

> **I like building AI systems — and then asking why they behave the way they do.**

---

## 🔬 Research

### Undergraduate Research Intern — Multimodal AI

**VISMA Lab, IIT Bhubaneswar · Dr. Debi Prosad Dogra**
*Aug 2026 – Present*

* Developing an AI-powered image-search system using pretrained **CLIP vision-language embeddings** for semantic retrieval from natural-language queries.
* Implementing a cross-modal retrieval pipeline in **PyTorch** using image/text embeddings and cosine similarity.
* Building an interactive Streamlit prototype integrating embedding generation, semantic search, and image retrieval into an end-to-end multimodal AI system.

### Research Fellow 

**Single Core Labs · Research Collective**
*Aug 2026 – Present*

* Selected for the **Single Core Labs Research Collective**.
* Contributing to research on **benchmarking and improving coding agents**.
* Working within a research-oriented mentorship and publication program focused on large language models and AI agents.

---

## ⚙️ AI Engineering Experience

### AI & Data Science Intern — XYlofy AI

*Jun 2026 – Jul 2026 · Remote*

* Developed end-to-end machine learning pipelines for retail demand forecasting using **Python, Pandas, Scikit-learn, Statsmodels, SARIMA, Prophet, and XGBoost**.
* Benchmarked forecasting approaches using **MAE, RMSE, and MAPE** to evaluate predictive performance.
* Implemented reusable anomaly-detection and demand-segmentation modules using **Isolation Forest, Z-score analysis, and K-Means**.
* Built and shipped an interactive **Streamlit decision-support application** integrating forecasting, anomaly detection, and analytics.
* Applied structured data-processing and model-evaluation workflows across real-world datasets.

---

##  AI & Research Projects

### `Phantom Plan` — Multi-Agent LLM Infrastructure

**AI Engineering · Python · FastAPI · AsyncIO · LLM APIs · Pydantic**

* Architected a **6-agent LLM inference pipeline** for financial planning using asynchronous execution and shared pipeline state.
* Designed structured communication between agents using **Pydantic-validated JSON contracts**.
* Implemented independent fallback and recovery logic for agent failures, achieving zero HTTP 500s under simulated full-agent outages.
* Stress-tested generated plans using **500-run Monte Carlo simulations** against user-specific spending variables.
* Explored reliable orchestration patterns for building production-oriented agentic AI systems.

[→ Repository](https://github.com/charu2210/phantom)

---

### `OpenCase` — LLM Investigation & Reasoning Platform

**AI Research / Full-Stack · Python · FastAPI · Next.js · TypeScript · Gemini API**

* Built an AI investigation platform exploring how LLMs reason over **staged evidence and competing hypotheses**.
* Designed four investigation personas with an evidence board, theory comparison, and step-by-step reasoning traces.
* Developed a FastAPI backend serving specialized investigation modes to a Next.js/TypeScript frontend.
* Explored the engineering challenges of turning LLM reasoning workflows into interactive research-oriented systems.

[→ Repository](https://github.com/charu2210/opencase)

---

### `FlowState` — Behavioral Anomaly Detection

**ML Research · Python · Scikit-learn · Statistical Feature Engineering**

* Developed a behavioral anomaly-detection system using a **7-dimensional statistical feature space** derived from keystroke dynamics.
* Benchmarked **Isolation Forest, Local Outlier Factor, and One-Class SVM**.
* Achieved **ROC-AUC 0.8512 and F1 0.7143** with LOF.
* Evaluated generalization to unseen users using **Leave-One-User-Out validation across 10 users**, achieving a cross-user mean AUC of **0.8031**.
* Designed the pipeline with privacy in mind by discarding raw key identity at the hardware level.

[→ Repository](https://github.com/charu2210/FlowState)

---

### `Demand Intelligence Engine` — ML Forecasting & Decision System

**Machine Learning · Python · SARIMA · Prophet · XGBoost · Streamlit**

* Built an end-to-end forecasting system over **4 years of retail transaction data**.
* Benchmarked SARIMA, Prophet, and XGBoost; SARIMA achieved the best result at **20.5% MAPE**.
* Combined forecasting with **Isolation Forest + Z-score anomaly detection** and K-Means/PCA-based product segmentation.
* Built a live 4-page Streamlit system for forecast exploration, anomaly analysis, and product segmentation.

[→ Live Demo](https://salesforecasting-9sfccbfx2bdpah4h3fezql.streamlit.app/) · [→ Repository](https://github.com/charu2210/SalesForecasting)

---

### `R-UDP` — Reliable Transport Protocol

**Systems Engineering · Java · Networking · Concurrency**

* Architected a reliable transport layer over UDP with a custom 12-byte application header containing sequence numbers, CRC32 checksum, and payload length.
* Implemented **Selective Repeat ARQ** with a thread-safe concurrent packet window.
* Achieved **90% goodput under 20% simulated packet loss**.
* Built network emulation tooling for testing packet drop, duplication, and reordering.

[→ Repository](https://github.com/charu2210/R-UDP-Project)

---

### `Industrial Telemetry Ingestion Service`

**AI Infrastructure / Backend · Java · Spring Boot · SQL · Concurrency**

* Built a high-throughput backend for ingesting manufacturing telemetry under concurrent load.
* Designed a thread-safe **4-state idempotent upsert model**: `NEW / DEDUPED / UPDATED / IGNORED`.
* Used `ConcurrentHashMap` and atomic operations to handle concurrent updates and out-of-order data.
* Added schema validation, timestamp checks, and structured error handling before persistence.

[→ Repository](https://github.com/charu2210/telemetry-ingestion-backend)

---

## 🧪 Research & AI Interests

<div align="center">

`LLM Reasoning` · `Mechanistic Interpretability` · `LLM Evaluation` · `AI Agents`
`Multimodal AI` · `Vision-Language Models` · `Representation Learning`
`Evidence-Based Reasoning` · `Model Probing` · `AI Reliability`
`Anomaly Detection` · `Statistical Learning` · `Intelligent Systems`

</div>

---

## 🛠️ Technical Stack

### AI / Machine Learning

`PyTorch` `Scikit-learn` `XGBoost` `Statsmodels` `Pandas` `NumPy`
`Feature Engineering` `Model Evaluation` `Anomaly Detection` `Time-Series Forecasting`

### LLMs / NLP

`Transformers` `TransformerLens` `Mechanistic Interpretability`
`LLM Evaluation` `Prompt Engineering` `LoRA` `QLoRA` `PEFT`
`Multi-Agent Systems` `Structured Generation` `LLM APIs`

### Multimodal AI

`CLIP` `Vision-Language Models` `Image-Text Embeddings`
`Cross-Modal Retrieval` `Semantic Search` `Cosine Similarity`

### AI Engineering

`Python` `FastAPI` `AsyncIO` `Pydantic` `REST APIs`
`Agent Orchestration` `Fault Tolerance` `Inference Pipelines`

### Systems

`Java` `C` `SQL` `Spring Boot` `Multithreading`
`Concurrent Data Structures` `Socket Programming` `TCP/UDP`

### Tools

`Git` `GitHub` `Docker` `Linux` `Streamlit` `Jupyter` `Postman` `Wireshark`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,java,c,fastapi,spring,docker,git,github,linux&theme=dark" />

</div>

---

## 🌱 Open Source

### GirlScript Summer of Code 2026

**Top 1% global contributor**

* Ranked among the top contributors out of **43,000+ participants**.
* Merged **13 pull requests across multiple projects**.
* Contributed production-quality fixes spanning:

  * Security and XSS prevention
  * Concurrency and race-condition handling
  * Data correctness
  * Image processing
  * Developer tooling and UX

[→ GSSoC Profile](https://gssoc.girlscript.org/profile/5deeb7c6-21ca-4415-ae1d-da355c6db586)

---

## 🏆 Achievements

* 🥇 **Finalist — India Innovates 2026**, presented at Bharat Mandapam, New Delhi
* 🏆 **National Finalist — IIT Bombay Upskill India Hackathon**
* 💻 **Semi-Finalist — Flipkart GRiD 8.0**, Software Development Track
* 🌍 **Selected Delegate — HPAIR 2026**, Harvard Project for Asian & International Relations
* ⭐ **NPTEL Programming in Java — Elite Gold**, Top 90th percentile
* 🔬 **Research Fellow — Single Core Labs Research Collective**
* 🧠 Undergraduate Researcher — **IISER Kolkata**
* 👁️ Undergraduate Research Intern — **VISMA Lab, IIT Bhubaneswar**

---

## 🎓 Education

**Manipal University Jaipur**

B.Tech in Computer Science & Engineering (Data Science)
**CGPA: 8.99 / 10 · 2024 – 2028**

Relevant coursework:

`Data Structures & Algorithms` · `Operating Systems`
`Computer Networks` · `Database Management Systems`
`Multithreading & Concurrency` · `Machine Learning`
`Probability & Statistics`

---

## 🤝 Leadership

### IEEE Computer Society MUJ — Joint Head of Corporate Affairs

* Led corporate outreach and industry engagement for **Genesis 5.0**, a flagship technical event with 20,000+ attendees.
* Secured **5+ industry sponsorship partnerships**.
* Coordinated with external organizations and cross-functional teams to support event execution.

---

## 📊 GitHub Activity

<div align="center">

![GitHub Stats](https://github-readme-stats-one-bice.vercel.app/api?username=charu2210\&show_icons=true\&theme=tokyonight\&hide_border=true)

![Top Languages](https://github-readme-stats-one-bice.vercel.app/api/top-langs/?username=charu2210\&layout=compact\&theme=tokyonight\&hide_border=true)

</div>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=charu2210&theme=tokyo-night&hide_border=true"/>
</p>
---

I am particularly interested in research questions around **LLM reasoning, model reliability, interpretability, evidence sensitivity, and multimodal intelligence**, while continuing to build the engineering systems required to turn those ideas into working AI applications.


<div align="center">

### Building AI systems. Studying how they reason.

**[charu.malik2210@gmail.com](mailto:charu.malik2210@gmail.com)** · [LinkedIn](https://linkedin.com/in/charu-malik-56636733a) · [GitHub](https://github.com/charu2210)

</div>
