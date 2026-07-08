
# 📊 Customer Churn Analysis using SQL & Python

## 📌 Project Overview

Customer retention is one of the biggest challenges for subscription-based businesses such as OTT platforms, SaaS companies, Telecom providers, and E-commerce organizations. Acquiring a new customer is significantly more expensive than retaining an existing one.

This project analyzes customer behavior to identify customers who are at high risk of churning and provides actionable business recommendations to improve customer retention and reduce revenue loss.

The project demonstrates the complete Data Analytics workflow—from SQL data extraction and data cleaning to feature engineering, exploratory data analysis, visualization, KPI calculation, and business insight generation.

---

## 🎯 Business Problem

The company wants to answer the following questions:

- Which customers are likely to churn?
- What factors contribute to customer churn?
- Which subscription plans have the highest churn?
- Which geographical regions have the highest churn?
- How much revenue is at risk?
- How can customer retention be improved?

---

## 🛠 Tech Stack

- Python
- SQL (SQLite)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Database Structure

The project uses three relational tables.

### 1. Customer Table

Contains customer demographic information.

- Customer ID
- Name
- Country
- State
- Gender
- Date of Birth
- Interests
- Pincode

---

### 2. Subscription Table

Contains subscription details.

- Customer ID
- Subscription Start Date
- Subscription Type
- Renewal Date
- Plan Type
- Contract Type
- Cancellation Date
- Cancellation Reason
- Monthly Charges
- Customer Lifetime Value (CLTV)
- Churn Score

---

### 3. Support Table

Contains customer support interactions.

- Customer ID
- Complaint Date
- Escalations
- CSAT Score
- Customer Comments

---

## 🔄 Project Workflow

### Step 1 : Connect SQL Database

- Connected SQLite database with Python
- Imported data using SQL queries
- Joined multiple tables using Customer ID

---

### Step 2 : Data Cleaning

Performed extensive data preprocessing.

✔ Removed duplicate records

✔ Handled missing values

✔ Converted date columns into datetime format

✔ Standardized gender values

✔ Corrected inconsistent data types

✔ Renamed columns

✔ Removed unnecessary columns

✔ Checked data quality

---

### Step 3 : Feature Engineering

Created new business features such as

- Customer Tenure
- Customer Age
- Active Customer Flag
- Revenue Contribution
- High Risk Customer
- Customer Lifetime Value (CLTV)

These engineered features helped improve business analysis.

---

### Step 4 : Exploratory Data Analysis (EDA)

Performed detailed analysis to understand customer behavior.

Analysis included:

- Customer demographics
- Subscription analysis
- Churn distribution
- Regional analysis
- Revenue analysis
- Customer support analysis
- Contract analysis
- Customer tenure analysis

---

### Step 5 : KPI Calculation

Calculated important business metrics including:

- Customer Churn Rate
- Customer Retention Rate
- Average Revenue Per User (ARPU)
- Average Customer Tenure
- Revenue at Risk
- Customer Lifetime Value (CLTV)
- Escalation Rate
- Average Complaints per Customer

---

### Step 6 : Data Visualization

Created visualizations using Matplotlib and Seaborn.

Visualizations include:

- Churn Distribution
- Churn by Subscription Plan
- Churn by State
- Monthly Churn Trend
- Revenue Analysis
- Customer Tenure Distribution
- Correlation Heatmap
- Customer Support Analysis

---

## 📈 Key Insights

The analysis revealed several important business insights:

- Overall churn rate was **28.6%**
- Retention rate was **71.4%**
- Basic subscription customers contributed to the highest churn volume.
- Monthly subscription users churned significantly more than annual subscribers.
- Karnataka experienced the highest customer churn.
- September recorded the maximum number of customer cancellations.
- Customers with multiple support escalations showed a much higher probability of churning.
- Customers with longer tenure demonstrated stronger loyalty.
- Revenue loss due to churn represented approximately **18%** of total revenue.
- High churn-score customers accounted for the majority of revenue at risk.

---

## 💡 Business Recommendations

Based on the analysis:

- Improve customer support response time.
- Launch retention campaigns for high-risk customers.
- Encourage migration from monthly to annual subscription plans.
- Monitor customers with high churn scores proactively.
- Investigate regional issues contributing to churn.
- Improve customer experience for Basic plan subscribers.
- Develop personalized offers for customers showing early churn signals.

---

## 📊 Project Outcome

Successfully developed an end-to-end customer churn analytics pipeline capable of:

- Identifying customers at risk of leaving
- Measuring revenue impact
- Understanding churn behavior
- Supporting data-driven retention strategies
- Providing actionable business recommendations

---

## 📁 Project Structure

```
Customer-Churn-Analysis/
│
├── data/
│   ├── customer.csv
│   ├── subscription.csv
│   ├── support.csv
│
├── sql/
│   ├── queries.sql
│
├── notebooks/
│   ├── Customer_Churn_Analysis.ipynb
│
├── images/
│   ├── churn_distribution.png
│   ├── heatmap.png
│   ├── revenue_analysis.png
│
├── README.md
└── requirements.txt
```

---

## 🚀 Skills Demonstrated

- SQL
- Python
- Data Cleaning
- Data Wrangling
- Feature Engineering
- Exploratory Data Analysis
- Business KPI Calculation
- Data Visualization
- Business Intelligence
- Analytical Thinking
- Customer Analytics

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Connecting SQL databases with Python
- Working with relational datasets
- Cleaning and transforming real-world data
- Engineering meaningful business features
- Performing exploratory data analysis
- Building professional visualizations
- Calculating business KPIs
- Generating actionable business insights

---

## 📌 Future Improvements

- Build Machine Learning model for churn prediction
- Deploy interactive dashboard using Streamlit
- Automate data pipeline
- Create Power BI dashboard
- Integrate real-time customer monitoring
- Perform predictive analytics

---

## ⭐ If you found this project useful, please consider giving it a Star!
