<div align="center">

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:0a0a0a,50:0d1117,100:161b22&height=220&section=header&text=Prathamesh%20Fuke&fontSize=56&fontColor=58a6ff&fontAlignY=55&desc=Building%20systems%20that%20think%2C%20reason%2C%20and%20trade&descSize=16&descAlignY=78&descColor=8b949e&animation=twinkling&rotate=-6&fontAlign=35" width="100%"/>

</div>

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│  ~/prathamesh  ❯  whoami                                                        │
│                                                                                 │
│  AI Engineer · LLM Researcher · Competitive Programmer · Quant Finance Nerd    │
│  Datasmith AI (GenAI Intern) · Founder @ Seris Tech                            │
│  CGPA 9.45 · Rank 1 · MMCOE, Pune · ICPC Global Rank 506                       │
└─────────────────────────────────────────────────────────────────────────────────┘
```

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=15&pause=1200&color=58A6FF&center=true&vCenter=true&multiline=false&repeat=true&width=720&height=30&lines=Hybrid+RAG+pipelines+that+cut+tender+review+from+hours+→+3+minutes;Execution-aware+loss+functions+for+live+LOB+trading+(%2B1.8%25+PnL);LLM+fine-tuning+%26+quantization+for+zero-cost+CPU+inference;SIH+2025+Winner+·+ICPC+Global+Rank+506+·+Codeforces+Expert)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/—LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/prathamesh-fuke-094642282)&nbsp;
[![Email](https://img.shields.io/badge/—Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:prathameshfuke@icloud.com)&nbsp;
[![Codeforces](https://img.shields.io/badge/—CF_Expert_1600%2B-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/shuracodes)&nbsp;
[![AgeWell](https://img.shields.io/badge/—AgeWell_Live-00C7B7?style=flat-square&logo=vercel&logoColor=white)](https://agewell-pi.vercel.app)&nbsp;
[![ScoreSight](https://img.shields.io/badge/—ScoreSight_Live-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://scoresight.streamlit.app)

</div>

---

## `$ cat about.py`

```python
class Prathamesh:
    role        = "GenAI Intern @ Datasmith AI  |  Founder @ Seris Tech"
    university  = "MMCOE · Savitribai Phule Pune University"
    degree      = "B.E. ETC (Hons. Data Science)"
    cgpa        = 9.45  # Top 0.1% · Rank 1 two consecutive years

    currently   = [
        "Hybrid RAG pipelines (BM25 + FAISS) for tender automation",
        "LLM fine-tuning & GGUF quantization for CPU-only inference",
        "Execution-aware loss functions for limit order book prediction",
    ]

    deep_interests = {
        "Quant Finance"   : "LOB modelling, execution-aware ML, microstructure",
        "Game Theory"     : "Nash equilibria, social choice, fair division algos",
        "LLM Research"    : "Reasoning, hallucination, RLHF, alignment",
        "Comp Prog"       : "Codeforces Expert · ICPC Global Rank 506 (2026)",
    }

    open_to     = "AI/ML Research Internships · Pune / Remote"
    contact     = "prathameshfuke@icloud.com  ·  +91-7249371213"
```

---

## `$ ls -la ./experience/`

<table>
<tr>
<td valign="top" width="50%">

**`▶ ACTIVE`**

### ⚙ Generative AI Intern · Datasmith AI
`Feb 2026 – Present` · Hybrid, Pune

Production hybrid RAG: **BM25 + FAISS** via LangChain → tender review time: hours **→ 3 min**

Fine-tuned + quantized **LLaMA / Mistral** (GGUF/GGML) — zero-cost CPU inference, no GPU

Multi-turn agentic workflows: **LangGraph** tool-calling agents + long-term memory + **RAGAS** evals

---

### 🚀 Founder · Seris Tech
`Aug 2025 – Present` · Pune

Building **HealthSentinel** (outbreak detection) + **AgeWell** (eldercare platform)

Stacking ensemble with Optuna TPE → **94% F1** on imbalanced medical data

OCR + NER pipeline (EasyOCR + spaCy) → **95% precision** via async FastAPI

End-to-end MLOps: MLflow · drift detection · auto-retraining

</td>
<td valign="top" width="50%">

**`▶ COMPLETED`**

### 🔬 AI/ML Research Intern · Infosys Springboard
`Oct – Dec 2025` · Remote

Ensemble stacking (LightGBM meta-learner) → **97.2% accuracy** on clinical imbalanced data

**SHAP** explainability · Scikit-learn Pipelines → 70% preprocessing code reduction

---

### 🤝 Agentic AI Intern · Multiverz
`Nov – Dec 2025` · Remote

Architected **AgentBoard**: 4-agent enterprise advisory system for a Sri Lankan listed company

Agents: Growth · Strategy · ESG · M&A — powered by **LangGraph + CrewAI**

Hybrid RAG: vector DB + knowledge graph → board-ready insights in **< 30 min**

---

### 📡 Developer Advocate · Kombai
`Jan – Feb 2026` · Remote

Adversarial prompt suites to stress-test AI → frontend code gen agent; failure taxonomy reports

</td>
</tr>
</table>

> 🔭 **Bonus origin story:** Research Intern @ **IUCAA Pune** (May 2019) — planetary motion modelling & IoT instrumentation

---

## `$ find ./projects -name "*.md" | sort -k score`

<details open>
<summary>&nbsp;<b>📈 L_EXEC — Execution-Aware Loss for LOB Prediction</b>&nbsp;&nbsp;<code>2026</code>&nbsp;&nbsp;<a href="https://github.com/prathameshfuke/quantres">[ repo ]</a></summary>
<br/>

> Standard cross-entropy treats all mispredictions equally. **L_EXEC doesn't.** It penalizes by spread, queue depth, and fill probability — the costs that actually matter in live trading.

| Metric | DeepLOB + CE | DeepLOB + L_EXEC | Δ |
|---|---|---|---|
| PnL | baseline | +1.8% | ✅ |
| Sharpe | baseline | +0.5 | ✅ |
| Significance | — | p < 0.001 | DM-test |

Validated across high / normal / low volatility regimes on **FI-2010** benchmark.

`PyTorch` `DeepLOB` `FI-2010` `NumPy` `Diebold-Mariano` `Statistical Validation`

</details>

---

<details open>
<summary>&nbsp;<b>📄 TenderExtractPro — Hybrid RAG for Gov Tender Documents</b>&nbsp;&nbsp;<code>Feb 2026</code>&nbsp;&nbsp;<a href="https://github.com/prathameshfuke/TenderExtractPro">[ repo ]</a></summary>
<br/>

BM25 sparse + FAISS dense + dedicated table extraction pipeline — **85–90% accuracy** on complex multi-section government tenders

GGUF-quantized LLaMA for **zero-infra CPU inference** · FastAPI returns structured JSON with source citations

`LangChain` `BM25` `FAISS` `LLaMA GGUF` `FastAPI` `RAGAS`

</details>

---

<details>
<summary>&nbsp;<b>🏥 HealthSentinel — Medical NER & Outbreak Detection</b>&nbsp;&nbsp;<code>🏆 SIH 2025 Winner (2nd / 120 teams)</code>&nbsp;&nbsp;<a href="https://github.com/prathameshfuke/healthsentinel">[ repo ]</a>&nbsp;&nbsp;<a href="https://youtu.be/JUrta4EyUmA?si=5bWr8HkIWvMWgb4-">[ demo ]</a></summary>
<br/>

Fine-tuned `bert-base-uncased` + **LoRA/PEFT** for medical NER (diagnoses · medications · symptoms) from unstructured clinical notes

Firebase Cloud Functions + Firestore real-time DB · React Native + Redux Toolkit mobile app

**National Finals · Smart India Hackathon 2025 · Govt. of India**

`BERT` `LoRA/PEFT` `HuggingFace` `Firebase` `React Native` `PostgreSQL`

</details>

---

<details>
<summary>&nbsp;<b>👴 AgeWell — AI-Powered Eldercare Platform</b>&nbsp;&nbsp;<a href="https://github.com/prathameshfuke/agewell">[ repo ]</a>&nbsp;&nbsp;<a href="https://agewell-pi.vercel.app/">[ live ]</a></summary>
<br/>

Real-time vitals monitoring (SpO₂, HR, temp, BP) via ESP32 · **Kalman filter** sensor fusion → 40% noise reduction

Prescription OCR → automated medication management · AI anomaly detection → WhatsApp + push alerts

Dual UX: elderly-friendly large-text UI + detailed caregiver dashboard

`TensorFlow` `OpenCV` `FastAPI` `Flutter` `ESP32` `FreeRTOS` `MQTT`

</details>

---

<details>
<summary>&nbsp;<b>⚽ ScoreSight — EPL Match & Season Prediction</b>&nbsp;&nbsp;<a href="https://github.com/prathameshfuke/scoresight">[ repo ]</a>&nbsp;&nbsp;<a href="https://scoresight.streamlit.app/">[ live ]</a></summary>
<br/>

54 leakage-safe features · temporal train/test splits · **97.2% accuracy** (league winner) · **R² = 0.977** (score regression)

Interactive Streamlit deployment · `LightGBM` `XGBoost` `Scikit-learn` `Pandas`

</details>

---

## `$ cat ./skills/stack.json`

<div align="center">

**Languages & Core**

[![My Skills](https://skillicons.dev/icons?i=python,cpp,ts,js,sql&theme=dark)](https://skillicons.dev)

**AI / ML / GenAI**

[![My Skills](https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme=dark)](https://skillicons.dev)

**Infrastructure & Cloud**

[![My Skills](https://skillicons.dev/icons?i=fastapi,docker,gcp,firebase,postgresql,mongodb,redis&theme=dark)](https://skillicons.dev)

**Tools**

[![My Skills](https://skillicons.dev/icons?i=git,github,linux,vscode&theme=dark)](https://skillicons.dev)

</div>

**Specialist stack not in icons:**
`LangChain` · `LangGraph` · `CrewAI` · `FAISS` · `BM25` · `LLaMA` · `Mistral` · `GGUF Quantization` · `LoRA/PEFT` · `RAGAS` · `SHAP` · `Optuna` · `MLflow` · `HuggingFace` · `YOLOv5` · `spaCy` · `EasyOCR`

---

## `$ cat ./achievements.log`

```
[2026-01] ICPC Global Rank 506       Huawei Sponsored · Codeforces Expert 1800+ (shuracodes)
[2025-12] SIH 2025 — 2nd / 120      National Finals · Govt. of India · BERT + LoRA Medical NER
[2025-10] Oracle Cloud AI Assoc.     1Z0-1122-25 · Credential: 102972266OCI25AICFA
[2025-00] Google Cloud — 47 Badges   Vertex AI MLOps · Responsible AI · BigQuery ML · Kubernetes
[2025-00] Infosys — 10 Certs         Deep Learning · NLP · CV · GenAI · RPA · Agile
[2023-25] Academic Rank #1           Two consecutive years · MMCOE · Top 3 all semesters (CGPA 9.45)
```

---

## `$ cat ./oss/contributions.md`

| Project | Role |
|---|---|
| **[DIPY](https://github.com/dipy/dipy)** — Diffusion MRI in Python | Tractography workflows & scientific computing utilities |
| **[FURY-GL](https://github.com/fury-gl/fury)** — Scientific 3D Visualization | OpenGL-based rendering components & visualization pipelines |

---

## `$ tail -f ./stats/live.log`

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=prathameshfuke&theme=onestar&no-frame=true&no-bg=true&margin-w=8&rank=SSS,SS,S,AAA,AA,A,B)](https://github.com/ryo-ma/github-profile-trophy)

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=prathameshfuke&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D)](https://git.io/streak-stats)

<br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=prathameshfuke&bg_color=0d1117&color=58a6ff&line=1f6feb&point=58a6ff&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

<br/>

<img src="https://komarev.com/ghpvc/?username=prathameshfuke&color=1f6feb&style=flat-square&label=profile+views"/>

</div>

---

<div align="center">

```
Open to AI/ML Research Internships  ·  Pune, Maharashtra  ·  Remote-friendly
prathameshfuke@icloud.com  ·  +91-7249371213
```

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:161b22,100:0d1117&height=80&section=footer&reversal=true&rotate=4" width="100%"/>

</div>
