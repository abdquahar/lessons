# Data Engineering Course

A 12-week hands-on program covering the full data engineering stack — from SQL fundamentals to building, scheduling, and deploying production-grade data pipelines.

---

## What You Will Build

By Week 12, you will have:

- A working local development environment (PostgreSQL, Python, Git, Docker)
- 10+ projects and labs pushed to a public GitHub portfolio
- A containerised, cloud-deployed end-to-end pipeline
- A Power BI dashboard connected to a data warehouse you built
- Interview-ready SQL, Python, and system design skills

---

## Who This Is For

- Analysts or developers who want to move into data engineering
- Beginners with no prior database or pipeline experience
- Anyone who wants to go from zero to job-ready in one structured program

**Prerequisites:** A Windows computer. No prior SQL, Python, or cloud experience required.

---

## Tools Covered

| Category | Tools |
|----------|-------|
| Database | PostgreSQL, pgAdmin |
| Query language | SQL (PostgreSQL dialect) |
| Programming | Python 3, pandas, requests, psycopg2 |
| Web scraping | BeautifulSoup, Playwright |
| File formats | CSV, JSON, Excel, Parquet |
| Transformation | dbt (data build tool) |
| Orchestration | Apache Airflow |
| Cloud | Google Cloud (BigQuery, Cloud Storage) or Azure (Blob Storage, Azure SQL) |
| Containerisation | Docker, Docker Compose |
| Visualisation | Power BI |
| Streaming | Apache Kafka |
| Version control | Git, GitHub |

---

## 12-Week Curriculum

| Week | Theme | Deliverable |
|------|-------|-------------|
| [**1**](week1/) | Introduction to Data Engineering & SQL Foundations | Assignment: customer database + 20 business questions |
| [**2**](week2/) | Intermediate SQL & Database Design | Project: Retail Sales Analytics Database |
| [**3**](week3/) | Python for Data Engineering | Project: Sales Data Cleaning Pipeline |
| [**4**](week4/) | Data Wrangling & APIs | Project: Weather Data API Pipeline (API → CSV → PostgreSQL) |
| [**5**](week5/) | Web Scraping & File Processing | Project: Remote Job Market Pipeline (Website → Playwright → PostgreSQL) |
| [**6**](week6/) | ETL Design & Data Warehousing | Project: Retail Data Warehouse (schema design + ETL pipeline) |
| [**7**](week7/) | Workflow Orchestration with Airflow | Project: Automated ETL Pipeline (API → PostgreSQL → Warehouse) |
| [**8**](week8/) | Cloud Data Engineering | Project: Deploy an ETL pipeline to the cloud |
| [**9**](week9/) | Analytics Engineering with dbt | Project: Customer Analytics Warehouse (raw → analytics-ready models) |
| [**10**](week10/) | Docker, Data Quality & Production Practices | Project: Containerise an ETL application |
| [**11**](week11/) | Streaming Concepts & End-to-End Pipeline | Project: End-to-End Data Platform (API/Web → PostgreSQL → Airflow → Warehouse → Power BI) |
| [**12**](week12/) | Capstone Project & Career Preparation | Capstone: full production pipeline + presentation + portfolio review |

> Weeks are released progressively. Pull the latest content each week with `git pull origin main`.

---

## Week-by-Week Detail

### Week 1 — Introduction to Data Engineering & SQL Foundations

**Learning objectives:**
- Understand the role of a data engineer
- Learn the modern data stack
- Set up the development environment
- Write basic SQL queries

**Topics:** What is Data Engineering · DE vs Data Analysis vs Data Science · Data lifecycle · Installing PostgreSQL · Git & GitHub · SELECT · WHERE · ORDER BY · LIMIT · DISTINCT

**Labs:** PostgreSQL installation · GitHub setup · Load CSV into PostgreSQL

**Assignment:** Build a simple customer database and answer 20 business questions using SQL.

---

### Week 2 — Intermediate SQL & Database Design

**Topics:** JOINs · Aggregations · GROUP BY · HAVING · CASE WHEN · Subqueries · CTEs · Window functions · Primary keys · Foreign keys · Indexes

**Project:** Retail Sales Analytics Database

**Assignment:** Write SQL to generate sales dashboards.

---

### Week 3 — Python for Data Engineering

**Topics:** Python fundamentals · Functions · Modules · File handling · Exception handling · Object-oriented basics

**Libraries:** pandas · requests

**Lab:** Read and clean multiple CSV files.

**Project:** Sales Data Cleaning Pipeline

---

### Week 4 — Data Wrangling & APIs

**Topics:** REST APIs · Authentication · Pagination · JSON · Data validation · Data cleaning · Logging · Configuration files

**Libraries:** requests · pandas

**Project:** Weather Data API Pipeline

**Pipeline:** API → CSV → PostgreSQL

---

### Week 5 — Web Scraping & File Processing

**Topics:** Static scraping · Dynamic scraping · HTML structure · CSS selectors · BeautifulSoup · Playwright

**File formats:** CSV · JSON · Excel · Parquet

**Project:** Remote Job Market Pipeline

**Pipeline:** Website → Playwright → PostgreSQL

---

### Week 6 — ETL Design & Data Warehousing

**Topics:** ETL vs ELT · Incremental loading · Batch processing · Slowly Changing Dimensions · Fact tables · Dimension tables · Star schema

**Project:** Retail Data Warehouse

**Deliverable:** Warehouse schema design and ETL pipeline.

---

### Week 7 — Workflow Orchestration with Airflow

**Topics:** DAGs · Operators · Scheduling · Retries · Dependencies · Variables · Connections · Logging

**Project:** Automated ETL Pipeline

**Pipeline:** API → PostgreSQL → Warehouse

---

### Week 8 — Cloud Data Engineering

**Topics:** Cloud fundamentals · Object storage · Cloud databases · IAM basics · Cost awareness

**Platform (choose one):** Google Cloud (Cloud Storage, BigQuery) or Azure (Blob Storage, Azure SQL)

**Project:** Deploy an ETL pipeline to the cloud.

---

### Week 9 — Analytics Engineering with dbt

**Topics:** dbt project structure · Sources · Models · Tests · Documentation · Lineage

**Project:** Customer Analytics Warehouse

**Deliverable:** Transform raw warehouse tables into analytics-ready models.

---

### Week 10 — Docker, Data Quality & Production Practices

**Topics:** Docker fundamentals · Docker Compose · Environment variables · Logging · Error handling · Data quality · Testing · Project documentation

**Project:** Containerise an ETL application.

---

### Week 11 — Streaming Concepts & End-to-End Pipeline

**Topics:** Batch vs Streaming · Event-driven systems · Apache Kafka concepts · Data architecture · Pipeline monitoring

**Project:** End-to-End Data Platform

**Pipeline:** API / Web → PostgreSQL → Airflow → Warehouse → Power BI

---

### Week 12 — Capstone Project & Career Preparation

**Capstone requirements:**

- Data ingestion from an API or dynamic website
- Automated ETL orchestration (Airflow)
- PostgreSQL data warehouse
- Data validation and quality checks
- Dockerised deployment
- Cloud deployment (optional)
- Power BI dashboard
- Technical documentation and architecture diagram

**Presentation:** Each learner presents their business problem, architecture, data model, ETL workflow, dashboard insights, and lessons learned.

**Career readiness:** GitHub portfolio review · CV optimisation · LinkedIn profile · Mock SQL interview · Mock Python interview · Data engineering system design basics · Internship and job application strategies

---

## Getting Started

### First time (no Git yet)

1. Go to the course GitHub repository
2. Click the green **Code** button → **Download ZIP**
3. Extract to `C:\Users\YourName\lessons\`
4. Open the `week1/` folder in VS Code or Jupyter
5. Start with [week1/README.md](week1/README.md)

### After completing Week 1 Lesson 3 (Git setup)

Replace your downloaded copy with a proper clone:

```bash
git clone https://github.com/[instructor]/de-course.git
cd de-course
```

Pull new content each week:

```bash
git pull origin main
```

---

## Repository Structure

```
lessons/
├── README.md          ← You are here
├── week1/             ← Available now
├── week2/             ← Released at Week 2
│   ...
└── week12/            ← Released at Week 12
```

Each week folder contains:

```
weekN/
├── README.md                        ← Week overview, schedule, objectives
├── lessonN_[topic].ipynb            ← Lesson notebooks
├── activities/
│   ├── weekN_activities.ipynb       ← Discussion, reading club, project review
│   └── engineering_growth_plan.ipynb  ← (Week 1 only)
├── labs/
│   └── labN_[topic].ipynb           ← Step-by-step hands-on lab
├── exercises/
│   └── [topic]_exercises.ipynb      ← Practice problems with solutions
└── data/
    └── *.csv / *.json               ← Sample datasets
```

---

## Submitting Your Work

Your completed work lives in **your own GitHub repository** (created in Week 1 Lesson 3).

```bash
git add week1/exercises/sql_exercises.ipynb
git commit -m "Complete Week 1 SQL exercises"
git push
```

Share your repository URL with your instructor so progress can be reviewed.

---

## Getting Help

| Situation | What to do |
|-----------|-----------|
| Stuck on a technical problem | Try for 20–30 minutes, then post in the group channel with the error message |
| Falling behind | Tell your instructor immediately — do not silently fall further behind |
| Environment not working | Re-read the setup lesson; check the Troubleshooting section in that week's notebook |
| Confused by a concept | Post the question publicly — if you are confused, someone else is too |

---

## Instructor

*Pipeline Africa*
