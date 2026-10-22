![Chike Osakwe — Data Science & Data Analytics](banner.svg)

### Data Science & Data Analytics | M.S. Information Technology (Data Science), Cal State Fullerton | Python · SQL · R · Tableau

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Chike%20Osakwe-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chike-osakwe/)
[![Graduate Program](https://img.shields.io/badge/M.S.%20Information%20Technology-Data%20Science-00274D?style=for-the-badge)](https://www.fullerton.edu/)
![Location](https://img.shields.io/badge/California%2C%20USA-424242?style=for-the-badge&logo=googlemaps&logoColor=white)
![Open to Roles](https://img.shields.io/badge/Open%20to%20Data%20Science%20%26%20Analytics%20Roles-238636?style=for-the-badge)

I'm a graduate student at **California State University, Fullerton**, pursuing an **M.S. in Information Technology with a concentration in Data Science**. I use Python, R, SQL, and visualization tools to investigate real questions, develop statistical and predictive models, and communicate findings that can inform decisions.

My portfolio brings together **machine learning, exploratory analysis, statistical modeling, SQL-based data preparation, and business intelligence**. I've worked with student retention data, World Bank development indicators, financial market returns, and operational datasets. I care as much about *whether a result is reliable and useful* as I do about the model or dashboard that produced it.

I also spent two years teaching mathematics and using student assessment data to help coordinate targeted interventions. That experience still influences how I approach analysis: understand the audience, question the metric, and make the findings actionable.

---

## Featured data science & analytics projects

### [Student Dropout Analysis](https://github.com/cosak001/student-dropout-analysis) | Python · scikit-learn · Tableau · SPSS

**Predictive modeling, model evaluation, and dashboard storytelling.** Analyzed a **600-record first-year student case dataset** to examine dropout patterns and compare logistic regression with a neural network. Rebuilt the models in Python using a stratified holdout set and five-fold cross-validation; logistic regression achieved **0.737 mean cross-validated ROC AUC**. Rather than relying on ~81% accuracy for an imbalanced outcome, tuned the decision threshold to improve **held-out dropout recall from 10% to 57%** (at **37% precision**). Built Tableau dashboards to communicate patterns in GPA, course load, and retention, while explicitly discussing selection bias in voluntary seminar attendance.

[**Explore the project →**](https://github.com/cosak001/student-dropout-analysis) · [**View the interactive Tableau dashboard →**](https://public.tableau.com/app/profile/chike.osakwe3768/viz/StudentDropoutAnalysis_17897246641970/StudentDropoutRiskPatterns)

### [Global Emissions & Economic Development](https://github.com/cosak001/worldbank-emissions-sql) | PostgreSQL · SQL · ETL

**Relational modeling, data transformation, and exploratory analysis.** Developed a reproducible PostgreSQL workflow covering **8 World Bank indicators across 200+ countries**, including CO₂ emissions, GDP per capita, inflation, and internet adoption. Used SQL staging tables, data cleaning, referential constraints, CTEs, and window functions to create **14 analytical views**. Added validation checks to distinguish country records from regional aggregates and test data completeness before interpreting the results.

[**Explore the SQL project →**](https://github.com/cosak001/worldbank-emissions-sql)

### [Mean-Variance Portfolio Optimization](https://github.com/cosak001/mean-variance-portfolio-optimization) | R · PostgreSQL · Docker

**Quantitative analysis, optimization, and out-of-sample evaluation.** Used historical returns from **15 securities** to construct a mean-variance-optimized portfolio and compare it with the S&P 500 Total Return index. Over a **58-trading-day out-of-sample backtest**, the portfolio returned **12.31% versus 6.20%** for the benchmark, with considerably greater volatility. The brief test period and risk differences are important limitations—not evidence of guaranteed future performance.

[**Explore the portfolio analysis →**](https://github.com/cosak001/mean-variance-portfolio-optimization)

### [Puglia Winery Business Intelligence & Data Warehouse](https://github.com/cosak001/pulgia-winery-bi-data-warehouse) | MySQL · Dimensional Modeling · BI

**Data warehousing and analytics-ready modeling.** Contributed to a team project organizing winery sales and production data around business reporting questions. Developed a **MySQL sample implementation** and documented a Kimball-style dimensional model, ETL requirements, and a proposed Power BI reporting design.

[**Explore the BI project →**](https://github.com/cosak001/pulgia-winery-bi-data-warehouse)

### [GPU Diagnostic & Bug Triage Toolkit](https://github.com/cosak001/gpu-triage-toolkit) | Python · Automation

**Python automation and structured diagnostic data.** Built a toolkit that runs reproducible GPU workloads, collects NVIDIA telemetry, flags threshold-based anomalies, and produces structured diagnostic reports with LLM-assisted triage hypotheses.

[**Explore the toolkit →**](https://github.com/cosak001/gpu-triage-toolkit)

---

## How I approach data problems

| Focus | Example from my work |
| --- | --- |
| **Exploratory analysis** — understand patterns and possible confounders before modeling. | Studied relationships between GPA, course load, seminar participation, and student retention. |
| **Statistical and predictive modeling** — select methods based on the question, not their complexity. | Compared logistic regression and a neural network with the same holdout and cross-validation framework. |
| **Meaningful evaluation** — use appropriate metrics, baselines, and tradeoffs. | Prioritized ROC AUC, recall, and precision over headline accuracy for an imbalanced dropout problem. |
| **Data quality and reproducibility** — make transformations and assumptions inspectable. | Built SQL ETL and validation checks for eight World Bank indicators. |
| **Clear communication** — explain what results mean and what they *don't* establish. | Created Tableau dashboards and identified why voluntary seminar attendance could not establish causation. |

---

## Technical stack

**Programming & analysis**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

**Databases & workflows**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![ETL](https://img.shields.io/badge/ETL%20%26%20Data%20Validation-236B65?style=for-the-badge)

**Visualization & reporting**

![Tableau](https://img.shields.io/badge/Tableau-1F4477?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![IBM SPSS](https://img.shields.io/badge/IBM%20SPSS-052FAD?style=for-the-badge&logo=ibm&logoColor=white)

**Statistical & analytical methods**

![Exploratory Data Analysis](https://img.shields.io/badge/Exploratory%20Data%20Analysis-176B61?style=for-the-badge)
![Regression](https://img.shields.io/badge/Regression-176B61?style=for-the-badge)
![Classification](https://img.shields.io/badge/Classification-176B61?style=for-the-badge)
![Cross Validation](https://img.shields.io/badge/Cross--Validation-176B61?style=for-the-badge)
![Hypothesis Testing](https://img.shields.io/badge/Hypothesis%20Testing-176B61?style=for-the-badge)
![PCA](https://img.shields.io/badge/Principal%20Component%20Analysis-176B61?style=for-the-badge)
![Dimensional Modeling](https://img.shields.io/badge/Dimensional%20Modeling-176B61?style=for-the-badge)

---

## Experience highlights

**Mathematics Educator — Antioch Unified School District** *(August 2024 – July 2026)*  
Taught mathematics to **150+ students annually** and worked with teachers, counselors, and administrators to use **i-Ready and state assessment results** to identify learning gaps. Helped organize targeted intervention groups for near-proficient students and communicated progress and instructional priorities to staff and families. This experience developed my ability to interpret performance data, collaborate with stakeholders, and explain findings clearly.

**Graduate Data Science & Analytics Projects — California State University, Fullerton** *(2025 – present)*  
Completed independent and team-based analyses across Python, R, SQL, Tableau, and SPSS, including predictive classification, statistical analysis, relational database design, portfolio optimization, and dimensional modeling. Project repositories above include methods, findings, and relevant limitations.

---

## Education

**California State University, Fullerton**  
**M.S., Information Technology — Data Science concentration** · *Expected June 2027*

**Completed:** Statistics for Data Science · Principles of Business Intelligence · Business Databases: Design & Processing · Data Warehousing and Foundations of Business Intelligence · Business Data Transformation · Information Resources and IT Project Management

**Currently studying (Fall 2026):** Forecasting for Analytical Decision Making · Advanced Regression Analysis · Data Mining for Business Applications

**University of California, Riverside**  
**B.S., Biology** · *June 2023*

---

## Areas of interest

![Predictive Modeling](https://img.shields.io/badge/Predictive%20Modeling-183B56?style=for-the-badge)
![Statistical Analysis](https://img.shields.io/badge/Statistical%20Analysis-183B56?style=for-the-badge)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-183B56?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-183B56?style=for-the-badge)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-183B56?style=for-the-badge)
![Data Quality](https://img.shields.io/badge/Data%20Quality-183B56?style=for-the-badge)

I'm open to **Data Scientist, Data Analyst, Business Intelligence Analyst, Reporting Analyst, and related data roles**, including internships and early-career opportunities.

[**Connect on LinkedIn**](https://www.linkedin.com/in/chike-osakwe/) · [**Explore all repositories**](https://github.com/cosak001?tab=repositories) · [**View my Tableau work**](https://public.tableau.com/app/profile/chike.osakwe3768)
