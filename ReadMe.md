<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Prathamesh%20Fuke&fontSize=50&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%7C%20LLM%20Researcher%20%7C%20Builder&descSize=18&descAlignY=58&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=16&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Building+production-grade+agentic+AI+systems;Fine-tuning+%26+quantizing+LLMs+for+real-world+deployment;Hybrid+RAG+pipelines+%7C+LangGraph+%7C+CrewAI;CGPA+9.45+%7C+Rank+1+Two+Consecutive+Years+%7C+MMCOE+Pune;SIH+2025+Winner+%7C+ICPC+2026+Global+Rank+506)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/prathamesh-fuke-094642282)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prathameshfuke@icloud.com)
[![Codeforces](https://img.shields.io/badge/Codeforces_Expert-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/shuracodes)
[![Portfolio](https://img.shields.io/badge/AgeWell_Live-00C7B7?style=for-the-badge&logo=vercel&logoColor=white)](https://agewell-pi.vercel.app)
[![Streamlit](https://img.shields.io/badge/ScoreSight_Live-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://scoresight.streamlit.app)

</div>

---

## ⚡ About Me

```python
prathamesh = {
    "role"        : "Generative AI Intern @ Datasmith AI | Founder @ Seris Tech",
    "education"   : "B.E. Electrical & Electronics (Hons. Data Science) — CGPA 9.45 | Top 0.1%",
    "university"  : "MMCOE, Savitribai Phule Pune University, Pune",
    "cgpa_journey": [9.59, 9.50, 8.86, 10.00, 9.29],   # Sem I → V
    "rank"        : "Rank 1 two consecutive academic years | Top 3 consistently",
    "building"    : ["Agentic AI systems", "Hybrid RAG pipelines", "LLM fine-tuning & quantization"],
    "interests"   : ["Quantitative Finance", "Game Theory", "LLM Research", "Computational Social Choice"],
    "open_to"     : "AI/ML Research Internships & Collaborations — Pune / Remote"
}
```

---

## 💼 Experience

<table>
<tr>
<td width="50%">

### 🤖 Generative AI Intern — Datasmith AI
`Feb 2026 – Present` · Hybrid, Pune

- Hybrid RAG (BM25 + FAISS) pipeline — tender doc review: hours → **3 min**
- Fine-tuned & quantized LLaMA, Mistral via **GGUF/GGML** for zero-cost CPU inference
- Multi-turn agentic workflows with **LangGraph** — tool-calling, memory, structured output
- End-to-end evaluation with **RAGAS** metrics

</td>
<td width="50%">

### 🏢 Agentic AI Intern — Multiverz
`Nov 2025 – Dec 2025` · Remote

- Designed **AgentBoard**: 4-agent enterprise AI advisory system for a Sri Lankan listed company
- Agents: Growth & Market Entry · Strategy & Ops · ESG & Compliance · M&A Intelligence
- Orchestrated via **LangGraph + CrewAI** — hybrid RAG: vector DB + knowledge graph
- Board-ready insights synthesized in **under 30 minutes**

</td>
</tr>
<tr>
<td width="50%">

### 🔬 AI/ML Research Intern & Team Lead — Infosys Springboard
`Oct 2025 – Dec 2025` · Remote · [📜 10 Certifications](https://drive.google.com/drive/folders/1m69-YSqE7vyTFA5rc79EsYIw5WBF8sUU?usp=sharing)

- Ensemble stacking (LightGBM meta-learner) → **97.2% accuracy** on imbalanced clinical data
- **SHAP** for post-hoc interpretability and feature attribution
- Scikit-learn Pipelines with custom transformers → preprocessing code cut by **70%**

</td>
<td width="50%">

### 🚀 Founder & AI/ML Engineer — Seris Tech
`Aug 2025 – Present` · Pune

- Building **HealthSentinel** (outbreak detection) and **AgeWell** (eldercare AI platform)
- Stacking ensemble → **94% F1-score** (Optuna TPE) on medical datasets
- OCR + NER pipeline (EasyOCR + spaCy) → **95% precision** via async FastAPI
- End-to-end MLOps: MLflow · model versioning · drift detection · auto-retraining

</td>
</tr>
</table>

> 🔭 Also interned at **IUCAA Pune** (Astronomy & Astrophysics, May 2019) — planetary motion research & IoT instrumentation.

---

## 🧪 Featured Projects

<details open>
<summary><b>🧮 L_EXEC — Execution-Aware Loss for Limit Order Book Prediction</b> &nbsp;<a href="https://github.com/prathameshfuke/quantres">[ GitHub ]</a></summary>
<br/>

> **The Problem:** Standard cross-entropy loss treats all prediction errors equally — but in live trading, predicting the wrong direction costs far more than predicting stationary.

- Custom PyTorch loss penalizing predictions by **spread, queue depth, and fill probability**
- Backbone: **DeepLOB** trained on **FI-2010** benchmark dataset
- **+1.8% PnL** and **+0.5% Sharpe** over DeepLOB+CrossEntropy baseline (p < 0.001)
- Validated via **Diebold-Mariano** tests across high, normal, and low volatility regimes
- Full ablation study: cost matrix, exec probability MLP, latency discount components

`PyTorch` `DeepLOB` `FI-2010` `NumPy` `Statistical Validation`

</details>

<details open>
<summary><b>📄 TenderExtractPro — Hybrid RAG for Government Tender Documents</b> &nbsp;<a href="https://github.com/prathameshfuke/TenderExtractPro">[ GitHub ]</a></summary>
<br/>

- **Hybrid RAG**: BM25 sparse retrieval + FAISS semantic dense embeddings + table extraction pipeline
- **85–90% accuracy** on complex multi-section government tender documents
- GGUF-quantized LLaMA for **zero-cost CPU inference**; FastAPI with structured JSON + source citations
- Review time: hours → **under 3 minutes**

`LangChain` `BM25` `FAISS` `LLaMA` `GGUF` `FastAPI` `RAGAS`

</details>

<details>
<summary><b>🏥 HealthSentinel — Medical NER & Outbreak Detection &nbsp; 🏆 SIH 2025 Winner</b> &nbsp;<a href="https://github.com/prathameshfuke/healthsentinel">[ GitHub ]</a> &nbsp;<a href="https://youtu.be/JUrta4EyUmA?si=5bWr8HkIWvMWgb4-">[ Demo ]</a></summary>
<br/>

- **Smart India Hackathon 2025 — 2nd / 120 teams, National Finals, Govt. of India**
- Fine-tuned `bert-base-uncased` with **LoRA/PEFT** for medical NER (diagnoses, medications, symptoms)
- Deployed via Firebase Cloud Functions + Firestore real-time DB
- React Native app with TypeScript + Redux Toolkit for live outbreak monitoring

`BERT` `LoRA/PEFT` `HuggingFace` `Firebase` `React Native` `PostgreSQL`

</details>

<details>
<summary><b>👴 AgeWell — AI-Powered Elderly Health Monitoring Platform</b> &nbsp;<a href="https://github.com/prathameshfuke/agewell">[ GitHub ]</a> &nbsp;<a href="https://agewell-pi.vercel.app/">[ Live ]</a></summary>
<br/>

- Real-time monitoring: SpO₂, heart rate, temperature, BP via ESP32 sensors
- **Kalman filter** sensor fusion → **40% noise reduction**
- Prescription OCR for automated medication management
- AI anomaly detection with WhatsApp + push alerts to caregivers
- Dual interface: elderly-friendly large UI + detailed caregiver dashboard

`TensorFlow` `OpenCV` `FastAPI` `Flutter` `ESP32` `FreeRTOS` `MQTT`

</details>

<details>
<summary><b>⚽ ScoreSight — EPL Match & Season Outcome Prediction</b> &nbsp;<a href="https://github.com/prathameshfuke/scoresight">[ GitHub ]</a> &nbsp;<a href="https://scoresight.streamlit.app/">[ Live App ]</a></summary>
<br/>

- End-to-end ML system for EPL prediction using historical match data + player statistics
- **54 leakage-safe features** engineered with careful temporal splits
- **97.2% accuracy** for league winner classification · **R² = 0.977** for score regression
- Deployed as interactive Streamlit app

`LightGBM` `XGBoost` `Scikit-learn` `Pandas` `Streamlit`

</details>

<details>
<summary><b>📊 PrimeTrade — Crypto Behavioral Finance Analysis</b> &nbsp;<a href="https://github.com/prathameshfuke/primetrade">[ GitHub ]</a></summary>
<br/>

- NLP sentiment analysis correlating Bitcoin Fear/Greed Index with trader performance across 10K+ records
- Statistical patterns for momentum and contrarian algorithmic trading strategies

`Python` `NLP` `Pandas` `Statistical Analysis` `Financial Modeling`

</details>

---

## 🛠️ Tech Stack

<div align="center">

### AI / ML Core
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AD3?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

### Generative AI & RAG
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-0f172a?style=flat-square)
![CrewAI](https://img.shields.io/badge/CrewAI-6366f1?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-009688?style=flat-square)
![LLaMA](https://img.shields.io/badge/LLaMA-7C3AED?style=flat-square)
![Mistral](https://img.shields.io/badge/Mistral-FF7000?style=flat-square)
![GGUF](https://img.shields.io/badge/GGUF_Quantization-334155?style=flat-square)

### MLOps & Cloud
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP_47_Badges-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=databricks&logoColor=white)

</div>

---

## 🏆 Achievements

| 🏅 Achievement | 📋 Details | 📅 Year |
|---|---|---|
| 🥈 Smart India Hackathon 2025 | 2nd / 120 teams · National Finals · Govt. of India | 2025 |
| 🌍 ICPC Global Rank 506 | Huawei Sponsored · [Codeforces Expert 1600+](https://codeforces.com/profile/shuracodes) | 2026 |
| 🎓 Academic Rank 1 | Two consecutive academic years at MMCOE · Top 3 all semesters | 2023–25 |
| ☁️ Oracle Cloud AI Foundations | 1Z0-1122-25 · Credential: 102972266OCI25AICFA | Oct 2025 |
| ☁️ Google Cloud 47 Badges | [Vertex AI MLOps · Responsible AI · BigQuery ML · Kubernetes](https://www.skills.google/public_profiles/51593f1b-e3d7-4e4d-bdea-9322678914bd) | 2025 |
| 📜 Infosys AI/ML 10 Certs | [Deep Learning · NLP · Computer Vision · GenAI · RPA](https://drive.google.com/drive/folders/1m69-YSqE7vyTFA5rc79EsYIw5WBF8sUU?usp=sharing) | 2025 |

---

## 🌱 Open Source Contributions

| Project | Description | Repo |
|---|---|---|
| **DIPY** — Diffusion MRI in Python | Tractography workflows & scientific computing utilities | [github.com/dipy/dipy](https://github.com/dipy/dipy) |
| **FURY-GL** — Scientific 3D Visualization | OpenGL-based rendering components & visualization pipelines | [github.com/fury-gl/fury](https://github.com/fury-gl/fury) |

---

## 🔭 Current Research Interests

```
┌─────────────────────────────────────────────────────────────────────────┐
│  📈  Quantitative Finance      — Execution-aware ML, LOB modelling      │
│  🎮  Game Theory & Soc. Choice — Nash equilibria, fair division algos   │
│  🧠  LLM Research              — Reasoning, hallucination, RLHF         │
│  👥  Behavioural AI            — Preference learning, human-AI dynamics │
│  🔢  Competitive Programming   — Codeforces Expert · 1600+ rating       │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 📊 GitHub Stats

<div align="center">


<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=prathameshfuke&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

<br/>

<img src="https://komarev.com/ghpvc/?username=prathameshfuke&color=58A6FF&style=for-the-badge&label=Profile+Views"/>

</div>

---

<div align="center">

**Open to AI/ML Research Internships · Based in Pune, Maharashtra · Available Remote**

`prathameshfuke@icloud.com` · `+91-7249371213`

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer&animation=twinkling" width="100%"/>

</div>
