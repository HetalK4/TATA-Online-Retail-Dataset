# DSA3050A – Advanced Power BI Examination Project

## Student Information
- Name: Hetal Kumbharana
- Admission Number: 670207
- Course Code: DSA 3050A

## Project Title
Advanced Sales Performance Analysis for an Online Retail Business

## Project Overview
This project presents a comprehensive Business Intelligence (BI) solution developed using Microsoft Power BI to analyze online retail sales performance. The solution covers the entire BI workflow — from raw data acquisition and transformation to analytical modeling, dashboard design, and business insight generation.
The dashboard is designed to support data‑driven decision‑making by providing interactive insights into revenue trends, product performance, customer behavior, geographic sales distribution, and operational efficiency.

## Business Problem
**Scenario**

I have been engaged as a Business Intelligence Analyst to design an advanced Power BI solution for an online retail company (TATA) operating across multiple countries. The company sells a wide variety of consumer products and records transaction-level sales data. Senior management wants a data‑driven analytical dashboard to understand performance, identify trends and risks, and uncover growth opportunities.
**Problem Statement**

Despite having large volumes of transactional sales data, management lacks an analytical view of sales performance across products, customers, time periods, and countries. Senior management is unable to easily identify sales trends, top‑performing products, high‑value customers, or regions contributing most to revenue, which limits strategic planning and performance monitoring.

## Dataset Description
The dataset I used is the TATA Online Retail Dataset obtained from Kaggle. It contains over 9,000 transaction-level data including invoice details, products sold, quantities, unit prices, customer identifiers, transaction dates, and countries.

## Tools Used
- Power BI Desktop
- Power Query (for data transformation)
- DAX (Data Analysis Expressions)
- GitHub (for project versioning and documentation)

## Methodology 
1. Data acquisition and understanding

2. Data cleaning and transformation using Power Query
    - Correcting data types
    - Handling missing customer identifiers
    - Identifying cancelled transactions
    - Removing invalid records (zero/negative prices)
    - Creating derived columns such as Revenue
    - Extracting date components for time analysis

3. Star schema data modeling with fact and dimension tables
    - A star schema data model was implemented consisting of:
        - Fact Table: Sales transactions
        - Dimension Tables:
            - Customer
            - Product
            - Country
            - Date
    Relationships were configured with correct cardinality and single‑direction filtering to optimize performance and ensure consistent analytical behavior. A dedicated Date table was created to enable time‑intelligence calculations.

4. Creation of calculated columns and advanced DAX measures, such as:
    - Total Revenue
    - Total Quantity
    - Total Transactions
    - Average Order Value
    - Distinct Customers
    - Revenue % Contribution by Product
    - Year‑to‑Date Revenue
    - Previous Year Revenue
    - Year‑on‑Year Growth %
    Additionally, calculated columns were created to classify transaction types and compute row‑level sales values.
5. Dashboard design and visualization across three report pages
6. Analysis of insights and formulation of business recommendations

## Dashboard Pages
- Executive Summary
    - KPI cards for overall performance
    - Revenue trend over time
    - Revenue by country
    - Interactive slicers for filtering
- Detailed Analysis
    - Top products by revenue
    - Matrix analysis by product and month name
    - Decomposition tree for root‑cause analysis
    - Drill‑down enabled visuals
- Insights & Performance Monitoring
    - Time‑intelligence comparison (current vs previous year)
    - Top and bottom products by revenue
    - Sales vs cancellations analysis
   
## Key DAX Measures
- Total Revenue
- Total Quantity
- Total Transactions
- Distinct Customers
- Average Order Value
- Revenue % Contribution by Product
- Year‑to‑Date Revenue
- Previous Year Revenue
- Year-over-Year Growth %

## Key Insights
- Revenue is highly concentrated among a small number of products
- Sales performance shows fluctuating trends with observable volatility
- The UK dominates revenue contribution
- Returns represent a non-negligible portion of transactions

## Business Recommendations
- Diversify product promotion to reduce revenue concentration risk
- Align inventory and promotions with seasonal trends
- Investigate and reduce high-return products
- Expand focus on international markets

## Challenges Encountered
- Handling cancelled invoices and negative quantities
- Managing missing customer identifiers
- Designing a clean and exam-compliant star schema

## Conclusion
The Power BI solution demonstrates advanced analytical capability by converting raw retail data into actionable insights through proper data modeling, DAX calculations, and interactive dashboards.

## Repository Structure
See folders for data, Power BI files, screenshots, and final report.