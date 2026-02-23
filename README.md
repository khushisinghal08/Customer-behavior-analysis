Overview:
This project demonstrates an end-to-end Data Analytics workflow — from data loading and cleaning to SQL analysis and interactive dashboard creation.
The goal of this project is to extract meaningful insights from raw data using Python, SQL, and Power BI, and present findings through a professional report and presentation.
This project highlights skills in:
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
SQL Querying & Data Extraction
Data Visualization
Business Insight Generation

The dataset contains structured data related to business performance (e.g., sales/customers/products/transactions).
It includes:
Multiple attributes (categorical + numerical)
Missing values and inconsistencies (handled during cleaning)
Time-based and category-based fields for trend analysis
The dataset was loaded and processed using Python before being analyzed in SQL and Power BI.
Tools & Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn) – Data loading, cleaning & EDA
PostgreSQL / MySQL / SQL Server – Writing SQL queries for analysis
Power BI – Interactive dashboard creation
Gamma – Presentation (PPT) creation
Jupyter Notebook – Development environment

Project Workflow / Steps
1️⃣ Data Loading (Python)
Imported dataset using Pandas
Checked structure using .info(), .describe()
Verified data types and null values

2️⃣ Data Cleaning
Handled missing values
Removed duplicates
Standardized column names
Converted data types (dates, numeric fields)
Treated outliers (if required)

3️⃣ Exploratory Data Analysis (EDA)
Distribution analysis
Category-wise comparisons
Trend analysis over time
Correlation analysis
Key performance metrics identification

4️⃣ SQL Analysis
Imported cleaned data into PostgreSQL/MySQL/SQL Server
Wrote queries to:
Calculate total revenue/sales
Find top-performing categories/products
Identify customer trends
Perform aggregations (GROUP BY, HAVING)
Create ranking queries (TOP / LIMIT)
Generate KPIs

5️⃣ Power BI Dashboard
Built an interactive dashboard including:
KPI cards (Total Sales, Revenue, Customers, etc.)
Bar chrts (Top categories/products)
Line charts (Sales trends)
Slicers (Filters by date/category/region)
Dynamic visuals for business insights

6️⃣ Report & Presentation
Created a structured analytical report
Highlighted key insights and recommendations
Designed a professional PPT using Gamma
Presented business-focused conclusions
 Dashboard Highlights
The Power BI dashboard provides:
 Sales trend over time

Top 5 performing categories/products
Customer segmentation insights
 Revenue distribution analysis
 Interactive slicers for dynamic filtering
The dashboard enables stakeholders to make data-driven decisions efficiently.

Key Results & Insights
Identified top-performing segments contributing maximum revenue
Discovered seasonal/monthly sales trends
Highlighted underperforming categories
Provided actionable recommendations for business growth
This project demonstrates the ability to transform raw data into meaningful business insights.

How to Run the Project
🔹 Python (EDA & Cleaning)
Clone the repository
Install required libraries:
pip install pandas numpy matplotlib seaborn
Open Jupyter Notebook
Run the notebook step-by-step
🔹 SQL
Import cleaned dataset into:
PostgreSQL / MySQL / SQL Server
Run the provided SQL scripts
Execute analytical queries
🔹 Power BI
Open the .pbix file
Connect to the dataset or SQL database
Refresh data
Explore the dashboard
