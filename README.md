
📊 Sales Data Analysis
🧭 Overview
This dataset contains 1,020 raws of sales transactions across multiple regions (North, South, East, West) and product categories (Electronics, Furniture). It includes details such as Order ID, Order Date, Customer Name, Region, Product, Category, Quantity, Unit Price, Sales, Cost, and Profit.

The dataset is designed for business intelligence, analytics, and data cleaning practice, with intentional issues such as missing values, inconsistent entries, and anomalies.

🔑 Key Insights
Regional Coverage: Sales span across all four regions, with notable variations in profitability.

Product Categories: Electronics (Smartphones, Laptops, Monitors, Headphones) and Furniture (Cabinets, Bookshelves, Office Desks, Desk Chairs).

Profitability Trends: Some transactions show negative or unusually high profits, highlighting data quality issues.

Temporal Range: Order dates range from the 1970s to 2025, useful for time-series analysis.

Data Quality Issues:

Missing customer names and regions in some rows.

Incorrect or inconsistent category labels (e.g., “Furniture” without product type).

Outliers in unit prices and profits.

⚙️ Potential Uses
Data Cleaning & Preprocessing: Handle missing values, fix inconsistent categories, and correct anomalies.
Dax :Calculate measueres.
Exploratory Data Analysis (EDA): Identify sales trends, regional performance, and product profitability.

Visualization Projects: Create dashboards in Power BI.



🚀 Recommendations
1. Improve Regional Performance

Use the West region's higher profit margin as a reference when reviewing pricing, product mix, and cost structure in other regions.

2. Focus on High-Profit Products

Monitor sales of Laptop and Bookshelf, which show relatively strong profit contribution/margins. Review whether their pricing and availability can be maintained.

3. Review Low-Margin Products

Investigate products such as Monitor and Cabinet, which have high sales but lower profit margins than some other products.

4. Investigate Negative Costs

Review the 29 negative Cost records before using profit figures for business decisions. Determine whether they represent returns, refunds, adjustments, or data-entry errors.

5. Improve Missing Data

Create a data-quality process to reduce missing:

Customer names
Regions
Products
Order dates
Sales
Cost
Profit
6. Monitor YTD Performance


.

📁 Repository Structure
📂 Sales-Data-Analysis
 ┣ 📊 data/
 ┣ 📈 notebooks/
 ┣ 🧮 scripts/
 ┣ 📘 documentation/
 ┗ README.md







