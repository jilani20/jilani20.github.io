---
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

- Pursuing Post Graduate Program in AI with Deep Learning, McCombs School of Business — University of Texas, Austin, 2026
- Post Graduate Program in Data Science and Business Analytics, McCombs School of Business — University of Texas, Austin, 2025
- Master of Computer Applications (MCA), Osmania University, India, 2006
- Bachelor of Mathematics, Acharya Nagarjuna University, India, 2001

# Work experience

- 2025 – present: Principal Consultant, BCBS MN (through Improving)
  * Evaluated and integrated GPT and Claude family models for natural-language-to-SQL and analytics summarization
  * Built a Databricks Genie self-service layer for population-health metrics
  * Population health Q&A hackathon: built a proof-of-concept application demonstrating LLM-powered querying of OLAP data
  * Candidate-matching hackathon (2nd place): owned the model/RAG layer for a candidate-to-opportunity matching system, using a locally-hosted Ollama LLM to semantically match candidates to opportunities and return match percentages as structured JSON
  * Technologies: Databricks, Databricks Genie, SQL, GPT, Claude, Claude Code, Cursor, Ollama, RAG, JSON

- 2025: Sr. Architect, Persistent Systems — Risk Data Modernization
  * Designed enterprise data platform architecture migrating credit-risk modules to Azure Databricks on the medallion architecture
  * Defined Python-based architecture and core framework to support the migration
  * Supported migrating BI reports from Cognos to Microsoft Power BI
  * Technologies: Python, Azure, Databricks, Power BI, Cognos

- 2016 – 2025: Principal Engineer, Optum — In-Office Assessment (IOA) & Medication Gap models
  * Built ensemble models (LightGBM, XGBoost, Random Forest) analyzing 2M+ member records — 83% accuracy, 23% higher enrollment, 31% better HEDIS quality-measure completion vs. rule-based baseline
  * Deployed the model on a distributed PySpark cluster, driving a 20% year-over-year increase in prospective returns
  * Built a medication-adherence model (HEDIS/CMS Star PDC measures; PySpark on Azure Databricks) deployed as an Azure ML managed endpoint, with MLOps drift detection and automated retraining on Delta Lake
  * Technologies: LightGBM, XGBoost, Random Forest, PySpark, Bayesian Optimization, A/B Testing, Azure Databricks, Ensemble Methods, Azure ML, Delta Lake, MLOps

- 2016 – 2025: Principal Engineer, Optum — Enterprise Data Platform Engineering
  * Architected a Kafka streaming platform processing 10M+ events/day; led migration to an Azure Databricks Delta Lakehouse (bronze/silver/gold/platinum layers)
  * Built reusable PySpark transformation libraries adopted by 4+ downstream teams, cutting development time roughly in half
  * Delivered pipelines processing ~100M records/day across 40+ clients and 3 lines of business, with automated PII/PHI governance (Unity Catalog, RBAC, HIPAA controls)
  * Designed an event-driven microservices platform (99.99% uptime, <200ms SLAs)
  * Optimized Databricks cluster/job configuration, cutting compute costs 30% and processing time 50%
  * Technologies: Azure, Databricks, PySpark, Spark, Kafka, Python, Unity Catalog, Spring Boot, Kubernetes, React, Terraform, Airflow

- 2016 – 2018: Sr Hadoop Developer, ICON IT Group (contractor via Optum) — PAFGEN
  * Built a high-volume Spark/Kafka pipeline (150M+ records) generating 500K+ PDF documents on user-defined criteria
  * Built Oozie coordinator workflows: file-arrival-triggered, time-based scheduled, and dependency-chained workflows
  * Worked across the Hadoop ecosystem (MapReduce, Hive, Sqoop, HBase) and Spring-based APIs on OpenShift
  * Technologies: Java, Spark, Hive, Oozie, Airflow, PySpark, Spring Boot

- 2015: Software Architect, CES Technology Services — SingleDigits BAP
  * Designed a real-time message-processing architecture (Storm, Kafka) for a managed guest-WiFi platform
  * Architected a backend usage-trend and bandwidth-projection service (REST/JSON API) for monthly capacity planning (D3.js frontend built with a teammate)
  * Technologies: Java, Spring, Storm, REST, Kafka, Elastic Search, Log stash, Kibana, PostgreSQL, OAuth API

- 2014 – 2015: Sr. Analyst, Bank of America
  * Sourced and prepared loan-level and delinquency-history data feeding Moody's RiskFrontier portfolio credit-risk models, supporting PD/LGD-based loss forecasting for CCAR regulatory stress testing
  * Migrated Cloudera 4.x to 5.3, bringing workflows onto YARN-based resource management
  * Technologies: Java, MapReduce, YARN, Hive, Pig, Sqoop, Oozie, Oracle, Teradata, Netezza, Autosys

- 2014: Sr. Technical Lead, Adroitent
  * Built a content-ingestion pipeline converting a large document repository into Solr, including custom relevance-ranking logic
  * Technologies: Java, Lucid Works Solr, Camel, Kafka, MS SQL Server, Couchbase, Maven, TFS

- 2011 – 2014: Technical Project Lead, ReThink IT Services
  * Led MapReduce-based vendor-behavior modeling, segmentation, and multidimensional spend analytics
  * Delivered a rules-driven organization management system (JBoss Drools)

- 2010 – 2011: Sr Software Engineer, United Health Group
  * Built server-side Java/Spring/Hibernate components for the Oxford Health Plan platform

- 2006 – 2010: Sr Software Engineer, CTE
  * Delivered enterprise Java applications (JSP/Struts), including a rules-engine-driven approval workflow and a test management system

# Skills

- Data Science
  * Statistics, Feature Engineering, Data Analysis, Cleaning and Data Visualization, EDA, A/B Testing
  * Unsupervised Learning (K-Means, Hierarchical Clustering)
- Healthcare Domain
  * HEDIS, CMS Star Ratings, NCQA Quality Measures
  * Population Health Management, Medicare/Medicaid/ACA Quality Reporting
- ML, Deep Learning & AI
  * PySpark, PyTorch, TensorFlow/Keras, CNN, Transfer Learning, Focal Loss
  * AWS SageMaker (XGBoost, hyperparameter tuning, endpoint deployment), scikit-learn
  * Time Series, Causal Inference
- Generative AI & NLP
  * RAG (LangChain, ChromaDB), Sentence-Transformer Embeddings
  * Local LLM Inference (Mistral-7B via llama.cpp, Ollama)
  * Prompt Engineering, LLM-as-Judge Evaluation
- MLOps and Deployment
  * ML Pipeline, Model Evaluation and Monitoring, MLOps, Data Drift Handling
  * Docker, CI/CD Pipelines, Model Registry
- Big Data & Streaming
  * Apache Spark, PySpark, Kafka, Elasticsearch, Airflow, Avro, Parquet, Delta Lake, Unity Catalog
- Cloud Technologies
  * Azure ML, Databricks, AKS, ADLS Gen 2, Azure OpenAI, AWS (S3, EC2), GCP (Familiar)
- Database
  * Oracle, MySQL, SQL Server, PostgreSQL, NoSQL (CosmosDB, HBase, MongoDB)
- Architecture & API Design
  * Microservices Architecture, Event-Driven Architecture, Cloud-Native Architecture
  * API Design (REST/SOAP), SOA, Swagger, JMS
- Security
  * Azure IAM, JWT, OAuth 2.0, Key Vault, API Security
- Methodologies
  * Agile (Scrum, Kanban), Scaled Agile Framework (SAFe), Shift Left, DevOps Practices, CI/CD (Jenkins)
- Monitoring & Observability
  * Grafana, Azure Monitor, Logging and Monitoring
- Languages
  * Python, Java, Scala
- Tools
  * Jupyter, Colab, MLflow, Optuna, Comet ML, GitHub, Boto3, VSCode, IntelliJ, Spring Boot, FastAPI, Postman, Rally, Aha, JIRA

# Certifications

- IEEE Senior Member, elevated May 2026
- Sun Certified Java Programmer, 2006

# Open source

- [ttgrasp](https://github.com/jilani20/ttgrasp) — a personal train/test DataFrame-profiling utility (Apache-2.0, 100% Python), published to PyPI and used across coursework projects. Currently validating a bugfix via a TestPyPI release candidate (0.0.9rc0).
