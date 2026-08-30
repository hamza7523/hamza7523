# Hi, I'm Hamza Zaman👋

AI/ML Engineer building agentic systems, RAG pipelines, and production ML infrastructure. BS Computer Science at IBA Karachi (2022–2026). My background started in data analytics and business intelligence, which now grounds how I build and evaluate AI systems in production.

- 🔭 Currently building agentic AI and voice-based systems (LangGraph, RAG, LLM inference optimization)
- 🌱 Deepening my focus on LLM inference internals, GPU/HPC compute
- 📄 Co-author, **FedAdaPriv-CPU** — presented at the AI4X Accelerate Conference, National University of Singapore (2026)
- 🎓 BS Computer Science 
- 🌍 Open to AI Engineer / MLOps / Data Engineering roles across Pakistan, the Gulf, and remote
- 📫 hamzazaman7523@gmail.com · [LinkedIn](https://linkedin.com/in/hamza-zaman7523)

---

## 🤖 Agentic AI & RAG Systems

**[Financial-Agent-Jarvis](https://github.com/hamza7523)** — Agentic voice financial assistant
Built from scratch to understand agent memory mechanics before adopting LangGraph. Integrates Whisper (STT) and Kokoro TTS over a provider-agnostic LLM backend for hands-free financial Q&A. Implements episodic memory allocation across turns and a test harness validating tool-call accuracy and node transitions, instrumented with LangSmith for trace-level observability.
`LangGraph` `Whisper` `Kokoro TTS` `LangSmith` `Context Engineering`

**Qur'an Chat App** — Hallucination-resistant RAG assistant
React Native + Supabase app with retrieval grounding designed to minimize hallucinated religious content.
`RAG` `React Native` `Supabase`

**CareCloud Voice Agent** — Live voice agent technical challenge
End-to-end voice agent built and deployed under time constraints for a technical assessment.
`VAPI` `Groq` `FastAPI` `Railway`

---

## ⚙️ MLOps & Production ML

**[Fluora Care](https://github.com/hamza7523)** — Production MLOps & AI system for plant disease detection
Swin Transformer model (38 classes) optimized with ONNX and deployed on Azure via FastAPI, achieving sub-second CPU inference. Hybrid BM25 + ChromaDB retrieval with confidence thresholding to suppress low-grounding outputs, monitored with Prometheus, Grafana, and Evidently AI for drift detection.
`PyTorch` `FastAPI` `Azure` `MLflow` `Prometheus` `Grafana` `ChromaDB`

**ChatOps DevOps Bot** — Slack-native infrastructure automation
RBAC-enforced command routing and a Prometheus metrics endpoint, deployed via a full Kubernetes manifest stack. Lets on-call engineers trigger deployments and check pod health directly from Slack.
`Python` `Kubernetes` `Prometheus` `Docker` `GitHub Actions`

**PPE Detection** — Real-time compliance detection
YOLOv11 model trained on Roboflow datasets, with iterative false-positive debugging for real-world reliability.
`YOLOv11` `Computer Vision` `Roboflow`

---

## 📊 Data Engineering & Analytics

**Cloud Data Warehouse** — Hackfest 2025 Winner
End-to-end ETL pipeline for 2,400+ transactions using Airflow DAGs with idempotent task design. Star schema models in BigQuery with partitioning and clustering, cutting query costs by 40%. Looker Studio dashboards for non-technical stakeholders.
`Python` `Apache Airflow` `BigQuery` `Looker Studio`

**Aura Fashion** — Supply chain and inventory analytics pipeline
Kafka stream processing 1,000+ IoT events/hour for real-time inventory alerts, plus ingestion policies cleaning 40,000+ records across 5 sources. Automated hourly audits reduced data discrepancies by 95%.
`AWS Lambda` `Kafka` `Apache Airflow` `Azure Blob Storage`

**Gallstone Predictive Analytics** — Cloud batch inference pipeline
Scheduled ETL on Azure Databricks ingesting clinical data every 5 hours with SLA monitoring, surfacing predictions on a BI dashboard for clinical stakeholders.
`Azure Databricks` `Azure Data Lake` `ETL`

**BriefAI** — Serverless AI proposal generator
S3 upload triggers a Lambda orchestrator routing to a FastAPI/EC2 inference backend, with structured output parsing and schema validation, writing a scoped proposal to S3 in under 30 seconds.
`AWS Lambda` `S3` `FastAPI` `EC2`

---

## 🔬 Research

**FedAdaPriv-CPU** — Adaptive differential privacy for federated medical imaging
A responsible AI framework preventing client data leakage across 3 simulated hospital clients with no GPU dependency. Three-signal adaptive per-client epsilon allocation, validated through ablation studies, reduced training time at equal privacy budget (ε = 3.0) versus static-allocation baselines. Presented at AI4X Accelerate, NUS Singapore.
`Federated Learning` `Differential Privacy` `PyTorch`

---

## 🎥 Demo

<!--
To embed your Loom video download:
1. Open a new issue or PR comment box on any of your repos (or this profile repo).
2. Drag and drop the downloaded video file into the comment box.
3. GitHub uploads it and generates a URL like https://github.com/user-attachments/assets/xxxxxxxx
4. Copy that URL and paste it below in place of the placeholder link, or wrap it in an HTML <video> tag:
   <video src="PASTE_URL_HERE" controls width="600"></video>
5. Delete this comment block once the video is embedded.
-->

Video Overview: **[https://www.loom.com/share/70bbdfa84f2c43599a8bf6a4c766456a](#)**

---

## 🛠️ Tech Stack

**AI/ML:** ![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white)

**MLOps:** ![MLflow](https://img.shields.io/badge/-MLflow-0194E2?logo=mlflow&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?logo=kubernetes&logoColor=white) ![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/-Grafana-F46800?logo=grafana&logoColor=white)

**Cloud & Data:** ![AWS](https://img.shields.io/badge/-AWS-232F3E?logo=amazonaws&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0078D4?logo=microsoftazure&logoColor=white) ![Kafka](https://img.shields.io/badge/-Kafka-231F20?logo=apachekafka&logoColor=white) ![Airflow](https://img.shields.io/badge/-Airflow-017CEE?logo=apacheairflow&logoColor=white) ![BigQuery](https://img.shields.io/badge/-BigQuery-4285F4?logo=googlebigquery&logoColor=white)

**Languages:** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?logo=postgresql&logoColor=white)

---

📫 hamzazaman7523@gmail.com · [github.com/hamza7523](https://github.com/hamza7523) · [linkedin.com/in/hamza-zaman7523](https://linkedin.com/in/hamza-zaman7523)
