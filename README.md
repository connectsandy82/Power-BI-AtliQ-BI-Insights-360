# Power-BI-AtliQ-BI-Insights-360
## Project Overview

AtliQ Hardware's recent rapid growth has prompted the implementation of data analytics using PowerBI for the first time. The aim is to surpass competitors by making data-driven decisions across all business aspects including finance, sales, marketing, and supply chain.

For this project, I followed the Codebasics Data Analytics Bootcamp 2.0: With Practical Job Assistance + AI Module  Course, accessible [Link](https://codebasics.io/bootcamps/data-analytics-bootcamp-with-practical-job-assistance?utm_campaign=dataanalyticsbootcamp&utm_id=googleadspaid&gad_source=1&gclid=CjwKCAjw9IayBhBJEiwAVuc3fgtq_Cm_GRVOiyzpRh4xKimc9dQiye3hnbnonsFc2oWCrlByqYwO2BoClwIQAvD_BwE).

[Power BI Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiNzNkOTM0OWEtMTE1Zi00ZWMyLWEwZjUtYWE5ZDFhZmQ1NTI4IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=ReportSection72e5494850265a4b8576)

## Technology Stack

- SQL
- PowerBI Desktop
- Excel
- DAX language
- DAX studio (for report optimization)
- Project charter file

## PowerBI Techniques Learned

- Pre-project questioning for clarity
- Calculated column creation
- DAX measures creation
- Data modeling
- Bookmark usage for visual switching
- Button-enabled page navigation
- Zero division error prevention using the divide function
- Date table creation with M language
- Dynamic titles reflecting applied filters
- KPI indicator utilization
- Visual value conditional formatting with icons or background color
- Data validation methods
- PowerBI services integration
- Report publishing to PowerBI services
- Personal gateway setup for data auto-refresh
- PowerBI App development
- Collaboration, workspace management, and access permissions in PowerBI services

## Business Terminology

- Gross price
- Pre-invoice deductions
- Post-invoice deductions
- Net invoice sale
- Gross Margin
- Net sales
- Net profit
- COGC - Cost of Goods Sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer

## Company Background

AtliQ Hardware has experienced substantial recent growth, expanding globally. They specialize in selling computers and accessories through retailers, direct sales, and distributors. Facing unexpected losses, particularly in their American stores, the company realized the necessity of data analytics for informed decision-making. Thus, the implementation of a robust analytics team became imperative for future survival in the industry.

### Pre-Project Inquiry Questions

- Project objectives
- Success metrics
- Project Timeline
- Stakeholder preview expectations
- Stakeholder hopes and fears
- User base and purpose
- Stakeholder expectations upon project completion
- Potential challenges
- Required resources/data
- Stakeholder design input

### Dataset Description

#### gdb041 Tables

#### dim_customer:
- **Markets**: 27 distinct markets (e.g., India, USA, Spain)
- **Customers**: 75 distinct customers across markets
- **Platforms**: 
    - Brick & Motors: Physical/offline store
    - E-commerce: Online Store (e.g., Amazon, Flipkart)
- **Channels**:
    - Retailer
    - Direct
    - Distributors

#### dim_market:
- **Markets**: 27 distinct markets (e.g., India, USA, Spain)
- **Sub-zones**: 7
- **Regions**:
    - APAC
    - EU
    - nan
    - LATAM

#### dim_product:
- **Divisions**:
    - P & A (Peripherals, Accessories)
    - PC (Notebook, Desktop)
    - N & S (Networking, Storage)
- **Categories**: 14 different categories (e.g., Internal HDD, Keyboard)
- **Variants**: Multiple variants available for each product

#### fact_forecast_monthly:
- Used for forecasting customer needs in advance
- Benefits:
    - Higher customer satisfaction
    - Reduced warehousing costs
- Denormalized by the data engineering team for analytical work
- Dates replaced by the start date of the month
- Columns include all necessary details, with forecasted quantity at the end

#### fact_sales_monthly:
- Similar to fact_forecast_monthly, but includes sold quantity instead of forecasted value

#### gdb056 Tables
- **freight_cost**: Details of travel and other costs per market per fiscal year
- **gross_price**: Details of gross prices with product code
- **manufacturing_cost**: Details of manufacturing costs with product code and year
- **Pre_invoice_deductions**: Details of pre-invoice deduction percentages for each customer per year
- **Post_invoice_deductions**: Details of post-invoice deductions and other deductions

## Importing Data into PowerBI

MySQL database datasets were imported into PowerBI using the provided credentials.

## Data Model

- Vital for report construction
- Followed Star Schema & Snowflake data modeling method
- Poor modeling affects report performance

![Image Description](https://github.com/connectsandy82/Power-BI-AtliQ-BI-Insights-360/raw/main/Data%20Modelling%20.png)


### Dashboard Design

- Based on received mock-ups
- Visual design and measure creation as needed

## Home View

- Central hub for all views
- Users navigate to specific views by clicking buttons
![Image Description](https://github.com/connectsandy82/Power-BI-AtliQ-BI-Insights-360/blob/main/AtliQ%20BI%20Insights%20360%20-%20Homepage.png)
## Finance View

![Finance](https://github.com/connectsandy82/Power-BI-AtliQ-BI-Insights-360/blob/main/AtliQ%20BI%20Insights%20360%20-%20Finance%20View.png)

## Sales View

![Sales](https://github.com/connectsandy82/Power-BI-AtliQ-BI-Insights-360/blob/main/AtliQ%20BI%20Insights%20360%20-%20Sales%20View.png)

## Marketing View

![Marketing](https://github.com/connectsandy82/Power-BI-AtliQ-BI-Insights-360/blob/main/AtliQ%20BI%20Insights%20360%20-%20Marketing%20View.png)

## Supply Chain View

![Supply chain](https://github.com/connectsandy82/Power-BI-AtliQ-BI-Insights-360/blob/main/AtliQ%20BI%20Insights%20360%20-%20Supply%20Chain%20View.png)

## Executive View

![Executive](https://github.com/connectsandy82/Power-BI-AtliQ-BI-Insights-360/blob/main/AtliQ%20BI%20Insights%20360%20-%20Executive%20View.png)

## Project Outcome

The implemented report facilitates data-driven decision-making across various business aspects, providing answers to numerous questions and enhancing situational understanding.
