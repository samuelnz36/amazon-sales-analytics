# Amazon Sales Analytics
### A Data Engineering & Analytics Project using SQL, Python, and Power BI  

---

## 📌 Project Overview
This project analyzes Amazon-style e-commerce sales data (India–focused) to uncover insights about revenue, orders, returns, customer behavior, and performance across product categories and states.

The workflow includes:
- Data cleaning using Python  
- Exploratory Data Analysis (EDA)  
- SQL-based analytical queries  
- Interactive dashboards built in Power BI  

This project demonstrates practical, beginner-friendly skills in data engineering and analytics.

---

## 🧹 1. Data Cleaning (`notebooks/01_data_cleaning.ipynb`)
Key steps performed:
- Removed missing or invalid values  
- Standardized column names  
- Converted date fields  
- Created additional columns (`Month_Name`, `Year`, `Returned`)  
- Validated revenue and numerical fields  

The cleaned dataset is used for SQL and visualization.

---

## 🔍 2. Exploratory Data Analysis (`notebooks/02_eda.ipynb`)
### Key KPIs from the dataset:
- **Total Revenue:** ~₹1.11B  
- **Total Orders:** 15,000  
- **Units Sold:** 44,770  
- **Average Order Value:** ₹74,544  
- **Average Rating:** 3.04  
- **Return Rate:** 32.5%  
- **Unique Customers:** 7,259  
- **States Covered:** 28  

### Visual analyses performed:
- Revenue over time  
- Category-level revenue breakdown  
- Rating insights  
- Return behavior  
- State-level performance  
- Payment method distribution  

---

## 🧮 3. SQL Analysis (`notebooks/03_sql_queries.ipynb`)
A SQLite database (`database/sales.db`) was created for deeper analysis.

### Example SQL insights:
#### Top Categories by Revenue
- Beauty  
- Electronics  
- Books  
- Clothing  
- Home & Kitchen  

#### Highest Return Rates  
- Books  
- Electronics  
- Clothing  

#### Return Rate by Payment Method  
- Credit Card: 33.34%  
- Debit Card: 32.70%  
- UPI: 32.11%  
- Cash on Delivery: 31.98%  

#### High-Revenue States  
Sikkim, Rajasthan, Chhattisgarh, Meghalaya, Tamil Nadu.

---

## 📊 4. Power BI Dashboard (`powerbi/Amazon_Sales_Analytics.pbix`)

### **Page 1 — Sales Overview**
- KPIs  
- Monthly Revenue Trend  
- Revenue by Category  
- Payment Method Split  
- Delivery Status Breakdown  

### **Page 2 — Product Deep Dive**
- Top 10 Products by Revenue  
- Top 10 Most Returned Products  
- Return Rate by Category  
- Average Rating by Category  
- Units Sold by Category  

### **Page 3 — State-Level Insights**
- India State Revenue Map  
- Return Rate by State  
- Rating by State  
- Rating Distribution  
- Return Rate by Payment Method  

---

## 📁 Project Structure

```
AMAZON-SALES-ANALYTICS/
│
├── dashboard/
│   └── Amazon_India_Sales_Dashboard.pbix
│
├── data/
│   ├── processed/
│   └── raw/
│       └── amazon_sales_2025_INR.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_sql_queries.ipynb
│
├── src/
│   ├── __init__.py
│
├── .gitignore
├── README.md
└── requirements.txt

```

---

## 🧠 Final Insights
- Beauty, Electronics, and Books dominate revenue.  
- Returns remain consistently high (~32%).  
- Ratings do not strongly affect return likelihood.  
- Payment methods behave similarly in return rate.  
- Certain states generate significantly higher revenue.  
- Customer ratings are evenly distributed across 1–5.

---

## 🛠 Skills Demonstrated
- Python (Pandas, Matplotlib, Seaborn)  
- SQL (SQLite)  
- Data Cleaning  
- Exploratory Data Analysis  
- Power BI Dashboarding  
- Business Insight Generation  

---

## 👤 Author
**Samuel N C**
