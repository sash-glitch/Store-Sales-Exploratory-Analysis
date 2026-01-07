# Store Sales Exploratory Analysis

## 📌 Project Overview

This project analyzes historical daily sales data from Corporación Favorita stores in Ecuador to understand **demand patterns**, identify **performance outliers** at the store and product-family level, and evaluate the impact of **promotions and holidays**.

The goal of this analysis is to provide insights that could inform sales strategies and guide future forecasting efforts.

---

## 🛠️ Tools & Libraries

* Python 3.x
* Pandas, NumPy (data manipulation)
* Matplotlib, Seaborn (visualization)
* Jupyter Notebook

---

## 🔍 Analysis Approach

### 1. Data Preparation

* Loaded sales data and standardized the date column for accurate time-based operations.
* Merged in holiday information to evaluate whether holidays influence sales.
* Checked for missing values, zero-sales days, and data inconsistencies.

### 2. Demand Profiling

* Aggregated sales to the daily level to identify **macro-level trends, peaks, and seasonality**.
* Visualized overall sales trends across all stores.
* Observed consistent weekly cycles, with **weekend sales highest** and December peak in monthly sales.

### 3. Store-Level Analysis

* Ranked stores by total sales to identify **high vs low performers**.
* **Store 44 (top performer):**

  * Strong yearly growth and regular weekly cycles.
  * Grocery, Beverages, and Home & Kitchen were top-selling families.
  * Promotions significantly increased sales, particularly for Home & Kitchen, Beverages, and Grocery.
* **Store 52 (low performer):**

  * Mostly zero sales until 2017, indicating a newly opened store.
  * Non-zero daily sales were inconsistent (zigzag pattern), showing unstable demand.
  * Promotions and product-family contribution differed from top stores.

### 4. Feature-Driven Observations

* Promotions are a strong driver of sales, but **impact varies by product family**.
* Weekly and monthly seasonality is evident and could inform future forecasting.
* Holiday effects exist but are minor compared to promotions.

---

## 📊 Key Takeaways

* Sales are concentrated in top-performing stores; underperforming stores require targeted attention.
* Promotions should be **product-family-specific**, not uniform across all items.
* Clear seasonality patterns exist: **weekends and December are peak sales periods**.
* This EDA lays the foundation for **data-driven decision-making** around promotions and store prioritization.

