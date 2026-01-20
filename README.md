  <img width="50" height="50" alt="image" src="https://github.com/user-attachments/assets/2b4bad5b-5e5b-4578-b822-5808535036c3" />
**Sales Performance & Customer Insight Analysis**
_An Interactive Excel Dashboard for Business Decision Support_

  **Project Overview**
This project focuses on transforming transactional sales data into clear, actionable insights through interactive Excel dashboards. The analysis was designed to support management in understanding how revenue is generated, who the most valuable customers are, and which products and regions drive performance.
By integrating sales, product, customer, and date data into a single analytical model, the project delivers a structured view of business performance that enables faster and more informed decision-making.

 ** Tools & Technologies**
•	Microsoft Excel
•	Pivot Tables and Pivot Charts
•	Power Pivot Data Model
•	DAX Measures
•	Time Intelligence (YoY & MoM Analysis)
•	Customer Segmentation
•	Executive Dashboard Design Principles

  **Dataset Description**
The dataset consists of four connected tables:
Sales Table: Order-level data including revenue, quantity sold, and transaction dates
Product Table: Product identifiers, names, and categories
Customer Table: Customer demographics such as region, gender, and age
Date Table: A custom calendar table created to enable accurate time-based analysis

The structure of the dataset supports both descriptive and comparative analytics across time, products, customers, and regions.

  Business Problem
Despite having detailed sales and customer data, the business lacks a unified reporting system to effectively monitor performance and identify trends. Key questions around growth, customer loyalty, product contribution, and regional effectiveness cannot be answered efficiently using raw data alone.
This project addresses that challenge by building interactive dashboards that convert data into insight and insight into action.

  Analysis Objectives
•	Track overall revenue, order volume, and sales trends
•	Identify key product and category revenue drivers
•	Understand customer purchasing behavior and loyalty patterns
•	Detect customer churn risk and lost customers
•	Compare regional performance and demand patterns
•	Enable strategic and operational decision-making

  Key Business Questions Explored
•	How has revenue evolved over time?
•	Which products and categories contribute the most to sales?
•	Are some regions consistently outperforming others?
•	Who are the highest-value customers?
•	Do demographic factors influence purchasing behavior?
•	Which products show weak performance despite high volume?
•	Are all product categories growing year-over-year?


  Data Model Design
A star-style data model was created using Power Pivot:
•	Sales table linked to the Date table via Order Date
•	Sales table linked to the Customer table via CustomerID
•	Sales table linked to the Product table via ProductID
This model ensures accurate filtering, aggregation, and time-based calculations across all dashboards.

  Data Preparation
The data required minimal transformation before analysis. Validation checks confirmed:
•	No duplicate records or missing values
•	Correct data types applied across all columns
•	Consistent relationships between tables
•	A dedicated Date table was created to support time intelligence
•	Calculated measures were added to enhance analytical depth
The dataset was therefore ready for analysis with minimal preprocessing.

  Dashboard 1 – Sales Overview

  Purpose
To provide a high-level snapshot of overall business performance.
Key Metrics
Total Revenue: $14.54M
Total Orders: 5000
Total Quantity Sold: 28,651
Average Order Value: $2,907

Key Findings
Revenue growth is stronger than order growth, indicating higher value per transaction rather than volume-led growth.
Sales performance varies across months, suggesting seasonal demand patterns.
Revenue contribution is concentrated in a few key categories and regions.

  Dashboard 2 – Customer Behavior & RFM Analysis
  Purpose
To evaluate customer value, loyalty, and churn risk.
Key Metrics
Total Customers:300
Revenue per Customer:$48.46K

Key Findings
A relatively small group of customers contributes a significant portion of revenue.
Customer spending varies by age group and gender, highlighting opportunities for targeted engagement.

  Dashboard 3 – Product & Regional Performance

  Purpose
To assess product effectiveness and regional demand patterns.

Key Metrics
•	Number of Unique Products:50
•	Average Revenue per Product:$290,732

Key Findings
High unit sales do not always translate to high revenue, pointing to pricing inefficiencies in some categories.
A small number of products dominate revenue, while several products consistently underperform.
Regional performance is uneven, with some regions delivering strong revenue efficiency and others lagging behind.

  Key Business Insights

•	Revenue growth is driven more by value per order than by order volume.
•	Customer retention represents a major opportunity for revenue protection and growth.
•	Product performance varies significantly, making portfolio optimization critical.
•	Regional strategies should be tailored rather than uniform.
•	Seasonality plays an important role in sales performance.

  Business Recommendations
•	Strengthen retention strategies for high-value and at-risk customers.
•	Optimize pricing and bundling for high-volume, low-revenue products.
•	Prioritize investment in high-performing products and categories.
•	Apply region-specific pricing and promotional strategies.
•	Align marketing and inventory planning with seasonal trends.

  Limitations
The absence of product cost data limits the analysis to revenue-based insights. Profitability and margin analysis could not be performed.

  Conclusion
This project demonstrates how Excel, when used effectively, can deliver powerful business intelligence. By combining a strong data model with interactive dashboards and targeted KPIs, the analysis provides clear visibility into performance drivers, customer behavior, and product effectiveness, enabling better strategic and operational decisions.


