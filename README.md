# Blinkit-Sales-Analysis-Dashboard
📌 Project Overview:<img width="1920" height="1080" alt="Screenshot (70)" src="https://github.com/user-attachments/assets/be4166f1-b0c7-45eb-97f1-8298d5359171" />
<img width="1920" height="1080" alt="Screenshot (69)" src="https://github.com/user-attachments/assets/f9fbe469-0344-4147-8d57-e803fa89765e" />
<img width="1920" height="1080" alt="Screenshot (68)" src="https://github.com/user-attachments/assets/b4c4ff84-f02c-4938-a6cb-1e629f4b13fe" />

The Blinkit 360° Ops Monitor is an end-to-end Power BI solution designed to analyze delivery performance, sales trends, and operational bottlenecks. This dashboard transforms raw multi-source CSV/Excel data into actionable insights for Store and Category Managers to optimize fulfillment rates and rider allocation.
🎯Key Business Questions Addressed:
How does delivery delay correlate with specific stores or product categories?

Which payment methods are most preferred across different order volumes?

What is the relationship between product pricing (MRP) and total sales volume?

How does customer sentiment impact overall order frequency?

📊 Dashboard Visuals
1. Operations Overview (Sales & Inventory)
Total Sales: ₹5.0M with 5K Total Orders.

AOV (Average Order Value): ₹994.48.

Inventory Insights: Real-time tracking of stock levels (Min/Max) to prevent stock-outs.

2. Delivery & Logistics Performance
Delivery Status: Real-time tracking of "On Time" vs. "Significantly Delayed" orders.

Sentiment Analysis: Categorization of orders into Positive, Negative, and Neutral sentiment.

Payment Split: Analysis of Card, Cash, Wallet, and UPI transaction distribution.

📈 Key Metrics (KPIs)
Operational KPIs: Average Delivery Delay (currently 4.44 mins), Fulfillment Success Rate.

Sales KPIs: Total Revenue, Total Orders, Average Unit Price (₹493.16).

Customer KPIs: Average Rating by Category, Sentiment Score by Order Volume.

🛠️ Tech Stack & Skills
Tool: Power BI Desktop

Data Modeling: Star Schema with multi-source Excel/CSV integration.

DAX (Data Analysis Expressions): * Dynamic AOV calculation.

Time-series sales forecasting.

Conditional formatting for delivery delay status.

Power Query: Data cleaning, attribute standardizing, and merging logistics and sales tables.

🧪 Documentation & Quality Assurance
As shown in the Documentation Page, this project followed a strict testing protocol:

TC-001: Navigation Action (Info icon leads to Project Info).

TC-003: DAX Accuracy (Verified Avg Delivery Delay of 4.44 against Excel Pivot tables).

TC-004: Slicer Sync (Ensured filters on Page 1 apply globally to Page 2 visuals).

💡 Business Recommendations
Logistics Optimization: Focus on Store IDs showing consistent "Significant Delays" (e.g., Store 14) to investigate local rider shortages.

Payment Strategy: With UPI and Cards holding a nearly equal share (~25% each), Blinkit should maintain robust integration for both to prevent checkout friction.

Stock Management: Categories like 'Baby Care' and 'Snacks' show high sales volatility; implementing automated re-order triggers at the 74.75 average stock level is recommended.
