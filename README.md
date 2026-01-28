# NORTHWIND SALES PERFORMANCE ANALYSIS
This case study analyzes Northwind’s historical sales data with a professional and interactive Excel dashboard,so as to understand revenue performance, customer value, product profitability, employee contribution, shipping efficiency, and discount behavior. This project includes data cleaning, modeling, KPI design, exploratory analysis, and an interactive Excel dashboard that delivers actionable business insights.

# Table of Contents
- [Dashboard](#dashboard)
- [Abstract](#abstract)
- [Project Overview](#project-overview)
- [Project Objectives](#project-objectives)
- [Business Questions](#business-questions)
- [Data Model Structure](#data-model-structure)
- [Data Preparation Steps](#data-preparation-steps)
- [Exploration Analysis](#exploration-analysis)
- [Key Metrics Table](#key-metrics-table)
- [Excel Functions Used & Purpose](#excel-functions-used--purpose)
- [Dashboard Results](#dashboard-results)
- [Analysis](#analysis)
- [Insights & Recommendations](#insights--recommendations)
  - [Insights](#insights)
  - [Recommendations](#recommendations)
- [Conclusion](#conclusion)

# Dashboard

  <img width="967" height="549" alt="image" src="https://github.com/user-attachments/assets/628322a6-8dcd-4031-ad05-e20bade9ad97" />
  
# Abstract
This case study analyzes Northwind’s historical sales data to understand revenue performance, customer value, product profitability, employee contribution, shipping efficiency, and discount behavior. Using a structured data model and an interactive Excel dashboard, the project uncovers key trends in sales growth, top‑performing products and customers, and operational reliability. The findings highlight strong revenue driven by premium products, high on‑time delivery rates, and concentrated value among a small group of customers and employees. The report concludes with actionable recommendations to strengthen customer relationships, optimize product strategy, and refine operational decisions. Northwind Sales Performance Analysis

# Project Overview
Northwind’s sales operations were analyzed using a fully cleaned and transformed dataset. The goal of this project is to build a dashboard that provides leadership with clear visibility into revenue performance, customer value, product profitability, employee contribution, shipping efficiency, and discount behavior. Northwind Traders is a global specialty foods distributor operating across multiple regions, product categories, and customer segments. As the company continues to scale, leadership requires deeper visibility into sales performance, customer behavior, product profitability, and operational efficiency. This project was initiated to transform raw transactional data into a structured, insight driven analytics solution that supports strategic decision making.

The analysis leverages historical order, product, customer, employee, and shipping data to uncover patterns that influence revenue growth, customer value, and operational reliability. Using Excel as the primary analytical environment, the project includes full data cleaning, transformation, modeling, and the development of an interactive dashboard that summarizes key performance indicators (KPIs). The goal is to provide a unified view of Northwind’s sales ecosystem — enabling stakeholders to quickly identify top performing products, high value customers, employee contributions, shipping performance, and discount trends. By converting raw data into actionable insights, this project equips management with the clarity needed to optimize pricing, inventory planning, customer engagement, and workforce performance. This report documents the entire analytical process, from data preparation to dashboard creation, and presents insights that highlight both strengths and opportunities within Northwind’s sales operations.

# Project Objectives
 •	Understand revenue trends across years and quarters

•	Identify top‑performing products and customers

•	Evaluate employee sales contribution

•	Assess shipping and delivery performance

•	Analyze discount behavior and its impact on sales

•	Provide actionable insights for strategic decision‑making

# Business Questions
•	What is the overall revenue trend

•	Which products generate the highest revenue

•	Who are the most valuable customers

•	Which employees contribute most to sales

•	How efficient are shipping operations

•	What is the product availability rate

•	Do discounts influence customer purchasing behavior

# Data Model Structure
Tables Used from dataset "https://mavenanalytics.io/data-playground/northwind-traders"
Orders, Order Details, Products, Customers, Employees, Shippers, Calendar Table
## Relationships
Orders → Customers

Orders → Employees

Orders → Shippers

Order Details → Products

Calendar → Orders

# Data Preparation Steps
•	Removed duplicates and null values

•	Standardized date formats

•	Normalized product, customer, and employee names

•	Created calculated fields

•	Merged Orders and Order Details into a fact table

•	Validated relationships for dashboard modeling

# Exploration Analysis
•	Sales are concentrated in premium imported products

•	Customer revenue distribution is uneven

•	Employee performance varies significantly

•	Shipping is mostly on time

•	Discounts are inconsistently applied and not always effective

# Key Metrics Table

## Metric	Value	Insight
Total Revenue	$1,265,793	Strong performance driven by premium products

Total Orders	830+	Healthy order volume

Average Order Value (AOV)	(Your value)	Useful for segmentation

On Time Delivery Rate	96.8%	Excellent shipping reliability

Product Availability	85.4%	Low stockout rate

Top Product	Côte de Blaye — $141,396	High margin premium wine

Top Customer	QUICK Stop — $110,277	Key recurring buyer

Top Employee	Margaret Peacock — $232,891	Highest revenue contributor

# Excel Functions Used & Purpose
•	Sales = [Unit Price] * [Quantity] * (1 - [Discount])

•	Total with Freight = [Sales] + [Freight]

•	Days to Ship = [ShippedDate] - [OrderDate]

•	Delivery Status = IF([ShippedDate] <= [RequiredDate], "On Time", IF([ShippedDate] = "", "Pending", "Late"))

•	Year = YEAR([OrderDate])

•	Quarter = "Q" & ROUNDUP(MONTH([OrderDate])/3,0)

•	Year Quarter = [Year] & "-" & [Quarter]

•	Product Availability = IF([UnitsInStock] > 0, "Available", "Not Available")

 # Dashboard Results

<img width="975" height="553" alt="image" src="https://github.com/user-attachments/assets/2f5bec45-f3c0-4a6e-a04b-a30b0718f10b" />

# Analysis
•	Revenue peaked in 2015 Q1 at approximately $298K

•	Premium products dominate revenue

•	QUICK Stop and Ernst Handel are top customers

•	Margaret Peacock leads employee revenue contribution

•	96.8% of orders are delivered on time

•	Discounts do not significantly increase sales volume

# Insights & Recommendations
## Insights
•	Revenue is steadily increasing

•	High value products are premium imports

•	A small group of customers contributes a large share of total revenue

•	Employee performance is uneven

•	Shipping operations are highly reliable

•	Discounting strategy is not strongly linked to higher revenue

# Recommendations
•	Strengthening relationships with top customers

•	Expand premium product lines

•	Support and coach lower performing employees

•	Optimize shipper allocation

•	Refine discount strategy to protect margins

# Conclusion
This Northwind sales analysis demonstrates strong overall performance, driven by premium products and reliable shipping operations. However, value is concentrated among a limited set of customers and employees, and discounts does not significantly influence sales. By focusing on customer retention, product strategy, and operational optimization, Northwind can further improve profitability and long term growth. The accompanying dashboard provides leadership with a dynamic, data driven view of performance to support informed decision making.










   


