<p align="center">
  <img src="Flipkart Logo.jpg" alt="Flipkart Logo" width="300"/>
</p>

<h1 align="center">
  Flipkart Sales Analysis Dashboard
</h1>

<p align="center">
  A comprehensive Power BI dashboard built to analyze Flipkart's sales data. This project transforms raw transaction data into an interactive report to uncover insights on transaction performance, customer purchasing behavior, and long-term value.
</p>

<p align="center">
  <img alt="Power BI" src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img alt="Data Analysis" src="https://img.shields.io/badge/Data_Analysis-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img alt="E-Commerce" src="https://img.shields.io/badge/E_Commerce-2874F0?style=for-the-badge&logo=flipkart&logoColor=white"/>
</p>

---

## 📊 Dashboard Showcase

The final interactive dashboard provides a 360-degree view of sales performance, allowing stakeholders to identify revenue patterns, customer engagement trends, and regional performance at a glance.

<p align="center">
  <img src="Flipkart Dashboard.png" alt="Flipkart Sales Dashboard" width="90%">
</p>

---

## ✨ Key Features & Insights

This dashboard is designed to support data-driven decision-making by tracking critical KPIs and providing deep-dive visualizations.

### 📈 Key Performance Indicators (KPIs)

* **Total Sales:** The total revenue generated.
* **Total Quantity:** The total number of items sold.
* **Total Orders:** The total count of unique orders placed.
* **Average Order Value (AOV):** The average amount spent per order (`Total Sales / Total Orders`).

### 🎨 Interactive Visualizations

* **Slicers (Filters):** Dynamically filter the entire report by **Region**, **Ship Mode**, **Category**, and **Sub-Category**.
* **Sales by Month (Line Chart):** Tracks revenue trends over time to identify seasonality and growth.
* **Sales by Sub-Category (Bar Chart):** Identifies top-performing and under-performing product sub-categories.
* **Sales by Region (Filled Map):** Provides a geographical overview of sales concentration.
* **Sales by Segment & Ship Mode (Pie/Donut Charts):** Breaks down revenue by customer segment and fulfillment method.
* **Detailed Matrix:** A tabular view of `Sales`, `Quantity`, and `AOV` by product **Category** for granular analysis.

---

## 🗃️ Data Model & Architecture

The foundation of this report is an optimized **Star Schema** created within Power BI. The raw, flat `FlipkartSales.xlsx.csv` file was transformed using Power Query to create a robust model. This reduces redundancy and significantly improves report performance and scalability.

* **Fact Table:** `FlipkartSales` (contains quantitative data like Sales, Quantity).
* **Dimension Tables:** `Calendar` (for time intelligence), `Region` (for geographical data), `Product` (for item details).



---

## 🛠️ Technologies Used

* **Microsoft Power BI:** The primary tool for data modeling, analysis, and visualization.
* **Power Query (M Language):** Used for the complete ETL (Extract, Transform, Load) process to clean the data and create the star schema.
* **DAX (Data Analysis Expressions):** Used to create custom measures for all KPIs (e.g., `Total Sales`, `AOV`).

---

## 🚀 How to Use

To explore this report:

1.  **Download the files:**
    * Download the `.pbix` file (the main Power BI report).
    * Download the `FlipkartSales.xlsx.csv` data file.
2.  **Open in Power BI Desktop:**
    * Open the `.pbix` file.
3.  **Update Data Source (If needed):**
    * If the report can't find the CSV, go to `Transform data` -> `Data source settings`.
    * Select `Change Source...`, browse to the location where you saved `FlipkartSales.xlsx.csv`, and click `OK`.
4.  **Interact:**
    * Click on any chart, slicer, or map to filter and explore the data!
