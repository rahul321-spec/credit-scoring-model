# E-Commerce Retail Sales Performance Analysis 📊

 This project focuses on analyzing retail sales data of an electronics store to derive actionable business insights using Python.

## 🎯 Project Objective
The goal is to analyze historical e-commerce transaction logs to help stakeholders understand:
1. **Spatial Trends:** Which cities generate the highest revenue to optimize regional marketing spend.
2. **Temporal Trends:** Which months experience peak sales demand to assist inventory and supply chain planning.

## 🛠️ Tech Stack & Tools
* **Language:** Python 3
* **Libraries:** Pandas (Data Wrangling), Matplotlib (Data Visualization)
* **Environment:** Jupyter Notebook (Anaconda Distribution)

## 🧼 Data Cleaning & Preprocessing Pipeline
Before exploring the data, a rigorous data cleaning workflow was established:
* **Handling Missing Data:** Identified and dropped 87 completely empty (`NaN`) rows.
* **Type Conversion:** Cast `Quantity Ordered` and `Price Each` from string objects to numerical formats (`int` and `float`).
* **Feature Engineering:** Created new attributes for granular analysis:
  * `Sales` = `Quantity Ordered` × `Price Each`
  * `Month` (Extracted from `Order Date`)
  * `City` (Extracted from `Purchase Address`)

## 📈 Key Insights & Visualizations

### 1. City-wise Revenue Contribution
* **Top Performer:** **San Francisco** emerged as the dominant market, driving the maximum sales volume.
* **Under
*
