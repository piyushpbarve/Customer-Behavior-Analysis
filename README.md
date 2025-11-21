# Customer-Behavior-Analysis-
Customer shopping behavior analysis using Python, SQL, and Power BI. Covers data cleaning, segmentation, product performance, discount impact, subscription behavior, and revenue insights across 3,900 purchases. Includes dashboards, SQL queries, and business recommendations.

# 🛒 Customer Shopping Behavior Analysis
This project analyzes customer shopping patterns using Python, SQL, and Power BI to uncover insights on demographics, spending behavior, product preferences, discount impact, and loyalty drivers across 3,900 transactions.  
:contentReference[oaicite:1]{index=1}

---

## 📌 Project Overview
A retail company aims to understand what influences customer decisions — discounts, reviews, age, subscriptions, shipping type, product preferences, and purchase frequency.  
This project answers the core question:

**“How can customer shopping data be used to improve engagement, retention, and marketing strategies?”**  
:contentReference[oaicite:2]{index=2}

---

## 📂 Dataset Summary
- **3,900 purchases**, **18 columns**  
- Includes demographics, purchase details, shipping type, review ratings, previous purchases  
- **37 missing values** in review ratings (cleaned using median per category)  
:contentReference[oaicite:3]{index=3}

---

## 🛠 Tools & Technologies
- **Python:** Pandas, NumPy  
- **SQL:** PostgreSQL  
- **Power BI:** Interactive dashboard  
- CSV & Excel data processing  

---

## 🧼 Data Preparation (Python)
Key steps:  
- Loaded & explored dataset  
- Cleaned missing values (median imputation)  
- Standardized column names  
- Feature engineering  
  - Age groups  
  - Purchase frequency  
- Loaded cleaned data into PostgreSQL  
:contentReference[oaicite:4]{index=4}

---

## 🗄 SQL Analysis
SQL queries were used to extract insights such as:
- Revenue by gender  
- High-value discount users  
- Top-rated products  
- Standard vs Express shipping spend  
- Subscribers vs non-subscribers revenue  
- Customer segmentation (New, Returning, Loyal)  
- Discount dependency  
- Top 3 products per category  
- Age-group revenue contribution  
:contentReference[oaicite:5]{index=5}

---

## 📊 Key Insights
1. **Female customers generate slightly higher revenue** than males.  
2. **Express shipping users spend 12% more per order.**  
3. **Subscribers show higher loyalty and spend more** overall.  
4. **High-value discount shoppers** represent strong marketing opportunities.  
5. **Top-rated products** include Blouse, Dress, and Shirt (high satisfaction).  
6. Customer segments:  
   - **New:** 50%  
   - **Returning:** 35%  
   - **Loyal:** 15%  
7. Age groups like **Young Adults** contribute highest revenue.  
:contentReference[oaicite:6]{index=6}

---

## 📈 Power BI Dashboard
The interactive dashboard displays:
- Revenue by category  
- Revenue by age group  
- Subscription impact  
- Sales by category  
- Customer segmentation  
- Shipping type performance  
- Review rating distribution  
:contentReference[oaicite:7]{index=7}

---

## 🎯 Business Recommendations
- **Boost subscriptions** through exclusive benefits  
- **Introduce loyalty programs** for returning buyers  
- **Promote top-rated products** in campaigns  
- **Target high-revenue age groups**  
- **Encourage express shipping** for higher basket value  
:contentReference[oaicite:8]{index=8}

---

## 📁 Project Structure
```
data/
  customer_shopping_behavior.csv
notebooks/
  Customer_Shopping_Behavior_Analysis.ipynb
sql/
  customer_behavior_sql_queries.sql
reports/
  Business Problem Document.pdf
  Customer Shopping Behavior Analysis.pdf
dashboard/
  Power BI Dashboard.pbix
presentation/
  Customer-Shopping-Behavior-Analysis.pptx
README.md
```
:contentReference[oaicite:9]{index=9}

---

## 🚀 How to Run
1. Clone repository  
2. Install dependencies  
3. Run Python notebook  
4. Execute SQL queries in PostgreSQL  
5. Open Power BI dashboard (.pbix file)

---

## 👤 Author
**Piyush Barve**  
Data Analyst skilled in SQL, Power BI, Python, ETL, and predictive analytics. Passionate about building dashboards, analyzing data, and solving real-world problems through analytics.
📧 Email: piyushbarve@outlook.com
🔗 GitHub: github.com/piyushpbarve
🔗 LinkedIn: linkedin.com/in/piyushbarve
