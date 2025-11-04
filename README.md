Bank Loan Data Analysis — Big Data Case Study

📘 Overview

This project analyzes bank loan applications from Indian branches to identify approval trends, default risks, and demographic influences. Using HiveQL, Python, and visualization tools, it demonstrates how big data techniques can improve decision-making in financial services.


---

🧾 Dataset

File: Bank_Loan_Data_India.csv (synthetic, ~500 records)

Key Columns:

customer_id, gender, age, marital_status, city

monthly_income, employment_type, loan_type, loan_amount

loan_term_months, interest_rate_percent, credit_score

approval_status, default_status, application_date, branch_city, existing_loans



---

🎯 Objectives

Analyze loan approvals by type and city.

Correlate credit score with approval and default rates.

Segment customers by income and risk level.

Measure branch performance and customer demographics.

Create dashboards and actionable insights.



---

🧰 Tools & Technologies

Tool	Purpose

HiveQL / Cloudera	SQL aggregation & queries
HDFS / Hadoop	Scalable data storage
Python / Pandas	Data cleaning & preprocessing
Power BI / Tableau	Visualization dashboards
Matplotlib	Charts for analysis



---

⚙️ Methodology

1. Data Loading: Imported CSV into Hive using CREATE TABLE & LOAD DATA.


2. Data Cleaning: Handled missing credit scores, standardized categories.


3. Exploratory Queries: Aggregated approvals, defaults, and city-level patterns.


4. Visualization: Created visuals for approval rates, income bands, credit scores.


5. Insight Generation: Derived patterns for risk management and product strategy.




---

📊 Key Insights

Metric	Observation

Overall Approval Rate	60.4%
Highest Approval	Personal Loans — 85.3%
Highest Default Risk	Home Loans — 76.2%
Top Performing City	Hyderabad — 68.9% approval
Major Risk Factor	Low credit score & long tenure



---

💡 Recommendations

Tighten underwriting for low credit score customers.

Introduce secured or credit-building loans for younger applicants.

Use risk-based interest rates for high-default segments.

Implement branch-level KPIs and real-time dashboards.



---

📂 Files Included

├── Bank_Loan_Data_Analysis_Full.pdf
├── Bank_Loan_Data_India.csv
├── SQL_Scripts/
│   ├── create_tables.sql
│   ├── exploratory_queries.sql
│   └── risk_analysis.sql
├── visuals/
│   ├── approval_by_loan_type.png
│   ├── loan_amount_by_city.png
│   └── credit_score_distribution.png
└── README.md

# Bank-Loan-Data-Analysis
