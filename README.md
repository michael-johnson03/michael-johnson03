## Hi, I'm Michael 👋

I build **production RAG systems, transformer models, and end-to-end ML pipelines**. Five pinned repositories below, each shipped against a real problem during my MS in Data Science at UNC Charlotte (2026) — including a fraud-intelligence pipeline built with a financial-services sponsor, a DistilBERT regressor for menu calorie prediction, a RAG chatbot with formal IR evaluation, and a Microsoft GraphRAG implementation running on private infrastructure.

I care about the parts most demos skip: **auditable classification, grounded synthesis with quality gates, honest limitations, and outputs an analyst can actually use.** Day job is consultant at Slalom in Delivery Leadership (Data & Financial Services); the ML work is where I'm heading next.

📍 Charlotte, NC

💼 Consultant @ Slalom — Delivery Leadership, Data & Financial Services

🎓 MS in Data Science & Business Analytics — UNC Charlotte (2026)

🪖 U.S. Army Intelligence Analyst — 4 years

---

### What I work on

- 🔍 **RAG pipelines** — retrieval-augmented generation with FAISS vector search, sentence-transformer embeddings, local-hosted Mistral-7B (4-bit NF4 quantization), grounded synthesis with structured output (Pattern / Targets & Impact / Watch Signals), verbatim-copy quality gates against hallucination
- 🧠 **Transformer fine-tuning** — DistilBERT regression with hybrid feature heads, GroupShuffleSplit to prevent leakage, mixed-precision training, stratified error analysis (MAE 87.5 kcal, 73.3% of predictions within ±100 kcal on test set)
- 🤖 **LLM application engineering** — LangGraph ReAct agents with custom tool nodes, Microsoft GraphRAG on private Ollama infrastructure, prompt engineering across Gemini / Flan-T5 / Mistral, function calling, multi-tool agent design
- ☁️ **Cloud ML platforms** — Amazon SageMaker (XGBoost ephemeral training, JumpStart, Bayesian HPO, real-time endpoints), Snowflake Cortex (`AI_COMPLETE`, `EMBED_TEXT_768`, `VECTOR_COSINE_SIMILARITY` for in-warehouse RAG), AWS Bedrock conceptually
- 📐 **Auditable classification** — weighted keyword taxonomies with per-document theme-match traces, designed for regulated-industry use cases where black-box classifiers aren't defensible

---

### What I'm looking for

Roles in **applied ML, ML engineering, AI engineering, or data science** where the work involves turning unstructured signals into decision-ready outputs. Strong interest in financial services, fraud and risk analytics, and any domain where explainability and auditability matter alongside model performance — but the technical stack travels across industries. Open to remote and Charlotte-area roles.

---

### Pinned projects

| Project | What it shows | Stack |
|---|---|---|
Repositories coming soon — currently being polished for public release. Reach out via LinkedIn if you'd like to discuss the work in the meantime.
<!--
| Project | What it shows | Stack |
|---|---|---|
| **[reddit-fraud-intelligence](https://github.com/michael-johnson03/reddit-fraud-intelligence)** | End-to-end production RAG built during a financial-services capstone: RSS ingestion → 18-theme classification → FAISS retrieval → Mistral-7B grounded synthesis. 5 dated production runs, 565 deduplicated posts. | Python · FAISS · sentence-transformers · Mistral-7B · 4-bit NF4 |
| **[menu-calorie-predictor](https://github.com/michael-johnson03/menu-calorie-predictor)** | DistilBERT fine-tuning for regression with engineered feature head; MAE 87.5 kcal, R² 0.452, 73.3% of predictions within ±100 kcal. Includes Model 1 → Model 2 iteration story. | PyTorch · HuggingFace Transformers · scikit-learn |
| **[it-helpdesk-rag-chatbot](https://github.com/michael-johnson03/it-helpdesk-rag-chatbot)** | RAG chatbot with formal IR evaluation (Recall@3 = 1.0, MRR = 1.0); progression from Colab prototype to Streamlit production app. | Streamlit · Gemini · cosine retrieval |
| **[graphrag-local-ollama](https://github.com/michael-johnson03/graphrag-local-ollama)** | Microsoft GraphRAG end-to-end on private infrastructure — no cloud API dependencies. 14-prompt customized library, LanceDB + Neo4j. | GraphRAG · Ollama · LanceDB · Neo4j |
| **[n8n-llm-workflow-patterns](https://github.com/michael-johnson03/n8n-llm-workflow-patterns)** | The same RAG and agent patterns expressed in low-code: basic LLM chain, Qdrant RAG, Snowflake-tool agent, Telegram news pipeline. Argues *which tool fits which problem*. | n8n · Qdrant · Ollama · Gemini · Snowflake |
-->

---

### Stack

**ML & deep learning** — PyTorch · HuggingFace Transformers · scikit-learn · DistilBERT · sentence-transformers · FAISS · XGBoost

**LLM & RAG** — LangChain · LangGraph · Microsoft GraphRAG · Ollama · Mistral · Gemini · Flan-T5 · Snowflake Cortex · n8n

**Cloud & data platforms** — AWS (S3, SageMaker, Bedrock, Lambda, CloudFormation, IAM) · Snowflake · Google Colab · Streamlit · Docker basics

**Data engineering** — Python · pandas · Parquet · SQL · MySQL · Terraform (conceptual)

**Stats & analysis** — R · regression diagnostics (VIF, multicollinearity) · time-series forecasting (ARIMA) · agent-based modeling (NetLogo)

**The work behind the code** — sponsor-facing communication · 7-document handoff packages · least-privilege IAM design · CloudFormation change-set safety · documentation engineering

---

### Background

**MS in Data Science & Business Analytics** at UNC Charlotte (2026): coursework across applied ML, deep learning, text mining & information retrieval, cloud computing, strategic business analytics, and a 14-week practicum with a financial-services sponsor. The pinned repos draw from across the program — RAG and LLM work from the text-mining and AI/deep-learning courses, transformer fine-tuning from the deep-learning project sequence, cloud ML from SageMaker coursework, and the production RAG pipeline from the capstone.

**Work history:** U.S. Army Intelligence Analyst (4 years), then commercial lending and program delivery in financial services, now Consultant at Slalom in Delivery Leadership. The intelligence-analyst and consulting work history is what shapes how I approach problems — *what does an analyst actually need, what does a stakeholder actually need to decide, what would a compliance team need to defend.* That perspective shows up across the pinned projects.

---

### Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/michael-d-johnson3/)
- 📄 Resume — *available on request*

<!-- ============================================================
