# Hi, I'm Uday Vimal 👋

I'm a **Data Analyst & AI Engineer** who turns messy data into decisions. I work across the full analytics stack — SQL deep-dives, Python EDA, BI dashboards, ML models, and production-grade LLM agents. I'm passionate about understanding user behavior, surfacing actionable insights, and automating the repetitive parts of analytics.

> Currently open to **Product Analytics / Business Analytics** roles. Comfortable with A/B experimentation, funnel analysis, user segmentation, churn modeling, and building self-service dashboards from scratch.

---

## 🛠 Tech Stack

**Languages & Query**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Analytics & BI**
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=flat&logo=googlesheets&logoColor=white)
![Looker](https://img.shields.io/badge/Looker-4285F4?style=flat&logo=looker&logoColor=white)

**Data Engineering**
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**ML & AI**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-000000?style=flat)

**AI Dev Tools**
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat&logo=cursor&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-CC785C?style=flat&logo=anthropic&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EF6821?style=flat&logo=n8n&logoColor=white)

---

## 📚 Table of Contents
- [Data Engineering](#data-engineering)
- [SQL](#sql)
- [Python & EDA](#python--eda)
- [Machine Learning](#machine-learning)
- [AI & LLM Agents](#ai--llm-agents)
- [Tableau & Dashboards](#tableau--dashboards)

---

# Data Engineering

Automated pipelines that move, transform, and serve data reliably — built with Airflow, PostgreSQL, Docker, and FastAPI.

| Project | Completion | Tools | Project Description |
|---|---|---|---|
| 🌦 [Weather Data ETL Pipeline](https://github.com/udayvimal/-Weather-Data-ETL-Pipeline-with-Apache-Airflow-PostgreSQL) | Feb 2025 | Python, Apache Airflow, PostgreSQL, Docker, Open-Meteo API | Production-ready ETL pipeline that fetches real-time weather metrics daily via API, parses and structures the data, and loads it into PostgreSQL — containerised with Docker for zero-config deployment and Airflow-scheduled for full automation. |
| 🧥 [Apparel Analytics Hub](https://github.com/udayvimal/apparel_analytics_hub) | 2025 | Python, Apache Airflow, Flask | Modular ETL pipeline with Airflow DAGs for ingesting apparel retail data, running transformations, and serving aggregated metrics through a Flask web app. |
| 🧠 [AI Context Engine](https://github.com/udayvimal/ai-context-engine) | 2025 | Python, FastAPI, Chrome Extension, WebSockets | Full-stack browser extension that captures, stores, and restores AI conversation context across sessions via a FastAPI backend — built using Cursor and Claude Code. |

---

# SQL

Deep-dive SQL projects covering fraud detection, pay equity, consumer pricing, and job market analytics — using CTEs, window functions, aggregations, and complex JOINs.

| Project | Area of Analysis | Project Description |
|---|---|---|
| 💡 [8-Week SQL Challenge](https://github.com/udayvimal/8-Week-SQL-Challenge) | Data analysis, transformation | Solutions to all 8 case studies from the [#8WeekSQLChallenge](https://8weeksqlchallenge.com) — covering data cleaning, aggregation, window functions, cohort analysis, and business KPI reporting. |
| 💼 [Job Market Analytics](https://github.com/udayvimal/JOBANALYTICS) | Market & demand analysis | SQL-driven job market analysis using CTEs, window functions, and YoY/MoM trend comparisons — with an automated Tableau dashboard tracking demand by skill, geography, and salary band. |
| 💳 [UPI Fraud Analysis](https://github.com/udayvimal/upi-fraud-analysis) | Fraud & anomaly detection | Analysed 15,000 synthetic UPI transactions using PostgreSQL — surfaced 5 anomaly detection rules: late-night transactions carry 19.2% fraud rate vs 0.8% mornings; amounts near ₹4,999/₹9,999 show 28–31% fraud rates. |
| 💰 [Indian Salary Gap Analysis](https://github.com/udayvimal/indian-salary-gap-analysis) | HR & pay equity analytics | Quantified an 18.2% gender pay gap across 8,000 Indian tech records — with Bangalore commanding a 32–35% city premium and MNCs paying 40.3% more than Indian corporates. Segmented by role, experience, and geography. |
| 🍔 [Swiggy Dark Patterns](https://github.com/udayvimal/swiggy-dark-patterns) | Pricing elasticity & consumer behavior | Exposed a 40–63% delivery fee surge during rain on Indian food platforms — r = −0.71 correlation between delivery time and satisfaction. Weekend platform fees 24.9% higher, costing users ₹864/year. |

---

# Python & EDA

Exploratory analysis projects tackling user behavior, pricing strategy, workforce analytics, and environmental data.

| Project | Area | Project Description | Libraries |
|---|---|---|---|
| 🌱 [HR Analytics](https://github.com/udayvimal/HR-ANALYTICS) | Employee segmentation & attrition | Analysed workforce data across 8,950 employees — segmented by education, department, and performance to model attrition drivers. Education level correlates with earnings (high school: ₹62K avg → PhD: ₹92K). Dashboard deployed on Netlify. | pandas, Faker, Tableau |
| 🛒 [Zepto vs Blinkit](https://github.com/udayvimal/ZEPTO-VS-BLINKIT) | Competitive & pricing analysis | Scraped and compared product pricing, discounts, and delivery performance across India's two largest quick-commerce platforms — revealing category dominance and pricing elasticity differences. | pandas, Selenium, matplotlib, seaborn |
| 💳 [UPI Fraud Analysis](https://github.com/udayvimal/upi-fraud-analysis) | Anomaly detection & user segmentation | EDA on 15K UPI transactions — built 5 segmentation-based fraud rules around time-of-day, recipient novelty, retry patterns, and amount clustering. | pandas, matplotlib, seaborn |
| 💰 [Indian Salary Gap Analysis](https://github.com/udayvimal/indian-salary-gap-analysis) | HR & compensation analytics | Statistical breakdown of gender pay gaps, city premiums, and MNC vs domestic pay across Indian tech — with visual comparisons by role, seniority, and company type. | pandas, matplotlib, seaborn |
| 🍔 [Swiggy Dark Patterns](https://github.com/udayvimal/swiggy-dark-patterns) | Consumer behavior & pricing | Quantified surge pricing mechanics on food delivery apps — used controlled comparisons to isolate weather, time, and demand as pricing levers. | pandas, matplotlib, seaborn |
| 🌫 [AQI Prediction](https://github.com/udayvimal/AQIPREDICTION) | Environmental analytics | Spatial interpolation and prediction of Air Quality Index across geographic regions — with interactive HTML map visualising AQI vs vegetation coverage. | Python, pandas, HTML |

---

# Machine Learning

End-to-end ML projects covering classification, regression, NLP, computer vision, and deployed prediction systems.

| Project | Area | Project Description | Libraries |
|---|---|---|---|
| 🤖 [ML Portfolio](https://github.com/udayvimal/machine-learning-portfolio) | ML / DL — 10 projects | Complete collection: hotel booking cancellation (logistic regression), road sign detection (CNN), real-time object detection (YOLO), user churn/auth anomaly detection, movie recommender, fake news NLP, YouTube ad demand forecasting, and more. | scikit-learn, TensorFlow, PyTorch, OpenCV, Streamlit |
| 🔐 [User Authentication ML System](https://github.com/udayvimal/User-Authentication-ML-Prediction-System) | Anomaly detection — Deployed | Full-stack app combining JWT user authentication with real-time ML predictions via a decision tree model. FastAPI backend + PostgreSQL deployed on Render; frontend on Netlify. | FastAPI, scikit-learn, PostgreSQL, SQLAlchemy |
| 🏨 [Hotel Booking Prediction](https://github.com/udayvimal/HOTEBOOKINGPREDICTION) | Demand forecasting / Churn | Predicted hotel booking cancellations (a user churn proxy) using logistic regression and tree-based models — enabling proactive demand management. | pandas, scikit-learn |
| 🎬 [Movie Recommendation System](https://github.com/udayvimal/MOVIE-RECOMMENDATION-SYSTEM) | Personalisation & user segmentation | Content-based filtering using TF-IDF and cosine similarity — recommends movies based on plot, genre, and metadata. | pandas, scikit-learn |
| 📰 [Fake News Predictor](https://github.com/udayvimal/fakenewspredicton) | NLP / Classification | TF-IDF vectorisation + ML classifier to detect misinformation — trained on labeled news article datasets. | pandas, scikit-learn, nltk |
| 📺 [YouTube Ads View Prediction](https://github.com/udayvimal/Youtube-ads-view-prediction-) | Regression / Demand forecasting | Predicted YouTube ad view counts from engagement signals (likes, comments, shares) — useful for media performance analytics. | pandas, scikit-learn |
| 📷 [Real-Time Object Detection](https://github.com/udayvimal/REAL-TIME-OBJECT-DETECTION-SYSTEM) | Computer vision | YOLOv8-based real-time object detection system implemented in Jupyter Notebook — supports custom YAML-defined object classes. | YOLOv8, OpenCV, Python |

---

# AI & LLM Agents

Agentic AI systems built with CrewAI, OpenAI, Gemini, and FastAPI — developed using **Cursor** and **Claude Code** for AI-accelerated development.

| Project | Tools | Project Description |
|---|---|---|
| 🧠 [LLM Portfolio](https://github.com/udayvimal/LLM-PORTFOLIO-UDAY) | CrewAI, OpenAI, Gemini, HuggingFace, FastAPI, Gradio | 6 agentic AI systems: multimodal medical agent (vision + voice + reasoning), finance analyst agent with custom dataset, image recognition chatbot (BLIP/CLIP), and a medical micro-agent suite for symptom analysis and lifestyle advice. |
| 🩺 [Blood Test Analyser](https://github.com/udayvimal/blood-test-analyser) | CrewAI, OpenAI, Python | Multi-agent CrewAI system that reads PDF blood test reports, interprets biomarker values, and generates plain-English medical summaries — built with Claude Code. |
| 📰 [Financial News Dashboard](https://github.com/udayvimal/financial-news-dashboard) | Python, Streamlit, FAISS, Embeddings | Streamlit dashboard that fetches financial news, embeds articles into a vector store, and surfaces the most relevant stories via semantic similarity search. |
| 📝 [Text Summarizer](https://github.com/udayvimal/Text-Summarizer) | Python, Docker, GitHub Actions | Extractive and abstractive text summarisation pipeline with a web interface — containerised with Docker and CI/CD via GitHub Actions. |
| 🧠 [AI Context Engine](https://github.com/udayvimal/ai-context-engine) | FastAPI, Chrome Extension, Python, WebSockets | Full-stack system capturing AI conversation history in the browser and restoring full context in new sessions — built with Cursor and Claude Code as core dev tools. |

---

# Tableau & Dashboards

Self-service dashboards built for business stakeholders — covering HR, job markets, quick-commerce, and competitive intelligence.

| Project | Description | Dashboard Link |
|---|---|---|
| 👥 [HR Analytics Dashboard](https://github.com/udayvimal/HR-ANALYTICS) | Interactive Tableau dashboard tracking workforce KPIs — headcount, attrition rate, gender distribution, department-level performance, and education-pay correlation across 8,950 employees. | [Dashboard](https://public.tableau.com/app/profile/uday.vimal/viz/Book4_17424976301220/HRSUMMARY) |
| 🛒 [Zepto vs Blinkit](https://github.com/udayvimal/ZEPTO-VS-BLINKIT) | Comparative BI dashboard covering pricing strategy, delivery speed, category dominance, and discount patterns across India's top two quick-commerce platforms. Includes a full BI storytelling presentation. | [Dashboard](https://public.tableau.com/views/ZEPTOVSBLINKIT-UDAYVIMAL/Dashboard1) · [Presentation](https://www.linkedin.com/posts/uday-vimal-9a1a3a253_dataanalytics-python-tableau-ugcPost-7344980857209704448-YHKA) |
| 💼 [Job Market Analytics](https://github.com/udayvimal/JOBANALYTICS) | Job market intelligence dashboard with geographic breakdowns, skill demand trends, salary comparisons, and YoY growth metrics — built on SQL-processed data with automated refresh. | Coming Soon |

---

## 🤖 How I Build

I use **[Cursor](https://cursor.sh)** (AI-powered IDE) and **[Claude Code](https://claude.ai/code)** (Anthropic's CLI) as core development tools — enabling faster prototyping, automated code review, and AI-assisted debugging across all my projects. I also use **n8n** for workflow automation and **Google Sheets** for quick ad-hoc analytics and stakeholder-ready reporting.

---

*Feel free to explore any project or reach out on [LinkedIn](https://linkedin.com/in/udayvimal)!*
