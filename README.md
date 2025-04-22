Project Title: Food Business Analysis for Leading Restaurant Chain
Tool Used: Power BI
Objective: To analyze sales and performance of food items across various categories, regions, and customer segments to identify trends, top performers, and business opportunities.

1. Data Collection & Import
Imported the dataset from Excel/CSV into Power BI.

Data included Order ID, Date, Product, Category, Sub-Category, Sales, Profit, Quantity, Region, and Customer Segment.

2. Data Cleaning & Transformation
Used Power Query to:

Remove duplicates and null values.

Format date fields correctly.

Create calculated columns (e.g., Year, Month Name) for time-based analysis.

Standardize categorical data like product categories and region names.

Ensured consistent data types for numerical fields like Sales, Profit, and Quantity.

3. Data Modeling
Designed a star schema with a central fact table (Sales Data) and dimension tables (Date, Product, Region, Customer Segment).

Defined relationships between tables for optimized performance and accurate cross-filtering.

4. DAX Measures & KPIs
Created custom DAX formulas to calculate:

Total Sales, Total Profit, Profit Margin (%)

Sales Growth YoY

Top 5 Products by Sales

Category-wise Profitability

Region-wise Performance

Example DAX:

Profit Margin = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Sales]), 0)

5. Dashboard Design
Built multiple interactive visualizations:

Bar and column charts for sales by region, category, and sub-category.

Line charts for monthly trends.

Donut charts for customer segments.

Slicers and filters for Year, Region, and Category.

Cards for KPIs like total sales, total profit, total orders.

6. Business Insights
Identified high-performing products and categories.

Pinpointed underperforming regions with low profit margins.

Highlighted customer segments contributing most to revenue.

Uncovered seasonal trends in food sales (e.g., spikes in specific months).

7. Outcome & Impact
Delivered a clean, visually appealing, and dynamic dashboard for business stakeholders.

Helped management understand key areas of growth, areas needing attention, and make data-driven decisions on inventory, pricing, and marketing strategies.
