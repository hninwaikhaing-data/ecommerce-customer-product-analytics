# Customer & Product Performance Analytics Dashboard \| E-commerce

## Project Overview

This project is an end-to-end **Power BI e-commerce analytics solution**
designed to evaluate customer behavior, sales performance, product
profitability, and business growth trends. The goal is to transform
transactional data into clear, decision-oriented insights that help
management understand revenue drivers, high-value customer segments,
product performance, profitability risks, and regional growth
opportunities.

The solution contains two main analytical dashboards:

1.  **Customer Segmentation & Performance Analytics** --- evaluates
    customer contribution, segment profitability, sales trends, top
    customers, and geographic performance.
2.  **Product Performance, Profitability & Trend Analysis** ---
    evaluates category and sub-category performance, top-selling
    products, profit margins, YoY growth, and loss-making products.

## Business Problem

E-commerce management needs a consolidated analytical view of customer
and product performance. Without an integrated dashboard, it is
difficult to determine which customers and products drive revenue, where
profitability is under pressure, which products consistently generate
losses, and how performance changes across customer segments, regions,
and time periods.

This project addresses those challenges by providing an interactive
Power BI solution for monitoring performance and supporting customer,
pricing, product-mix, and regional growth decisions.

## Project Objectives

-   Analyze overall sales and profitability performance.
-   Evaluate customer segments and identify high-value customer groups.
-   Identify top customers and geographic sales patterns.
-   Analyze product, category, and sub-category performance.
-   Monitor monthly sales and profit trends and YoY sales growth.
-   Detect loss-making products and potential profitability risks.
-   Translate analytical findings into actionable business
    recommendations.

## Business Questions

-   How are sales and profit performing over time?
-   Which customer segments contribute most to sales and profitability?
-   Who are the highest-performing customers?
-   How does customer performance vary geographically?
-   Which categories, sub-categories, and products drive sales?
-   Which products consistently generate losses?
-   Is profit growth keeping pace with sales growth?
-   Where are the main opportunities for customer, product, and regional
    optimization?

## Key KPIs

### Customer Performance

-   Total Customers
-   Total Orders
-   Total Sales
-   Total Profit
-   Profit Margin %

### Product Performance

-   Total Products
-   Total Sales
-   Total Profit
-   Profit Margin %
-   Sales YoY Growth %

## Dashboard Pages

### 1. Customer Segmentation & Performance Analytics

This page provides a customer-focused view of business performance
through:

-   Main customer and financial KPI cards
-   Top 5 best-selling customers
-   Monthly sales and profit trend
-   Profitability comparison by customer segment
-   Customer distribution/performance by region
-   Geographic customer sales analysis
-   Interactive Segment, Month, and Year filters

### 2. Product Performance, Profitability & Trend Analysis

This page focuses on product-level commercial performance through:

-   Product, sales, profit, margin, and YoY growth KPIs
-   Sales and profit by category
-   Product/order distribution by customer segment
-   Top 5 products by sales
-   Sales by sub-category
-   Loss-making product analysis
-   Interactive Category and Year filters

## Data Preparation & Modeling

The project uses **Power Query** for data preparation and transformation
and a structured analytical data model in Power BI. Reusable **DAX
measures** are used to calculate business KPIs and support interactive
filtering and time-based analysis.

Core analytical dimensions include customer segments, products,
categories, sub-categories, geography, and time.

## Key Insights

-   Sales demonstrate a positive upward trend, while profit grows more
    slowly, indicating potential margin pressure.
-   Sales contribution is concentrated among a relatively small group of
    customers.
-   Consumer customers generate the highest sales volume, while
    Corporate and Home Office segments show strong profit efficiency.
-   Technology is a major contributor to product sales performance.
-   Several individual products generate negative profit and require
    further investigation.
-   Customer and sales performance varies across geographic markets,
    highlighting opportunities for more targeted regional strategies.

## Business Recommendations

-   **Profitability:** Review pricing, discounts, product costs, and
    category margins to address margin pressure and support sustainable
    profit growth.
-   **Customer Strategy:** Focus on retaining and expanding high-value
    customer segments through targeted engagement and loyalty
    strategies.
-   **Product Optimization:** Evaluate loss-making products for
    repricing, cost optimization, bundling, or removal where
    appropriate.
-   **Product Mix:** Prioritize high-performing categories while
    improving the pricing and efficiency of underperforming products.
-   **Regional Growth:** Strengthen high-performing markets and
    investigate growth opportunities in weaker regions through targeted
    strategies.

## Tools & Technologies

  -----------------------------------------------------------------------
  Tool / Skill                        Purpose
  ----------------------------------- -----------------------------------
  Power BI                            Dashboard development and
                                      interactive business analysis

  Power Query                         Data cleaning and transformation

  DAX                                 KPI calculations and analytical
                                      measures

  Data Modeling                       Building relationships and an
                                      analytical reporting model

  Business Intelligence               Converting data into insights and
                                      recommendations
  -----------------------------------------------------------------------

## Repository Structure

``` text
customer-product-performance-analytics/
├── data/
│   └── README.md                 # Dataset notes or source information
├── powerbi/
│   └── Customer_Product_Performance_Analytics.pbix
├── image/
├── ├── project_information.png
│   ├── customer_segmentation_analysis.png
│   ├── product_performance_analysis.png
│   ├── insight.png
│   └── recommendations.png
└── README.md
```

## Skills Demonstrated

-   Business problem framing
-   Data preparation and transformation
-   Power BI data modeling
-   DAX measure development
-   KPI design
-   Customer segmentation analysis
-   Product and profitability analysis
-   Time-series and YoY analysis
-   Geographic analysis
-   Dashboard design and visual storytelling
-   Business insight generation
-   Actionable recommendation development

## Business Value

This project demonstrates how an e-commerce business can use Power BI to
move from raw transactional data to a consolidated view of customer and
product performance. The dashboards support management decisions related
to customer targeting, profitability improvement, product portfolio
optimization, performance monitoring, and regional growth planning.

## Dashboard Preview

Add your exported dashboard screenshots to the `images/` folder and
update the paths below if necessary.

``` markdown
![Customer Segmentation & Performance Analytics](image/customer_segmentation_analysis.png)

![Product Performance, Profitability & Trend Analysis](image/product_performance_analysis.png)
```

## Author

**Hnin Wai Khaing**\
Data Analyst \| Analytics Engineer

------------------------------------------------------------------------

If you find this project useful, feel free to explore the repository and
review the dashboard documentation.
