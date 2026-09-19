📌 About the Project

E-Commerce Sales Analytics is an end-to-end Power BI Business
Intelligence project developed to analyze e-commerce sales, customers,
products, orders, payments, customer value, and retention-related
patterns.

The project transforms raw transactional datasets into an interactive
dashboard that provides a management-friendly view of business
performance through KPIs, monthly analysis, customer analysis, product
and category analysis, order and payment analysis, and customer value
analysis.

The project demonstrates the complete analytics workflow:

Raw Data → Data Preparation → Data Modeling → DAX → Dashboard
Development → Business Analysis → Insights & Recommendations

🎯 Business Objective

The objective of this project is to create a centralized analytical
solution that helps understand:

💰 Revenue performance

🛒 Order activity

👥 Customer behavior

📦 Product and category performance

💳 Order and payment patterns

💎 Average Order Value (AOV)

🔄 Customer value and retention-related patterns

📅 Monthly business performance


🗂️ Dataset

The Power BI data model uses the following tables:

Table           Description

customers     Customer information and customer attributes
orders        Order-level transaction information
order_items   Individual items associated with orders
products      Product and category information
DateTable     Date and month-based analysis

The datasets were prepared and modeled in Power BI before developing the
analytical dashboard.

🔄 Project Workflow

Raw Data
   ↓
Data Preparation
   ↓
Data Modeling
   ↓
DAX Measures
   ↓
Interactive Visualizations
   ↓
Business Analysis
   ↓
Insights & Recommendations
   ↓
Final Dashboard

1. Data Preparation

Prepared the available e-commerce datasets and ensured that the required
fields were suitable for analysis and reporting.

2. Data Modeling

Created a Power BI data model using customer, order, order-item,
product, and date information.

3. DAX Development

Created analytical measures for important business KPIs, including:

Total Revenue

Total Orders

Total Quantity Sold

Average Order Value (AOV)

4. Dashboard Development

Developed a six-page Power BI report with KPI cards, charts, tables,
monthly analysis, customer analysis, product/category analysis,
order/payment analysis, and interactive filtering.

5. Business Analysis

Analyzed the available data from sales, customer, product, order,
payment, customer value, and retention perspectives.

6. Insights & Recommendations

Converted observable dashboard patterns into business-focused insights
and recommendations.

📊 Dashboard Pages

1. 🏠 Executive Summary

Provides a high-level overview of overall e-commerce performance.

Includes:

Total Revenue

Total Orders

AOV

Monthly analysis

Customer-type analysis

High-level performance indicators

Purpose: Provide decision-makers with a quick overview of business
performance.

2. 📈 Sales Performance

Focuses on sales and revenue trends.

Analysis includes:

Revenue trends

Order trends

Time-based performance

Sales patterns

Changes in business activity

Purpose: Understand how sales performance changes over time.

3. 👥 Customer Analytics

Focuses on customer behavior and contribution.

Analysis includes:

Customer activity

Customer types

Customer contribution

Customer-level patterns

Customer-related performance indicators

Purpose: Understand customer behavior and identify meaningful
customer patterns.

4. 📦 Product & Category

Analyzes product and category performance.

Analysis includes:

Product performance

Category performance

Sales contribution

Quantity-related trends

Product-level patterns

Purpose: Understand how products and categories contribute to
business performance.

5. 🧾 Orders & Payment

Focuses on order and payment-related analysis.

Analysis includes:

Order activity

Payment behavior

Transaction patterns

Order-related metrics

Payment-related patterns

Purpose: Provide visibility into transaction and payment activity.

6. 💎 Customer Value & Retention

Focuses on customer value and retention-related patterns.

Analysis includes:

AOV

Customer type

Customer value patterns

Order behavior

Retention-related observations

Purpose: Understand customer value and identify patterns that can
support customer engagement and retention strategies.

📌 Key Performance Indicators

The dashboard tracks the following major KPIs:

KPI                                          Value Meaning

💰 Total Revenue                       116.15M Overall revenue
represented in the
analyzed data

🛒 Total Orders                            500 Number of orders
represented in the
dataset

Monthly Example

The dashboard supports month-level interactive analysis. For example:

Month            AOV   Total Orders

January      239.80K             35
February     194.14K             42
March        206.00K             43

Selecting a month interactively updates connected visuals and KPI values
through Power BI filtering and cross-filtering.

💡 Business Insights

💰 Sales Performance

The analyzed dataset contains 500 orders and approximately
116.15M in total revenue.

The overall AOV is approximately 232.31K per order.

Monthly analysis shows variation in both order volume and AOV.

January shows an AOV of approximately 239.80K, while February
and March show approximately 194.14K and 206.00K
respectively.

The difference between monthly order volume and AOV demonstrates why
both metrics should be considered when evaluating sales performance.

Recommendations

Monitor revenue, order volume, and AOV together.

Investigate months with lower AOV to understand changes in
purchasing behavior or product mix.

Study higher-value order patterns to identify opportunities for
increasing order value.

👥 Customer Insights

Insights

Customer analysis shows differences in contribution across customer
types.

Customer-level and customer-type views provide visibility into
purchasing behavior.

Customer value patterns can be used to understand differences
between customer groups.

Recommendations

Segment customers according to purchasing behavior and value.

Develop targeted engagement strategies for different customer
segments.

Monitor customer contribution over time to identify changes in
engagement.

📦 Product & Category Insights

Insights

Product and category analysis provides visibility into sales and
quantity contribution.

Comparing revenue with quantity can reveal differences in product
purchasing patterns.

Category-level analysis provides a broader view of product
performance.

Recommendations

Regularly monitor high-contributing products and categories.

Investigate products with high quantity but comparatively lower
revenue.

Use product and category performance to support inventory and
promotional decisions.

Review weaker-performing categories to identify improvement
opportunities.

🧾 Orders & Payment Insights

Insights

Order-level analysis provides visibility into transaction activity.

Payment analysis adds another perspective for understanding
transaction behavior.

Changes in order and payment patterns can be explored through the
dashboard.

Recommendations

Monitor order and payment activity regularly.

Investigate unusual changes in transaction patterns.

Combine payment information with customer and order data for deeper
analysis.

💎 Customer Value & Retention Insights

Insights

AOV provides an indicator of the value generated by individual
orders.

Customer type and order behavior can be used to understand
differences in customer value.

The dashboard provides a foundation for examining retention-related
patterns.

Recommendations

Monitor AOV and order behavior as indicators of customer value.

Identify valuable customer segments for targeted engagement.

Use relevant offers and product recommendations to encourage repeat
purchases.

Track customer behavior over time to identify changes in engagement.

🧮 Power BI & DAX Skills Demonstrated

This project demonstrates practical experience with:

Microsoft Power BI Desktop

Power Query

DAX measures

Data transformation

Data modeling

Table relationships

Filter context

KPI calculations

Date-based analysis

Interactive filtering

Cross-filtering

Data visualization

Dashboard design

Business analysis

Business storytelling

📊 Visualization Features

The report uses:

KPI Cards

Charts

Tables

Monthly analysis

Customer analysis

Product and category analysis

Order and payment analysis

Interactive filters

Cross-filtering

Consistent visual design

The dashboard was designed to make analytical information easier to
explore and interpret.

🛠️ Tools & Technologies

Technology               Usage

Microsoft Power BI   Dashboard development and visualization
DAX                  KPI and analytical calculations
Power Query          Data preparation and transformation
Data Modeling        Relationships and analytical model
CSV / Excel          Source data where applicable
GitHub               Project portfolio and version control

📁 Repository Structure

The repository contains the project data and Power BI report used for
the analysis.

E-Commerce-Sales-Customer-Product-Analytics/
│
├── 📂 01_Raw_data/
│   ├── customers.csv
│   ├── orders.csv
│   ├── order_items.csv
│   └── products.csv
│
├── 📂 02_PowerBI/
│   └── E-Commerce_Sales_Customer_Product_Analytics.pbix
│
└── 📄 README.md

🎓 Project Context

This project was completed as part of the Power BI Project associated
with Innomatics Research Labs.

The project provided practical experience in applying Power BI concepts
to a real-world style business analytics problem, including data
preparation, modeling, DAX, dashboard development, business analysis,
and presentation.

📌 Conclusion

The E-Commerce Sales Analytics project demonstrates an end-to-end
Business Intelligence workflow, from raw transactional data to an
interactive Power BI dashboard.

By combining data preparation, data modeling, DAX, visualization,
business analysis, and storytelling, the project provides a structured
approach to exploring e-commerce performance and generating actionable
business insights.

Note: The insights and recommendations in this README are based on
the available project dataset and dashboard. Additional business
decisions would require information such as profit margins, marketing
spend, customer acquisition cost, inventory, returns, and other
operational metrics.

👩‍💻 Author

Madishetti Rakshitha

CSE (AI & ML) Student | Data Analytics & Power BI Enthusiast | Data
Science

Skills Highlighted

Power BI · DAX · Power Query · Data Modeling ·
Data Visualization · Business Analysis

Connect With Me

💻 GitHub: https://github.com/Rakshitha152003

🔗 LinkedIn: https://www.linkedin.com/in/madishetti-rakshitha/

⭐ If you find this project useful, feel free to explore the
repository and connect with me on LinkedIn.
