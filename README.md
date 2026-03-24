<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:0066cc,100:0a0a0a&height=120&section=header" width="100%"/>

# Venkatesh P
### AI/ML Engineer · GenAI Systems · MLOps

*Building production-grade AI systems — from raw data to autonomous action.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/venkatesh-ml)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://venkatesh-hyper.github.io/resume/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:venkateshpvnky9@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/venkatesh-hyper)

</div>

---

## About

I'm an AI/ML Engineer specialising in **RAG pipelines, LLM agents, and scalable ML infrastructure**. I work across the full loop — data ingestion, feature engineering, model training, agent orchestration, and production deployment.

My background spans healthcare AI (production RAG on GCP), genomics ML (GWAS-based risk prediction), and enterprise data systems — giving me an ability to move between domains without losing engineering precision.

---

## Tech Stack

**GenAI & LLM**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![RAG](https://img.shields.io/badge/RAG_Pipelines-0066CC?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-6B21A8?style=flat-square)
![LoRA](https://img.shields.io/badge/LoRA%2FQLoRA-E11D48?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS_Eval-059669?style=flat-square)

**Vector Search & Retrieval**

![FAISS](https://img.shields.io/badge/FAISS-0096FF?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square)
![Weaviate](https://img.shields.io/badge/Weaviate-6BBF4E?style=flat-square)
![Hybrid Search](https://img.shields.io/badge/Hybrid_Search_(BM25+Dense)-6366F1?style=flat-square)

**ML / DL Frameworks**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**MLOps & Deployment**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-945DD6?style=flat-square&logo=dvc&logoColor=white)

**Cloud & Data**

![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

## Featured Projects

### 🔍 PaperLens — Semantic Search Engine
> Semantic search over 100K+ arXiv research papers with agentic RAG summarisation.

| Metric | Result |
|---|---|
| Query throughput | **76,540 QPS** |
| p95 latency | **0.07ms** |
| Cache speedup | **1,738× faster** (1,100ms → 0.44ms) |
| Index size | 1.4MB (FAISS IVFFlat + PQ) |

**Stack:** `sentence-transformers` `FAISS` `FastAPI` `Groq LLaMA-3` `ChromaDB` `Docker` `Streamlit`

**Architecture:** arXiv API → 384-dim embeddings → FAISS IVFFlat index → LRU cache → FastAPI → LLaMA-3 RAG summarisation

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/venkatesh-hyper/paperlens)
[![Live Demo](https://img.shields.io/badge/Live_Demo-00C853?style=flat-square&logo=vercel&logoColor=white)](https://paperlens-i.streamlit.app/)

---

### 🤖 Enterprise Ticket Analysis Bot — Agentic RAG
> Natural-language querying over 70MB+ of enterprise ticket logs via a LangChain agent.

| Metric | Result |
|---|---|
| p95 retrieval latency | **< 200ms** |
| Dataset size | **70MB+** ticket logs |
| Agent capabilities | Tool use · Memory · Planning loops |

**Stack:** `LangChain` `Groq Llama-4 Scout` `ChromaDB` `SentenceTransformers` `FastAPI` `Streamlit`

**Architecture:** PDF parsing → chunking → SentenceTransformer embeddings → ChromaDB → LangChain ReAct agent → natural language UI

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/venkatesh-hyper/ticket_bot_llm)

---

### 🧬 MS Risk Prediction — Genomics ML (RUSA Project)
> Clinical ML pipeline for Multiple Sclerosis risk stratification from GWAS SNP data.

| Metric | Result |
|---|---|
| Model accuracy | **87.6%** |
| Dataset | 500K+ SNP variants |
| Deployment | GCP + Streamlit dashboard |

**Stack:** `XGBoost` `Random Forest` `Scikit-learn` `Streamlit` `GCP` `DVC` `PLINK`

**Pipeline:** GWAS data → SNP feature engineering → PRS computation → ensemble training → interpretable clinical dashboard

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/venkatesh-hyper)

---

### 🧠 Brain Tumor Classifier — CNN Medical Imaging
> Deep learning pipeline for 4-class MRI-based brain tumor classification.

| Metric | Result |
|---|---|
| Classification accuracy | **95%** |
| Classes | Glioma · Meningioma · Pituitary · No Tumor |
| Deployment | Docker · Streamlit inference UI |

**Stack:** `TensorFlow` `CNN` `Transfer Learning` `Data Augmentation` `Docker` `OpenCV`

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github)](https://github.com/venkatesh-hyper/Brain-Tumour-classification)

---

## Experience

**AI/ML Engineer Intern** · NASO Technologies *(Jan 2024 – Apr 2024)*
Built **Well.AI** — a production medical RAG system on GCP handling live health queries. Full stack: LangChain → HuggingFace embeddings → ChromaDB → FastAPI. Containerised with Docker Compose; Supabase session logging for audit traceability.

**ML Researcher** · RUSA Project, University of Madras *(Apr 2024 – Jul 2024)*
Genomics ML pipeline for MS risk prediction from GWAS data. Deployed interpretable Streamlit dashboard used by clinical researchers; DVC-tracked experiments on GCP.

---

## Achievements

**Winner** — AI Front-End Hackathon 2025, MCC Chennai  
**Finalist** — National AI Hackathon, Top 5% nationwide  
**Technical Blogger** — EDA, NLP pipelines, Genomics ML (Medium)  
**Vice President** — Rotaract Club, led 5+ AI awareness events

---

## Currently Building

- **Compliance Intelligence Agent** — multi-agent RAG system over regulatory documents (SEBI/RBI), LangGraph orchestration, RAGAS evaluation
- **PaperLens v2** — scaling to 100K papers, hybrid BM25 + FAISS, cross-encoder reranking
- **Biomedical LLM Fine-Tune** — QLoRA fine-tuning of Mistral-7B on PubMedQA

---

<div align="center">

## Let's Connect

If you're working on **RAG systems, LLM agents, or ML infrastructure** — I'd like to hear about it.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/venkatesh-ml)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:venkateshpvnky9@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://venkatesh-hyper.github.io/resume/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:0066cc,100:0a0a0a&height=80&section=footer" width="100%"/>

</div>
