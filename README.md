<h1>Tableau Projects - Sales & Customer Dashboard</h1>

<p align="center">
Sales Dashboard: <br/>
<img src="https://i.imgur.com/JhigP5B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Customer Dashboard:  <br/>
<img src="https://i.imgur.com/lGS95Ap.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<h2>PROJECT DESCRIPTION</h2>

<p>This project involves creating two Tableau dashboards: a Sales Dashboard and a Customer Dashboard.</p> 
<p>These dashboards are designed to help stakeholders, including sales managers, executives, and marketing teams, analyze key performance metrics, identify trends, and gain actionable insights to improve business performance. </p>
<p>The Sales Dashboard focuses on year-over-year sales performance, while the Customer Dashboard provides insights into customer behavior and segmentation.</p>
<p>This project aims to analyze sales performance, customer segmentation, and order trends using sales data. The dataset includes information on customers, locations, orders, and products. Insights will be derived to enhance business decision-making and improve operational efficiency.</p>

<h2>METHODOLOGY</h2>

<p>The project follows these key phases:</p>
<p>1. Analyzing user requirements and creating dashboard mockups.</p>
<p>2. Preparing the data source, including data modeling and cleaning.</p>
<p>3. Building calculated fields, visualizations, and dynamic filters in Tableau.</p>
<p>4. Designing the dashboards by organizing content with containers, ensuring a clean, interactive layout.</p>
<p>5. Adding finishing touches, including legends, tooltips, and interactivity.</p>

<h3>Sales Dashboard | Requirements</h3>

<p>Dashboard Purpose: The purpose of sales dashboard is to present an overview of the sales metrics and trends in order to analyze year-over-year sales performance and understand sales trends.

KPI Overview: Display a summary of total sales, profits and quantity for the current year and the previous year.

Sales Trends:
<p>– Present the data for each KPI on a monthly basis for both the current year and the previous year.</p>
<p>– Identify months with highest and lowest sales and make them easy to recognize.</p>

Product Subcategory Comparison:
<p>– Compare sales performance by different product subcategories for the current year and the previous year.</p>
<p>– Include a comparison of sales with profit.</p>

Weekly Trends for Sales & Profit:
<p>– Present weekly sales and profit data for the current year.</p>
<p>– Display the average weekly values.</p>
<p>– Highlight weeks that are above and below the average to draw attention to sales & profit performance.</p>

 <h3>Customer Dashboard | Requirements</h3>

 <p>Dashboard Purpose: The customer dashboard aims to provide an overview of customer data, trends and behaviors. It will help marketing teams and management to understand customer segments and improve customer satisfaction.</p>

KPI Overview: Display a summary of total number of customers, total sales per customer and total number of orders for the current year and the previous year.

Customer Trends:
<p>– Present the data for each KPI on a monthly basis for both the current year and the previous year.</p>
<p>– Identify months with highest and lowest sales and make them easy to recognize.</p>

Customer Distribution by Number of Orders:
<p>- Represent the distribution of customers based on the number of orders they have placed to provide insights into customer behavior, loyalty and engagement.</p>

Top 10 Customers By Profit:
<p>– Present the top 10 customers who have generated the highest profits for the company.</p>
<p>– Show additional information like rank, number of orders, current sales, current profit and the last order date.</p>

 
<h2>DATA PREPROCESSING</h2>
<h3>Data Overview</h3>
<p>The dataset consists of the following components:</p>
<p>- <b>Customers</b>: Information about customer IDs and names.</p>
<p>- <b>Location</b>: Details of postal codes, cities, states, and regions.</p>
<p>- <b>Orders</b>: Comprehensive order details, including order dates, shipping modes, product IDs, customer ID, quantity, and sales figures.</p>
<p>- <b>Products</b>: Categories, sub-categories, product ID, and product names.</p>

<h3>Data Cleaning</h3>
<p>Key cleaning steps:</p>
<p>- Resolved encoding and delimiter issues in the raw data files.</p>
<p>- Standardized date formats and corrected data types (e.g., string to numeric).</p>
<p>- Addressed missing values and removed duplicates to ensure data integrity.</p>

<h3>Feature Creation</h3>
<p>Custom calculated fields were created, including:</p>
<p>- <b>Dynamic Year Selection:</b> Allows users to choose the current year for analysis.</p>
<p>- <b>Sales and Profit Trends:</b> Highlights year-over-year differences and weekly patterns.</p>
<p>- <b>Performance Indicators:</b> Identifies months with the highest and lowest sales, and subcategories with profit/loss trends.</p>

<h2>EXPLORY DATA ANALYSIS</h2>
<h3>Questions for Sales Performance</h3>
<ul>
  <li>What are the total sales, profit, and quantities for the current and previous years?</li>
  <li>Which months had the highest and lowest sales in the current year?</li>
  <li>How do product subcategories compare in terms of sales and profit performance?</li>
  <li>What are the weekly trends for sales and profits?</li>
</ul>

<h3>Questions for Customer Segmentation and Trends</h3>
<ul>
  <li>Which customer segments are most profitable?</li>
  <li>What is the distribution of customers based on order frequency?</li>
  <li>Who are the top 10 customers by profit?</li>
</ul>

<h3>Questions for Orders</h3>
<ul>
  <li>Which product categories have the highest order volumes?</li>
  <li>What are the most common order trends across time?</li>
</ul>

<h2>CONCLUSION</h2>
<h3>Sales Dashboard Insights</h3>
<p><b>1. Sales Performance:</b> The total sales for 2023 reached $733K, showing a 20.4% increase compared to the previous year (PY). Sales trends reveal notable spikes and dips, with clear identification of the highest and lowest performing months.</p>
<p><b>2. Profit Analysis:</b> Total profit for 2023 amounted to $93K, a 12.5% improvement from PY. The weekly trends highlight periods of strong performance above the average profit line and areas for potential improvement.</p>
<p><b>3. Quantity Sold:</b> The total quantity sold in 2023 was 12K, a 26.8% growth compared to PY, indicating an increase in demand.</p>
<p><b>4. Product Subcategories:</b> Chairs, Phones, and Tables are top-performing subcategories, whereas categories like Art and Envelopes incurred losses, providing a roadmap for product strategy adjustments.</p>

<h3>Customer Dashboard Insights</h3>

<p><b>1. Customer Engagement:</b> The total number of customers in 2023 increased by 8.6%, totaling 693. The average sales per customer stood at $1,058, an increase of 10.8% from PY, indicating effective customer retention and revenue maximization strategies.</p>
<p><b>2. Order Growth:</b> Total orders rose significantly by 28.3% to 1,687 in 2023, with a consistent monthly upward trend. Customer distribution data shows loyalty among those placing multiple orders.</p>
<p><b>3. Top Customers:</b> The top 10 customers contributed significantly to the company's profitability, with Raymond Buch generating the highest profit of $6,781. This highlights the importance of targeted customer retention efforts.</p>
<p><b>4. Order Trends:</b> The distribution analysis indicates a majority of customers place 1-2 orders, with fewer making five or more. This provides an opportunity to explore customer loyalty programs to increase order frequency.</p>

<h2>RECOMMENDATION</h2>

<h2>REFERENCE</h2>

 ### [YouTube Data with Baraa - Tableau Complete Project End-to-End | Like I Do in My Real Project](https://www.youtube.com/watch?v=dahrmqT5GD4)
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
Beta
0 / 10
used queries
1
