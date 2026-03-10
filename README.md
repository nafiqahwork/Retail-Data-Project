## Global E-Commerce Transaction Audit
Maximizing Revenue Yield & Minimizing Operational Risk

---

## Project Overview
This project conducts a strategic audit of global transaction operations using sales data from a UK-based international e-commerce retailer selling gifts and homeware products.

Using Python-based analytics and SQL-style business logic, the project evaluates:
- Market-level operational risk
- Global sales seasonality
- Product portfolio efficiency
- Customer loyalty patterns

The analysis transforms raw transaction data into actionable strategic recommendations to improve profitability, supply chain efficiency, and market expansion decisions. 

--- 

## Problem
E-commerce companies operating globally often struggle with hidden operational inefficiencies across markets, products, and customers.

Key business challenges include:

- Revenue leakage from product returns
- Supply chain strain caused by seasonal demand spikes
- Misallocation of logistics resources toward low-margin products
- Dependence on a small segment of high-value customers

Without structured auditing of transaction data, these issues remain invisible within aggregate sales numbers, leading to inefficient operational decisions and reduced profitability.

--- 

## Methodology

1. Market Risk Audit — Identifying Revenue Leakage
To evaluate the operational health of international markets, a multi-step auditing pipeline was developed.

### Analytical Steps:
    1. Gross Revenue Isolation
    Filtered all positive transactions to establish market potential.

    2. Refund Identification
    Detected negative transaction values to quantify returned goods.

    3. Return Rate Calculation
    Computed refund-to-revenue ratios for each country to detect high-risk markets.

Key Insight
The United States emerged as a major operational outlier, with a 46.9% return rate, compared with core markets like the UK and Germany (<5%). 

This suggests severe revenue leakage and logistical inefficiency.

## Market Return Rate Analysis
<p align="center"><img width="481" height="253" alt="image" src="https://github.com/user-attachments/assets/42e2754d-48a2-4448-802f-624c91e19792" /></p>
<p align="center"> Figure 01: Return Rate by Country — highlighting the USA as a high-risk market. </p>

2. Sales Trend & Market Leader Analysis
To understand the seasonal dynamics of the business, a chronological time-series analysis was conducted.

### Analytical Steps:
    - Converted raw transaction dates into monthly time series
    - Aggregated monthly global revenue
    - Identified top-performing countries per month

Key Insight
The business exhibits extreme Q4 seasonality, with revenue peaking at $7.8M in November. 

Sales accelerate significantly from September to November, suggesting strong year-end wholesale procurement cycles.

--- 

## Global Sales Seasonality
<p align="center"><img width="453" height="283" alt="image" src="https://github.com/user-attachments/assets/3a07fd70-7164-4ded-becd-987a7bc1bd69" /></p>
<p align="center"> Figure 02: Monthly global revenue showing strong Q4 seasonality. </p>


3. Product Portfolio Efficiency Analysis
Rather than analyzing products purely by sales volume, this analysis introduced a Revenue Density metric.

### Analytical Steps: 
    Calculated average revenue per unit
    Compared:
       - High-volume products
       - High-value products

Key Insight
Products like Jumbo Bags sell in high volume but generate only ~$6 per unit.

Meanwhile, products like Regency Cakestand generate $22.14 per unit, nearly 4× higher revenue density. 

This indicates that logistics resources may be misallocated toward low-value items.

 4. Customer Loyalty & Business Model Analysis
Customer behavior analysis was conducted to determine the underlying business model.

### Analytical Steps:
    - Identified repeat customers
    - Calculated retention rate
    - Measured average order size

Key Findings
- 70.07% customer retention rate
- Average order size: 282 items
These signals confirm a B2B wholesale business model, driven by large repeat buyers. 

The analysis identified 839 VIP “Big Buyer” customers responsible for a significant portion of revenue.

---

## Results
1. Revenue Risk Identification
The analysis identified major revenue leakage in the US market, where nearly half of all shipments are returned.

   This represents:
  - Wasted shipping costs
  - Warehouse inefficiencies
  - Significant profit erosion.

2. Operational Seasonality Insights
Sales analysis revealed strong Q4 dependency, creating potential supply chain pressure known as the Bullwhip Effect.

   Strategic recommendation:
  - Conduct warehouse audits during early-year demand slumps
  - Begin peak inventory buildup by July

3. Product Portfolio Optimization
Revenue density analysis revealed high-margin “hidden gem” products that deliver significantly more revenue per shipment.

   Recommendation:
   - Expand high-margin product categories into new markets.

4. Customer Strategy Insight
The business operates as a wholesale ecosystem, heavily dependent on a relatively small group of loyal buyers.

   Strategic recommendation:
   - Implement a VIP loyalty program for the top 800 customers
   - Shift from generic marketing → key account management

---

## Tech Stack

### Python
| Category           | Tools                                    |
| ------------------ | ---------------------------------------- |
| Data Processing    | pandas, numpy                            |
| Data Visualization | seaborn, matplotlib                      |
| Data Analysis      | exploratory data analysis (EDA)          |
| Query Logic        | SQL-style analysis (joins, aggregations) |

---

## Key Skills Demonstrated
- Business Data Analytics
- Revenue Leakage Detection
- Market Risk Analysis
- E-commerce Strategy Analytics
- Supply Chain Insight Generation
- Customer Segmentation
- Data Storytelling for Business Strategy

--- 

##📂 Due to the file size (over 25MB), the raw transaction data is hosted on Google Drive:
## [Download Raw CSV Data Here]((https://drive.google.com/file/d/1wMy3HgYoVd95u7OoZ_vlC2J4FWa-COcN/view?usp=share_link))
---

