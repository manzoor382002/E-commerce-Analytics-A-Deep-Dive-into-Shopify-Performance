
#  E-commerce Analytics – A Deep Dive into Shopify Performance

This Power BI project provides a detailed sales and customer funnel analysis for a Shopify-based e-commerce business. Through this interactive dashboard, we explored sales trends, customer behavior, product performance, and regional sales insights.
---
##  Tools & Technologies Used

- **Power BI Desktop**  
- **DAX (Data Analysis Expressions)**  
- **Excel/CSV Data Sources**  
- **Data Modeling (Star Schema)**  
- **Custom Visualizations and Filters**
  
![img1](Dashboard%20Images/Screenshot%202025-06-30%20184741.png)
---

## Analyzed Shopify’s transactional and customer data 

- **Customer Retention** – Repeat customers vs single-time buyers  
- **Net Sales & Revenue Trends** – Time-based sales analysis and AOV  
- **Regional Sales Distribution** – Top-performing cities and states  
- **Product Category Performance** – Which products drive the most revenue?  
- **Payment Gateway Preferences** – Shopify Payments, PayPal, Amazon, etc.  

---

## Insights Uncovered 
- **Analyzed $4.18M in net sales across 7,534 orders to identify high-performing product categories and purchasing 
 trends.**

- **Identified top-selling items like Tennis Shoes ($1.5M), helping the company prioritize inventory, bundle offers, and focus 
 marketing on high-revenue products.**

- **Found that Shopify Payments contributed 58.45% of total revenue, guiding the company to streamline and promote 
 preferred, higher-performing payment options.**

- **Lifetime value of $943.6 per customer enabled the business to estimate customer acquisition costs and set optimal ad 
 spend thresholds**

- **Visualized sales distribution across 20+ U.S. cities, uncovering top regions like Houston and New York City for targeted 
 marketing.**

- **Built dynamic visualizations such as maps, trend lines, and KPI selectors to enable real-time data exploration by 
 stakeholders.**
 
- **Using drill-through pages, decision-makers could explore individual customer journeys, helping identify churn patterns or 
 upsell opportunities**


![img2](Dashboard%20Images/Screenshot%202025-06-30%20184816.png)


![img3](Dashboard%20Images/Screenshot%202025-06-30%20190453.png)


![img4](Dashboard%20Images/Screenshot%202025-06-30%20185911.png)

---



##  DAX Measures Used

Some of the key DAX formulas used in this project include:

- **Net Sales**
  `Net Sales = SUM('Sales Data'[Net Amount])`
-**Average Order Value (AOV)**
  `AOV = [Net Sales] / [Total Orders]`
-**Customer Repeat Rate**
  `Repeat Rate = DIVIDE([Repeat Customers], [Total Customers])`
  -**Purchase Frequency**
  `Purchase Frequency = [Total Orders] / [Total Customers]`
  -**Customer Lifetime Value (CLV)**
  `CLV = [AOV] * [Purchase Frequency]`
---
## Recommendations
- **Implement Loyalty Programs to increase repeat customer rates beyond 50%.

- **Target Top Cities like New York, Los Angeles, and Dallas with local promotions.

- ** Stock Best-selling Categories such as Tennis & Running Shoes more aggressively.

- ** Optimize Checkout Experience on preferred payment gateways for higher conversions.

- **Segment Repeat vs One-time Buyers for personalized marketing campaigns

