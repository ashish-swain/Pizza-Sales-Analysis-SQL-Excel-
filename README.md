# Pizza-Sales-Analysis-SQL-Excel-

🍕 Pizza Sales Analysis (SQL)
Analyze pizza sales data using SQL to uncover revenue drivers, order trends, and product performance across categories and sizes.

📊 Key Metrics (KPIs)
- Total Revenue: SUM(total_price)
- Average Order Value: SUM(total_price) / COUNT(DISTINCT order_id)
- Total Pizzas Sold: SUM(quantity)
- Total Orders: COUNT(DISTINCT order_id)
- Avg Pizzas per Order: SUM(quantity) / COUNT(DISTINCT order_id)

📈 Trend Analysis
- Daily Orders: Grouped by weekday using strftime('%w')
- Hourly Orders: Grouped by strftime('%H')

📦 Category & Size Breakdown
- % of Sales by:
- Pizza Category
- Pizza Size
- Total Pizzas Sold by Category

🏆 Product Performance
- Top 5 Best Sellers by quantity
- Bottom 5 Sellers by quantity
- January Category Sales % using SUBSTR(order_date, 4, 2) = '01'

📊 Excel Enhancements
- Added Order_Day column using =TEXT([@[order_date]],"dddd")
- Created pivot tables for revenue and order metrics
- Calculated:
- Distinct order count
- Avg Order Value
- Total Quantity
- Avg Pizzas per Order

🧰 Tools Used
- SQL (SQLite syntax)
- Microsoft Excel

- SQL (SQLite syntax)
- Microsoft Excel
