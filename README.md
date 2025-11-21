# Customer-Behavior-Analysis
Customer Shopping Behavior Analysis
This project analyzes 3,900 customer purchases to uncover trends in consumer behavior, spending patterns, product preferences, and loyalty indicators. The goal is to help businesses make data-driven decisions for marketing, customer retention, and product strategy.


📌 Project Overview
A retail company wants to understand what drives customer shopping decisions such as discounts, reviews, age groups, purchase frequency, and subscription behavior.
This project explores the dataset using Python, SQL, and Power BI, transforming raw data into actionable insights.


📂 Project Structure
├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
├── sql/
│   └── customer_behavior_sql_queries.sql
├── reports/
│   ├── Business Problem Document.pdf
│   └── Customer Shopping Behavior Analysis.pdf
├── dashboard/
│   └── Power BI Dashboard (PBIX File)
├── presentation/
│   └── Customer-Shopping-Behavior-Analysis.pptx
└── README.md


🛠️ Tools & Technologies
⦁	Python (Pandas, NumPy, Matplotlib)
⦁	SQL (PostgreSQL)
⦁	Power BI
⦁	Excel / CSV Processing


📊 Dataset Summary
⦁	3,900 rows
⦁	18 columns
⦁	Contains demographic data, purchase details, discounts, previous purchases, ratings, and shipping types
⦁	37 missing values in Review Ratings (cleaned using median imputation)


📝 Data Preparation (Python)
Key steps:
⦁	Loaded & explored dataset
⦁	Cleaned missing values
⦁	Renamed columns to snake_case
⦁	Feature Engineering
	Age groups
	Purchase frequency
⦁	Dropped redundant columns
⦁	Loaded cleaned dataset into PostgreSQL for SQL analysis


🗄️ SQL Analysis
SQL queries extracted insights such as:
⦁	Revenue by gender
⦁	High-value discount users
⦁	Top-rated products
⦁	Shipping type comparison
⦁	Subscriber vs. non-subscriber revenue
⦁	Customer segmentation (New, Returning, Loyal)
⦁	Age-group revenue contribution
⦁	Discount dependency
⦁	Top 3 products per category


📈 Power BI Dashboard
The interactive dashboard highlights:
⦁	Revenue by category
⦁	Revenue by age group
⦁	Subscription impact
⦁	Sales by category
⦁	Customer segments
⦁	Review rating distribution
⦁	Shipping preference impact


🔍 Key Insights
1.	Gender-based Revenue
Female customers generate slightly higher revenue.
2.	High-Value Discount Users
Many customers spend above average even with discounts → high-value opportunity.
3.	Top-Rated Products
Items like Blouse, Dress, and Shirt receive the highest customer ratings.
4.	Shipping Preferences
Express shipping customers spend 12% more per order.
5.	Subscription Impact
Subscribers:
⦁	Spend more
⦁	Show higher loyalty
⦁	Contribute a major share to revenue
6.	Customer Segmentation
⦁	New Customers: 50%
⦁	Returning: 35%
⦁	Loyal: 15%


📌 Business Recommendations
⦁	Promote subscription benefits to boost recurring revenue
⦁	Launch loyalty programs to convert Returning → Loyal customers
⦁	Highlight top-rated products in marketing
⦁	Target high-revenue age groups
⦁	Promote express shipping for higher purchase value


📦 Files Included
⦁	Python Notebook
⦁	Cleaned Dataset
⦁	SQL Queries
⦁	PPT Presentation
⦁	Business Problem PDF
⦁	Power BI Dashboard


🚀 How to Run the Project
1.	Clone the repository
git clone https://github.com/piyushpbarve/customer-shopping-behavior-analysis.git
2.	Install dependencies
pip install -r requirements.txt
3.	Open the Jupyter Notebook
jupyter notebook
4.	Run SQL queries
Execute .sql file in PostgreSQL.
5.	View Dashboard
Open the .pbix file using Power BI Desktop.


📞 Contact
Piyush Barve
Data Analyst skilled in SQL, Power BI, Python, ETL, and predictive analytics. Passionate about building dashboards, analyzing data, and solving real-world problems through analytics.
📧 Email: piyushbarve@outlook.com
🔗 GitHub: github.com/piyushpbarve
🔗 LinkedIn: linkedin.com/in/piyushbarve
