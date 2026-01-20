IKEA Customer Retention Analysis
Project Overview
This project focuses on analyzing customer behavior and retention for IKEA to identify key drivers of loyalty and churn. As a Data Analyst, I developed a comprehensive Power BI dashboard to visualize critical business KPIs, segment customers based on their lifetime value (CLV), and provide actionable insights into regional and store-type performance.

Key Business Questions Addressed

Retention & Churn: What is the overall retention rate, and which regions/loyalty tiers have the highest churn? 


Customer Lifetime Value (CLV): How are customers distributed across value segments (Low, Medium, High Value)? 


Promotion Impact: Does applying promotions significantly increase the average transaction amount? 


Store Performance: How do "Express" stores compare to "Superstores" in terms of transaction size and retention? 

Dashboard Features
The solution is organized into four strategic views:


Overview KPIs: Tracking high-level metrics like Total Customers, Retention Rate (87.59%), and average CLV ($49.84K).


Loyalty & Promotion Impact: Analyzing the relationship between loyalty points earned vs. redeemed and the effectiveness of promotions.


Store & Region Insights: Geographic analysis across Birmingham, Leeds, London, and Manchester, and performance by store type.


Customer Segmentation: Deep dive into "Days Since Last Purchase" and segmentation by purchase frequency (Low, Mid, and High-Tier).

Technical Implementation (DAX Measures)
To power this analysis, I created several complex DAX measures, including:


Retention Rate: Calculated based on a 6-month cutoff from the last transaction date.


Churn Rate%: Calculated as [Churned Customers] / [Total Customers].


Customer Lifetime Value ($CLV): Calculated as [Total Amount Spent] / [Membership Duration].


Customer Segmentation Logic: Utilizing SWITCH(TRUE(), ...) to categorize customers into tiers based on purchase count.

Tools Used

Power BI: For data modeling, DAX development, and interactive dashboard creation.

Power Query: For data cleaning and transformation (ETL)
