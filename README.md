## Hi, I'm Vikas 

**AI/ML Engineer** — I build LLM systems meant to survive contact with production, not demos that break the moment they leave a notebook.

🎓 BS in Data Science, **IIT Madras** (Expected 2027)
📍 Bengaluru, India
🔎 **Open to AI Engineer / ML Engineer / Generative AI internships**

---

### What I work on

- **RAG systems** — hybrid retrieval (dense + BM25 + RRF), cross-encoder reranking, and evaluation gates that block bad deploys
- **Agentic AI** — multi-agent pipelines on LangGraph with self-reflection, quality loops, and traceable citations
- **Deep Learning** — transformer fine-tuning and sequence models implemented from scratch in PyTorch

I care about retrieval that returns the right thing, agents that don't confidently make things up, and shipping behind a FastAPI + Docker layer with tracing and tests.

---

### Projects

| Project | What it is | Highlights |
|---|---|---|
| **[ResearchMind](https://github.com/23f3001800/ResearchMind)** · [live](https://research-agent-ui.agreeablestone-a7a39990.centralindia.azurecontainerapps.io) | Multi-agent research assistant (LangGraph) | Researcher → Analyst → Writer with self-reflection & guardrails · every citation is a page the system actually retrieved · **51 tests passing** · FastAPI + React on Azure Container Apps |
| **[DevDocs-AI](https://github.com/23f3001800/DevDocs-AI)** | Production RAG over any GitHub repo or docs site | Hybrid retrieval (dense + BM25 + **RRF**) + cross-encoder reranking · **RAGAS eval gate blocks CI below 0.75** · ~300ms streaming TTFT · multi-stage Docker **<200MB** · JWT/RBAC · LangSmith |
| **[AutoApply-AI](https://github.com/23f3001800/AutoApply-AI)** · [live](https://autoapply.up.railway.app) | 5-agent job-application pipeline (LangGraph) | Scout → Research → Writer → Quality → Applier · **LLM-as-judge loop** rewrites until it clears a 4/5 bar · full application in **under 8 minutes** · Playwright + Claude + Supabase |
| **[Music Genre Classifier](https://github.com/23f3001800/deep-audio-classifier)** · [live](https://audioclassificationproj.streamlit.app/) · [🤗 model](https://huggingface.co/Vikas25S/messy-mashup-ast-v2) | Fine-tuned Audio Spectrogram Transformer | **0.887 macro-F1**, 0.890 accuracy on 10-class genre classification over noise-corrupted audio · 86.2M params |
| **[Protein Secondary Structure](https://github.com/23f3001800/Protein-Secondary-Structure-Prediction)** | Sequence-to-sequence protein structure prediction | Bidirectional RNN and Bi-LSTM/GRU **implemented from scratch in PyTorch** · predicts Q8 & Q3 labels from amino-acid sequences · Kaggle |
| **[CampusHire](https://github.com/23f3001800/CampusHire-From-Classroom-to-Career-)** | Full-stack campus placement platform | Role-based access (Admin / Company / Student) · async background jobs (Celery) · Redis caching · REST API — the systems side of my work |

---

### 🛠️ Tech Stack

**Languages** — Python · SQL

**LLM / GenAI** — LangGraph · LangChain · RAG · Hybrid Retrieval · Cross-Encoder Reranking · RAGAS · LangSmith · Claude & Gemini APIs · Prompt Engineering

**ML / DL** — PyTorch · Hugging Face Transformers · Sentence Transformers · Fine-tuning · Sequence Models

**Vector / Retrieval** — ChromaDB · FAISS · Semantic Search

**Backend / Deployment** — FastAPI · Docker · CI/CD · Azure Container Apps · Railway · Streamlit · Celery · Redis

---

### 📫 Reach me

Open to internships and collaboration on RAG or agentic systems — feel free to reach out here or on [LinkedIn](https://www.linkedin.com/in/vikas-255rajput).
