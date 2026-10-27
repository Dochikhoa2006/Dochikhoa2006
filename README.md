
<div align="center">

# Hi, I'm Chi Khoa (Kelvin) Do 👋

### AI Engineer · Machine Learning · Generative AI / LLM Systems

**Computer Science (Data Science) @ Concordia University 🇨🇦**  
**Montréal, Canada · Expected graduation: May 2028**

**🎯 Open to 2027 AI/ML, Applied AI, and Software Engineering internships**

</div>

---

## 👨‍💻 About Me

I'm a **Computer Science undergraduate at Concordia University**, focused on **machine learning, LLMs, agentic AI, NLP, and AI systems engineering**. Through two AI/ML internships and independent projects, I've worked across the full lifecycle: **training, retrieval, orchestration, benchmarking, optimization, and deployment**.

I care about turning promising models into **reliable, measurable, real-world software**.

### ⚡ Impact at a Glance

<table>
<tr>
<td align="center"><b>~4s P95</b><br /><sub>Multi-agent CRM assistant<br />30+ concurrent sessions</sub></td>
<td align="center"><b>20+</b><br /><sub>Reusable Langflow<br />AI workflow nodes</sub></td>
<td align="center"><b>200+</b><br /><sub>Clients included in<br />AI system A/B evaluations</sub></td>
<td align="center"><b>~0.7s P95</b><br /><sub>Recommendation serving<br />50+ concurrent sessions</sub></td>
</tr>
</table>

---

## 💼 Internships

- **FPT Software — AI Engineer Intern** *(May 2026 – Aug 2026)*  
  Built a **multi-agent CRM assistant** for support, knowledge management, and reminder automation; developed hybrid RAG using **OpenSearch BM25, ChromaDB, BGE, RRF, and cross-encoder reranking**. Created **20+ reusable Langflow components**, evaluated AI configurations across **200+ clients**, and served models using **FastAPI, Docker, Ollama, and vLLM**.

- **Truong Thinh Technology & Engineering — Machine Learning Intern** *(Sep 2024 – Dec 2024)*  
  Developed a **Top-K movie recommender** using Factorization Machines and SVD++, optimized inference with **ONNX Runtime and batched scoring**, and built NLP data-quality and load-testing workflows for deployable ML services.

---

## 🌱 Leadership & Volunteering

- **Peer Tutor Volunteer — Google Developer Groups on Campus, FPT University** *(Feb 2026 – May 2026)*  
  Helped fellow students develop **programming, mathematics, and problem-solving skills** through peer discussions, coursework review, and collaborative small-group study sessions.

- **Event Support Volunteer — Concordia University Economics Student Society** *(Sep 2026)*  
  Assisted with **event setup, attendee check-in, participant guidance, and logistics**, helping create an organized and welcoming student society gathering.

- **Campus Open Day Volunteer — FPT University** *(Sep 2024 – Sep 2025)*  
  Supported **visitor registration, campus tours, and event coordination**; guided prospective students and families to activities, classrooms, and information booths.

- **Community Volunteer — Local Student Volunteer Group** *(Nov 2024 – Dec 2024)*  
  Joined a **student-led community cleanup**, helping with litter collection, waste sorting, and upkeep of shared public spaces.

---

## 🚀 Featured Projects

### 🩺 [SympScan — Hybrid Medical Graph-RAG Assistant](https://github.com/Dochikhoa2006/Hybrid-Medical-Graph-RAG-Assistant)

A medical-information RAG prototype combining **BM25 + FAISS HNSW + reciprocal rank fusion + cross-encoder reranking + Neo4j/Cypher**, with Qwen 2.5 via Ollama. Includes query rewriting, HyDE, context compression, and structured responses.

**Results:** `0.92 RAGAS faithfulness` · `0.89 context precision` · `~1.1s P95 TTFT`  
**Stack:** `Python` `FAISS` `Neo4j` `PySpark` `Ollama` `Streamlit` `Docker`

### 🤖 [RLHF-Aligned Chatbot — GPT-2, RoBERTa & PPO](https://github.com/Dochikhoa2006/Reinforcement-Learning-Human-Feedback-Chatbot)

Built an end-to-end **reinforcement learning from human feedback** pipeline: supervised fine-tuning, a RoBERTa preference-reward model, and custom PPO with KL regularization and a value baseline.

**Results:** `546 PPO wins vs. 53 SFT wins` — **~91%** of counted LLM-as-a-judge comparisons.  
**Stack:** `PyTorch` `Hugging Face` `GPT-2` `RoBERTa` `PPO` `Docker`

### 🔎 [Quora Duplicate Question Detection — SBERT, LoRA & LightGBM](https://github.com/Dochikhoa2006/Quora-Question-Pairs-Duplicate-Detection)

Fine-tuned **Sentence-BERT with LoRA**, engineered lexical features, and combined semantic and statistical signals using LightGBM to identify duplicate questions across **~404K labeled pairs**.

**Results:** `0.82 ROC-AUC`  
**Stack:** `Sentence-BERT` `LoRA` `LightGBM` `NLP` `Docker`

### 💬 [Five-Class Sentiment Analysis — BiGRU, BiLSTM & FastText](https://github.com/Dochikhoa2006/Sentiment-Analysis-Extended-RNNs)

Developed an end-to-end Amazon Appstore sentiment-analysis pipeline, from **PySpark data processing** and FastText embeddings to recurrent neural networks and Dockerized inference.

**Results:** `83.1% mean BiGRU accuracy` in shuffled 10-fold cross-validation.  
**Stack:** `TensorFlow / Keras` `BiGRU` `BiLSTM` `FastText` `PySpark`

### 🎮 [Deep Reinforcement Learning for 10×10 GridWorld — DQN, DDQN & Expected SARSA](https://github.com/Dochikhoa2006/GridWorld-Deep-Reinforcement-Learning)

Built and benchmarked an **obstacle-aware navigation agent** in a 10×10 GridWorld using **Deep Q-Network (DQN), Double DQN, and Deep Expected SARSA**. Developed a reproducible workflow for state encoding, Q-value learning, target-network updates, and policy evaluation across different maps.

**Results:** `22,000+ state transitions` · `100 states / 4 actions` · `3 evaluation maps`  
**Stack:** `Python` `Deep Reinforcement Learning` `DQN` `Double DQN` `Expected SARSA` `Docker`

### 🌙 [Sleep Disorder Multi-Class Prediction — SVM & Gradient Boosting](https://github.com/Dochikhoa2006/Sleeping-Disorder-Multi-Classification)

Developed an end-to-end **multi-class machine learning pipeline** to predict **Healthy, Insomnia, and Sleep Apnea** outcomes from lifestyle and physiological features. Compared **Logistic Regression, polynomial-kernel SVM, and Gradient Boosting**, with data preprocessing, feature engineering, PCA, cross-validation, and containerized inference.

**Results:** `0.88 macro-F1` with Gradient Boosting  
**Stack:** `Python` `scikit-learn` `SVM` `Gradient Boosting` `PCA` `Docker`

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
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
</p>

- **Languages:** Python, C/C++, Java, SQL, R, Bash
- **AI & ML:** PyTorch, TensorFlow/Keras, scikit-learn, Hugging Face, PEFT/LoRA, RLHF, NLP
- **LLM & retrieval systems:** Multi-agent architectures, LangGraph, LangChain, BM25, FAISS, ChromaDB, OpenSearch, Neo4j, reranking
- **Inference & engineering:** FastAPI, ONNX Runtime, Ollama, vLLM, TensorRT, CUDA, Docker, AWS, Azure, CI/CD

---

## 🏆 Honors & Awards

- 🥉 **3rd Prize — HCMC Informatics Competition**, Data Structures & Algorithms
- 📐 **Top 5% — Fermat Contest**, University of Waterloo (CEMC)

---

## 🤝 Let's Connect!

I'm interested in **applied AI, LLM systems, machine learning engineering, and opportunities to build impactful software**. I'm happy to connect with engineers, researchers, and recruiters.

