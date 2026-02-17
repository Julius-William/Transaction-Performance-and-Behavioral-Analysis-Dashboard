# Transaction Performance & Behavioral Analysis Dashboard

## Background

With the increasing adoption of digital transactions, the financial technology industry has experienced significant growth over the past few years. The rise of online payments, debit and credit card usage, and digital banking services has transformed how customers interact with financial institutions.

As transaction volumes continue to grow, understanding transaction patterns, customer behavior, and payment preferences becomes increasingly important. Companies must leverage data to monitor performance trends, identify seasonal patterns, and understand demographic differences in spending behavior.

Through data analysis and visualization, businesses can gain actionable insights to support strategic decision-making and optimize overall transaction performance.


---

## Project Objective

This project aims to:

- Analyze overall transaction performance
- Identify seasonal and behavioral spending patterns
- Understand demographic-based transaction behavior
- Evaluate payment method and channel preferences
- Provide data-driven business recommendations

---

##  Data Source & Workflow

The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/datasets/valakhorasani/bank-transaction-dataset-for-fraud-detection). 

To simulate a real-world data pipeline, the raw CSV data was first imported into a PostgreSQL database. The analysis environment (Python) was then connected to PostgreSQL using `psycopg2` to extract the data for preprocessing and analysis.

This approach replicates a practical business scenario where data is stored in relational databases rather than directly accessed from flat files.

---

## Key Analysis Areas

- Monthly transaction trends and seasonality
- Transaction distribution by weekday
- Spending behavior across age groups
- Payment method comparison (Debit vs Credit)
- Occupation-based transaction patterns
- Channel preference behavior across age segments

---

## Libraries & Tech Stack

### Programming & Data Processing
- Python
- Pandas
- NumPy
- psycopg2

### Data Visualization
- Matplotlib
- Seaborn
- Tableau Public

### Development Environment
- Jupyter Notebook
- GitHub

---
##  Key Insights

- Transaction value shows a strong upward trend toward the end of the year, with September recording the highest value.
- April experienced a noticeable dip in transaction value.
- All recorded transactions occurred on weekdays, with Monday generating the highest transaction count and amount.
- Baby Boomers contribute the highest total transaction value, while Baby Boomers and Gen Z show the highest average transaction amount.
- 77.5% of transactions are made using Debit cards, although Credit card transactions have a higher average value.
- Channel preference varies by age group, where younger segments are more digitally adaptive and older segments prefer traditional channels (ATM & Branch).

---

##  Business Recommendations

Based on the analysis:

- Maximize Q3–Q4 momentum through targeted seasonal campaigns.
- Introduce stimulus campaigns during low-performing months (e.g., April).
- Encourage Credit card utilization to increase transaction value per customer.
- Develop age-segmented marketing strategies.
- Accelerate digital adoption initiativ

---

##  Dashboard

You can view the interactive dashboard here:  
https://public.tableau.com/app/profile/julius.william1751/viz/Transaction_Analysis_17713412764140/Dashboardpg_1?publish=yes
