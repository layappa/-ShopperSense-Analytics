

📊 Customer Behavior Dashboard & Analysis

## 🔍 Project Overview

This project focuses on analyzing **customer shopping behavior** using **Python, SQL, and Power BI** to uncover insights related to customer segments, purchasing patterns, revenue drivers, and subscription behavior.
The final output is an **interactive Power BI dashboard** that enables data-driven business decisions.

---

## 📁 Project Components

* **Python (EDA & Data Cleaning)**
* **PostgreSQL (Business Analysis using SQL)**
* **Power BI (Interactive Dashboard & Visualization)**

---

## 🗂 Dataset Summary

* **Total Records:** ~3,900 customers
* **Total Columns:** 18
* **Key Attributes:**

  * Customer Demographics: Age, Gender, Subscription Status
  * Purchase Details: Category, Purchase Amount, Rating
  * Behavioral Data: Purchase Frequency, Shipping Type, Discounts
* **Missing Values:** Review ratings (handled during EDA)

---

## 🐍 Exploratory Data Analysis (Python)

Performed detailed EDA using **Pandas, NumPy, and Matplotlib/Seaborn**:

* Data loading and inspection (`info()`, `describe()`)
* Handling missing values using **median imputation**
* Column name standardization (snake_case)
* Feature engineering:

  * `age_group`
  * `purchase_frequency_days`
* Redundancy check and column optimization
* Exported cleaned dataset to **PostgreSQL**

📄 **File name suggestion:**
`customer_behavior_eda.ipynb`

---

## 🛢 SQL Analysis (PostgreSQL)

Conducted advanced SQL queries to answer business-focused questions:

* Revenue comparison by **gender**
* High-spending customers using **discounts**
* **Top-rated products**
* Shipping type vs average purchase value
* Subscribers vs non-subscribers analysis
* Discount dependency by product
* Customer segmentation (New, Returning, Loyal)
* Revenue contribution by **age group**

📄 **File name suggestion:**
`customer_behavior_analysis.sql`

---

## 📈 Power BI Dashboard

An interactive **Customer Behavior Dashboard** built using Power BI with:

### 🔑 Key KPIs

* Total Customers
* Average Purchase Amount
* Average Customer Rating

### 📊 Visual Insights

* Customers by subscription status
* Revenue & sales by category
* Customer distribution by age group
* Purchase frequency trends
* Category-wise performance

### 🎛 Filters

* Gender
* Subscription Status
* Product Category
* Shipping Type


---

## 💡 Business Insights & Recommendations

* Promote **subscription plans** to increase recurring revenue
* Introduce **loyalty programs** for repeat customers
* Optimize **discount strategies** to protect profit margins
* Focus marketing on **high-revenue age groups**
* Highlight **top-rated and best-selling products**

---

## 🛠 Tools & Technologies Used

* **Python:** Pandas, NumPy
* **SQL:** PostgreSQL
* **BI Tool:** Power BI
* **Database Connector:** SQLAlchemy

---

## 🎯 Project Use Case

This project demonstrates end-to-end **Data Analytics workflow**:

> Raw Data ➜ Cleaning ➜ Analysis ➜ Visualization ➜ Business Decisions

Ideal for:

* Data Analyst Portfolio
* Business Intelligence Roles
* SQL + Python + Power BI Showcase


