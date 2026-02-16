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

> Ingénieur Data Engineer & AI Developer, expert en pipelines de données temps réel, Apache Spark, Kafka et architectures distribuées. Expérience en mise en production de plateformes data et systèmes analytiques à grande échelle, avec fortes contraintes de latence, scalabilité et observabilité. Motivé par la construction de solutions data robustes, performantes et industrialisées.

---

## 🎓 Education

**École Nationale des Sciences Appliquées – Tétouan**
🎓 *Ingénierie en Sciences des Données, Big Data & IA (2021 – 2026)*

---

## 💼 Professional Experience

### 🏦 Data/ML Engineer Intern — **Banque Centrale Populaire** (Casablanca) | *02/2026 – 08/2026*
#### **Système de Détection de Fraude Bancaire Temps Réel (PFE – Entité Architecture Groupe)**
- Conception d'une **architecture Big Data temps réel** pour la détection de fraude sur virements instantanés, basée sur **Apache Kafka, Spark Streaming et 4 microservices** (Spring Boot / FastAPI), avec une latence de scoring end-to-end **< 100 ms**
- Développement du **pipeline de traitement distribué** : ingestion événementielle (Kafka), enrichissement comportemental temps réel et feature engineering avancé
- Traitement batch des historiques transactionnels via **Apache Spark** (PySpark, Spark SQL) : nettoyage, gestion du déséquilibre des classes (SMOTE), réduction dimensionnelle (394 → 263 features)
- Entraînement et évaluation de modèles ML : **Isolation Forest** (détection d'anomalies) + **XGBoost / Random Forest** (supervisé), avec règles métier anti-APP et anti-ATO. Versioning des modèles via **MLflow**
- Développement d'un **dashboard de monitoring temps réel** (React / Next.js, TypeScript, Material-UI) : visualisation des transactions, gestion des alertes par sévérité, module de simulation
- Mise en place de la sécurité : **Keycloak** (OAuth2 / OpenID Connect / JWT), chiffrement **TLS 1.3 / mTLS** inter-services, **AES-256** au repos
- **Résultats :** Précision > 92% | Faux positifs < 2% | Latence < 100 ms | Disponibilité 99.9%
- **Stack :** Apache Kafka, Spark (PySpark), Spring Boot, FastAPI, Redis, PostgreSQL, React / Next.js, TypeScript, XGBoost, Scikit-learn, MLflow, Keycloak, Docker, Prometheus / Grafana

---

### 🧠 Data Scientist Intern — **Izemx** (Paris, France) | *02/2025 – 02/2026*

#### **Projet 3 : IAVIA – Plateforme Multi-Agents IA Enterprise**
- Architecture **microservices** (Java Spring Boot + Python FastAPI) pour plateforme multi-agents IA avec isolation mémoire par agent
- **Memory Service** unifié multi-canal (Web, Slack, Teams, Telegram, WhatsApp) avec contexte conversationnel LangChain
- Système **RAG hybride** (Vector + BM25, RRF fusion) avec **cache sémantique Redis** réduisant de **100x** le temps de réponse
- Wizard React/TypeScript pour intégration OAuth multi-cloud (Google Drive, SharePoint, S3) et indexation automatique
- **Stack :** Java 17, Spring Boot, FastAPI, LangChain, Qdrant, Redis, PostgreSQL, React, TypeScript, n8n, Docker

#### **Projet 2 : Zyra – Plateforme d'investissement crypto autonome**
- Conception et implémentation d'un **pipeline ETL distribué** (Python, Redis, PostgreSQL) pour l'ingestion de données de marchés avec traitement de **5k+ transactions/minute**
- Architecture événementielle avec **Redis Streams** pour la cohérence et fiabilité des flux de données temps réel
- Développement d'un **dashboard Grafana** connecté à PostgreSQL pour le monitoring temps réel et la détection d'anomalies transactionnelles
- Alertes automatiques sur les écarts de prix et volumes anormaux, réactivité immédiate sur les incidents
- Système d'**analyse prédictive** pour anticiper les tendances du marché et optimiser les décisions d'investissement
- Réduction de **40%** du temps de traitement des indicateurs stratégiques
- **Stack :** Python, Redis, PostgreSQL, Grafana, Docker

#### **Projet 1 : BrainBoost – Plateforme éducative complète**
- Architecture **microservices** pour plateforme d'accompagnement scolaire IA destinée aux élèves du primaire
- Chatbot **multimodal** traitant texte, images (OCR), audio (transcription) et PDF avec filtrage intelligent IA adapté à l'âge des enfants
- Système **RAG hybride** (Qdrant + BM25) avec cache sémantique Redis, réduisant le temps de réponse de **100x** via reranking adaptatif
- Back-office React pour éducateurs : personnalisation des indices, règles de modération, support multilingue et validation des réponses IA
- Intégration de **Langfuse** pour l'observabilité LLM : tracing end-to-end, debugging LangChain, suivi des coûts API et scoring automatisé
- **Stack :** Java 17, Spring Boot, Python, Django REST, React, TypeScript, LangChain, Qdrant, Redis, PostgreSQL, MLflow, Docker, Langfuse, Jira

---

### 🤖 Data Scientist Intern — **Digital Place** (Tanger, Morocco) | *06/2024 – 09/2024*
- Conception et développement d'un **assistant client intelligent multicanal** (texte + vocal) bilingue français/darija pour application bancaire marocaine, réduisant de **40%** le temps de traitement des requêtes
- Système **RAG multilingue** (LangChain, Groq API, Qdrant) avec pipeline de récupération contextuelle adapté au vocabulaire bancaire marocain
- API conversationnelle **FastAPI** avec intégration **React Native** pour déploiement mobile cross-platform (iOS/Android)
- Tests utilisateurs itératifs avec validation métier bancaire pour conformité réglementaire
- Formation des équipes SGI et rédaction de la documentation technique et fonctionnelle complète
- **Stack :** FastAPI, LangChain, Groq API, Qdrant, React Native, Git, Jira | Méthodologie Agile

---

## 🚀 Featured Projects

### 📊 **Plateforme de Streaming Analytics E-Commerce Temps Réel**
- Architecture **event-driven** temps réel (Kafka, PyFlink, FastAPI, Redis) pour détection de fraude, recommandations et prévision d'inventaire, traitant **2.7M+ événements**
- 3 jobs **PyFlink** (fenêtres tumbling/session/sliding) avec feature engineering (90+ features) et modèles ML (RandomForest, Prophet+ARIMA)
- API REST FastAPI (5 endpoints) avec Kafka consumers et cache Redis, lakehouse **Iceberg/dbt** (Bronze/Silver/Gold)
- Monitoring **Prometheus/Grafana** (7 alertes, 20 panels) et orchestration Airflow, 13 services Docker Compose
- **Résultats :** Précision fraude 94% | Latence < 500ms | 177 tests, 78% coverage
- **Stack :** Apache Kafka, PyFlink, FastAPI, Redis, scikit-learn, Apache Iceberg, dbt, MinIO, Prometheus, Grafana, Airflow, Docker

### 💰 **CryptoVibe – Analyse de sentiment des marchés crypto**
- Pipeline ETL automatisé pour l'ingestion et le traitement de données crypto issues des réseaux sociaux et des prix de marché (BTC, ETH, SOL)
- Analyse de sentiment hybride **VADER custom + RoBERTa fine-tuné** orchestrée via **Apache Airflow**
- Chatbot **RAG intelligent** (LangChain, Pinecone, Llama 3 – Groq) avec mémoire conversationnelle et évaluation RAGAS
- Backend FastAPI et dashboard React interactif pour la visualisation des tendances et corrélations sentiment/prix
- **Stack :** Python, FastAPI, Pinecone, Groq, HuggingFace, React, Apache Airflow, Docker, GitHub Actions

### 🛒 **Pipeline de Données Financières – AWS (Architecture Medallion)**
- Pipeline ETL automatisé avec architecture **Medallion** (Bronze/Silver/Gold) pour traiter des données transactionnelles de **10k+ produits**
- Orchestration : MySQL (RDS) → AWS DMS → S3 → AWS Glue (PySpark) → Redshift
- Dashboards **QuickSight** pour l'analyse de tendances et rapports métier
- **Stack :** AWS (DMS, RDS MySQL, Glue, Lambda, Step Functions, S3, Redshift, QuickSight), Python (PySpark, Boto3), SQL

### 🎓 **Educational Assistant**
- Assistant IA multimodal pour accompagnement éducatif personnalisé
- Analyse et organisation automatisée des ressources éducatives avec suivi de performance
- **Stack :** Python, FastAPI, Streamlit, LlamaIndex, Qdrant, LangChain, Whisper, MLflow, Postman

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
- **Architecture :** Microservices, Architecture Medallion, Event-Driven
- **Project Management :** Agile / Scrum, Jira
- **Languages :** Arabe (Courant) | Français (Courant)

---

## 🏆 Certifications

- 🎓 **IBM Data Science Professional Certificate**
- 🧠 **Machine Learning with Python (Coursera)**
- 🗃️ **Databases and SQL for Data Science (Coursera)**
- ⚙️ **Deep Learning Mastery (Udemy)**
- 📊 **Power BI Data Analysis (Microsoft)**

---

## 🌍 Extracurricular Activities

- 🎤 **Event Organizer** – Forum ENSA Tétouan
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

---
