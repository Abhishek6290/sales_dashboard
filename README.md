 📊 A Power BI dashboard to analyze sales performance, regional trends, and product insights from a retail dataset.

📌 Overview
This project analyzes sales data from cleaned_train_data.csv to uncover key business insights, including:

Sales trends over time

Regional performance comparisons

Product category breakdowns

Shipping efficiency metrics

Built with Power BI, the dashboard provides actionable recommendations for improving sales and logistics.

📂 Dataset
File: cleaned_train_data.csv

Columns:

order_id, order_date, ship_date

region, city, state

category, sub-category, product_name

sales, customer_segment

🚀 Key Features
✅ Interactive Visualizations – Filter by date, region, or product category.
✅ Sales Trends – Monthly performance tracking.
✅ Top Products – Best-selling items ranked by revenue.
✅ Shipment Analysis – Delivery time comparisons across regions.
✅ Business Insights – Actionable recommendations for sales growth.

Here is my cool dashboard image link....
![imgage alt](https://github.com/Abhishek6290/sales_dashboard/blob/main/dashboard.png?raw=true)

📝 Step-by-Step Guide
1. Data Preparation
Import the CSV into Power BI.

Ensure order_date is formatted as a date.

Create a new column:

DAX
Copy
Order Month = FORMAT([order_date], "YYYY-MM")  
2. Sales Trends (Line Chart)
X-Axis: Order Month

Y-Axis: Sum of Sales

Insight: Identify seasonal trends (e.g., holiday spikes).

3. Regional Sales (Clustered Column Chart)
X-Axis: Region

Y-Axis: Sum of Sales

Insight: Compare performance across regions.

4. Product Category Breakdown (Donut Chart)
Category: Category

Value: Sum of Sales

Insight: See which categories drive the most revenue.

5. Top Products (Horizontal Bar Chart)
Y-Axis: Product Name

X-Axis: Sum of Sales

Filter: Top 10 by sales.

Insight: Track delivery performance.

💡 Key Insights
🔹 Corporate clients spend 2x more than Home Office customers.
🔹 Furniture sales lag behind Technology by 22%.
🔹 West region has the fastest shipment time (avg. 3 days).

📈 Business Recommendations
Increase inventory for high-demand Office Supplies

Dataset (.csv)


🔗 Connect
👨‍💻 Author: Abhishek Verma
📧 Email:  abhishekverma6290@gmail.com
🌐 LinkedIn:  https://www.linkedin.com/in/abhishek-verma-52603a313/

🚀 Happy Analyzing! 🚀
