
<div align="center">

# Hi, I'm Chi Khoa (Kelvin) Do 👋

### AI/ML & Software Engineering

**Bachelor of Computer Science, Major in Data Science — Concordia University 🇨🇦**  
**Expected graduation: May 2028**

**🎯 Open to 2027 AI/ML, Applied AI, and Software Engineering internships**

[LinkedIn](https://www.linkedin.com/in/chikhoado/) · [Email](mailto:dochikhoa2006@gmail.com)

</div>

---

## 👨‍💻 About Me

I'm a **Computer Science undergraduate at Concordia University**, specializing in **Data Science** and interested in **AI/ML engineering, LLM systems, agentic workflows, retrieval-augmented generation, and backend software development**. Through two internships and hands-on projects, I've worked on **data preparation, model training, hybrid retrieval, AI orchestration, performance evaluation, inference optimization, and deployment**.

I enjoy building **end-to-end systems that people can actually use**, with an emphasis on **reliability, measurable performance, and production-minded engineering**.

### ⚡ Impact at a Glance

| **~4s P95** | **20+** | **200+** | **~0.7s P95** |
|:---:|:---:|:---:|:---:|
| Multi-agent CRM assistant<br>30+ concurrent sessions | Reusable Langflow<br>workflow nodes | Clients included in<br>A/B experiments | Recommendation serving<br>50+ concurrent sessions |

---

## 💼 Work Experience

### **AI Engineer Intern — FPT Software** | May 2026 – Aug 2026

- Built a **Python/FastAPI multi-agent CRM assistant** for support, knowledge retrieval, and automation, achieving **~4s P95 latency with 30+ concurrent sessions**.
- Engineered **user-isolated hybrid RAG** with **BM25, ChromaDB, BGE, reciprocal rank fusion (RRF), and cross-encoder reranking**, incorporating reliability safeguards and Docker-based LLM serving.
- Designed and developed **20+ reusable Langflow nodes** for modular AI orchestration, workflow integration, and automated task execution.
- Conducted **A/B experiments across 200+ clients**, analyzing system performance and comparative outcomes to inform product improvements.

### **Software Engineer Intern — Truong Thinh Technology Co., Ltd.** | Sep 2024 – Dec 2024

- Built a **Top-K movie recommendation system** using **100K+ ratings across 9K+ movies**, benchmarking **Factorization Machines vs. SVD++** with 10-fold cross-validation.
- Optimized **ONNX Runtime batch inference** to approximately **0.7s P95 latency under 50+ concurrent sessions**.
- Cleaned and validated **50K+ NLP samples**, achieving **98%+ data-quality pass rates**; implemented automated testing and P50/P95 monitoring, reducing P95 latency by **~18%**.

---

## 🚀 Featured Projects

### 🩺 [SympScan — Medical Graph-RAG System](https://github.com/Dochikhoa2006/Hybrid-Medical-Graph-RAG-Assistant) | Mar 2026 – Jul 2026

Built a medical-information **Graph-RAG prototype** using **BM25, FAISS, Neo4j/Cypher, cross-encoder reranking, HyDE, query expansion, and context compression**, with structured output validation.

**Results:** `0.92 faithfulness` · `0.81 answer relevancy` · `0.89 context precision` · `0.74 context recall` (RAGAS, 200 queries) · `~1.1s P95 TTFT`  
**Stack:** `Python` `FAISS` `PostgreSQL` `Neo4j` `Qwen 2.5` `Ollama` `Docker`

### 🤖 [RLHF Language Model — GPT-2, RoBERTa & PPO](https://github.com/Dochikhoa2006/Reinforcement-Learning-Human-Feedback-Chatbot) | Aug 2025 – Dec 2025

Developed an end-to-end **reinforcement learning from human feedback (RLHF)** pipeline with **supervised fine-tuning, a RoBERTa reward model, and custom actor-critic PPO**, using **UltraFeedback**, margin-ranking loss, and KL regularization. Deployed interactive inference with Streamlit and Docker.

**Results:** `546 PPO wins vs. 53 SFT wins` · `~91% PPO win rate` in LLM-as-a-judge comparisons  
**Stack:** `Python` `PyTorch` `Hugging Face` `GPT-2` `RoBERTa` `PPO` `React Native` `Node.js` `Streamlit` `Docker`

### 🔎 [Quora Semantic Question Matching — SBERT, LoRA & LightGBM](https://github.com/Dochikhoa2006/Quora-Question-Pairs-Duplicate-Detection) | Aug 2025 – Nov 2025

Fine-tuned **Sentence-BERT with LoRA** on **404K Quora question pairs**, using contrastive, triplet, and classification objectives. Combined semantic embeddings with **13 lexical features** in a **1,000-tree LightGBM GOSS** ensemble.

**Results:** `0.82 ROC-AUC`  
**Stack:** `Python` `Sentence-BERT` `LoRA` `LightGBM` `React Native` `TypeScript` `AWS DynamoDB`

### 💬 [Neural Sentiment Analysis — BiGRU, BiLSTM & FastText](https://github.com/Dochikhoa2006/Sentiment-Analysis-Extended-RNNs) | Apr 2025 – Jul 2025

Built a **five-class sentiment analysis pipeline** using **PySpark, FastText, and BiGRU/BiLSTM networks**, with containerized inference. Compared model performance using 10-fold cross-validation.

**Results:** `BiGRU: 83.1% ± 12.5% accuracy` · `BiLSTM: 82.4% ± 7.8% accuracy`  
**Stack:** `Python` `TensorFlow/Keras` `PySpark` `FastText` `BiGRU` `BiLSTM` `CUDA` `Docker`

### More Projects

- 🎮 **[Deep Reinforcement Learning for 10×10 GridWorld](https://github.com/Dochikhoa2006/GridWorld-Deep-Reinforcement-Learning)** — Benchmarked **DQN, Double DQN, and Deep Expected SARSA** for obstacle-aware navigation across **3 evaluation maps**, with **22,000+ state transitions** and a **100-state / 4-action** environment.
- 🌙 **[Sleep Disorder Multi-Class Prediction](https://github.com/Dochikhoa2006/Sleeping-Disorder-Multi-Classification)** — Compared **Logistic Regression, polynomial-kernel SVM, and Gradient Boosting**, with preprocessing, feature engineering, PCA, and cross-validation; achieved **0.88 macro-F1** with Gradient Boosting.

---

## 🛠️ Technical Toolkit

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
</p>

- **Languages:** Python, C/C++, Java, JavaScript, TypeScript, SQL, HTML5/CSS
- **AI & ML:** PyTorch, TensorFlow/Keras, CrewAI, LangChain, LlamaIndex, RAG, tool calling, MCP, vLLM, CUDA Graphs
- **Backend & Frameworks:** REST APIs, FastAPI, PostgreSQL, MongoDB, Redis, Kafka
- **Cloud & DevOps:** AWS (EC2, Lambda, RDS, S3), Azure, GCP, Docker, Kubernetes, Linux, Git, GitHub, CI/CD
- **Hands-on ML Systems:** Hybrid retrieval, cross-encoder reranking, ONNX Runtime inference, A/B testing, load testing, P50/P95 monitoring

---

## 🌱 Leadership & Volunteering

- **Peer Tutor Volunteer — Google Developer Groups on Campus, FPT University** *(Feb 2026 – May 2026)*  
  Helped students strengthen programming, mathematics, and problem-solving skills through peer discussions, coursework review, and small-group study sessions.
- **Event Support Volunteer — Concordia University Economics Student Society** *(Sep 2026)*  
  Assisted with event setup, attendee check-in, participant guidance, and logistics.
- **Campus Open Day Volunteer — FPT University** *(Sep 2024 – Sep 2025)*  
  Supported visitor registration, campus tours, and coordination for prospective students and families.
- **Community Volunteer — Local Student Volunteer Group** *(Nov 2024 – Dec 2024)*  
  Participated in community cleanup, litter collection, waste sorting, and upkeep of shared public spaces.

---

## 🏆 Honors & Awards

- 📐 **Top 5% — Fermat Contest**, University of Waterloo (CEMC), Mathematics Competition
- 🥉 **3rd Prize — HCMC Informatics Competition**, Data Structures & Algorithms

---

## 🤝 Let's Connect!

I'm interested in **applied AI, LLM systems, machine learning engineering, and software engineering**—especially opportunities to turn research ideas into dependable, practical products. I enjoy connecting with engineers, researchers, and recruiters.

**[LinkedIn](https://www.linkedin.com/in/chikhoado/) · [GitHub](https://github.com/Dochikhoa2006) · [Email](mailto:dochikhoa2006@gmail.com)**
