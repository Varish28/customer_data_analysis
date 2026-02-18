# customer_data_analysis
Data analysis project showcasing customer behavior analysis using Python, SQL and Power Bi in a visualization format.

📊 Customer Behavior Data Analytics Project
📌 Overview

This project presents an end-to-end data analytics workflow focused on customer behavior analysis. It covers data loading, cleaning, transformation, SQL querying, dashboard development, and reporting. The objective is to extract meaningful business insights and present them through structured analysis and interactive visualizations. The project demonstrates practical skills in Python, SQL, data preprocessing, visualization, and business reporting.

📂 Dataset

The dataset contains customer transaction and behavioral information, including:

Customer demographics (Age, Gender, Location)

Purchase details (Category, Purchase Amount, Frequency of Purchases)

Review ratings

Discount and promotion usage

Subscription status

Payment methods

Data preprocessing included:

Standardizing column names (snake_case formatting)

Handling missing values using median and category-wise imputation

Feature engineering (age grouping, frequency-to-days conversion)

Data transformation for SQL and visualization

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn)

SQL (PostgreSQL / MySQL)

Jupyter Notebook

Power BI (Dashboard creation)

Gamma App (Business report generation)

pgAdmin (Database management)

🔎 Project Workflow
1️⃣ Data Cleaning & Preparation

Imported dataset using Pandas

Cleaned and standardized column names

Handled missing values

Converted categorical features into numerical representations

Created new engineered features for analysis

2️⃣ SQL Analysis

Created database and tables in PostgreSQL/MySQL

Imported cleaned dataset into SQL

Executed aggregation queries (SUM, AVG, COUNT)

Performed customer segmentation using GROUP BY

Analyzed revenue trends and category performance

3️⃣ Dashboard Development

Connected Power BI to SQL database

Built interactive dashboards including:

Sales performance analysis

Customer segmentation

Category-wise revenue

Purchase frequency insights

Discount impact analysis

4️⃣ Reporting

Generated structured business report using Gamma App

Highlighted KPIs, trends, insights, and recommendations

📈 Key Insights

Identified top-performing product categories

Analyzed customer purchase frequency behavior

Evaluated impact of discounts on revenue

Segmented customers based on spending patterns

Determined demographic contribution to total revenue

▶️ How to Run
Python Analysis

Install required libraries:

pip install pandas numpy matplotlib seaborn


Open the Jupyter Notebook file.

Run all cells sequentially.

SQL Setup

Install PostgreSQL or MySQL.

Create a database.

Import the cleaned dataset.

Execute the provided SQL queries.

Power BI Dashboard

Open Power BI Desktop.

Connect to the SQL database.

Load required tables.

Open or recreate dashboard visuals.

🎯 Project Outcome

This project demonstrates:

End-to-end data analytics workflow

Data cleaning and preprocessing expertise

SQL querying and database management

Dashboard development and reporting

Ability to convert raw data into actionable business insights

🚀 Future Enhancements

Implement predictive modeling (customer churn prediction)

Deploy dashboard online

Automate ETL pipeline

Integrate real-time data processing

