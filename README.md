
---

# 👋 Hey, I'm Zakariae YAHYA (o゜▽゜)o☆

![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Data+Engineer+%26+AI+Developer;Real-Time+Pipelines+%7C+Spark+%7C+Kafka;Scalable+Data+Architectures&font=Fira+Code&center=true&width=500&height=50&duration=4000&pause=1000)

<div id="header" align="center">
  <img src="https://github.com/user-attachments/assets/f55ea8a0-99db-47bb-96b0-5012390ab5a3" width="100%" />
</div>

---

## 👨🏻‍💻 About Me

🎓 **Data Engineer & AI Developer | ENSA Tétouan**
🔍 **Focus:** Real-time data pipelines, Apache Spark, Kafka, distributed architectures
📍 Casablanca, Morocco
📧 zakariae.yh@gmail.com | 📱 +212 648 151 446

> Data Engineer & AI Developer specializing in real-time data pipelines, Apache Spark, Kafka, and distributed architectures. Experienced in deploying large-scale data platforms and analytical systems with strict latency, scalability, and observability requirements. Passionate about building robust, high-performance, and industrialized data solutions.

---

## 🎓 Education

**École Nationale des Sciences Appliquées – Tétouan**
🎓 *Data Science Engineering, Big Data & AI (2021 – 2026)*

---

## 💼 Professional Experience

### 🏦 **Data/ML Engineer Intern — Banque Centrale Populaire** (Casablanca) | *02/2026 – 08/2026*
#### **Real-Time Bank Fraud Detection System (PFE – Group Architecture Division)**
- Designed a **real-time Big Data architecture** for fraud detection on instant transfers, using **Apache Kafka, Spark Streaming, and 4 microservices** (Spring Boot/FastAPI), with end-to-end scoring latency **< 100 ms**
- Developed a **distributed processing pipeline**: event ingestion (Kafka), real-time behavioral enrichment, and advanced feature engineering
- Batch processing of transaction histories via **Apache Spark** (PySpark, Spark SQL): cleaning, class imbalance handling (SMOTE), dimensionality reduction (394 → 263 features)
- Trained and evaluated ML models: **Isolation Forest** (anomaly detection) + **XGBoost/Random Forest** (supervised), with anti-APP/ATO business rules. Model versioning via **MLflow**
- Built a **real-time monitoring dashboard** (React/Next.js, TypeScript, Material-UI): transaction visualization, severity-based alert management, simulation module
- Implemented security: **Keycloak** (OAuth2/OpenID Connect/JWT), **TLS 1.3/mTLS** inter-service encryption, **AES-256** at rest
- **Results:** Accuracy > 92% | False positives < 2% | Latency < 100 ms | Availability 99.9%
- **Stack:** Apache Kafka, Spark (PySpark), Spring Boot, FastAPI, Redis, PostgreSQL, React/Next.js, TypeScript, XGBoost, Scikit-learn, MLflow, Keycloak, Docker, Prometheus/Grafana

---

### 🧠 **Data Scientist Intern — Izemx** (Paris, France) | *02/2025 – 02/2026*

#### **Project 3: IAVIA – Enterprise Multi-Agent AI Platform**
- **Microservices architecture** (Java Spring Boot + Python FastAPI) for a multi-agent AI platform with per-agent memory isolation
- Unified **Memory Service** for multi-channel (Web, Slack, Teams, Telegram, WhatsApp) with LangChain conversational context
- Hybrid **RAG system** (Vector + BM25, RRF fusion) with **Redis semantic cache**, reducing response time by **100x**
- React/TypeScript wizard for multi-cloud OAuth integration (Google Drive, SharePoint, S3) and automatic indexing
- **Stack:** Java 17, Spring Boot, FastAPI, LangChain, Qdrant, Redis, PostgreSQL, React, TypeScript, n8n, Docker

#### **Project 2: Zyra – Autonomous Crypto Investment Platform**
- Designed and implemented a **distributed ETL pipeline** (Python, Redis, PostgreSQL) for market data ingestion, processing **5k+ transactions/minute**
- Event-driven architecture with **Redis Streams** for real-time data consistency and reliability
- Developed a **Grafana dashboard** connected to PostgreSQL for real-time monitoring and anomaly detection
- Automated alerts for price deviations and abnormal volumes, with immediate incident response
- **Predictive analytics system** to anticipate market trends and optimize investment decisions
- **40% reduction** in strategic indicator processing time
- **Stack:** Python, Redis, PostgreSQL, Grafana, Docker

#### **Project 1: BrainBoost – Comprehensive Educational Platform**
- **Microservices architecture** for an AI-powered educational platform for primary school students
- **Multimodal chatbot** handling text, images (OCR), audio (transcription), and PDFs with age-appropriate AI filtering
- Hybrid **RAG system** (Qdrant + BM25) with Redis semantic cache, reducing response time by **100x** via adaptive reranking
- React back-office for educators: customization of hints, moderation rules, multilingual support, and AI response validation
- Integrated **Langfuse** for LLM observability: end-to-end tracing, LangChain debugging, API cost tracking, and automated scoring
- **Stack:** Java 17, Spring Boot, Python, Django REST, React, TypeScript, LangChain, Qdrant, Redis, PostgreSQL, MLflow, Docker, Langfuse, Jira

---

### 🤖 **Data Scientist Intern — Digital Place** (Tangier, Morocco) | *06/2024 – 09/2024*
- Designed and developed a **multichannel intelligent customer assistant** (text + voice), bilingual French/Darija, for a Moroccan banking app, reducing query processing time by **40%**
- **Multilingual RAG system** (LangChain, Groq API, Qdrant) with contextual retrieval pipeline tailored to Moroccan banking vocabulary
- **FastAPI conversational API** with **React Native** integration for cross-platform mobile deployment (iOS/Android)
- Iterative user testing with banking compliance validation
- Trained banking teams and authored comprehensive technical and functional documentation
- **Stack:** FastAPI, LangChain, Groq API, Qdrant, React Native, Git, Jira | Agile Methodology

---

## 🚀 Featured Projects

### 📊 **Real-Time E-Commerce Streaming Analytics Platform**
- **Event-driven real-time architecture** (Kafka, PyFlink, FastAPI, Redis) for fraud detection, recommendations, and inventory forecasting, processing **2.7M+ events**
- 3 **PyFlink jobs** (tumbling/session/sliding windows) with feature engineering (90+ features) and ML models (RandomForest, Prophet+ARIMA)
- FastAPI REST API (5 endpoints) with Kafka consumers and Redis cache, **Iceberg/dbt lakehouse** (Bronze/Silver/Gold)
- **Prometheus/Grafana monitoring** (7 alerts, 20 panels) and Airflow orchestration, 13 Docker Compose services
- **Results:** 94% fraud accuracy | Latency < 500ms | 177 tests, 78% coverage
- **Stack:** Apache Kafka, PyFlink, FastAPI, Redis, scikit-learn, Apache Iceberg, dbt, MinIO, Prometheus, Grafana, Airflow, Docker

### 💰 **CryptoVibe – Crypto Market Sentiment Analysis**
- Automated ETL pipeline for ingesting and processing crypto data from social media and market prices (BTC, ETH, SOL)
- Hybrid sentiment analysis (**custom VADER + fine-tuned RoBERTa**) orchestrated via **Apache Airflow**
- **Intelligent RAG chatbot** (LangChain, Pinecone, Llama 3 – Groq) with conversational memory and RAGAS evaluation
- FastAPI backend and interactive React dashboard for trend visualization and sentiment/price correlations
- **Stack:** Python, FastAPI, Pinecone, Groq, HuggingFace, React, Apache Airflow, Docker, GitHub Actions

### 🛒 **Financial Data Pipeline – AWS (Medallion Architecture)**
- Automated ETL pipeline with **Medallion architecture** (Bronze/Silver/Gold) for processing transactional data of **10k+ products**
- Orchestration: MySQL (RDS) → AWS DMS → S3 → AWS Glue (PySpark) → Redshift
- **QuickSight dashboards** for trend analysis and business reporting
- **Stack:** AWS (DMS, RDS MySQL, Glue, Lambda, Step Functions, S3, Redshift, QuickSight), Python (PySpark, Boto3), SQL

### 🎓 **Educational Assistant**
- Multimodal AI assistant for personalized educational support
- Automated analysis and organization of educational resources with performance tracking
- **Stack:** Python, FastAPI, Streamlit, LlamaIndex, Qdrant, LangChain, Whisper, MLflow, Postman

---

## 🧠 Technical Skills & Technologies

### 💻 Programming & Frameworks
| Category | Technologies |
|-----------|---------------|
| **Languages** | ![Python](https://img.shields.io/badge/-Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Java](https://img.shields.io/badge/-Java%2017-007396?style=for-the-badge&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) ![Django](https://img.shields.io/badge/-Django-092E20?style=for-the-badge&logo=django&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/-React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![React Native](https://img.shields.io/badge/-React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) |

---

### 📊 Data Engineering & Big Data
| Category | Technologies |
|-----------|---------------|
| **ETL & Processing** | ![Apache Spark](https://img.shields.io/badge/-Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white) ![Airflow](https://img.shields.io/badge/-Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white) ![dbt](https://img.shields.io/badge/-dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white) ![AWS Glue](https://img.shields.io/badge/-AWS%20Glue-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white) |
| **Streaming** | ![Kafka](https://img.shields.io/badge/-Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white) ![PyFlink](https://img.shields.io/badge/-PyFlink-E6526F?style=for-the-badge&logo=apacheflink&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) |
| **Cloud & Storage** | ![AWS](https://img.shields.io/badge/-AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white) ![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white) ![Redshift](https://img.shields.io/badge/-Amazon%20Redshift-232F3E?style=for-the-badge&logo=amazonredshift&logoColor=white) |

---

### 🤖 AI & Machine Learning
| Category | Technologies |
|-----------|---------------|
| **Frameworks** | ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white) ![XGBoost](https://img.shields.io/badge/-XGBoost-006600?style=for-the-badge&logo=xgboost&logoColor=white) |
| **Generative AI & RAG** | ![LangChain](https://img.shields.io/badge/-LangChain-000000?style=for-the-badge&logo=chainlink&logoColor=white) ![LlamaIndex](https://img.shields.io/badge/-LlamaIndex-FFD21E?style=for-the-badge) ![HuggingFace](https://img.shields.io/badge/-HuggingFace-FEDB00?style=for-the-badge&logo=huggingface&logoColor=black) |
| **MLOps & Observability** | ![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white) ![Langfuse](https://img.shields.io/badge/-Langfuse-000000?style=for-the-badge) |

---

### 🗄️ Databases & Vector Stores
| Category | Technologies |
|-----------|---------------|
| **Relational** | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) |
| **NoSQL & Caching** | ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) |
| **Vector Databases** | ![Qdrant](https://img.shields.io/badge/-Qdrant-FF0000?style=for-the-badge&logo=qdrant&logoColor=white) ![Pinecone](https://img.shields.io/badge/-Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white) |

---

### ☁️ Cloud, DevOps & Monitoring
| Category | Technologies |
|-----------|---------------|
| **Infrastructure** | ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white) |
| **CI/CD & Versioning** | ![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) |
| **Monitoring** | ![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) |
| **Security** | ![Keycloak](https://img.shields.io/badge/-Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white) |

---

### 📈 Data Visualization & BI
| Tools | Icons |
|--------|--------|
| **Power BI** | ![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) |
| **QuickSight** | ![QuickSight](https://img.shields.io/badge/-QuickSight-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white) |
| **Grafana** | ![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) |

---

### 🧩 Methodologies & Architecture
- **Architecture:** Microservices, Medallion Architecture, Event-Driven
- **Project Management:** Agile/Scrum, Jira
- **Languages:** Arabic (Fluent) | French (Fluent)

---

## 🏆 Certifications

- 🎓 **IBM Data Science Professional Certificate**
- 🧠 **Machine Learning with Python (Coursera)**
- 🗃️ **Databases and SQL for Data Science (Coursera)**
- ⚙️ **Deep Learning Mastery (Udemy)**
- 📊 **Power BI Data Analysis (Microsoft)**

---

## 🌍 Extracurricular Activities

- 🎤 **Event Organizer** – ENSA Tétouan Forum
- 💻 **Community Member** – Moroccan Microsoft Community
- 🤝 **Networking** – AI & Data Science meetups

---

## 📈 GitHub Insights

<p align="center">
<a href="https://github.com/zakariaeyahya">
	<picture>
	<source srcset="https://github-readme-stats.vercel.app/api?username=zakariaeyahya&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000"/>
	<img src="https://github-readme-stats.vercel.app/api?username=zakariaeyahya&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000">
	</picture>
</a>
<a href="https://github.com/zakariaeyahya">
	<picture>
	<source srcset="https://github-readme-stats.vercel.app/api/top-langs?username=zakariaeyahya&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"/>
	<img src="https://github-readme-stats.vercel.app/api/top-langs?username=zakariaeyahya&layout=compact&langs_count=8&theme=tokyonight&hide_border=true">
	</picture>
</a>

[![Profile views](https://u8views.com/api/v1/github/profiles/105231126/views/day-week-month-total-count.svg)](https://u8views.com/github/zakariaeyahya)
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MohaElbadry/MohaElbadry/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MohaElbadry/MohaElbadry/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/MohaElbadry/MohaElbadry/output/github-contribution-grid-snake.svg">
</picture>

---

## 📫 Let's Connect!

<p align="center">
  <a href="https://www.linkedin.com/in/zakariae-yahya/">
    <img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/>
  </a>
  <a href="mailto:zakariae.yh@gmail.com">
    <img src="https://skillicons.dev/icons?i=gmail" alt="Email"/>
  </a>
  <a href="https://github.com/zakariaeyahya">
    <img src="https://skillicons.dev/icons?i=github" alt="GitHub"/>
  </a>
</p>

---

### 💡 Fun Fact
*"I love transforming complex data into intelligent systems — building bridges between algorithms, people, and innovation."*
