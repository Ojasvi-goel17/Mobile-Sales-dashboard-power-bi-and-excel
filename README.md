# 📱 Mobile Sales Performance Dashboard (Power BI)

A comprehensive, interactive retail analytics solution built in **Power BI** to evaluate sales trajectories, track time-intelligence metrics, map geographical hubs, and decipher consumer purchasing behaviors. 

This project bridges the gap between raw, multi-year transaction logs and executive-level strategic decision-making.

---

## 📊 Business Problem & Objective
In a competitive retail landscape, stakeholders need real-time data clarity to optimize inventory, streamline payment operations, and direct localized marketing efforts. 

The primary objective of this project was to clean, model, and visualize retail transactional data to discover:
1. **Sales Momentum:** How current metrics compare against historical performance.
2. **Product Performance:** Which brands and individual models generate the highest revenue.
3. **Consumer Habits:** What payment modes dominate the transaction volume.
4. **Geographical Demand:** Where the primary sales hubs are located across India.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Power BI Desktop:** Core platform for data modeling, DAX architecture, and report visualization.
* **Power Query (M Language):** Used for advanced data profiling, cleaning, removing duplicates, and establishing proper data types.
* **DAX (Data Analysis Expressions):** Engineered to build robust KPIs, custom aggregation measures, and time-intelligence logic.
* **Data Modeling:** Built a clean star/snowflake schema separating dimensional tables from the core transactional fact table.

---

## 🔑 Key Features & Technical Architecture

### 1. Advanced Time-Intelligence (DAX Measures)
To evaluate retail health accurately, the project bypassed basic calendar groupings to establish advanced dynamic calculations:
* **Month-to-Date (MTD) Revenue:** Displays a continuous rolling sum of sales across individual days of the current month, peaking at a cumulative **18.9M** in the analyzed August cycle.
* **Same Period Last Year (SPLY):** Compares the active selected timeframe with historical performance exactly 12 months prior to isolate true seasonal growth trends (e.g., contrasting YoY performance for Quarter 2 across 2022, 2023, and 2024).

### 2. Multi-Dimensional Interactive Filters (Slicers)
The interface features top-aligned global filters that sync smoothly across the report view:
* **Mobile Model & Brand:** Instantly filters the layout to zero in on specific device tiers.
* **Payment Method:** Breaks down the metrics by client spending preferences.
* **Time Hierarchy Slicers:** Allows drill-down options from Year to Quarter down to individual Months and Days.

### 3. Geospatial Visualization
Integrated a mapping engine that references coordinate/city inputs to map sales distribution. It visually highlights volume concentrations across major cities, providing instant clarity on market penetration.

---

## 💡 Analytical Insights & Business Discoveries

* **The Digital Shift (Payment Preferences):** **UPI** emerged as the dominant payment infrastructure, claiming **47.9%** of all customer transactions. Cash and Credit Card routes followed, suggesting that promotional tie-ins and checkout flows should optimize heavily around instant digital UPI payments.
* **Top-Tier Revenue Drivers:** The **Galaxy A51** stood out as a high-volume revenue champion, demonstrating long-term market popularity and helping to map out inventory priorities for upcoming retail quarters.
* **Regional Sales Hubs:** Data points indicate exceptional market depth in major urban regions including **Delhi, Patna, Hyderabad, and Kolkata**, showing where localized marketing spend will yield the highest return on investment.
* **Service Quality Control:** Over **44.4%** of analyzed logs secured "Good" or "Average" ratings, providing a reliable foundation for tracking customer satisfaction alongside traditional sales numbers.

---

## 📂 Project Repository Structure
```text
├── Data/                 # Contains raw/processed dataset (CSV/Excel files)
├── Screenshots/          # High-resolution dashboard snapshots for preview
├── Mobile_Sales.pbix     # Master Power BI Project file containing model and layouts
└── README.md             # Project documentation and summary
