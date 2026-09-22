# E-Commerce-Sales-Intelligence-Dashboard-on-PowerBI
## 📌 Project Overview
ShopNest is a simulated e-commerce retail business. As a data analyst for this capstone project, I designed an Interactive Power BI Dashboard from raw multi-table data ingestion through Power Query and DAX to an interactive executive dashboard. 
The dashboard answers critical business questions across key metrics of an e-commerce business, including sales performance, order delays, customer behavior, and payment trends. The goal is to extract actionable insights, improve decision-making, and optimize business operations using data visualization and analysis.
## 🔍 Problem Statement
E-commerce platforms generate massive volumes of data every day — orders, transactions, and customer interactions — but without structured analysis, that data stays an untapped asset rather than a strategic tool. This project tackles four core business challenges:

1. **Sales Performance** — Uncover sales trends and identify top-performing products to guide inventory and marketing decisions.
2. **Delivery & Customer Satisfaction** — Pinpoint the root causes of order delays and quantify their impact on the customer experience.
3. **Customer & Market Insights** — Analyze customer behavior, payment preferences, and regional sales performance to surface growth opportunities.
4. **Strategic Decision-Making** — Translate raw data into actionable, data-driven insights that inform long-term strategy.

This dashboard was built to close that gap — turning fragmented e-commerce data into a clear, decision-ready view of the business.
## Approach to solve the problem

To address these challenges, I followed a structured, end-to-end analytics workflow:

1. **Data Collection & Cleaning** – Used Power Query to clean and preprocess the raw datasets, handling missing values, correcting inconsistencies, and standardizing data types.
2. **Data Modeling & Relationships** – Built a relational model connecting Orders, Products, Customers, and Payments to enable efficient, accurate querying across the dataset.
3. **DAX Calculations & KPIs** – Developed key measures including Total Sales, Delayed Orders, On-Time Orders, Review Scores, and Revenue Trends to quantify business performance.
4. **Dashboard Design & Interactivity** – Designed a multi-page dashboard with interactive navigation buttons, tooltips, and drillthrough pages for deeper exploration.
5. **Visualization & Insight Extraction** – Used bar charts, line graphs, pie charts, and tree maps to surface meaningful trends and highlight actionable business performance.

## 🚀 Implementation 

### 1️⃣ Data Cleaning & Transformation
- Resolved missing values (e.g., in `order_delivered_carrier_date`) to ensure data completeness and accuracy.
- Corrected inconsistent data types and standardized formats across all datasets.
- Merged multiple raw datasets into a single, structured, and optimized data model.

### 2️⃣ Data Modeling & DAX Calculations
- Established one-to-many relationships across key datasets (Orders, Customers, Products, Sellers) to enable seamless cross-table analysis.
- Built DAX measures to calculate Total Revenue, Average Review Score, Delayed Orders, and Seasonal Sales Trends.

### 3️⃣ Dashboard Development & Design
- **Multi-Page Navigation** – Implemented custom button shapes to navigate across Sales Analysis, Delayed Orders, Customer Insights, and Payment Analysis pages.
- **Contextual Tooltips** – Enabled hover-based tooltips for deeper, in-context insights without cluttering the main visuals.
- **Dynamic Slicers & Filters** – Added interactive filters for Year, Quarter, and State to support flexible, on-the-fly data exploration.

### 4️⃣ Key Insights & Business Impact
- Identified best-selling product categories to sharpen marketing strategy.
- Uncovered delivery inefficiencies by analyzing delayed-order patterns across regions.
- Surfaced customer payment preferences to help streamline the checkout experience.
- Mapped regional sales performance to support targeted expansion decisions.

## 🛠 Tools Used

- ✔ **Power BI** – Data modeling, visualization, and DAX-based calculations
- ✔ **Power Query** – Data cleaning and transformation
- ✔ **DAX (Data Analysis Expressions)** – Custom measures and KPIs

## 📢 Conclusion

This project demonstrates end-to-end data analytics and visualization capabilities — from cleaning raw, messy e-commerce data to building a fully interactive Power BI dashboard. Beyond the technical build, it delivers real business value: clear visibility into sales trends, delivery performance, customer behavior, and revenue patterns, enabling data-driven decisions that can directly improve e-commerce operations.

