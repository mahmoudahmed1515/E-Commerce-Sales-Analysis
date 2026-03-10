# 📊 Sales & Logistics Performance Dashboard

## 📋 Project Overview
This project provides a deep dive into an e-commerce sales dataset. The primary goal was to transform raw transactional data into actionable business intelligence using Microsoft Excel. This dashboard allows stakeholders to track profitability, identify sales trends, and monitor logistics efficiency across different regions and product categories.

## 🚀 Key Performance Indicators (KPIs)
* **Total Profit:** $18,746
* **Total Sales:** $241,131
* **Order Volume:** 1,000 Transactions

## 🛠️ Data Engineering & Modeling
The backbone of this dashboard relies on a clean data pipeline and robust analytical modeling:

* **Data Cleaning & Preparation:** - Standardized date formats for time-series analysis.
    - Handled missing values and categorized inconsistent entries to ensure data integrity.
* **Analytical Engine (Pivot Tables):**
    - Utilized complex Pivot Tables to aggregate data across multiple dimensions (Time, Geography, Category).
    - Created calculated fields to derive Profit Margins and unique order identifiers.
* **Dynamic Visualization:**
    - Integrated **Slicers** to enable end-user interactivity (Filtering by Region, State, and Category).
    - Designed interactive charts (Line, Pie, and Bar charts) to highlight performance bottlenecks and high-growth areas.
* **Automation:** - The architecture is built for scalability; adding new data to the "Raw Data" source automatically updates the Pivot Cache and refreshes the Dashboard visuals.

## 📂 Project Structure
- `Raw Data`: The source transactional dataset.
- `pt_table / pt_range`: Dedicated sheets for data aggregation and calculation logic.
- `Dashboard`: The primary UI featuring interactive slicers for Category, Region, and State.

## 📈 Insights Summary
- **Regional Performance:** Identifying top-performing states (e.g., California) vs. underperforming regions.
- **Logistics Efficiency:** Analyzing the relationship between "Shipping Mode" and net profitability to optimize delivery costs.
- **Category Trends:** Seasonal analysis of "Technology" vs. "Office Supplies" and "Furniture" sales volume.

## 🛠️ Tools & Technologies
- **Microsoft Excel** (Pivot Tables, Slicers, Data Modeling, Conditional Formatting).

---
*Created for data analysis and business performance tracking.*


## 🖼️ Dashboard Preview

### Main Dashboard Interface
![Sales Dashboard](https://i.ibb.co/S4SYQNft/Screenshot-2026-03-10-211912.png)
![Sales Dashboard](https://i.ibb.co/TMw2FzWz/Screenshot-2026-03-10-211931.png)
![Sales Dashboard](https://i.ibb.co/ds4khjPr/Screenshot-2026-03-10-211944.png)



### Data Modeling & Behind the Scenes
![Data Analysis](https://i.ibb.co/1t0zstkW/Screenshot-2026-03-10-212325.png)
![Data Analysis](https://i.ibb.co/cckQBC5v/Screenshot-2026-03-10-212310.png)
