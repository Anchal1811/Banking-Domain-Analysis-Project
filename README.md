Banking Domain Data Analysis Project
📌 Project Overview
This project focuses on Risk Analytics within the banking sector. The primary goal is to analyze customer data to understand financial behaviors and minimize the risk of financial loss (defaults) during the lending process. By leveraging a full data stack—Python, SQL, and Power BI—this project identifies key patterns in loan distribution, deposit health, and customer demographics.

📁 Repository Structure
Banking.csv: The raw dataset containing client information, income, loans, and account balances.

banking.ipynb: Python notebook containing Exploratory Data Analysis (EDA) and data cleaning scripts.

bank.sql: SQL scripts for database schema creation and data querying.

bd.pbix: The interactive Power BI dashboard file.

Dashboard Images:

Summ.png: Summary View (KPIs)

loan.png: Loan Distribution Analysis

deposit.png: Deposit and Liquidity Analysis

dashboard.png: Full Project Overview

🛠️ Tools & Technologies
Python: (Pandas, Matplotlib, Seaborn) for EDA and data profiling.

SQL (MySQL): For structured data storage and management.

Power BI: For building interactive visualizations and business intelligence reports.

Excel/CSV: Source data format.

📊 Key Insights & Findings
Customer Financial Integrity: Analysis revealed a strong positive correlation between high balances in Checking Accounts and Savings Accounts. Customers maintaining multiple account types are statistically lower-risk for loans.

Credit Card Usage: Approximately 70% of customers hold only one credit card, suggesting a conservative credit culture among the majority of the bank's client base.

Risk Segmentation: By categorizing customers into "High," "Medium," and "Low" income bands, the analysis pinpointed that higher-income brackets hold the majority of business lending, while lower-income brackets are more susceptible to personal loan defaults.

Geographic Trends: European and Asian demographics represent the largest segments of the bank’s loan portfolio, each exhibiting distinct repayment behaviors.

📈 Outcomes & Results
Risk Mitigation: Developed a risk-weighing model that helps the bank identify potential defaulters before loan approval.

360° Financial View: Created a 4-page interactive dashboard providing stakeholders with real-time access to:

Total Loan Value vs. Business Lending

Total Deposits vs. Foreign Currency Holdings

Customer Demographics (Age, Occupation, Nationality)

Data-Driven Decision Making: The project provides a clear roadmap for the bank to adjust interest rates and credit limits based on the identified "Income Bands."

🚀 How to Use
Clone the Repo: git clone https://github.com/Anchal1811/Banking-Domain-Analysis-Project.git

Run the Analysis: Open banking.ipynb in Jupyter Notebook or Google Colab to see the EDA process.

Database Setup: Import bank.sql into your MySQL Workbench to view the structured data tables.

View Dashboard: Open bd.pbix in Power BI Desktop to interact with the visualizations.

Screenshots
Summary View	Loan Analysis	Deposit Analysis
Author: Anchal1811

Project Link: GitHub Repo
