
📊 Bank Loan Analysis Dashboard (Power BI & SQL)

An end-to-end data analysis and visualization project focused on a bank's loan portfolio. Built using SQL for data preparation and Power BI for interactive dashboards, this project provides actionable insights on loan applications, funding, repayments, and customer demographics.


---

🔍 Project Overview

This project analyzes ~38,000 loan records to answer key business questions such as:

How many loan applications were received?

What is the total funded amount vs. repayments?

What’s the risk profile of the loan book?

How do demographics affect loan performance?



---

✅ Features

Data Cleaning & Modeling: Handled in SQL and Power BI.

Advanced SQL Queries: KPIs, trends, repayment analysis, risk segmentation.

Interactive Dashboards: Built in Power BI with filters, field parameters, and exportable grids.

Dynamic Visuals: Includes time trends, state-wise maps, and loan performance analysis.

Modular Project Structure: Easily reusable and scalable.



---

🗂 Dataset

Source: Sample bank loan CSV file

Records: ~38,576 rows | 24 fields

Key Fields: Loan ID, Application Type, Employment Length, Home Ownership, Loan Term, Interest Rate, Loan Status, Total Payment, DTI, etc.



---

📁 Project Structure

Bank-Loan-Analysis/
│
├── data/
│   └── bank_loan_data.csv
├── sql/
│   ├── create_db_and_tables.sql
│   └── kpi_queries.sql
├── powerbi/
│   └── bank_loan_dashboard.pbix
└── README.md


---

⚙ Installation & Setup

Prerequisites

Power BI Desktop (June 2023+)

MS SQL Server (2019+)

SQL Server Management Studio


Setup Steps

1. Clone the repo:
git clone https://github.com/yourusername/Bank-Loan-Analysis.git


2. Create DB & Tables using create_db_and_tables.sql


3. Import CSV into the SQL table


4. Run kpi_queries.sql for KPI generation


5. Open the .pbix file in Power BI and connect to your SQL Server


6. Refresh data and explore insights




---

📈 Key Insights

KPIs: Total applications, repayments, interest rates, DTI

Loan Risk Analysis: Good vs Bad loans over time

Loan Status Breakdown: Current, Fully Paid, Charged-off

Detailed Analysis: By state, term, employment, purpose, ownership

Data Grid View: Exportable loan-level data for audit/compliance



---

🧠 Skills Demonstrated

SQL-based data cleaning, transformation, and KPI generation

Power BI data modeling, relationships, and DAX

Business storytelling through dashboards

ETL pipeline for reproducible analytics

Domain knowledge in financial analytics



---

🚀 How to Use

Start with the Summary Dashboard for high-level KPIs

Use filters & slicers for drill-downs by demographics and loan type

Review the Grid View for detailed data exports

Adapt the project for your own datasets or finance domain use cases



---

📬 


---

--Duration

Start date:1 July 2025

End date:20 July 2025
