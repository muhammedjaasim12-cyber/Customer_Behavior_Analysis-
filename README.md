# Customer_Behavior_Analysis-
Data analysis project showcasing customer behavior analysis using PYTHON,SQL and Power Bi
📊 Customer Analytics Project
1. Overview

This project focuses on analyzing customer shopping behavior using Python, SQL, and Power BI to generate actionable business insights.

The workflow covers:

Data loading and preprocessing in Python

Exploratory Data Analysis (EDA)

Data cleaning and transformation

SQL-based business analysis

Interactive dashboard development in Power BI

Business reporting and presentation (Gamma PPT)

The goal is to convert raw transactional data into meaningful insights that support strategic decision-making.

2. Dataset

Rows: ~3,900 transactions

Columns: 18 features

Key Attributes:

Customer Demographics (Age, Gender, Location, Subscription Status)

Purchase Details (Item, Category, Amount, Season, Size, Color)

Shopping Behavior (Discount, Promo Code, Shipping Type)

Engagement Metrics (Review Rating, Previous Purchases, Frequency)

Data Quality Notes:

Missing values identified in review ratings

Column names standardized to snake_case

Data types corrected for consistency

3. Tools & Technologies

Python – Data cleaning & EDA

Pandas / NumPy – Data manipulation

Matplotlib / Seaborn – Visualization

PostgreSQL / MySQL / SQL Server – Business queries

Power BI – Interactive dashboard

Gamma – Presentation (PPT)

GitHub – Version control

4. Project Workflow
Step 1 – Data Loading (Python)

Imported dataset using Pandas

Checked structure (head(), info(), describe())

Identified missing values

Step 2 – Data Cleaning

Handled missing review ratings

Removed duplicates

Standardized column names

Converted data types

Step 3 – Exploratory Data Analysis (EDA)

Revenue distribution analysis

Customer segmentation (New / Returning / Loyal)

Shipping type comparison

Subscription impact on revenue

Discount dependency analysis

Age group revenue contribution

Step 4 – SQL Analysis

Executed structured business queries such as:

Total revenue by category

Top 5 products by sales

Repeat customers analysis

Subscription revenue comparison

Discount impact on total revenue

Database systems used:

PostgreSQL

MySQL

SQL Server

5. Dashboard (Power BI)

An interactive dashboard was built to visualize:

Revenue trends

Customer segmentation

Top-performing products

Shipping type comparison

Subscription vs Non-subscription revenue

Age-based revenue contribution

The dashboard allows filtering by:

Category

Subscription status

Shipping type

Customer segment

6. Key Results

Identified high-revenue customer segments

Found top-performing products and categories

Measured subscription impact on profitability

Analyzed discount dependency risk

Provided targeted marketing recommendations

Business Recommendations:

Strengthen subscription benefits

Improve loyalty programs

Optimize discount strategies

Target high-value customer segments

7. How to Run the Project
1️⃣ Python Analysis
pip install pandas numpy matplotlib seaborn


Run:

python analysis.py

2️⃣ SQL Queries

Import dataset into:

PostgreSQL / MySQL / SQL Server

Run provided SQL scripts in /sql_queries folder

3️⃣ Power BI Dashboard

Open dashboard.pbix file

Refresh dataset connection

Interact with filters and visuals

4️⃣ Presentation

Open the Gamma-generated PPT file for executive summary and insights.

8. Project Structure
├── data/
├── notebooks/
├── sql_queries/
├── dashboard/
├── presentation/
├── report/
└── README.md

9. Why This Project Matters

This project demonstrates:

End-to-end analytics workflow

SQL + Python integration

Business-focused thinking

Data storytelling with dashboards

Clear reporting and communication
