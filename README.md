# Sales Data Analysis & EDA Project

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a multi-sheet sales dataset to uncover **revenue trends, customer behavior, product performance, regional insights, and profitability patterns**.
The final outcome is a **clean analytical dataset**, meaningful **business insights**, and **visualizations ready for dashboarding (Power BI/Tableau)**.

---

## 🎯 Objectives

* Clean and merge data from multiple Excel sheets
* Perform feature engineering (profit, margin, time features, etc.)
* Analyze:

  * Monthly & seasonal sales trends
  * Product and state performance
  * Channel contribution
  * Customer segmentation
  * Profitability patterns
* Generate **visual insights** for business decision-making

---

## 📂 Dataset Description

The dataset contains multiple sheets:

* **Sales Orders** → Order-level transactions (revenue, cost, quantity, dates)
* **Products** → Product lookup information
* **Customers** → Customer identifiers
* **Regions / State Regions** → Geographic mapping
* **2017 Budgets** → Budget allocation by product

---

## 🧹 Data Cleaning Steps

* Standardized column names (lowercase, underscores)
* Fixed incorrect headers in Excel sheets
* Converted `order_date` to **datetime**
* Removed incomplete periods (e.g., Jan–Feb 2018)
* Created new features:

  * `profit = revenue − cost`
  * `profit_margin = profit / revenue`
  * Time features → month, year, seasonality

---

## 📊 Exploratory Data Analysis

### Time-Series Analysis

* Monthly revenue trend
* Overall **seasonality by calendar month**

### Product Analysis

* **Top 10 & Bottom 10 products by revenue**
* Unit price distribution per product

### Geographic Analysis

* **Top states by revenue & order count**
* Region-wise performance

### Channel Performance

* Revenue by sales channel
* **Average profit margin by channel**

### Customer Analytics

* Top & bottom customers by revenue
* **Customer segmentation (Revenue vs Profit Margin)**

### Statistical Insights

* Correlation heatmap of numeric features
* Average Order Value (AOV) distribution

---

## 📈 Key Business Insights

* Revenue is concentrated in **few high-performing products/states**
* Some channels generate **high revenue but low margin**
* Clear **seasonality pattern** exists across months
* Customer base shows **distinct profitability segments**
* Strong correlation between **revenue, quantity, and cost**

---

## 🛠️ Tech Stack

* **Python**

  * pandas → data manipulation
  * matplotlib & seaborn → visualization
* **Excel** → raw data source
* **Power BI / Tableau (optional)** → dashboarding

---

## 🚀 How to Run

1. Place the Excel dataset in the project folder
2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the Jupyter Notebook or Python script step-by-step
4. Visualizations and insights will be generated automatically

---

## 📌 Future Improvements

* Build an **interactive dashboard**
* Add **forecasting (time-series modeling)**
* Perform **RFM or CLV customer analysis**
* Deploy as a **web analytics app**

---

## 👤 Author

**Shivam Singh**
Final-year B.E. (Computer Science) student
Aspiring **Data Analyst / Data Scientist**

---

## ⭐ Project Value

This project demonstrates:

* Real-world **data cleaning & merging**
* Strong **EDA & visualization skills**
* Ability to derive **business insights from raw data**
* Readiness for **Data Analyst roles & internships**

---


### Preview Dashboard

Dashboard_image.png

