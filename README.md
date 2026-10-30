# 👋 Hi, I'm Thura Venkata Naveen

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=23&pause=1000&color=8B5CF6&center=true&vCenter=true&width=750&lines=Aspiring+AI%2FML+Engineer;Python+Developer;Generative+AI+Enthusiast;Building+Practical+AI+Applications)](https://git.io/typing-svg)

**B.Tech Graduate in Computer Science Engineering**  
Sri Venkateswara University College of Engineering (SVUCE)

I build practical AI applications using Machine Learning, NLP, Generative AI, and Retrieval-Augmented Generation (RAG).

[![GitHub](https://img.shields.io/badge/GitHub-naveen057-181717?style=for-the-badge&logo=github)](https://github.com/naveen057)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/venkata-naveen-thura/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-7C3AED?style=for-the-badge&logo=googlechrome)](https://naveen057.ccbp.tech)

</div>

---

## 🧭 Explore My Profile

<div align="center">

[👨‍💻 About Me](#-about-me) • [🛠️ Skills](#️-my-ai-ml-toolkit) • [🚀 Projects](#-featured-projects) • [🔄 Workflow](#-how-i-build-ai-applications) • [📊 Stats](#-github-dashboard) • [📬 Contact](#-lets-connect)

</div>

---

## 👨‍💻 About Me

- 🎓 B.Tech graduate in Computer Science Engineering from SVUCE.
- 🤖 Interested in Machine Learning, Deep Learning, NLP, and Generative AI.
- 🔎 Exploring LLMs, RAG, vector databases, embeddings, and information retrieval.
- 🌐 Building AI applications using Python, FastAPI, and Streamlit.
- 📊 Practicing data preprocessing, feature engineering, and model evaluation.
- 🎯 Seeking entry-level opportunities in AI/ML, Python Development, and Data Science.

---

## 🛠️ My AI/ML Toolkit

| Category | Technologies |
|---|---|
| 💻 Programming | Python, SQL |
| 📊 Data Analysis | NumPy, Pandas, Matplotlib, Seaborn |
| 🤖 Machine Learning | Scikit-learn, XGBoost, Joblib |
| 🧠 Deep Learning | PyTorch, TensorFlow, Neural Networks |
| ✨ Generative AI | NLP, LLMs, RAG, Gemini API, Prompt Engineering |
| 🔍 Information Retrieval | FAISS, BM25, Embeddings, Hybrid Search, Reranking |
| 🌐 API & Applications | FastAPI, Streamlit, REST APIs |
| 🗄️ Databases | MySQL, Pinecone |
| 🧰 Development Tools | Git, GitHub, Jupyter Notebook, SQLAlchemy, Pydantic |

<details>
<summary><b>🔍 Explore my technical skills</b></summary>

**Python and Data:** Python programming, SQL, data manipulation, data visualization, exploratory data analysis.

**Machine Learning:** Data preprocessing, feature engineering, supervised learning, model training, evaluation, classification, XGBoost, Scikit-learn.

**Generative AI:** Natural Language Processing, Large Language Models, RAG pipelines, embeddings, Gemini API, prompt engineering.

**Search and Retrieval:** FAISS, Pinecone, BM25, hybrid retrieval, reciprocal rank fusion, cross-encoder reranking.

**Deployment:** FastAPI, Streamlit, REST API development, Joblib, Docker fundamentals.

**Tools:** Git, GitHub, MySQL, SQLAlchemy, Pydantic, Jupyter Notebook.

</details>

---

## ⭐ Major Project — RepoRAG

<div align="center">

### 🧠 RepoRAG — AI-Powered Code Intelligence System

**Ask questions about a codebase in natural language.**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)](https://ai.google.dev/)
[![Pinecone](https://img.shields.io/badge/Pinecone-Vector_Database-2E8B57?style=flat)](https://www.pinecone.io/)

</div>

### 📌 Problem Statement

Developers, especially beginners, can struggle to understand unfamiliar GitHub repositories. Manually opening files and searching for relevant functions or classes takes time.

### 💡 Solution

RepoRAG is an AI-powered code intelligence system designed to help developers explore repositories by asking questions in plain English. It retrieves relevant code snippets and uses a RAG pipeline to help generate context-aware answers.

### ⚙️ Key Features

- 📂 Ingests source code from GitHub repositories.
- ✂️ Splits code into manageable chunks for retrieval.
- 🧠 Uses embeddings to represent code and support semantic search.
- 🗄️ Stores and searches vector representations using Pinecone.
- 🔎 Retrieves relevant code context for user questions.
- 💬 Uses a Gemini-powered generation step to help answer questions about the codebase.
- 🌐 Uses FastAPI for backend API development.

### 🏗️ System Architecture

```mermaid
flowchart TD
    A["📂 GitHub Repository"] --> B["📥 Repository Ingestion"]
    B --> C["✂️ Code Parsing and Chunking"]
    C --> D["🧠 Generate Embeddings"]
    D --> E[("🗄️ Pinecone Vector Database")]
    F["💬 User Question"] --> G["🔎 Semantic Retrieval"]
    E --> G
    G --> H["📄 Relevant Code Context"]
    H --> I["✨ Gemini LLM"]
    I --> J["✅ Context-Aware Answer"]
    J --> K["🌐 FastAPI"]

    style A fill:#1D4ED8,color:#FFFFFF
    style E fill:#0E7490,color:#FFFFFF
    style I fill:#6D28D9,color:#FFFFFF
    style J fill:#166534,color:#FFFFFF
```

### 🛠️ Tech Stack

**Python • FastAPI • RAG • Gemini API • Embeddings • Pinecone • Semantic Search**

### 🎯 Expected Benefits

- Reduces manual code searching.
- Helps developers navigate unfamiliar repositories.
- Makes code exploration more accessible through natural-language questions.

📂 **Repository:** Add your actual RepoRAG repository URL here when available.

---

## 🚀 Featured Projects

<details open>
<summary><b>⭐ 1. RepoRAG — AI-Powered Code Intelligence System (Major Project)</b></summary>

An AI-powered code intelligence system that helps developers understand unfamiliar GitHub repositories by asking questions in natural language instead of manually searching through multiple files.

**💡 Problem Statement**

Developers often spend considerable time understanding unfamiliar codebases, locating relevant functions, and tracing code across files.

**🚀 Solution**

RepoRAG uses Retrieval-Augmented Generation (RAG) to retrieve relevant code snippets from a GitHub repository and help generate context-aware answers to developers' questions.

**✨ Key Features**
- 📂 GitHub repository ingestion and code processing.
- ✂️ Source-code chunking for efficient retrieval.
- 🧠 Gemini embeddings for representing code.
- 🗄️ Pinecone vector database for storing and retrieving embeddings.
- 🔎 Semantic search to identify relevant code snippets.
- 💬 Gemini-powered answers grounded in retrieved code context.
- 🌐 FastAPI backend for API-based interaction.

**🛠️ Tech Stack**

`Python` · `FastAPI` · `RAG` · `Gemini API` · `Embeddings` · `Pinecone` · `Semantic Search`

**🔄 Workflow**

GitHub Repository → Code Ingestion → Chunking → Embeddings → Pinecone Vector Database → Relevant Code Retrieval → Gemini LLM → Context-Aware Answer

**🎯 Impact**

Designed to reduce manual code exploration and make unfamiliar repositories easier to understand through natural-language questions.

📂 **[View Source Code](REPLACE_WITH_YOUR_REPORAG_REPOSITORY_URL)**

</details>

<details>
<summary><b>📄 2. Resume Intelligence — AI-Powered Resume Analysis</b></summary>

An AI-powered application that compares resumes with job descriptions, retrieves relevant evidence, and identifies matching skills and potential skill gaps.

**Key Features**
- Resume parsing and text extraction.
- BM25 and FAISS-based retrieval.
- Hybrid search and reranking.
- Evidence-based skill matching.
- Optional Gemini-generated explanations.

**Tech Stack:** Python, NLP, RAG, FAISS, BM25, Gemini API, FastAPI, Streamlit.

[📂 Source Code](https://github.com/naveen057/resume-intelligence) · [🌐 Live Demo](https://resume-intelligence-entgyngd5vq2pmrrpzyf84.streamlit.app/)

</details>

<details>
<summary><b>🛡️ 3. Real-Time Fraud Detection System</b></summary>

A machine learning application that identifies potentially fraudulent transactions using a trained model and API-based predictions.

**Tech Stack:** Python, Pandas, Scikit-learn, FastAPI, Joblib, Docker.

[📂 Source Code](https://github.com/naveen057/fraud-detection) · [🌐 Live Demo](https://fraud-detection-dz3c.onrender.com/)

</details>

<details>
<summary><b>❤️ 4. Heart Disease Risk Prediction</b></summary>

A machine learning application that estimates heart disease risk from health-related input features.

**Tech Stack:** Python, Pandas, NumPy, Scikit-learn, FastAPI, Joblib.

[📂 Source Code](https://github.com/naveen057/heart-disease-risk-prediction)

</details>

<details>
<summary><b>🌐 5. Multi-Source Web Scraping Pipeline</b></summary>

A Python-based pipeline for collecting and processing information from multiple web sources.

[📂 Source Code](https://github.com/naveen057/multi-source-web-scraping-pipeline)

</details>

<details>
<summary><b>🔧 6. Vehicle Service Management System</b></summary>

A Django application for managing customers, mechanics, service requests, repairs, invoices, and feedback.

[📂 Source Code](https://github.com/naveen057/vehicle-service-management-system)

</details>

<details>
<summary><b>📊 7. OpenPowerlifting Data Analysis</b></summary>

A data analysis project exploring powerlifting datasets using Python and Jupyter Notebook.

[📂 Source Code](https://github.com/naveen057/openpowerlifting-data-analysis)

</details>
---

## 🔄 How I Build AI Applications

```mermaid
flowchart TD
    A(["💡 Identify a Real-World Problem"]) --> B["📥 Collect Data"]
    B --> C["🧹 Clean and Explore Data"]
    C --> D["⚙️ Feature Engineering"]
    D --> E["🤖 Train the Model"]
    E --> F["📊 Evaluate Performance"]
    F --> G{"Is the performance acceptable?"}
    G -- "No" --> D
    G -- "Yes" --> H["🌐 Build API with FastAPI"]
    H --> I["🖥️ Create Interface with Streamlit"]
    I --> J(["🚀 Deploy and Test"])

    style A fill:#6D28D9,color:#FFFFFF
    style E fill:#0E7490,color:#FFFFFF
    style G fill:#92400E,color:#FFFFFF
    style J fill:#166534,color:#FFFFFF
```

**My approach:** Understand the problem → Prepare the data → Build the solution → Evaluate the results → Develop the application → Deploy and improve.

---

## 📚 My Learning Journey

```mermaid
flowchart LR
    A["🐍 Python and SQL"] --> B["📊 Data Analysis"]
    B --> C["🤖 Machine Learning"]
    C --> D["🧠 Deep Learning"]
    D --> E["✨ Generative AI and RAG"]
    E --> F["🚀 AI Application Development"]

    style A fill:#1D4ED8,color:#FFFFFF
    style C fill:#6D28D9,color:#FFFFFF
    style E fill:#0E7490,color:#FFFFFF
    style F fill:#166534,color:#FFFFFF
```

### 🎯 Currently Exploring

- [ ] Deep Learning with PyTorch
- [ ] Neural Networks and Backpropagation
- [ ] Convolutional Neural Networks (CNNs)
- [ ] Transfer Learning and Model Optimization
- [ ] Advanced RAG and LLM Applications
- [ ] AI Application Deployment

---

## 📊 GitHub Dashboard

<div align="center">

<a href="https://github.com/naveen057">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=naveen057&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=22D3EE" alt="GitHub statistics" />
</a>

<a href="https://github.com/naveen057">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=naveen057&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA" alt="Most-used programming languages" />
</a>

<a href="https://git.io/streak-stats">
  <img src="https://streak-stats.demolab.com?user=naveen057&theme=tokyonight&hide_border=true&background=0D1117&ring=A78BFA&fire=22D3EE" alt="GitHub contribution streak" />
</a>

</div>

---

## 📬 Let's Connect

<div align="center">

I'm interested in entry-level AI/ML opportunities, Python development, and projects involving Generative AI.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/venkata-naveen-thura/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/naveen057)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-7C3AED?style=for-the-badge&logo=googlechrome)](https://naveen057.ccbp.tech)
[![Email](https://img.shields.io/badge/Email-Contact-CB3837?style=for-the-badge&logo=gmail)](mailto:venkatanaveendcme057@gmail.com)

### ⭐ Thanks for visiting my profile! 

*Keep learning. Keep building. Keep improving.* 🚀

</div>
