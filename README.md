# Nike Sales Performance & EDA Project

## Project Overview
This repository contains an end-to-end Data Analysis and Visualization project focused on Nike's regional sales, product distribution, and discounting strategy. The project covers data cleaning, SQL exploratory analysis, and an interactive Power BI dashboard.

---

## Tech Stack & Tools
* **Python (Pandas):** Data Cleaning, Missing Values Handling, Column Formatting.
* **SQL (DuckDB):** Exploratory Data Analysis, Grouping, Aggregations, Subqueries.
* **Power BI:** Interactive Dashboard, DAX Measures, Top 5/Bottom 5 Dynamic Filtering.
* **Google Colab:** Interactive Development Environment.
* **GitHub:** Version Control & Portfolio Presentation.

---

## 📊 Power BI Dashboard & Visualizations

An interactive Power BI dashboard was developed to complement the SQL analysis and provide visual business insights.

### Key Features & Interactivity
* **Dynamic Top 5 / Bottom 5 Filtering:** Custom bookmarks and measures allow users to toggle between the top 5 performing products/regions and the lowest-performing lines.
* **KPI Overview:** High-level metrics for Revenue, Profit, Units Sold, and Average Discount.
* **Multi-Dimensional Breakdown:** Visualizations across Sales Channels (Online vs. Retail), Product Categories, and Geographic Regions.

### Interactive Demo
https://github.com/user-attachments/assets/748caaff-04fb-422c-9e99-9558e8298a1f

> **Note on Data Discrepancies:**  
> You may observe slight numerical differences between the SQL/Python query outputs and the Power BI visuals. This is due to dynamic filtering applied within the Power BI dashboard (such as date slicers or specific channel filters), as well as differences in automated data aggregation logic within Power BI vs. raw dataset queries.

---

## Key Business Findings (KPIs & Pillars)

1. **Overall Performance:** Tracked Total Revenue, Units Sold, Total Orders, and Average Order Value (AOV).
2. **Regional Trends:** Identified top-performing revenue-generating cities vs. emerging markets.
3. **Product Performance:** Segmented top 5 best-sellers vs. lowest-performing lines to optimize stock.
4. **Discount Strategy:** Analyzed discount application per channel to evaluate impact on unit volume and gross margins.
5. **Channel Comparison:** Evaluated Online vs. In-Store/Outlet performance to measure conversion efficiency.

---

## Strategic Recommendations
* **Inventory Optimization:** Prioritize high-tier product drops in top revenue cities (e.g., Bangalore, Hyderabad).
* **Margin Protection:** Cap promotional discounts on top-selling footwear lines while utilizing discounts in Outlets for slow-moving stock.
* **Product Bundling:** Bundle lower-performing accessories with high-demand flagship products in digital channels.

---

## Repository Structure
* `data/` - Contains raw and cleaned versions of the Nike Sales dataset (`Nike_Sales_Uncleaned.csv`, `Nike_Sales_Cleaned.csv`).
* `power_bi/` - Power BI report file (`Nike_Sales_Dashboard.pbix`) and preview assets.
* `Nike_Sales_Analysis.ipynb` - Jupyter Notebook containing Python cleaning & DuckDB SQL analysis.
* `README.md` - Executive summary and project documentation.
