# Raman Kumar Kheti

**Python Developer · AI Engineer · Agents & Automation Engineer**

I build agentic AI systems, LLM applications and ML pipelines, with a focus on tool-using agents, retrieval, computer vision and production-grade APIs, on top of a strong foundation in core computer science: C/C++, data structures & algorithms, operating systems and system design.

**Core strengths:** `Agentic AI` · `LLMs & RAG` · `Computer Vision` · `System Design` · `Data Structures & Algorithms` · `C / C++` · `Operating Systems`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-raman--kumar--kheti-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/raman-kumar-kheti)
[![Portfolio](https://img.shields.io/badge/Portfolio-ramankumarkheti.com-1f2937)](https://www.ramankumarkheti.com/)
[![Email](https://img.shields.io/badge/Email-ramank.kheti@gmail.com-D14836?logo=gmail&logoColor=white)](mailto:ramank.kheti@gmail.com)

📍 Bhubaneswar, India

---

## 🚀 AI & ML Projects

### 🧠 [NexusResearch AI](https://github.com/raman-kumar-kheti/nexus-research-ai): Multi-Agent Research Platform
A stateful **6-agent LangGraph workflow** (planner → parallel web search → extractor → analyst → critic / fact-checker → human approval → reporter) that produces research reports with verified-only citations.
- **MCP** server and client for tool integration, with **human-in-the-loop** approval before reports are finalized
- Execution guardrails: bounded retries, token and cost budgets, per-agent latency tracing, loop limits
- Fact-vs-interpretation separation, an agent evaluation framework, PDF / Markdown export, and CI with GitHub Actions

`LangGraph` `LangChain` `MCP` `FastAPI` `Streamlit` `PostgreSQL` `Docker`

### 📚 [KnowMatrix AI](https://github.com/raman-kumar-kheti/knowmatrix-ai): Document Intelligence & RAG
A retrieval-augmented generation platform that answers questions over PDFs with **page-level source citations**.
- **Hybrid retrieval** (FAISS semantic search + BM25) with reranking
- Document-level access control (`public` / `internal` / `admin`) and session-based conversational memory
- Pluggable LLM providers (HuggingFace, Ollama, OpenAI-compatible) with **SSE streaming**
- RAG evaluation: faithfulness, context precision, hallucination-risk scoring and insufficient-evidence refusal

`Python` `FastAPI` `FAISS` `sentence-transformers` `LangChain` `React` `Docker`

### 📸 [Gallery](https://github.com/raman-kumar-kheti/gallery): AI Event Photo Delivery SaaS
Guests scan a QR code, upload a selfie, and instantly find all their photos using **AI face recognition**.
- Async AI pipeline: upload → Celery task → **InsightFace** embedding → per-event **FAISS** index → similarity search
- Multi-tenant model for studios, photographers and customers, with team RBAC, Google OAuth + JWT and Razorpay payments
- Fully containerised with Docker Compose

`Python` `FastAPI` `InsightFace` `FAISS` `Celery` `Redis` `PostgreSQL` `Next.js`

### 🏭 [VisionGuard AI](https://github.com/raman-kumar-kheti/visionguard-ai): Industrial Defect Detection
A visual inspection platform built on **PatchCore (ResNet18)** with pixel-level defect localization.
- k-center greedy coreset subsampling, calibrated anomaly thresholds, and defect severity classification (`OK` → `CRITICAL`)
- **ONNX + OpenVINO** export, with CPU inference benchmarked at about 51 ms per image
- FastAPI inspection service with SQLite history, a Streamlit dashboard and a Pytest suite

`PyTorch` `OpenVINO` `FastAPI` `Streamlit` `Docker`

### 📈 [PredictFlow ML](https://github.com/raman-kumar-kheti/predictflow-ml): Churn Prediction & MLOps
An end-to-end machine learning pipeline for customer churn, from data validation to monitored serving.
- Feature engineering, class-imbalance handling (SMOTE) and model comparison across Logistic Regression, Random Forest and Gradient Boosting
- **MLflow** experiment tracking and Model Registry with automated best-model selection
- FastAPI prediction service with risk tiers, **PSI + KS drift monitoring**, Streamlit dashboard and CI

`Scikit-learn` `MLflow` `FastAPI` `Streamlit` `Docker` `GitHub Actions`

---

## 🧰 Tech Stack

| | |
|---|---|
| **Agentic AI & LLMs** | Anthropic Claude Agent SDK, Claude API, MCP, LangGraph, LangChain, RAG, Hybrid Search (FAISS + BM25), Hugging Face Transformers, Sentence-Transformers, Ollama, Prompt Engineering, Claude Code, Gemini CLI |
| **ML & Computer Vision** | PyTorch, Scikit-learn, MLflow, InsightFace, FaceNet, FAISS, Keras, TensorFlow, OpenVINO, ONNX, Matplotlib, Seaborn |
| **Backend** | Python (FastAPI, asyncio, Pydantic, SQLAlchemy, Celery), Pandas & NumPy, Node.js, REST APIs, Microservices, JWT / OAuth 2.0 / RBAC, PostgreSQL, SQL Server, Redis, Streamlit |
| **Core CS** | C, C++, Data Structures & Algorithms, Operating Systems, System Design, Multithreading |
| **Frontend & Mobile** | React, Next.js, Angular, React Native, TypeScript |
| **DevOps** | Docker, GitHub Actions, CI/CD, AWS (EC2, Lambda), Linux, Git, Pytest, Postman |

---

## 🧱 Core Computer Science

Good AI engineering sits on solid fundamentals, and I enjoy working close to the machine as much as at the model layer.

- **C / C++ and systems programming:** low-level and embedded work, including autonomous vehicle and robotics code in [C++](https://github.com/raman-kumar-kheti/Autonomous-Guided-Vehicle-Material)
- **Operating systems:** Linux internals, processes and threads, concurrency and PAM authentication, applied in my own Debian-based OS, [RS-OS](https://github.com/raman-kumar-kheti/RS-OS)
- **Data structures & algorithms:** problem solving, complexity analysis, and choosing the right structure for the workload (for example indexing and similarity search in my FAISS-based projects)
- **System design:** scalable and fault-tolerant architectures, API design, async and queue-based pipelines, caching and database design

---

<details>
<summary><b>🛠️ More Projects</b></summary>

<br>

- **[Docklly](https://github.com/raman-kumar-kheti/Docklly)**: AI-powered legal document management (C#, ASP.NET Core 8)
- **[FreeMailo](https://github.com/raman-kumar-kheti/freemailo)**: self-hosted multi-domain email (Postfix, Dovecot, Rspamd, NestJS, Next.js)
- **[RS-OS](https://github.com/raman-kumar-kheti/RS-OS)**: custom Debian-based Linux OS with PAM authentication and a PyQt desktop (Python)
- **[Smart-Home](https://github.com/raman-kumar-kheti/Smart-Home)**: IoT automation with a React Native app and ESP8266 firmware over MQTT
- **[Color-Minds](https://github.com/raman-kumar-kheti/Color-Minds)**: Android color-guessing game (React Native)
- **[Whiteboard](https://github.com/raman-kumar-kheti/Whiteboard)**: canvas drawing app in vanilla JavaScript · [Live demo](https://whiteboard-mauve-one.vercel.app)
- **[Autonomous-Guided-Vehicle-Material](https://github.com/raman-kumar-kheti/Autonomous-Guided-Vehicle-Material)**: autonomous vehicle and robotics code (C++)

</details>

---

## 🤝 Let's Connect

Open to conversations about **agentic AI, LLM applications, RAG, ML engineering and systems design**.

📧 [ramank.kheti@gmail.com](mailto:ramank.kheti@gmail.com) · 💼 [LinkedIn](https://linkedin.com/in/raman-kumar-kheti) · 🌐 [ramankumarkheti.com](https://www.ramankumarkheti.com/)
