
##Executive Summary
AdventureWorks Cycles lacked a overview of business performance, making it difficult for leadership to monitor sales, compare regional results, identify top-performing products, and recognize high-value customers. Using Power BI, I developed an interactive executive dashboard that shows key business metrics.

Business Recommendations:
1. Increase marketing and inventory investment in the highest-performing regions, particularly the Northwest, while evaluating the factors driving its success.

2. Investigate underperforming regions, such as Central West and Mexico West, to identify opportunities to improve sales performance.

3. Prioritize promoting top-performing products and brands to maximize revenue, while evaluating lower-performing products for pricing, merchandising, or assortment improvements.

4. Strengthen customer retention by developing loyalty programs and targeted promotions for high-value customers to encourage repeat purchases.


Business Problem:

Leadership at AdventureWorks Cycles spends too much time compiling reports from multiple data sources and lacks timely visibility into company performance. Management a single source for tracking KPIs, comparing regional sales, analyzing product performance, and identifying high-value customers.

Methodology:
1. Imported CSV files and cleaned data using Power Query.
2. Built a snowflake schema data model and defined relationships between fact and dimension tables using one-to-many relationships
3. Developed DAX measures to calculate business KPIs.
4. Created interactive Power BI dashboards to analyze sales performance, regional trends, product performance, and customer value.
5. Used slicers to filter visuals


Skills:
Power BI: Power Query (ETL), Data Cleaning, Data Transformation, Data Modeling, DAX Measures, Calculated columns, Data visualization


Dashboard Preview Executive Overview
Page 1

The executive overview provides a high-level summary of revenue, orders, and sales trends. It allows stakeholders to quickly evaluate overall business performance.




<img width="2078" height="1168" alt="Screenshot 2026-07-29 203949" src="https://github.com/user-attachments/assets/176ee35f-1c4c-455a-960b-c22c804ecce5" />



Dashboard Preview Page 2 
Product Analysis 
The product analysis highlights top-performing products, categories, and their contribution to total revenue.

<img width="2137" height="1215" alt="pag2 " src="https://github.com/user-attachments/assets/cac3ff94-9f20-4be0-ac74-713cfcc7bdb8" />






Results:


Revenue Over Time

Revenue remained relatively stable throughout most of the year, ranging between approximately $135K and $150K per month. Sales strengthened in the fourth quarter, with revenue increasing in November ($164.6K) and reaching its highest level in December ($169.3K), indicating a strong year-end sales surge
<img width="1618" height="340" alt="revenue over time" src="https://github.com/user-attachments/assets/53af764d-19de-40c1-864a-fb583907c3e5" />


Top Product Categories by Revenue

Hermanos generated the highest product-brand revenue at $57K, followed by Tell Tale at $51K and Ebony at $50K. Overall, revenue was distributed fairly evenly across the top brands, with only a $17K difference between the highest- and lowest-performing brands.


<img width="754" height="435" alt="revenue by product category" src="https://github.com/user-attachments/assets/d8d13065-9357-42c9-9fd9-3f38660373e3" />




Top Products by Revenue

Hermanos Green Pepper generated the highest product revenue at $2,490, followed closely by Hilltop Mint Mouthwash ($2,447) and Carlson Head Cheese ($2,418). Revenue among the top-performing products was highly consistent, with less than $200 separating the top 10 products, indicating a balanced contribution across the leading products.
<img width="1572" height="452" alt="top 10 product revenue" src="https://github.com/user-attachments/assets/7a121781-9399-4942-bd45-302db80efdbb" />





