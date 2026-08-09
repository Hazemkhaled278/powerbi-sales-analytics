Financial & Sales Analytics Dashboard
 Overview
This project presents a comprehensive Financial and Sales Analytics Dashboard developed using Power BI. The primary objective is to provide executive-level insights into sales performance, product profitability, and the impact of pricing strategies on business growth. By synthesizing complex data into interactive visualizations, this dashboard enables data-driven decision-making.

 Key Analytical Insights
The dashboard is structured into three strategic layers:

Executive Financial Overview: High-level KPIs tracking Total Sales, Total Profit, Units Sold, and Year-over-Year (YoY) Sales Growth.

Product & Market Segment Performance: A deep dive into segment-wise distribution, highlighting top-performing products and discount trends.

Pricing Strategy, Costs & Discount Impact: An analysis of manufacturing costs, sale prices, and the correlation between discount bands and profit margins.

Tech Stack
Power BI: Data modeling, DAX measures, and interactive UI/UX design.

Python: Data cleaning, preprocessing, and exploratory data analysis (EDA).

SQL: Data extraction, transformation, and optimization of large datasets.

Data Challenges & Solutions
During the development of this project, I encountered several technical hurdles that required creative solutions:

Data Cleaning & Normalization: The raw dataset contained inconsistencies and missing values. I utilized Python (Pandas) to handle outliers and ensure data integrity before feeding it into Power BI.

Metric Complexity: Implementing accurate DAX calculations for YoY Growth and Profit Margins was challenging due to the need for time-intelligence functions. I resolved this by building a customized Date Table and substituting specific metric aliases to ensure accurate reporting.

Performance Optimization: With complex data relationships, the model initially faced latency issues. I optimized the Star Schema architecture to improve dashboard responsiveness and ensure a smooth user experience.
