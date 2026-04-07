
# Interactive Sales Performance Intelligence Report

## Project Overview
This project features a high-fidelity Power BI report designed to track and analyze sales performance across diverse product lines and geographic regions. The goal was to provide stakeholders with a "single source of truth" for monitoring revenue trends, profit margins, and sales rep performance.

## Key Objectives
- **Trend Analysis:** Visualize monthly and quarterly sales growth to identify seasonal patterns.
- **Profitability Mapping:** Identify high-margin vs. low-margin products to inform inventory strategy.
- **Geospatial Insights:** Map sales distribution to identify underperforming or high-growth territories.
- **Operational Efficiency:** Track order fulfillment and shipping performance metrics.

## Tools & Technical Stack
- **Power BI Desktop:** Data modeling, DAX (Data Analysis Expressions), and visualization.
- **Power Query:** ETL (Extract, Transform, Load) processes to clean and shape the data.
- **DAX Measures:** Created custom measures for Year-to-Date (YTD) sales, Profit Margin %, and Total Orders.
- **GitHub:** Project documentation and version control.

## Data Architecture
The report is built on a star schema model, ensuring optimized performance and scalability:
- **Fact Table:** Centralized sales transactions including revenue, quantity, and costs.
- **Dimension Tables:** Descriptive data for Products, Geography (Regions/Cities), Calendar (Time Intelligence), and Sales Teams.

## Dashboard Features
### 1. Executive Summary
A high-level overview of total revenue, gross profit, and total units sold. 
* **KPI Cards:** Real-time tracking of performance against previous year targets.
* **Revenue Trend:** A line chart displaying sales fluctuations over time.

### 2. Product Intelligence
Detailed breakdown of performance by Category and Sub-category.
* **Top 10 Products:** Identifying the "hero" products driving the most value.
* **Category Split:** A donut chart showing the market share of different product types.

### 3. Regional Sales Map
An interactive map allowing users to drill down from a global or national level to specific cities to see localized performance metrics.

## Data Insights
- **Growth Drivers:** Identified that specific product categories contribute to over 40% of total revenue despite making up only 15% of the inventory.
- **Profit Leaks:** Discovered regions where high shipping costs were significantly eroding net profit margins.
- **Seasonality:** Pinpointed a recurring 20% spike in sales during Q4, suggesting a need for increased staffing and inventory during that period.

## How to View the Project
1. view the raw data set
3.  **Download the .pbix file:** You can download the  file from this repository.
4.  **Open in Power BI Desktop:** Ensure you have the latest version of [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed to view the interactive elements and DAX formulas.

---

### Key Competencies Demonstrated
* Advanced Data Modeling
* DAX Calculations (Time Intelligence & Aggregations)
* User Experience (UX) focused Dashboard Design
* Actionable Business Insight Generation
