# 💳 Credit Card Financial Dashboard | Power BI, SQL

## 📌 Project Overview

The **Credit Card Financial Dashboard** is a data analytics project developed using Power BI, SQL, and CSV datasets. The project focuses on analyzing credit card transactions, customer demographics, revenue, interest earned, and transaction behavior.

The dashboard provides interactive visualizations and key performance indicators (KPIs) to help stakeholders monitor credit card business performance, identify trends, and make data-driven decisions.

The project includes two main dashboards:
- **Credit Card Customer Report**
- **Credit Card Transaction Report**

## 🎯 Project Objectives

- Analyze overall credit card revenue and transaction performance.
- Monitor total transaction amount and transaction count.
- Understand customer demographics based on age, gender, education, marital status, and occupation.
- Analyze revenue by credit card category.
- Compare revenue and transactions across quarters.
- Evaluate spending patterns across different expenditure categories.
- Identify the contribution of different states and customer segments.
- Present business insights through an interactive Power BI dashboard.

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard development and data visualization.
- **SQL / PostgreSQL** — Database creation, table management, and data import.
- **Microsoft Excel / CSV** — Dataset storage and preparation.
- **DAX (Data Analysis Expressions)** — Calculated columns and measures.
- **Data Analytics** — KPI analysis, customer segmentation, and business insights.

## 📂 Project Files

The project uses customer and transaction datasets along with SQL queries and dashboard reports.

| File | Description |
|---|---|
| `credit_card.csv` | Credit card transaction data |
| `customer.csv` | Customer demographic and financial data |
| `cc_add.csv` | Additional credit card transaction records |
| `cust_add.csv` | Additional customer records |
| `SQL Query - Financial Dashboard Data.sql` | SQL database and table creation queries |
| `Credit Card Financial Dashboard-Customer.pdf` | Customer dashboard report |
| `Credit Card Financial Dashboard-Transaction.pdf` | Transaction dashboard report |
| `Credit Card Financial Weekly Dashboard Report.pdf` | Project documentation and reference report |

*Note: Update the filenames above if your GitHub repository uses different names or file extensions.*

## 🗄️ Database & SQL

PostgreSQL was used to create the database and organize the data into two main tables.

### 1. `cc_detail`

This table contains credit card transaction and financial information.

Important columns include:
- Client_Num
- Card_Category
- Annual_Fees
- Activation_30_Days
- Customer_Acq_Cost
- Week_Start_Date
- Qtr
- Credit_Limit
- Total_Revolving_Bal
- Total_Trans_Amt
- Total_Trans_Ct
- Avg_Utilization_Ratio
- Use_Chip
- Exp_Type
- Interest_Earned
- Delinquent_Acc

### 2. `cust_detail`

This table contains customer demographic and financial information.

Important columns include:
- Client_Num
- Customer_Age
- Gender
- Dependent_Count
- Education_Level
- Marital_Status
- State_cd
- Customer_Job
- Income
- Cust_Satisfaction_Score

### Database Workflow

1. Created the `ccdb` database.
2. Created the customer and transaction tables.
3. Imported CSV datasets into PostgreSQL.
4. Added additional weekly records.
5. Prepared the data for Power BI analysis.

## 📊 Power BI Dashboard

### 1. Credit Card Customer Report

The customer dashboard focuses on customer demographics and revenue performance.

**Key visualizations include:**
- Total Revenue
- Total Income
- Total Interest
- Customer Satisfaction Score (CSS)
- Revenue by Gender
- Revenue by Customer Job
- Revenue by Education Level
- Revenue by Marital Status
- Revenue by Age Group
- Revenue by State
- Revenue by Salary Group
- Customer segmentation and dependent count

### 2. Credit Card Transaction Report

The transaction dashboard focuses on credit card usage and financial performance.

**Key visualizations include:**
- Total Revenue
- Total Transaction Amount
- Total Transaction Count
- Total Interest Earned
- Revenue by Expenditure Type
- Revenue by Credit Card Category
- Revenue by Customer Job
- Revenue by Education Level
- Revenue by Chip Usage
- Quarterly Revenue and Transaction Count
- Customer Acquisition Cost by Card Category

### Interactive Features

The dashboards include filters and slicers that allow users to explore the data by week, quarter, card category, and other available customer or transaction segments.

## 📈 Key Performance Indicators (KPIs)

The dashboard displays important financial and operational metrics, including:

- **Total Revenue:** Overall revenue generated from credit card customers.
- **Total Transaction Amount:** Total value of recorded credit card transactions.
- **Total Transaction Count:** Number of transactions recorded.
- **Total Interest Earned:** Interest generated from credit card activity.
- **Total Income:** Combined customer income represented in the dashboard.
- **Customer Satisfaction Score:** Customer satisfaction metric.
- **Customer Acquisition Cost:** Cost associated with acquiring customers.
- **Revenue by Card Category:** Comparison of revenue across Blue, Silver, Gold, and Platinum cards.
  
## 🔍 Key Insights

The following insights are based on the supplied dashboard reports and project reference document.

### Overall Financial Performance

- The customer report shows approximately **55.4 million in total revenue**.
- Total income is displayed as approximately **577 million**.
- Total interest is approximately **7.9 million**.
- The transaction report shows approximately **657K transactions** and a total transaction amount of approximately **45 million**.

### Customer Analysis

- The dashboard compares revenue generated by male and female customers.
- Customer revenue is analyzed across different age groups, education levels, marital statuses, and occupations.
- State-wise analysis highlights Texas (TX), New York (NY), California (CA), Florida (FL), and New Jersey (NJ).

### Credit Card Analysis

- Blue cards contribute the largest share of revenue among the displayed card categories.
- Revenue and interest earned are compared across Blue, Silver, Gold, and Platinum cards.
- The dashboard also compares annual fees by card category.

### Transaction Behavior

- Revenue is analyzed across expenditure categories such as bills, entertainment, fuel, grocery, food, and travel.
- Chip, swipe, and online transactions are compared to understand card usage patterns.
- Quarterly revenue and transaction counts help identify changes in business performance over time.

## 💡 Business Value

This project demonstrates how customer and transaction data can be transformed into meaningful business insights.

The dashboard can help business stakeholders:

- Monitor important financial KPIs.
- Understand customer spending behavior.
- Compare the performance of different card categories.
- Identify high-revenue customer segments.
- Evaluate quarterly trends.
- Support business planning and data-driven decision-making.

## 🧠 Skills Demonstrated

- Data Cleaning and Preparation
- SQL Database Management
- CSV Data Import
- Power BI Dashboard Development
- DAX Calculations
- KPI Development
- Data Visualization
- Customer Segmentation
- Financial Data Analysis
- Business Insight Generation

## 🚀 Project Workflow

1. **Data Collection:** Prepared customer and credit card transaction datasets.
2. **Database Creation:** Created PostgreSQL database tables.
3. **Data Import:** Imported CSV files into the database.
4. **Data Preparation:** Organized the data for analysis.
5. **Data Modeling:** Connected the relevant customer and transaction data in Power BI.
6. **DAX Calculations:** Created calculated fields and measures for analysis.
7. **Dashboard Development:** Designed customer and transaction reports.
8. **Insights Generation:** Analyzed KPIs, customer segments, and transaction trends.

## 👨‍💻 Author

**MD Subhan Khan**

Aspiring Data Analyst | Power BI | SQL | Data Visualization

This project demonstrates practical skills in data analysis, dashboard development, and business reporting.
