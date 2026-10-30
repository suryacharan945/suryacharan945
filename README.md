# Surya Charan Pallekala

**AI/ML Engineer in Development | Python, Machine Learning, Deep Learning, NLP, Computer Vision, LLMs, RAG and Full-Stack Applications**  
Hyderabad, India • [LinkedIn](https://linkedin.com/in/suryacharan945) • [GitHub](https://github.com/suryacharan945)

I build applied AI/ML systems, computer vision inspection pipelines, LLM-driven developer tools, and robust Android and web applications. My focus is on writing clean, reproducible, and well-tested code that bridges machine learning models with real-world software engineering.

---

## 🛠️ Technical Competencies

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | Python, Kotlin, TypeScript, JavaScript, SQL (PostgreSQL, PL/pgSQL), HTML5, CSS3 |
| **Machine Learning & Deep Learning** | PyTorch, Hugging Face Transformers, LightGBM, XGBoost, scikit-learn, OpenCV, Faiss, Prophet, LSTM |
| **LLMs, NLP & Agentic AI** | Local LLM Integration (Ollama), Prompt Engineering, WebSockets Streaming, Text Classification (DistilBERT) |
| **Mobile & Android** | Kotlin 2.2, Jetpack Compose, Material 3, Clean Architecture, Room SQLite, SQLCipher, Google Tink AEAD, Robolectric |
| **Backend & Web** | FastAPI, Node.js, Express.js, Supabase (Row-Level Security), RESTful APIs, React 18, Vite, Tailwind CSS |
| **DevOps & Testing** | Git, GitHub Actions (CI/CD), Docker, Gradle (Kotlin DSL), Pytest, Unit Testing, Linux / Shell |

---

## 🌟 Featured Engineering Projects

### 1. [SpendWise](https://github.com/suryacharan945/SpendWise)
> **Android personal finance platform engineered with Jetpack Compose, Clean Architecture, and on-device behavioral AI.**
* **Stack:** Kotlin 2.2.21, Jetpack Compose, Material 3, Room SQLite, SQLCipher (256-bit AES), Google Tink AEAD, Gradle 9.3.
* **Engineering Highlights:**
  * Implemented an unboxed `@JvmInline value class Money(val paise: Long)` sub-unit currency engine, completely eliminating IEEE 754 floating-point rounding drift with zero heap object allocation.
  * Designed an offline-first distributed sync engine with Last-Write-Wins (LWW) monotonic `syncVersion` tie-breaking and soft-delete tombstones.
  * Built an on-device behavioral AI engine featuring a 4-week Weighted Moving Average (WMA) spend predictor, Z-Score anomaly detector, and multi-lingual voice expense parser.
  * Established 100% test coverage with **93 automated unit tests** across 19 suites and passing GitHub Actions CI.
* **Links:** [Repository](https://github.com/suryacharan945/SpendWise) • [CI Status](https://github.com/suryacharan945/SpendWise/actions)

---

### 2. [GhostTerminal AI](https://github.com/suryacharan945/ghostterminal-ai)
> **Interactive local AI terminal emulator featuring dual-agent orchestration and low-latency WebSocket streaming.**
* **Stack:** FastAPI, React, TypeScript, Ollama (Local LLM), WebSockets, Pytest, GitHub Actions.
* **Engineering Highlights:**
  * Implemented an asynchronous client-server architecture capturing and streaming terminal sessions with low-latency WebSockets.
  * Built custom command interception logic enabling local LLM agents to provide contextual CLI assistance and debugging without third-party cloud dependencies.
  * Established automated CI via GitHub Actions covering backend pytest suites and frontend TypeScript builds.
* **Links:** [Repository](https://github.com/suryacharan945/ghostterminal-ai) • [CI Status](https://github.com/suryacharan945/ghostterminal-ai/actions)

---

### 3. [SkillSpot 2.0](https://github.com/suryacharan945/skillspot)
> **Multi-tenant web platform connecting vocational NGOs with learners for verified training programs.**
* **Stack:** React 18, TypeScript, Vite, Tailwind CSS, Supabase, PostgreSQL, Row-Level Security (RLS).
* **Engineering Highlights:**
  * Designed a multi-tenant relational schema with PostgreSQL Row-Level Security (RLS) separating NGO administrative data from public learner registries.
  * Integrated Supabase OAuth and session guards, supporting role-based access control (RBAC) across learners, organizers, and super-admins.
  * Deployed responsive web application on Vercel with client-side routing and clean state management.
* **Links:** [Repository](https://github.com/suryacharan945/skillspot) • [Live Demo](https://skillspot-omega.vercel.app/)

---

### 4. [DefectVision AI](https://github.com/suryacharan945/DefectVision-AI)
> **Autonomous 3D optical industrial inspection platform using PatchCore, PaDiM, and EfficientNet.**
* **Stack:** PyTorch, Fastify, React, OpenCV, Faiss, EfficientNet-B0 v3, NumPy.
* **Engineering Highlights:**
  * Engineered an unsupervised anomaly detection and localization pipeline for manufacturing quality inspection on high-resolution industrial surfaces (MVTec AD).
  * Implemented memory-bank embedding compression using Faiss k-NN vector search alongside PaDiM multivariate Gaussian distribution modeling.
  * Evaluated localized defect heatmaps using ROC-AUC and pixel-level anomaly scoring for production inspection monitoring.
* **Links:** [Repository](https://github.com/suryacharan945/DefectVision-AI)

---

### 5. [MerchantGuard AI](https://github.com/suryacharan945/MerchantGuardAI)
> **Financial transaction fraud detection engine using gradient boosting with explainable AI (XAI).**
* **Stack:** Python, LightGBM, XGBoost, Streamlit, Scikit-learn, Google Gemini API.
* **Engineering Highlights:**
  * Developed an ensemble gradient boosting classifier tuned for severe transaction class imbalance (precision-recall threshold optimization).
  * Constructed interactive dashboards delivering merchant fraud risk scoring with low-latency inference.
  * Integrated an explainable AI reasoning layer to transform feature importances into clear fraud narrative justifications.
* **Links:** [Repository](https://github.com/suryacharan945/MerchantGuardAI)

---

### 6. [AI-Powered Fake News Detector](https://github.com/suryacharan945/fake-news-detector)
> **NLP classification pipeline fine-tuning DistilBERT for online misinformation detection.**
* **Stack:** PyTorch, Hugging Face Transformers, DistilBERT, Gradio, Python.
* **Engineering Highlights:**
  * Fine-tuned a lightweight Transformer architecture (DistilBERT) for binary sequence classification, balancing inference speed with high classification accuracy.
  * Built modular training (`train.py`) and inference (`inference.py`) pipelines with an interactive Gradio web demonstration.
* **Links:** [Repository](https://github.com/suryacharan945/fake-news-detector)

---

## 🔬 Hackathons & Open Source Contributions

* **Hacktoberfest 2026:** Created and open-sourced [GhostTerminal AI](https://github.com/suryacharan945/ghostterminal-ai), building a full-stack terminal application with automated CI testing and dual-agent local LLM execution.
* **DeepLearn Hackathon Series:** Participated in competitive machine learning challenges spanning NLP Renaissance historical document extraction, gravitational lensing detection, and scientific ML tracks ([DeepLearnHackathon](https://github.com/suryacharan945/DeepLearnHackathon)).

---

## 📬 Contact & Professional Links

* **GitHub:** [@suryacharan945](https://github.com/suryacharan945)
* **LinkedIn:** [linkedin.com/in/suryacharan945](https://linkedin.com/in/suryacharan945)
