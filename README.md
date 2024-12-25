Sales Performance Analysis of Walmart Stores Using Advanced MySQL Techniques
Table of Contents
Introduction
Dataset Overview
Techniques Used
Project Tasks and Insights
How to Use This Project
Results and Visualizations
Conclusion and Recommendations
Contact


Introduction
This project involves a comprehensive analysis of Walmart's sales data using advanced MySQL techniques. The primary goal was to extract meaningful insights, identify trends, and provide actionable recommendations to improve business performance.

Key Objectives:

Analyze sales performance and growth.
Identify customer spending patterns.
Detect anomalies in transactions.
Understand sales trends by various dimensions (e.g., gender, day of the week).
Provide strategic recommendations based on findings.
Dataset Overview
Source: It's already provided in csv file.
Key Columns:
Date: Transaction date.
Branch: Store location identifier.
Customer Type: Member or Normal customer.
Product Line: Category of products sold.
Total: Transaction value.
Payment: Mode of payment (Cash, Credit Card, etc.).
Format: CSV file.
Techniques Used
This project leverages advanced MySQL features, including:

Common Table Expressions (CTEs) for modular and readable queries.
Window Functions: ROW_NUMBER, RANK, DENSE_RANK for ranking and segmentation.
Aggregations: SUM, AVG, MAX, and COUNT for calculating key metrics.
Subqueries: For nested data analysis.
Joins: To combine multiple tables where necessary.
Project Tasks and Insights

Task 1: Identifying the Top Branch by Sales Growth Rate
Analyzed monthly sales growth rates to identify the branch with the highest growth over time.

Insight: Branch X demonstrated a consistent upward trajectory in sales growth.

Task 2: Most Profitable Product Line by Branch
Calculated profit margins for each product line in each branch.

Insight: The "Home and Lifestyle" product line had the highest profitability in most branches.

Task 3: Customer Segmentation Based on Spending
Segmented customers into High, Medium, and Low spenders based on average purchase behavior.

Insight: High spenders accounted for 20% of customers but contributed 60% of revenue.

Task 4: Detecting Anomalies in Sales Transactions
Identified transactions significantly above or below the average sales for each product line.

Insight: Found anomalies in the "Fashion Accessories" category, requiring further investigation.

Task 5: Most Popular Payment Method by City
Determined the most used payment method in each city.

Insight: Credit Card payments were the most popular across all cities.

Task 6: Monthly Sales Distribution by Gender
Analyzed the contribution of male and female customers to monthly sales.

Insight: Male customers contributed slightly more to sales overall, except in December.

Task 7: Best Product Line by Customer Type
Identified preferred product lines for Members and Normal customers.

Insight: Members preferred "Electronic Accessories," while Normal customers leaned toward "Fashion Accessories."

Task 8: Identifying Repeat Customers
Found customers who made repeat purchases within a 30-day timeframe.

Insight: 15% of customers were repeat buyers, contributing to 40% of sales.

Task 9: Top 5 Customers by Sales Volume
Ranked customers by total revenue generated.

Insight: The top 5 customers accounted for 8% of total sales.

Task 10: Sales Trends by Day of the Week
Analyzed sales patterns to identify the most profitable day.

Insight: Saturdays had the highest sales, while Mondays were the slowest.

How to Use This Project
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/Walmart-Sales-Analysis.git
Import the provided dataset (walmartsales.csv) into your MySQL database.
Execute the SQL queries provided in the SQL Scripts folder.
Review the PowerPoint presentation for a summary of results.
Explore the README for additional insights.

Results and Visualizations
Charts: Included in the PowerPoint presentation to illustrate:
Sales trends.
Spending behavior by customer segments.
Anomalies and payment method popularity.
Tables: Highlighting key metrics for each task.

Conclusion and Recommendations
Focus marketing efforts on high-spending customers to maximize ROI.
Optimize inventory for high-profit product lines like "Home and Lifestyle."
Investigate anomalies to prevent revenue leakage.
Promote sales on weekdays to balance weekly sales distribution.
Contact
For questions or collaboration:

Name: Himanshu Jagga
Email: himanshujagga97@gmail.com
GitHub: HimanshuJagga
LinkedIn: https://www.linkedin.com/in/himanshu-jagga-b08ab6170/