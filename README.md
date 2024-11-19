# Project Background
Northwind Traders is a global import and export company specializing in supplying high-quality gourmet food products to restaurants, cafes, and specialty food retailers. The company has been operating since the 1990s with a business model focused on B2B sales, leveraging a network of trusted suppliers and logistics providers.

This project focuses on developing a Power BI dashboard to provide the executive team with a clear view of the company's **current-year (CY) performance** in the following key areas:

- **Sales Trends:** Tracking year-over-year (YoY) changes and monthly performance.
- **Product Performance:** Identifying the top-performing and most costly products.
- **Key Customers:** Highlighting customers driving the most revenue and costs.
- **Shipping Costs:** Analyzing trends and variations in freight costs.

An interactive Power BI dashboard used to report and explore sales trends can be found here [link].



# Data Structure & Initial Checks

The Northwind database contains five key tables used in this analysis:
- **Customers:** Information about clients, including regions and contact details.
- **Orders:** Sales transactions with dates, quantities, and freight costs.
- **Products:** Product catalog, including names, prices, and categories.
- **Employees:** Detials of sales representatives and managers.
- **Shippers:** Shipping provider details and associated costs.

The relationship between these tables are shown below:

[Entity Relationship Diagram here]



# Executive Summary

### Overview of Findings

Northwind Traders' performance in **2015** showed the following key trends:
- **Sales & Freight Costs:** Sales grew by **12% YoY,** with total revenue reaching $1.2M, while freight costs remained stable.
- **Customer Segmentation:** Top 10 customers accounted for **45% of total sales,** highlighting a concentrated revenue base.
- **Product Insights:** The most-ordered product contributed **20% of sales,** but costly items like gourmet oils showed high shipping costs impacting margins.

These insights help drive decisions for marketing analysts optimizing customer engagement and finance analysts monitoring cost efficiency.

![remote_work_report]



# Insights Deep Dive
### Sales Trends

* **YoY Performance:** Sales in 2015 grew by **12% YoY** compared to 2014.
  
* **Monthly Trends** Sales peaked in **November** with a **15% increase** over the monthly average.
  
* **Daily Trends:** Daily sales trends show strong performance mid-week but a significant drop during weekends.
  

[Monthly and Daily Sales Visualizations here]


### Product Performance

* **Best Products:** The top product, **Chai Tea**, generated **$250K** in sales in 2015.
  
* **Costly Products:** Gourmet oils has the highest freight-to-sale ratio, with **freight costs averaging 20% of total revenue** for these items.
  
[Product Sales Visualizations here]


### Key Customers

* **Revenue Concentration:** The top 10 customers contributed nearly half of the annual revenue.
  
* **High Cost Customers:** A few large accounts had disproportionately high freight costs, such as **Save-A-Lot Grocery,** impacting profitability.
  

[Customer Insights Visualizations here]


### Shipping Costs

* **Consistent Providers:** Shipping costs were stable across providers, but **Speedy Express** offered the lowest average cost per order.
  
* **Monthly Variation:** Costs spiked during the holiday season, particularly in December.
  
[Freight Costs Visualization here]



# Recommendations:

Based on the insights above, the following actions are recommended for the executive team:

* **Customer Strategy:** Focus on expanding relationships with high-revenue customers while reviewing freight pricing for less-profitable accounts. **Recommendation or general guidance based on this observation.**
  
* **Product Focus:** Consider promoting high-margin, top-selling items like **Chai Tea** while optimizing shipping methods for costly products. **Recommendation or general guidance based on this observation.**
  
* **Shipping Optimization:** Leverage **Speedy Express** for bulk orders to reduce costs further during peak seasons. **Recommendation or general guidance based on this observation.**

* **Sales Campaigns:** Schedule promotional campaigns during slower months (e.g., January and March) to balance monthly revenue. **Recommendation or general guidance based on this observation.**
  
  


# Assumptions and Caveats:

This analysis is based on the following assumptions:

* **Data Scope:** Only current-year (2015) data was used for simplicity and actionable insights.

* **Missing Data:** Some freight cost records were incomplete and replaced with median values for analysis.

* **Exclusions:** Customer returns and refunds were excluded due to inconsistent reporting.

