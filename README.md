# Data Analysis Project: Olist E-commerce Performance Dashboard

## Background & Project Goal

This project is an end-to-end data analysis case study of the Olist dataset, featuring data from one of the largest e-commerce platforms in Brazil. The primary goal was to build a focused **Data Mart** and develop a comprehensive **interactive dashboard** to answer key business questions related to sales performance, customer profiling, and logistics efficiency.

---

## 🔗 Interactive Dashboard

The live, interactive dashboard created from this analysis can be accessed publicly via the following link:

**[View the E-commerce Analysis Dashboard Here](https://lookerstudio.google.com/reporting/e60e42f8-90a3-478d-b855-fe5d737a143d)**

---

## 🛠️ Tech Stack

* **Data Processing & Analysis:** Python (Pandas)
* **IDE / Notebook:** Google Colab
* **Data Storage (Data Mart):** Google Sheets
* **Data Visualization & Dashboard:** Looker Studio (formerly Google Data Studio)

---

## 🗂️ Project Workflow (Data Pipeline)

1.  **Data Collection:** Utilized the public Olist dataset, which consists of 9 separate CSV files.
2.  **Data Transformation & Modeling:**
    * Merged 5 key tables (orders, order\_items, products, customers, payments) into a single master table using **Python (Pandas)**.
    * Cleaned the data by handling null values (`NaN`) and converting date columns to the proper datetime format.
    * Performed feature engineering to create new, insightful columns such as `delivery_duration` and `purchase_month`.
3.  **Data Loading:** Exported the cleaned and enriched DataFrame to **Google Sheets**, which serves as the Data Mart for this project.
4.  **Data Visualization:** Connected Google Sheets to **Looker Studio** to build a multi-page interactive dashboard.

---

## 📊 Dashboard Analysis & Insights

The dashboard is composed of three main pages, each with a different analytical focus:

### Page 1: Executive Summary
Provides a high-level overview of the business performance, featuring main KPIs like **Total Revenue**, **Total Orders**, alongside **monthly sales trends** and a **geographical revenue map**.

### Page 2: Customer Deep Dive
Analyzes customer profiles and behavior, including a **ranking of cities by customer count**, **preferred payment methods**, and the **distribution of payment installments**.

### Page 3: Shipping & Logistics Analysis
Evaluates logistics efficiency by showcasing metrics such as the **average delivery duration per state**, a **freight cost heatmap**, and the **accuracy between estimated and actual delivery times**.
