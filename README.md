# 🌌 Thura Venkata Naveen | AI/ML Engineer

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0B1026,45:075985,75:0F766E,100:7C3AED&text=THURA%20VENKATA%20NAVEEN&fontColor=FFFFFF&fontSize=34&fontAlignY=38&desc=AI%20%7C%20Machine%20Learning%20%7C%20Deep%20Learning%20%7C%20Applied%20LLMs&descAlignY=58&descSize=14&animation=fadeIn" width="100%" alt="Aurora gradient profile banner"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=800&color=38BDF8&center=true&vCenter=true&width=800&lines=Building+practical+AI+applications;Turning+data+into+actionable+insights;Exploring+Deep+Learning+with+PyTorch;Developing+LLM+and+RAG+systems;From+ML+experiments+to+deployable+APIs" alt="Animated introduction"/>
</p>

<p align="center">
  <a href="https://github.com/naveen057"><img src="https://img.shields.io/badge/GitHub-Explore%20Projects-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://www.linkedin.com/in/venkata-naveen-thura/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://naveen057.ccbp.tech"><img src="https://img.shields.io/badge/Portfolio-Visit-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:venkatanaveendcme057@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## ✨ About Me

Hi! I'm **Thura Venkata Naveen**, a Computer Science Engineering graduate from Sri Venkateswara University College of Engineering (SVUCE), 2026.

I'm focused on building practical AI and machine learning applications that connect data, intelligent models, retrieval systems, and production-ready APIs.

- 🤖 Exploring machine learning, deep learning, NLP, and applied LLMs.
- 🔎 Building retrieval-augmented applications using embeddings, FAISS, BM25, hybrid search, and reranking.
- 📊 Working with data analysis, model evaluation, feature engineering, and statistical methods.
- ⚙️ Developing APIs and interfaces with FastAPI and Streamlit.
- 🧠 Currently strengthening my deep learning skills with PyTorch.
- 🎯 Seeking entry-level opportunities in AI/ML engineering, data science, and Python development.

> My goal: build AI systems that are understandable, measurable, useful, and deployable.

## 🧭 My AI Engineering Journey

```mermaid
flowchart TD
    A["📚 Python & Mathematics"] --> B["📊 Data Analysis"]
    B --> C["🧹 Data Preparation & Feature Engineering"]
    C --> D["🤖 Machine Learning"]
    D --> E["🧠 Deep Learning"]
    E --> F["💬 NLP & LLM Applications"]
    F --> G["🔎 Retrieval & RAG"]
    G --> H["⚙️ FastAPI & Streamlit"]
    H --> I["🚀 Evaluation & Deployment"]

    classDef foundation fill:#172554,stroke:#38BDF8,color:#FFFFFF
    classDef modeling fill:#134E4A,stroke:#2DD4BF,color:#FFFFFF
    classDef ai fill:#312E81,stroke:#A78BFA,color:#FFFFFF
    classDef deploy fill:#164E63,stroke:#67E8F9,color:#FFFFFF

    class A,B,C foundation
    class D,E modeling
    class F,G ai
    class H,I deploy
```

## 🛠️ Technical Skills

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,django,mysql,git,github,docker,pytorch,tensorflow&theme=dark" alt="Technology icons"/>
</p>

| Area | Technologies and concepts |
|---|---|
| Programming | Python, SQL |
| Data analysis | NumPy, Pandas, Matplotlib, Seaborn |
| Machine learning | Scikit-learn, XGBoost, feature engineering, model evaluation, hyperparameter tuning |
| Deep learning | Neural networks, CNN fundamentals, PyTorch learning, TensorFlow |
| NLP & LLMs | Embeddings, prompt engineering, Google Gemini API, RAG |
| Information retrieval | FAISS, BM25, hybrid search, Reciprocal Rank Fusion (RRF), cross-encoder reranking |
| Backend development | FastAPI, REST APIs, Pydantic, SQLAlchemy ORM |
| Databases | MySQL |
| Applications | Streamlit |
| Tools | Git, GitHub, Joblib, Docker |

## 🚀 Featured Projects

Projects are organized by the engineering problem they solve. Each project links to its source repository; a live demo is shown only where a public URL has been verified or supplied and clearly identified.

### 01 · Resume Intelligence

<p>
  <img src="https://img.shields.io/badge/Domain-AI%20%26%20Information%20Retrieval-075985?style=flat-square" alt="AI and retrieval"/>
  <img src="https://img.shields.io/badge/Interface-Streamlit-0F766E?style=flat-square" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/API-FastAPI-7C3AED?style=flat-square" alt="FastAPI"/>
</p>

**Problem:** Comparing resumes with job descriptions can be time-consuming, and simple keyword matching can miss relevant experience.

**Solution:** A resume-to-job matching application that combines lexical and semantic retrieval, rank fusion, reranking, and AI-generated explanations.

**Project journey**

```mermaid
flowchart TD
    A["📄 Resume"] --> C["Text extraction"]
    B["💼 Job description"] --> D["Requirement analysis"]
    C --> E["Candidate evidence"]
    D --> F["Search query"]
    E --> G["BM25 + dense FAISS retrieval"]
    F --> G
    G --> H["RRF rank fusion"]
    H --> I["Cross-encoder reranking"]
    I --> J["Evidence-based match assessment"]
    J --> K["Gemini explanation"]
    K --> L["Streamlit interface / FastAPI"]

    classDef input fill:#172554,stroke:#38BDF8,color:#FFFFFF
    classDef retrieval fill:#134E4A,stroke:#2DD4BF,color:#FFFFFF
    classDef output fill:#312E81,stroke:#A78BFA,color:#FFFFFF

    class A,B,C,D input
    class E,F,G,H,I retrieval
    class J,K,L output
```

**What it demonstrates**
- Combining keyword and semantic retrieval.
- Improving ranking through fusion and reranking.
- Separating evidence-based matching from generated explanations.
- Connecting an AI workflow to a user-facing application and API.

<p>
  <a href="https://github.com/naveen057/resume-intelligence"><img src="https://img.shields.io/badge/View%20Source-GitHub-111827?style=for-the-badge&logo=github" alt="View Resume Intelligence source"/></a>
</p>

*Live demo: a previously supplied Streamlit URL has not been independently verified, so it is intentionally not presented here as a confirmed live demo.*

### 02 · Fraud Detection API

<p>
  <img src="https://img.shields.io/badge/Domain-Financial%20Machine%20Learning-075985?style=flat-square" alt="Financial ML"/>
  <img src="https://img.shields.io/badge/Backend-FastAPI-0F766E?style=flat-square" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Deployment-Render-7C3AED?style=flat-square" alt="Render"/>
</p>

**Problem:** Financial transaction systems need a way to identify potentially risky transactions from transaction features.

**Solution:** A machine learning project that evaluates transaction risk and exposes predictions through an API.

**Project journey**

```mermaid
flowchart TD
    A["📊 Transaction dataset"] --> B["Data preparation"]
    B --> C["Train / validation evaluation"]
    C --> D["Model training"]
    D --> E["Threshold selection"]
    E --> F["Model evaluation"]
    F --> G["Save model artifacts"]
    G --> H["FastAPI prediction endpoint"]
    H --> I["Transaction features"]
    I --> J["Risk prediction"]
    J --> K["Client receives response"]

    classDef data fill:#172554,stroke:#38BDF8,color:#FFFFFF
    classDef model fill:#134E4A,stroke:#2DD4BF,color:#FFFFFF
    classDef service fill:#312E81,stroke:#A78BFA,color:#FFFFFF

    class A,B data
    class C,D,E,F,G model
    class H,I,J,K service
```

**What it demonstrates**
- Transaction classification and model evaluation.
- Decision-threshold selection.
- Serving predictions through a REST API.
- Packaging model artifacts for application use.

<p>
  <a href="https://github.com/naveen057/fraud-detection"><img src="https://img.shields.io/badge/View%20Source-GitHub-111827?style=for-the-badge&logo=github" alt="View Fraud Detection source"/></a>
  <a href="https://fraud-detection-dz3c.onrender.com/"><img src="https://img.shields.io/badge/Live%20Demo-Open%20App-0F766E?style=for-the-badge&logo=render" alt="Open Fraud Detection live demo"/></a>
</p>

### 03 · Heart Disease Risk Prediction

<p>
  <img src="https://img.shields.io/badge/Domain-Healthcare%20ML-075985?style=flat-square" alt="Healthcare ML"/>
  <img src="https://img.shields.io/badge/Focus-Classification-7C3AED?style=flat-square" alt="Classification"/>
</p>

**Problem:** Understand how structured health-related features can be used in a classification workflow.

**Project journey**

```mermaid
flowchart LR
    A["Structured data"] --> B["Data cleaning"]
    B --> C["Exploratory analysis"]
    C --> D["Feature preparation"]
    D --> E["Classification model"]
    E --> F["Evaluation"]
    F --> G["Risk prediction output"]

    classDef prep fill:#172554,stroke:#38BDF8,color:#FFFFFF
    classDef model fill:#134E4A,stroke:#2DD4BF,color:#FFFFFF
    class A,B,C,D prep
    class E,F,G model
```

**What it demonstrates**
- Exploratory data analysis.
- Classification workflow design.
- Model evaluation and interpretation.

<p>
  <a href="https://github.com/naveen057/heart-disease-risk-prediction"><img src="https://img.shields.io/badge/View%20Source-GitHub-111827?style=for-the-badge&logo=github" alt="View Heart Disease Risk Prediction source"/></a>
</p>

*This is an educational machine learning project, not a clinical diagnostic tool. No live demo is listed.*

### 04 · Multi-source Web Scraping Pipeline

<p>
  <img src="https://img.shields.io/badge/Domain-Data%20Engineering-075985?style=flat-square" alt="Data engineering"/>
  <img src="https://img.shields.io/badge/Focus-Automation-0F766E?style=flat-square" alt="Automation"/>
</p>

**Problem:** Data from different websites can have inconsistent structures and require repeated manual collection.

**Project journey**

```mermaid
flowchart TD
    A["🌐 Source websites"] --> B["HTTP requests"]
    B --> C["HTML parsing"]
    C --> D["Field extraction"]
    D --> E["Normalization"]
    E --> F["Validation & deduplication"]
    F --> G["Structured output"]
    G --> H["Analysis or downstream use"]

    classDef source fill:#172554,stroke:#38BDF8,color:#FFFFFF
    classDef processing fill:#134E4A,stroke:#2DD4BF,color:#FFFFFF
    classDef result fill:#312E81,stroke:#A78BFA,color:#FFFFFF

    class A,B source
    class C,D,E,F processing
    class G,H result
```

**What it demonstrates**
- Extracting structured data from web pages.
- Cleaning and standardizing records.
- Organizing repeatable data collection workflows.

<p>
  <a href="https://github.com/naveen057/multi-source-web-scraping-pipeline"><img src="https://img.shields.io/badge/View%20Source-GitHub-111827?style=for-the-badge&logo=github" alt="View scraping pipeline source"/></a>
</p>

### 05 · Vehicle Service Management System

<p>
  <img src="https://img.shields.io/badge/Domain-Web%20Application-075985?style=flat-square" alt="Web application"/>
  <img src="https://img.shields.io/badge/Framework-Django-0F766E?style=flat-square" alt="Django"/>
</p>

**Problem:** Vehicle servicing involves customers, mechanics, service requests, repairs, invoices, and feedback.

**Project journey**

```mermaid
flowchart TD
    A["👤 Customer"] --> B["Service request"]
    B --> C["Service workflow"]
    C --> D["🧰 Mechanic / repair"]
    D --> E["Service completion"]
    E --> F["Invoice"]
    E --> G["Customer feedback"]

    classDef user fill:#172554,stroke:#38BDF8,color:#FFFFFF
    classDef workflow fill:#134E4A,stroke:#2DD4BF,color:#FFFFFF
    classDef outcome fill:#312E81,stroke:#A78BFA,color:#FFFFFF

    class A user
    class B,C,D workflow
    class E,F,G outcome
```

**What it demonstrates**
- Web application development with Django.
- Managing related business entities and workflows.
- Organizing service requests, repairs, invoices, and feedback.

<p>
  <a href="https://github.com/naveen057/vehicle-service-management-system"><img src="https://img.shields.io/badge/View%20Source-GitHub-111827?style=for-the-badge&logo=github" alt="View Vehicle Service Management source"/></a>
</p>

### 06 · OpenPowerlifting Data Analysis

<p>
  <img src="https://img.shields.io/badge/Domain-Exploratory%20Data%20Analysis-075985?style=flat-square" alt="Data analysis"/>
  <img src="https://img.shields.io/badge/Focus-Visualization-7C3AED?style=flat-square" alt="Visualization"/>
</p>

**Project journey**

```mermaid
flowchart LR
    A["📂 Powerlifting dataset"] --> B["Data inspection"]
    B --> C["Cleaning & transformation"]
    C --> D["Exploratory analysis"]
    D --> E["Statistical comparisons"]
    E --> F["Visualizations"]
    F --> G["Insights & conclusions"]

    classDef source fill:#172554,stroke:#38BDF8,color:#FFFFFF
    classDef analysis fill:#134E4A,stroke:#2DD4BF,color:#FFFFFF
    classDef insights fill:#312E81,stroke:#A78BFA,color:#FFFFFF

    class A,B source
    class C,D,E,F analysis
    class G insights
```

**What it demonstrates**
- Working with a real-world dataset.
- Cleaning, analyzing, and comparing structured data.
- Communicating findings through visualizations.

<p>
  <a href="https://github.com/naveen057/openpowerlifting-data-analysis"><img src="https://img.shields.io/badge/View%20Source-GitHub-111827?style=for-the-badge&logo=github" alt="View OpenPowerlifting analysis source"/></a>
</p>

## 🏗️ How I Approach AI Applications

```mermaid
flowchart TD
    A["🎯 Define the problem"] --> B["📦 Collect data"]
    B --> C["🧹 Prepare & validate"]
    C --> D["🔬 Establish a baseline"]
    D --> E["🧠 Train or retrieve"]
    E --> F["📏 Evaluate results"]
    F --> G{"Meets requirements?"}
    G -->|No| H["🔁 Diagnose & improve"]
    H --> E
    G -->|Yes| I["⚙️ Build API or interface"]
    I --> J["🚀 Deploy"]
    J --> K["📈 Monitor & iterate"]

    classDef planning fill:#172554,stroke:#38BDF8,color:#FFFFFF
    classDef engineering fill:#134E4A,stroke:#2DD4BF,color:#FFFFFF
    classDef delivery fill:#312E81,stroke:#A78BFA,color:#FFFFFF

    class A,B,C,D planning
    class E,F,G,H engineering
    class I,J,K delivery
```

My focus is on more than obtaining a model prediction. I aim to understand the data, evaluate performance, make results accessible, and communicate limitations clearly.

## 📚 Current Learning Focus

- **Deep learning:** tensors, autograd, forward propagation, backpropagation, optimizers, CNNs, regularization, and transfer learning.
- **Model development:** validation, error analysis, hyperparameter tuning, and reproducible experiments.
- **LLM applications:** retrieval quality, embeddings, reranking, grounded generation, and evaluation.
- **Deployment:** API design, input validation, testing, and containerization.

## 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=naveen057&show_icons=true&hide_border=true&bg_color=0B1026&title_color=38BDF8&text_color=C4B5FD&icon_color=2DD4BF" height="165" alt="GitHub profile statistics"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=naveen057&layout=compact&hide_border=true&bg_color=0B1026&title_color=38BDF8&text_color=C4B5FD" height="165" alt="Most-used programming languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=naveen057&hide_border=true&background=0B1026&ring=7C3AED&fire=2DD4BF&currStreakLabel=38BDF8&sideLabels=C4B5FD&dates=94A3B8" alt="GitHub contribution streak"/>
</p>

*Stats and language cards are provided by external services and may occasionally be unavailable. Language percentages reflect repository contents, not a direct measure of expertise.*

## 🤝 Let's Connect

I'm interested in entry-level opportunities, practical AI/ML projects, and collaborating with engineers who enjoy building useful products.

<p align="center">
  <a href="https://github.com/naveen057"><img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub profile"/></a>
  <a href="https://www.linkedin.com/in/venkata-naveen-thura/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile"/></a>
  <a href="https://naveen057.ccbp.tech"><img src="https://img.shields.io/badge/Portfolio-0F766E?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:venkatanaveendcme057@gmail.com"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,45:0F766E,100:0B1026&height=120&section=footer" width="100%" alt="Aurora gradient footer"/>
</p>

<p align="center">
  <i>Learn continuously. Build thoughtfully. Deploy responsibly. 🌌</i>
</p>
