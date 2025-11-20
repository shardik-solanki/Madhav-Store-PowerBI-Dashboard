Ecommerce Sales & Profit Dashboard (Power BI)

Overview
A Power BI dashboard built from spreadsheet data to track ecommerce sales, profit, order volume, and product/customer performance.

Data Sources
Excel/CSV files
Fields: date, state, customer, category, sub-category, amount, profit, quantity, payment mode

Key Metrics
Total Sales Amount
Total Profit
Total Quantity Sold
Average Order Value (AOV)

Visuals
Top States (bar)
Top Customers (bar)
Quantity by Category (donut)
Quantity by Payment Mode (donut)
Profit/Loss by Month (bar with negatives)
Profit by Sub-Category (bar)
Slicers: Quarter, Category

Transformations / Calculations
AOV = Sum(Amount) / Count(Orders)
Extracted Month & Quarter
Cleaned text fields; standardized state/customer names
Converted date fields
Kept negative profit values
Basic model: Orders ↔ Customers ↔ Products

Intended Users
Ecommerce managers, analysts, and category/operations teams.

Decisions Supported
High-value states/customers
Most/least profitable categories and sub-categories
Months with losses
Payment mode distribution
Inventory and marketing planning

Refresh Instructions
Replace/update spreadsheets in /Data (keep filenames & schema).
Open .pbix in Power BI Desktop.
Select Refresh.
Verify relationships.
Publish to Power BI Service if needed.

Requirements & Structure
Power BI Desktop
