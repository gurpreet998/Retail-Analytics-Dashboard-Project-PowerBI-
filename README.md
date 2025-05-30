# 🛍️ ShopNest Retail Analytics Dashboard - Power BI Project

A comprehensive Power BI dashboard project designed to analyze sales, customer behavior, delivery performance, product ratings, payment methods, and regional insights using a retail dataset for **ShopNest**.

### Dashboard Link https://drive.google.com/file/d/1DsKtOWheCl0uT3fwDACtsIPO3jGxlmdl/view?usp=sharing](https://drive.google.com/file/d/1N4Ttmpe8FUd2htyZxY7K1zw0b34NC3ZG/view?usp=sharing

---

## 📊 Project Overview

This Power BI project answers key business questions for a retail company using advanced data modeling and visual analytics. It brings together 9 datasets and uncovers actionable insights through interactive dashboards.

---

## 🗂️ Data Sources

This project uses the following datasets:

| Dataset Name              | Description |
|--------------------------|-------------|
| **Customers**            | Customer ID, ZIP code, city, state |
| **GeoLocation**          | ZIP-level geolocation data |
| **Order Items**          | Order ID, product ID, seller ID, shipping date, price, freight |
| **Order Payments**       | Payment type, installments, payment value |
| **Order Reviews**        | Customer reviews and scores |
| **Orders**               | Order timelines, statuses |
| **Products**             | Product attributes (weight, dimensions, etc.) |
| **Sellers**              | Seller location details |
| **Product Categories**   | Product category translations |

---

## 🧠 Insights & Analysis

### 1. 📦 Top Categories by Total Sales
- Identify and visually represent the top 10 product categories by total sales.

Vizualization Used:



![Top Categories Chart](https://github.com/gurpreet998/ShopNest/blob/main/Images/Top%20Categories%20by%20Total%20Price.png)


 




Insights: This visual highlights the top 10 product categories by total sales value on the ShopNest platform. The Total Sales measure was calculated using the sum of product prices from the order items dataset. Categories such as health_beauty, watches_gifts, and bed_bath_table emerged as the top-performing segments. This analysis helps identify high-revenue categories, enabling strategic focus on best-selling product lines for inventory planning, marketing campaigns, and revenue optimization.







---

### 2. ⏱️ Delayed Orders Analysis
Determine the number of delayed orders in each category, an order is considered delayed if the actual delivery date is later than the estimated delivery date

Vizualization Used:
 

![Delayed Orders Chart](https://github.com/gurpreet998/ShopNest/blob/main/Images/Delayed%20Order%20Analysis.png)




Insights: This visual illustrates the number of delayed orders across product categories, where a delivery is considered delayed if the actual delivery date exceeded the estimated delivery date. The column chart shows that bed_bath_table and health_beauty have the highest number of delays, with 770 and 717 orders respectively. This insight helps identify categories with potential logistics or fulfillment challenges, enabling ShopNest to improve delivery accuracy, enhance customer satisfaction, and refine operational efficiency across critical product segments.








---

### 3. 📅 Monthly Comparison of Delayed vs. On-time Orders
i. Create a dynamic visual that compares the number of delayed orders to the number of orders received earlier for each month. Utilize the drill-through cross report feature to provide a detailed analysis of late and on-time analysis. 

Vizualization Used:


![Monthly Comparison Chart](https://github.com/gurpreet998/ShopNest/blob/main/Images/Monthly%20Comparison%20of%20delayed%20and%20on-time%20orders.png
)



 

Insights: This stacked bar chart presents a monthly breakdown of delayed vs. on-time orders across the year. Each bar compares the proportion of orders delivered later than expected versus those delivered on or before the estimated date. February , March and November show the highest delay ratios, indicating potential seasonal or operational challenges. This visual helps ShopNest identify patterns in delivery performance and highlights opportunities to optimize fulfilment. Drill-through features offer deeper insights at the individual order level for root cause analysis.

ii.
## Drill-through Feature

### Visual 


![Drill through Chart](https://github.com/gurpreet998/ShopNest/blob/main/Images/Drill%20Through%20Visual.png
)






Insights: Drill-Through: Daily Analysis of Delayed and On-Time Orders
This drill-through report provides a granular day-wise breakdown of delayed and total orders across months and years. Users can explore specific time periods, for instance August 2017, to assess how delivery performance fluctuated daily. This detailed view empowers ShopNest to pinpoint operational bottlenecks, identify high-delay days, and take corrective actions. By offering interactive drill-down capabilities, it enhances the depth of analysis beyond monthly aggregates and supports more targeted supply chain improvements.

---

### 4. 💳 Payment Method Analysis
Analyze the most frequently used payment methods by customer using a visually appealing representation such as pie chart or other suitable visuals.


Vizualization Used:


![Payment Method Analysis Chart](https://github.com/gurpreet998/ShopNest/blob/main/Images/Payment%20method%20Analysis.png)
 


Insights: This donut chart visualizes the distribution of payment methods used by customers on ShopNest. The analysis reveals that credit cards dominate transactions, accounting for approximately 74% of all payments. This is followed by boleto (19%), a popular Brazilian payment slip method. Vouchers and debit cards form a smaller share, contributing around 5.5% and 1.5%, respectively. Understanding these preferences helps ShopNest align marketing strategies, streamline checkout processes, and enhance customer convenience by focusing on the most utilized and trusted payment options.





---

### 5. ⭐ Product Rating Analysis
Determine the top 10 highest rated product and the bottom 10 lowest rated product using a bar or column chart.

Vizualization Used:  
1.	Top 10 highest rated products:

Visual: 


![product rating top 10 Chart](https://github.com/gurpreet998/ShopNest/blob/main/Images/PRA%20-%20top.png)
 

Insights: The chart displays the top 10 highest-rated products, each receiving a perfect rating of 5.0, indicating maximum customer satisfaction. These consistently top-rated products highlight excellent performance in quality, functionality, and customer service. Their high ratings can serve as benchmarks for other products and are ideal candidates for promotion and upselling strategies. The fact that multiple products have perfect scores suggests effective product listing, good delivery experience, and alignment with customer expectations. Understanding what makes these products successful could help drive improvements in the broader catalog and refine vendor or seller performance benchmarks.


2.  Bottom 10 lowest rated products:

Visual:

![Product rating bottom 10 chart](https://github.com/gurpreet998/ShopNest/blob/main/Images/PRA-Bottom.png)
 

Insights: The bottom 10 lowest-rated products all share a consistent rating of 1.0, indicating significant dissatisfaction among customers. These low scores may result from poor product quality, misleading descriptions, damaged goods, delayed shipping, or lack customer service. This clear underperformance flags them as high-risk items that could harm brand trust and loyalty if not addressed. Immediate investigation and corrective actions—such as reviewing seller practices, issuing refunds, improving logistics, or even removing certain listings—are essential. These insights also provide a roadmap for quality control and process optimization across product categories.

---

### 6. 🗺️ State-wise Sales Analysis
Identify and Visually represent states with high and low sales. Providing a clear understanding of regional sales performance.

Vizualization Used:


![State-wise Sales Chart](https://github.com/gurpreet998/ShopNest/blob/main/Images/StateWise%20Analysis.png)
 

Insights: The map visual depicts state-level sales performance across various global locations, with a concentration in South America—particularly Brazil—indicating higher sales volumes. Each blue bubble represents a state, and the bubble size corresponds to total sales in that region. Denser and larger bubbles signify higher revenue-generating states, allowing easy identification of key markets. This geographic analysis helps pinpoint high-performing areas for reinforcement and low-performing ones for strategic improvement. The visual enables regional sales comparison at a glance, aiding in tailored marketing, logistics, and expansion strategies.

---

### 7. 📈 Seasonal Sales Patterns: 
--- Investigate and visualize any seasonal patterns (quarterly) or trends in sales year over the course of the year.

Vizualization Used: 


![State-wise Sales Chart](https://github.com/gurpreet998/ShopNest/blob/main/Images/Seasonal%20Analysis.png)

 

Insights: The line chart visualizes quarterly sales trends from 2016 to 2018, highlighting seasonal patterns. In 2018, sales peaked in Q2 at 2.86M before dropping to 1.70M in Q3, indicating possible seasonal decline. Conversely, 2017 shows a steady upward trend, rising from 0.74M in Q1 to 2.42M in Q4, suggesting consistent growth throughout the year. Data for 2016 is minimal, showing only a slight increase in Q4. These patterns help identify strong quarters for planning inventory, marketing, and staffing. Recognizing sales fluctuations across quarters is crucial for forecasting and aligning business strategies with seasonal demand.

---

### 8. 💰 Revenue Trend Analysis
Determine the Total revenue generated by ShopNest store and analyze how it changes over time (yearly). Represent this information through suitable visuals to highlight trends and patterns.

Vizualization used: 
 

![Revenue Chart](https://github.com/gurpreet998/ShopNest/blob/main/Images/Revenue%20analysis.png)


Insights: The line chart illustrates the total annual revenue for ShopNest from 2016 to 2018. Starting from nearly zero in 2016, the revenue sharply increases to approximately 7 million in 2017, indicating a major growth phase. The upward trend continues in 2018, reaching over 8 million, although the growth rate is slightly slower than the previous year. This steady increase reflects successful business scaling, customer acquisition, and product performance. The visual highlights key revenue milestones and provides a clear picture of the company’s financial trajectory, which can inform budgeting, forecasting, and strategic planning.







---

## 🧱 Data Modeling

All datasets are integrated using Power BI relationships based on keys like `Order_id`, `Customer_id`, `Product_id`, and `Seller_id`. Optional geolocation relationships are modeled using ZIP codes.

The model follows a star schema with:
- **Fact Tables:** Orders, Order Items, Payments
- **Dimension Tables:** Customers, Products, Categories, Sellers, Reviews

### Tables Joined on
Orders_dataset[Customer_id] → Customers_dataset[Customer_id]
Orders_dataset[Order_id] → Order_items_dataset[Order_id]
Order_items_dataset[Product_id] → Products_dataset[Product_id]
Order_items_dataset[Seller_id] → Sellers_dataset[Seller_id]
Orders_dataset[Order_id] → Order_payments_dataset[Order_id]
Orders_dataset[Order_id] → Order_reviews_dataset[Order_id]
Products_dataset[Product_category_name] → Product_categories_dataset[Product_category_name]
Customers_dataset[Customer_zip_code] → GeoLocation_dataset[Geolocation_zipcode]
Sellers_dataset[Seller_zipcode_prefix] → GeoLocation_dataset[Geolocation_zipcode]

### Conclusion

Conclusion:
The Power BI dashboard designed for ShopNest provides a comprehensive and interactive overview of key business metrics across multiple dimensions—product performance, customer behaviour, operational efficiency, and regional trends. Through visually compelling charts, maps, and drill-through features, the dashboard successfully uncovers actionable insights:
•	The Top Categories and Product Rating analyses help highlight both best-performing and underperforming product segments.
•	Delayed Orders and On-Time Comparisons offer clear visibility into fulfilment efficiency, enabling better logistics and delivery planning.
•	Payment Method Analysis reveals customer preferences, guiding improvements in the checkout experience.
•	State-Wise Sales and Seasonal Sales Patterns visualizations uncover geographical and temporal patterns critical for targeted marketing and inventory optimization.
•	Finally, the Revenue Analysis shows a strong upward trend in yearly earnings, confirming the company’s growth trajectory and providing a solid base for strategic expansion.
Overall, this dashboard acts as a powerful decision-support tool, helping stakeholders make data-driven decisions, monitor performance, and proactively identify opportunities for growth and improvement.

### Dashboard Snapshot 

![Dashboard Snapshot](https://github.com/gurpreet998/ShopNest/blob/main/Images/ShopNest%20Dashboard%20Snapshot.png) 


### About Me

🔍 Data Analyst | PowerBI Enthusiast | Driving Business Insights with Data | Open to New Opportunities

Hi, I’m Gurpreet Singh — a results-driven Data Analyst currently working at Accenture, Gurugram. With a strong foundation in data visualization, statistical analysis, and business intelligence, I help organizations turn raw data into strategic insights that support better decision-making.

Over the past few years, I’ve worked on cross-functional projects involving data wrangling, dashboard creation (using Power BI/Tableau), SQL querying, and predictive analytics. I take pride in not just analyzing numbers but telling the story behind the data — enabling teams to unlock growth opportunities, reduce costs, and improve performance.

At Accenture, I’ve had the privilege of working with diverse global clients, where I’ve honed my ability to translate complex business challenges into actionable data solutions. Whether it’s streamlining reporting workflows or building scalable data models, I bring clarity and value at every step of the analytics journey.

I’m now looking for a new challenge where I can apply my skills in a more dynamic or product-oriented environment, ideally within a forward-thinking company that values data as a key strategic asset.

📩 Let’s connect if you’re hiring Data Analysts or just want to talk data, business, or technology.

### LinkedIn URL : https://www.linkedin.com/in/gurpreetsingh1998

### GitHub URL: https://github.com/gurpreet998/

### Contact email: gs268197@gmail.com

### Mobile No. 7018320090



