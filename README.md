# 📦 FedEx Shipment Data - Exploratory Data Analysis (EDA)

This project focuses on performing **Exploratory Data Analysis (EDA)** on a FedEx shipment dataset to uncover insights about logistics performance, cost drivers, delivery patterns, and shipment behaviors. The analysis aims to support strategic decision-making and operational efficiency improvements.

---

## 📌 Table of Contents

- [Project Overview](#project-overview)  
- [Objectives](#objectives)  
- [Dataset Description](#dataset-description)  
- [Libraries Used](#libraries-used)  
- [Key Analysis Sections](#key-analysis-sections)  
- [Insights Summary](#insights-summary)  
- [Running the Notebook](#running-the-notebook)  
- [Screenshots & Visuals](#screenshots--visuals)  
- [Future Work](#future-work)  
- [Author](#author)

---

## 📄 Project Overview

Shipping logistics play a crucial role in customer satisfaction, cost management, and service efficiency. This notebook provides an in-depth look at various factors affecting **FedEx deliveries**, including shipment modes, customer segments, delivery statuses, and financial metrics.

Through statistical summaries, visualization techniques, and correlation analysis, we aim to understand what affects delivery times, shipping costs, and overall efficiency in operations.

---

## 🎯 Objectives

- Analyze the distribution of different shipping modes and delivery statuses.
- Explore the relationship between shipping cost, weight, and discounts.
- Identify patterns in delivery delays and cost fluctuations.
- Segment customers based on shipment preferences.
- Provide actionable insights that could guide business or logistics strategy.

---

## 📊 Dataset Description

The dataset consists of structured shipment-related data including:

| Feature            | Description                                   |
|--------------------|-----------------------------------------------|
| `ID`               | Unique shipment ID                            |
| `Customer Name`    | Name of the customer                          |
| `Ship Mode`        | Shipping method used (e.g., First Class)      |
| `Segment`          | Customer type/segment (Consumer, Corporate)   |
| `Product Category` | Category of the item shipped                  |
| `Sales`, `Profit`  | Financial figures for the shipment            |
| `Shipping Cost`    | Cost incurred during shipping                 |
| `Order Date`       | Date the order was placed                     |
| `Delivery Date`    | Actual delivery date                          |
| `Delivery Status`  | Delivered/Delayed                             |
| `Weight`, `Volume` | Shipment metrics                              |

---

## 🛠️ Libraries Used

The notebook uses the following Python libraries for data handling and visualization:

- `pandas` – DataFrame manipulation and cleaning
- `numpy` – Numerical operations
- `matplotlib.pyplot` – Static plotting
- `seaborn` – Enhanced statistical visualization
- `plotly.express` – Interactive charts
- `warnings` – Suppressing warning messages

---

## 📈 Key Analysis Sections

1. **Data Cleaning & Preparation**
   - Missing value analysis
   - Date formatting
   - Derived features (e.g., delivery time)

2. **Univariate Analysis**
   - Frequency distribution of shipment modes and delivery statuses
   - Top product categories and customer segments

3. **Bivariate & Multivariate Analysis**
   - Shipping cost vs. weight
   - Profit vs. sales correlation
   - Segment-wise shipping behavior

4. **Time-Based Insights**
   - Orders and deliveries over time
   - Monthly trends in delivery delays

5. **Visualizations**
   - Heatmaps, bar charts, scatter plots, pie charts, box plots

6. **Business Insights & Interpretation**
   - Commentary on observed trends and what they imply

---

## 📌 Insights Summary

- **First Class** and **Standard Class** are the most used shipping modes.
- A significant portion of delays are associated with heavy-weight shipments.
- **Corporate clients** tend to have higher shipping costs on average.
- **Discounts** have a non-linear impact on **profitability**.
- Certain customer segments show consistent delivery delays, requiring deeper analysis.

---
👤 Author-
Shishir Varun
Data Analyst | Python | SQL | Power BI
📬 varunshishir@gmail.com

