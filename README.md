# Hi, I'm Alex Picard 👋

I build and operate production ML systems end to end: training, serving, drift detection, and automated retraining. Currently an ML Data Associate II at Amazon, based in Boston, and completing an MS in Software Development at Boston University (2027). I love building things at the intersection of machine learning and full-stack engineering.

---

## 🛠️ Tech Stack

Languages: Python · TypeScript · JavaScript · Java · C/C++

Frameworks & Libraries: React · FastAPI · Spring Boot · Node.js/Express · Flask · PyTorch · TensorFlow

Data & Infrastructure: PostgreSQL · pgvector · Redis · MongoDB · SQLite · Docker · AWS · Git

AI / ML: Retrieval-augmented generation (RAG) · vector search (HNSW) · ONNX Runtime · LightGBM · LLM evaluation · PINNs
---

## 💼 What I'm Up To

- 🤖 Working as an **ML Data Associate II at Amazon**, engineering high-quality training datasets for LLMs across classification, ranking, and adversarial testing tasks
- ⚾ Building and operating The Bullpen in production
- 🎓 Pursuing my **MS in Software Development at Boston University** (2025–2027)
- 🔬 Previously a **ML Research Assistant** at UMaine's Advanced Structures and Composite Center, building multi-fidelity Physics-Informed Neural Networks in PyTorch

---

## 🚀 Featured Projects

### [The Bullpen](https://thebullpen.net)
Self-hosted baseball analytics platform serving four ML models (LightGBM pitch heads, 30-park multi-head MLP) from a Java 21 / Spring Boot API with in-process ONNX Runtime: p99 34 ms at a verified 300 req/s. Custom ML systems layer built without MLflow: versioned model registry with feature-schema-hash enforcement, shadow A/B routing, PSI and calibration drift detection, and a human-gated retraining queue proven end-to-end (unattended retrain on ~1.2M batted balls in 96.8 minutes, cutting per-park calibration error 10×). Operated with 2,400+ tests, CI-enforced temporal-leakage and ONNX parity checks, 28 Prometheus alerts, and drilled 25-minute restores.

### [StudyForesight](https://studyforesight.com)
Production RAG study platform (FastAPI/Python, React 19/TypeScript, Postgres + pgvector): an LLM tutor that answers only from the user's own uploads (PDFs, image OCR, Whisper audio, Word docs), with every answer citing its source passages. Two-stage retrieval (pgvector HNSW search, then MMR reranking) fronted by a Redis semantic cache; fault-tolerant ingestion via dual paths (FastAPI background tasks plus a durable QStash queue) made idempotent with Redis SETNX; Postgres row-level security, per-provider circuit breakers, sliding-window rate limiting, and prompt-injection hardening. ~1,284 tests at 87% coverage.

### [Multi-Fidelity PINN](https://github.com/Alexm-picard/ECE471-Final-Project)
Dual-network physics-informed neural network architecture in PyTorch, combining low-fidelity analytical models with high-fidelity experimental data to predict concrete compressive strength.

### [Cloud Microservices To-Do App](https://github.com/Alexm-picard/COS-442-Cloud-Computing-Final-Project)
Distributed microservices application: four Flask services behind an Nginx reverse proxy with three Redis instances, orchestrated with Docker Compose and deployed on AWS EC2. Built as the final project for COS 442 (Cloud Computing) at UMaine.

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alexpicard0/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://alexpicard.info)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:am.picard03@gmail.com)
