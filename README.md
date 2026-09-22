# 📊 RetailPulse Analytics — Data Analytics Project

End-to-end data analytics project covering data cleaning, exploratory data analysis (EDA), SQL-based analysis, and an interactive Power BI dashboard on customer purchase and sales data.

## 📌 Overview
This project analyzes customer purchase and sales data to uncover revenue trends, customer segments, and top-performing categories. The goal is to clean and explore the data in Python, answer business questions using SQL, and present key insights through an interactive Power BI dashboard.

**Key objectives:**
- Identify top-performing product categories and products by revenue
- Understand purchase behavior across gender, age group, and subscription status
- Provide actionable recommendations based on the data

## 🛠️ Tools & Technologies
| Category | Tools |
|---|---|
| Data Loading & Cleaning | Python (Pandas, NumPy) |
| Exploratory Data Analysis | Python (Pandas) |
| Querying & Analysis | SQL (MySQL) |
| Visualization | Power BI |
| Reporting | Power BI Report / PDF |

## 🔄 Project Steps
1. **Data Loading** — Imported the raw customer purchase dataset into Python using Pandas
2. **Data Cleaning** — Handled missing values, duplicates, and inconsistent formatting; standardized data types
3. **Exploratory Data Analysis (EDA)** — Analyzed distributions, trends, and correlations using summary statistics and visualizations
4. **SQL Analysis** — Loaded cleaned data into MySQL and wrote queries to answer key business questions (top categories, customer segments, revenue trends)
5. **Dashboard Building** — Designed an interactive Power BI dashboard with KPIs, filters, and visual breakdowns
6. **Reporting** — Summarized findings and recommendations in a final report

## 📈 Dashboard
**RetailPulse Analytics — Customer Purchase & Sales Dashboard**

**KPI cards:**
- Total Customers: 3.9K
- Total Revenue: $233K
- Average Purchase: $59.8
- Average Rating: 3.75
- Repeat Customers: 3,817

**Visuals:**
- Revenue by Category & Subscription Status
- Revenue by Gender
- Revenue Share: Subscriber vs Non-Subscriber
- Revenue by Age Group
- Top 5 Products by Revenue

**Filters/Slicers:** Category, Subscription Status, Gender, Shipping Type


<img width="634" height="331" alt="image" src="https://github.com/user-attachments/assets/eabdda34-f5fc-4f6b-8b1c-7124ec00f8a9" />


## ✅ Results & Key Insights
- Male customers generate 2x the revenue of female customers ($158K vs $75K)
- Non-subscribers contribute 73.12% of total revenue, while subscribers contribute 26.88%
- Clothing is the top category ($104K), nearly 2x the next-highest category (Accessories)
- Senior and middle-aged customers drive the highest revenue by age group ($88K and $66K respectively)
- Blouse, Shirt, and Dress lead as the top revenue-generating products

**Recommendations:**
- Investigate why subscribers contribute less revenue than non-subscribers and explore subscription incentives
- Target marketing campaigns toward younger age groups to close the revenue gap with senior/middle-aged segments
- Expand the Clothing category's best-sellers, given its outsized share of revenue

## 🚀 How to Run
1. Clone this repository
   ```bash
   git clone https://github.com/Pradnya3018/RetailPulse-Analytics
   ```
2. Install required Python libraries
   ```bash
   pip install pandas numpy 
   ```
3. Run the Python scripts/notebooks in order (data loading → cleaning → EDA)
```bash
   Retail Pulse Analytics.ipynb
```
4.Import the cleaned dataset into MySQL and run the queries in 
```bash
Retail Pulse sql code.sql
```
5.Open Retail Pulse Power BI.pbix in Power BI Desktop to view/interact with the dashboard


📫 Contact

LinkedIn: linkedin.com/in/pradnya-gajare-912011285

Email: pradnyagajare2@gmail.com
