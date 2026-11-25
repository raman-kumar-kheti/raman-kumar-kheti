# Raman Kumar Kheti

**Python Developer · AI Engineer · Agents & Automation Engineer**

Agentic AI · Claude Agent SDK · MCP · GenAI · LLMs · FastAPI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-raman--kumar--kheti-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/raman-kumar-kheti)
[![Portfolio](https://img.shields.io/badge/Portfolio-ramankumarkheti.com-1f2937)](https://www.ramankumarkheti.com/)
[![Email](https://img.shields.io/badge/Email-ramank.kheti@gmail.com-D14836?logo=gmail&logoColor=white)](mailto:ramank.kheti@gmail.com)

📍 Bhubaneswar, India · 💼 Software Developer, AI Agents & Full Stack at **HyScaler (NetTantra Technologies)**

---

## About

Software engineer with 3+ years of experience building and shipping **agentic AI and LLM-based systems** on the **Anthropic Claude Agent SDK** for a live fintech and legal-intelligence platform. I design agent harnesses, MCP servers and custom tools, and turn manual business processes into autonomous agent workflows, backed by Python (FastAPI), Node.js and PostgreSQL / SQL Server. I also lead engineering teams and work directly with senior leadership on technical direction.

---

## 🤖 AI Engineering: Production Work

| Project | What I built | Impact |
|---|---|---|
| **Hyally Merqube: Contract Automation** (Legal Intelligence Platform, live) | Owned the AI agent layer end to end on the Claude Agent SDK for contract drafting, gap analysis and amendment creation. Built the agent harness (session and context handling, tool permissions, response streaming, error recovery) plus custom tools and MCP servers for controlled access to contract, client and clause data. Added an application-wide AI chat assistant for instant client and contract search. | **~90%** of a manual contract creation process automated; API latency cut by **~80%** |
| **Merqube Index Automation** (browser-based AI assistant) | Built an assistant that connects to email, historical data (via MCP) and previous index calculations, then creates new indices through the browser JS API. It fills forms and makes decisions autonomously, with output validation so every index stays consistent and reviewable. | **~80%** less manual index-creation work |
| **GMI Checking: Face Recognition Attendance Platform** (live product) | Led the team and designed a Node.js backend with a separate Python (FastAPI) microservice for real-time face recognition, built on a custom neural-network model and FaceNet embeddings. Used from both an Angular web app and an iOS app, with registration and verification APIs that drive automated monthly work-hour reports. | **95%** recognition accuracy |

> These are proprietary company products, so the code is private.

---

## 🌟 Featured Open-Source AI Project

### [Gallery: AI-Powered Event Photo Delivery SaaS](https://github.com/raman-kumar-kheti/gallery)

Guests scan a QR code, upload a selfie, and instantly find all their photos using AI face recognition.

**How the AI pipeline works**

- **Upload:** photo stored in Cloudflare R2 → Celery task queued → InsightFace generates a face embedding → embedding added to the event's FAISS index → thumbnail generated
- **Guest search:** selfie upload → query embedding (InsightFace) → FAISS similarity search on the event's index → matching photos returned, with the session cached to avoid reprocessing

**Highlights**

- One FAISS index per event, mapped to PostgreSQL rows and persisted across restarts
- Async AI worker (Celery + Redis) separated from the API for scalable processing
- Multi-tenant model for studios, photographers and customers, with team RBAC, Google OAuth + JWT and Razorpay payments
- Fully containerised with Docker Compose

**Stack:** Python · FastAPI · InsightFace · FAISS · Celery · Redis · PostgreSQL · Next.js 14 · TypeScript · Docker

### [Docklly: AI-Powered Legal Document Management](https://github.com/raman-kumar-kheti/Docklly)

An AI-powered platform for legal document creation, management, compliance checking and secure storage.

**Stack:** C# · ASP.NET Core 8 · SQL Server

---

## 🧰 Tech Stack

| | |
|---|---|
| **Agentic AI & GenAI** | Anthropic Claude Agent SDK, Claude API, MCP Servers, Agent Harness Design, Context Management, Tool Design, Prompt Engineering & Output Validation, Agentic Workflow Automation, Claude Code, Gemini CLI |
| **Computer Vision** | InsightFace, FaceNet, FAISS, Face Recognition Pipelines |
| **Backend** | Python (FastAPI, asyncio), Node.js (Express), REST APIs, Microservices, JWT, OAuth 2.0, RBAC |
| **Data** | PostgreSQL, SQL Server, Redis, Query Optimization |
| **Cloud & DevOps** | AWS (EC2, Lambda), Docker, CI/CD, Git, Linux |
| **Frontend & Mobile** | Next.js, Angular, React, React Native |

---

<details>
<summary><b>🛠️ Other Projects</b></summary>

<br>

- **[RS-OS](https://github.com/raman-kumar-kheti/RS-OS)**: custom Debian-based Linux OS with PAM authentication and a PyQt desktop interface (Python)
- **[Smart-Home](https://github.com/raman-kumar-kheti/Smart-Home)**: IoT home automation with a React Native app and ESP8266 firmware over MQTT
- **[Color-Minds](https://github.com/raman-kumar-kheti/Color-Minds)**: Android color-guessing game built with React Native CLI
- **[Whiteboard](https://github.com/raman-kumar-kheti/Whiteboard)**: canvas drawing app in vanilla JavaScript · [Live demo](https://whiteboard-mauve-one.vercel.app)
- **[Autonomous-Guided-Vehicle-Material](https://github.com/raman-kumar-kheti/Autonomous-Guided-Vehicle-Material)**: autonomous vehicle and robotics code in C++

</details>

---

## 🤝 Let's Connect

I'm open to conversations about **agentic AI, MCP and LLM-powered automation, and computer-vision products**.

📧 [ramank.kheti@gmail.com](mailto:ramank.kheti@gmail.com) · 💼 [LinkedIn](https://linkedin.com/in/raman-kumar-kheti) · 🌐 [ramankumarkheti.com](https://www.ramankumarkheti.com/)
