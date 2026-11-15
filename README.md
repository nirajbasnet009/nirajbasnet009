# Niraj Basnet

Computer Science student at the University of South Florida (USF '28).  
I build SQL analytical models, dimensional data warehouses, and automated Python ETL pipelines, targeting **Data Analyst, Business Intelligence, and Data Engineering internships**.

[Portfolio](https://nirajbasnet.com.np/) · [Resume](https://nirajbasnet.com.np/resume/) · [LinkedIn](https://www.linkedin.com/in/nirajbasnet009) · [Email](mailto:niraj.basnet009@gmail.com)

---

## Featured Projects

### 1. [Olist E-Commerce SQL Analytics & Dimensional Modeling](https://github.com/nirajbasnet009/Ecommerce_Data_Modeling_SQL)
*Targeting Data Analyst & Business Intelligence Roles* - [Read Case Study](https://nirajbasnet.com.np/blog/olist-ecommerce-sql-analytics-and-olap-modeling/)
- Built an end-to-end analytical workflow across 100k+ Brazilian customer orders in MySQL 8.0 on Docker.
- Implemented rigorous data hygiene audits (`03_data_hygiene_audits.sql`), resolving 160 missing dates and verifying 0 orphaned foreign keys.
- Engineered 4 business query suites (`04_business_analytics.sql`) using window functions, CTEs, and payment aggregations, isolating 23,073 credit card orders over 10 installments (R$ 4,008,189.17 merchandise total).
- Modeled a Kimball star schema (`05_olap_modeling.sql`) anchored by a 110,197-row `fact_sales` table at the order-item grain connected to 4 dimensions.
- **Skills:** SQL, MySQL 8.0, Dimensional Modeling (Star Schema), Data Hygiene, Docker, Business Intelligence

### 2. [TMDB Movie Data ETL Pipeline](https://github.com/nirajbasnet009/tmdb-etl-project)
*Targeting Data Engineering Roles* - [Read Case Study](https://nirajbasnet.com.np/blog/tmdb-movie-data-etl-pipeline/)
- Developed an automated batch Python pipeline extracting paginated movie records across the TMDB REST API.
- Engineered resilient extraction with HTTP status handling, exponential backoff retries, and schema normalization in `pandas`.
- Built pre-load defensive validation checking duplicate IDs, non-empty primary fields, and non-negative metric bounds before exporting to clean CSV.
- Included failure-recovery documentation with SHA-256 integrity verification against corrupt runs.
- **Skills:** Python, Pandas, REST APIs, Batch ETL, Data Validation, Error Handling, Git

### 3. [Smart Task Manager](https://github.com/nirajbasnet009/Smart_Task_Manager)
*Full-Stack Python & Database Systems* - [View Project](https://nirajbasnet.com.np/projects/)
- Implemented user authentication, dynamic CRUD workflows, priority filtering, and category tagging using Python and Django.
- Designed a normalized relational schema in SQLite enforcing strict foreign key constraints for secure task isolation.
- **Skills:** Python, Django, SQLite, Relational Database Design, Tailwind CSS

---

## Technical Skills Demonstrated in My Code

- **Databases & Modeling:** SQL (Window functions, CTEs, Aggregations), MySQL 8.0, SQLite, PostgreSQL (in progress), Dimensional Modeling (Star Schema, Fact/Dimension Tables, Grain Definition), Relational Database Normalization.
- **Data Engineering & Scripting:** Python, Pandas, REST API Pagination & Extraction, Batch ETL Pipelines, Data Validation & Cleaning, Docker, Git/GitHub.
- **Analytics & BI:** Business Metrics Calculation (AOV, Cancellation Rate, Fulfillment Latency), Cohort/Segment Analysis, Power BI (reports in progress).

---

## Education

**University of South Florida (USF)** - Tampa, FL  
*Bachelor of Science in Computer Science* | GPA: 3.69 / 4.00  
*Expected Graduation:* May 2028  
*Relevant Coursework:* Database Systems, Data Structures & Algorithms, Artificial Intelligence, Probability & Statistics, Computer Logic & Design
