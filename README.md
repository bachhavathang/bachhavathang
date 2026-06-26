# Athang Bachhav

**AI Engineer / Data Scientist** — I build agentic and retrieval systems: LLM pipelines that have to make the *right* call, not just a plausible one. Backed by 4+ years shipping production ML at a Fortune 100 insurer and beyond.

My fascination is the reasoning layer — retrieval, adjudication, agents — but I've learned the hard way that the AI is only as good as the validation underneath it. So I build systems that fail loudly, document where they break, and stay auditable.

```
What I'm into        →  agentic retrieval · RAG that's actually precise · LLM-as-judge · NLP
What makes it work   →  honest evaluation · validation discipline · production serving
```

- 🔭 Building agentic retrieval systems · interviewing for AI / DS / ML Engineer roles
- 🧰 Python · LangGraph / LangChain · RAG · Transformers · XGBoost · FastAPI · Docker · GCP / AWS
- 🎓 M.S. Data Science, University at Buffalo (SUNY) · 2 published CV papers
- 📍 Greater NYC · open to remote
- 📫 bachhavathang88@gmail.com · [LinkedIn](https://www.linkedin.com/in/bachhavathang)

---

### What I'm building

**Retrieval systems that earn their confidence.**
Most RAG optimizes for recall and stops there. The interesting failures live at the precision step — when two candidates look equally good to an embedding model and the wrong one wins by a hair. My recent work centers on **retrieve-then-judge**: retrieval as a cheap recall tool, an LLM as a deliberate precision tool, with every decision made explicit and auditable. That's the core of [**Backtrace**](https://github.com/bachhavathang/backtrace).

**AI grounded in production reality.**
Before the agents, there were the pipelines. At AIG I built LLM/RAG systems over 50,000+ insurance documents and lifted risk-classification precision from 71% to 89% on 2M+ records — then cut deployment from 3 weeks to 4 days so the work actually reached production. The AI is the interesting part; the discipline is why it ships.

---

### Featured work

| Project | What it is | Why it matters |
|---|---|---|
| 🧠 **[Backtrace](https://github.com/bachhavathang/backtrace)** | Agentic spend-recovery pipeline: semantic retrieval → LLM adjudicator → recover / escalate / skip | Retrieve-then-judge on LangGraph. Ships with a real worked failure: semantic search ranked the wrong contract by a 0.056 margin — and how the judge layer catches it. |
| 📄 **[Insurance Doc Intelligence (RAG)](https://github.com/bachhavathang/insurance-doc-intelligence)** | Grounded RAG over insurance PDFs with citations; pluggable embedding backend | Built to be run, not just read. Eval harness: Hit@4 = 1.00, MRR = 1.000. |
| 📡 **[Sensor Anomaly Detection](https://github.com/bachhavathang/sensor-anomaly-detection)** | PyTorch autoencoder for unsupervised predictive maintenance | ROC-AUC 0.922, F1 0.857 — with the 79%-recall failure mode documented openly, not hidden. |
| 🎯 **[Creator Monetization Segmentation](https://github.com/bachhavathang/creator-monetization-segmentation)** | K-Means segmentation of 758 creators into 5 monetization archetypes | A 0–100 readiness score that maps to concrete product actions per tier. |

---

### How I think about AI systems

1. **A model is a claim — validate it like one.** Hard baselines, honest splits, metrics I can defend under pressure.
2. **Recall and precision are different tools.** Don't ask retrieval to do the judge's job.
3. **Silent failures are the expensive ones.** Logging, validation, and alerting are part of the system, not an afterthought.
4. **Write the failure mode down.** If I can't explain where it breaks, I don't understand it yet.

---

### Where I've shipped

**AI / Data Research Lead** · Asian Community Development Center *(2025–present)* — LangChain reporting pipeline (3 days → 4 hrs), RAG knowledge portal for 200+ staff, NLP targeting +34%
**Associate Data Scientist** · AIG *(2025)* — Insurance RAG over 50K+ docs, risk classification 71% → 89%, deployment 3 wks → 4 days
**Data Scientist** · InfoWay Solutions *(2021–2023)* — <200ms p95 serving at 50K daily calls, churn/conversion models in client CRMs

---

### Toolkit

**Languages** · Python · SQL · Bash
**AI / LLM** · LangGraph · LangChain · RAG · Transformers · spaCy · Pinecone · Milvus · semantic search
**ML** · scikit-learn · XGBoost · PyTorch · Bayesian modeling (PyMC) · A/B testing
**Serving & MLOps** · FastAPI · Flask · Docker · CI/CD · MLflow · model monitoring
**Data & Cloud** · BigQuery · ETL pipelines · GCP (Vertex AI) · AWS (S3, Lambda, SageMaker)

---

<sub>📌 Pinned repositories below — that's the work worth your time.</sub>
