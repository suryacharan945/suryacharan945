# Surya Charan Pallekala

**AI/ML Engineer in Development | Python, Machine Learning, Deep Learning, NLP, Computer Vision, LLMs, RAG and Full-Stack Applications**  
Hyderabad, India • [LinkedIn](https://linkedin.com/in/suryacharan945) • [GitHub](https://github.com/suryacharan945)

I build applied AI/ML systems, computer vision inspection pipelines, LLM-driven developer tools, and robust Android and web applications. My focus is on writing clean, reproducible, and well-tested code that bridges machine learning models with real-world software engineering.

---

## 🛠️ Technical Competencies

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | Python, Kotlin, TypeScript, JavaScript, SQL (PostgreSQL, PL/pgSQL), HTML5, CSS3 |
| **Machine Learning & Deep Learning** | PyTorch, Hugging Face Transformers, LightGBM, scikit-learn, OpenCV, Faiss, SHAP, Prophet, LSTM |
| **LLMs, NLP & AI Systems** | Local GGUF LLM Runtime (`llama-cpp-python`, Qwen 2.5), Google Gemini API, Text Classification (DistilBERT) |
| **Mobile & Android** | Kotlin 2.2, Jetpack Compose, Material 3, Clean Architecture, Room SQLite, Robolectric, Coroutines / StateFlow |
| **Backend & Web** | FastAPI, Node.js, Express.js, Supabase (Row-Level Security), RESTful APIs, React 19, Vite, Tailwind CSS, Streamlit |
| **DevOps & Testing** | Git, GitHub Actions (CI/CD), Docker, Gradle (Kotlin DSL), Pytest, Unit Testing, Linux / Shell |

---

## 🌟 Featured Engineering Projects

### 1. [SpendWise](https://github.com/suryacharan945/SpendWise)
> **Android personal finance platform engineered with Jetpack Compose, Clean Architecture, and on-device behavioral heuristics.**
* **Stack:** Kotlin 2.2.21, Jetpack Compose, Material 3, Room SQLite, Gradle 9.3, Robolectric.
* **Engineering Highlights:**
  * Implemented an unboxed `@JvmInline value class Money(val paise: Long)` sub-unit currency engine, completely eliminating IEEE 754 floating-point rounding drift with zero heap object allocation.
  * Designed deterministic conflict resolution algorithms with Last-Write-Wins (LWW) monotonic `syncVersion` tie-breaking and soft-delete tombstones.
  * Built an on-device behavioral analysis engine featuring a 14-day Weighted Moving Average (WMA) spend predictor and statistical Z-Score anomaly detector.
  * Established 100% test coverage with **93 automated unit tests** across 19 suites and passing GitHub Actions CI.
* **Links:** [Repository](https://github.com/suryacharan945/SpendWise) • [CI Status](https://github.com/suryacharan945/SpendWise/actions)

---

### 2. [GhostTerminal AI](https://github.com/suryacharan945/ghostterminal-ai)
> **Interactive local AI terminal emulator bridging local GGUF models with shell execution and safety guardrails.**
* **Stack:** FastAPI, React, TypeScript, llama-cpp-python, Qwen 2.5 (0.5B GGUF), Pytest, GitHub Actions.
* **Engineering Highlights:**
  * Implemented an asynchronous client-server architecture serving local LLM inference on-device using `llama-cpp-python`.
  * Built pre-execution safety inspection logic intercepting potentially dangerous shell commands before execution.
  * Automated testing via GitHub Actions covering backend pytest suites and frontend TypeScript builds.
* **Links:** [Repository](https://github.com/suryacharan945/ghostterminal-ai) • [CI Status](https://github.com/suryacharan945/ghostterminal-ai/actions)

---

### 3. [SkillSpot 2.0](https://github.com/suryacharan945/skillspot)
> **Multi-tenant web platform connecting vocational NGOs with learners for verified training programs.**
* **Stack:** React 19, TypeScript, Vite, Tailwind CSS, Supabase, PostgreSQL, Row-Level Security (RLS).
* **Engineering Highlights:**
  * Designed a multi-tenant relational schema (`schema.sql`) with PostgreSQL Row-Level Security (RLS) separating NGO administrative data from learner registries.
  * Integrated Supabase authentication and session guards with automated client fallback to local seed data for offline resilience.
  * Deployed responsive web application on Vercel with automated GitHub Actions CI integrity testing.
* **Links:** [Repository](https://github.com/suryacharan945/skillspot) • [Live Demo](https://skillspot-eight.vercel.app/) • [CI Status](https://github.com/suryacharan945/skillspot/actions)

---

### 4. [DefectVision AI](https://github.com/suryacharan945/DefectVision-AI)
> **Autonomous 3D optical industrial inspection platform using PatchCore, PaDiM, and EfficientNet.**
* **Stack:** PyTorch, Fastify, React, OpenCV, Faiss, EfficientNet-B0 v3, PatchCore, PaDiM.
* **Engineering Highlights:**
  * Evaluated unsupervised surface defect detection pipelines across 856 industrial images on the MVTec AD benchmark (EfficientNet-B0 Mean AUROC: 0.9732, PatchCore Mean AUROC: 0.9651, PaDiM Mean AUROC: 0.8911).
  * Implemented memory-bank embedding compression using Faiss k-NN vector search alongside PaDiM multivariate Gaussian modeling.
  * Deployed interactive web inspector and analytics dashboard on Vercel with automated CI verification.
* **Links:** [Repository](https://github.com/suryacharan945/DefectVision-AI) • [Live Demo](https://defectvision-ai.vercel.app/) • [CI Status](https://github.com/suryacharan945/DefectVision-AI/actions)

---

### 5. [MerchantGuard AI](https://github.com/suryacharan945/MerchantGuardAI)
> **Financial transaction fraud detection engine using gradient boosting, Platt scaling, and explainable AI.**
* **Stack:** Python, LightGBM, Streamlit, Scikit-learn, SHAP (TreeExplainer), Google Gemini API, FAISS.
* **Engineering Highlights:**
  * Developed an ensemble detection pipeline combining LightGBM gradient boosting with Platt scaling probability calibration to handle extreme transaction class imbalance.
  * Integrated SHAP TreeExplainer local attribution alongside FAISS policy retrieval and Gemini natural language fraud incident reporting.
  * Constructed interactive Streamlit dashboard with persistent SQLite decision audit logging and automated CI pipeline tests.
* **Links:** [Repository](https://github.com/suryacharan945/MerchantGuardAI) • [Live Demo](https://merchantguardai.streamlit.app/) • [CI Status](https://github.com/suryacharan945/MerchantGuardAI/actions)

---

### 6. [AI-Powered Fake News Detector](https://github.com/suryacharan945/fake-news-detector)
> **NLP classification pipeline fine-tuning DistilBERT for online misinformation detection.**
* **Stack:** PyTorch, Hugging Face Transformers, DistilBERT, Gradio, Python.
* **Engineering Highlights:**
  * Fine-tuned `distilbert-base-uncased` for binary sequence classification (`FAKE` vs `REAL`), hosted publicly on Hugging Face Model Hub.
  * Built an interactive Gradio web demonstration supporting single-article evaluation with softmax label confidences and batch CSV processing.
  * Automated testing and validation via GitHub Actions CI pipeline.
* **Links:** [Repository](https://github.com/suryacharan945/fake-news-detector) • [Model Hub](https://huggingface.co/suryacharan945/fake-news-detector) • [CI Status](https://github.com/suryacharan945/fake-news-detector/actions)

---

## 🔬 Hackathons & Open Source Contributions

* **Hacktoberfest 2026:** Created and open-sourced [GhostTerminal AI](https://github.com/suryacharan945/ghostterminal-ai), building a full-stack terminal application with automated CI testing and local GGUF LLM execution.
* **DeepLearn Hackathon Series:** Participated in competitive machine learning challenges spanning NLP historical document extraction, gravitational lensing detection, and scientific ML tracks ([DeepLearnHackathon](https://github.com/suryacharan945/DeepLearnHackathon)).

---

## 📬 Contact & Professional Links

* **GitHub:** [@suryacharan945](https://github.com/suryacharan945)
* **LinkedIn:** [linkedin.com/in/suryacharan945](https://linkedin.com/in/suryacharan945)
