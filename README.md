# Niraj Basnet

Computer Science student at the University of South Florida (Expected graduation: May 2028).  
I build SQL analytical models, dimensional data warehouses, and automated Python ETL pipelines, targeting **Data Analyst, Business Intelligence, and Data Engineering internships for 2027**.

[Portfolio](https://nirajbasnet.com.np/) · [Download Résumé](https://nirajbasnet.com.np/resume/) · [LinkedIn](https://www.linkedin.com/in/nirajbasnet009) · [Email](mailto:niraj.basnet009@gmail.com)

---

## Featured Work

### 1. [Olist Brazilian E-Commerce: SQL Analytics & Star Schema](https://github.com/nirajbasnet009/Ecommerce_Data_Modeling_SQL)
- **What I built:** An analytical data warehouse in MySQL 8.0 inside Docker auditing 100k+ customer transactions across 9 tables, engineering modular CTEs for Average Order Value (AOV), and designing a Kimball star schema centered on a 110,197-row sales fact table.
- **What you can inspect:** Open [`05_olap_modeling.sql`](https://github.com/nirajbasnet009/Ecommerce_Data_Modeling_SQL/blob/main/05_olap_modeling.sql) to review the order-item grain and referential integrity checks (0 orphaned foreign keys), and [`03_business_analysis.sql`](https://github.com/nirajbasnet009/Ecommerce_Data_Modeling_SQL/blob/main/03_business_analysis.sql) for CTE metric queries reconciling R$ 13,591,643.70 in delivered merchandise revenue.
- [Read Case Study](https://nirajbasnet.com.np/blog/olist-ecommerce-sql-analytics-and-olap-modeling/)

### 2. [TMDB Movie Data ETL Pipeline](https://github.com/nirajbasnet009/tmdb-etl-project)
- **What I built:** An automated batch Python pipeline extracting paginated movie data across the TMDB REST API, cleaning schema fields and parsing ISO dates in pandas, and enforcing pre-load data validation.
- **What you can inspect:** Open [`pipeline.py`](https://github.com/nirajbasnet009/tmdb-etl-project/blob/main/pipeline.py) for orchestrator execution and empty-data guardrails, and [`extract.py`](https://github.com/nirajbasnet009/tmdb-etl-project/blob/main/extract.py) for requests timeout handling and bounded retry loops that safeguard existing CSVs on HTTP 401 failures.
- [Read Case Study](https://nirajbasnet.com.np/blog/tmdb-movie-data-etl-pipeline/)

---

## Technical Skills Demonstrated in My Code

- **Databases & Modeling:** SQL, MySQL 8.0, CTEs, Window Functions, Dimensional Modeling, Kimball Star Schema, 1NF-3NF Relational Normalization, Docker.
- **Programming & ETL:** Python, Pandas, NumPy, REST APIs, JSON & CSV Processing, Batch ETL Pipelines, Data Validation, Error Handling, Git.

---

## Education

**University of South Florida (USF)** - Tampa, FL  
*Bachelor of Science in Computer Science* | GPA: 3.69 / 4.00  
*Expected Graduation:* May 2028  
*Relevant Coursework:* Database Systems, Data Structures & Algorithms, Artificial Intelligence, Probability & Statistics, Computer Logic & Design
