# Business-Insights-360-AtliQ-Hardware

## Project Overview
AtliQ Hardware, experiencing rapid growth, has implemented Power BI analytics to drive data-based decisions across finance, sales, marketing, and supply chain. This project is AtliQ's first venture into analytics, designed to provide valuable insights to compete effectively and guide stakeholders' decision-making.

I worked on this project by following the [Codebasics Power BI Course](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project), which provided comprehensive training and practical experience.



## Tech Stack
- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for performance optimization)
- **Project Charter File**


## Key Power BI Techniques Learned
- **Initial Project Planning**: Defined objectives, metrics, and timelines based on stakeholder input.
- **Data Modeling**: Structured using a Snowflake schema to optimize performance.
- **DAX Calculations**: Created calculated columns and measures with functions like `CALCULATE()`, `DIVIDE()`, `FILTER()`, `SWITCH()`.
- **Interactive Visuals**: Used Bookmarks, buttons for navigation, and dynamic titles.
- **Data Validation and Error Prevention**: Leveraged data validation techniques and conditional formatting for enhanced accuracy.
- **Automation and Collaboration**: Published to Power BI Services, with auto-refresh using personal gateway, Power BI App creation, and workspace management.



## Business and Domain Knowledge Applied
- **Finance**: Gross Price, Net Sales, Gross Margin, Net Profit.
- **Sales and Marketing**: Market segmentation, YTD/YTG metrics, retail and distributor performance.
- **Supply Chain**: COGS, inventory tracking, forecasting for improved customer satisfaction.
- **Executive View**: provide overall insights to stakeholders




## Data Overview
Understanding the datasets was key to efficient analysis. Data was reviewed for accurate model design, helping avoid performance issues.

### Dataset Tables and Structures
- **Dimension Tables**:
  - `dim_customer`: Contains 27 markets, 75 customers, two platforms (Brick & Mortar, E-commerce), and three channels (Retailer, Direct, Distributors).
  - `dim_market`: Geographical data covering 7 sub-zones in regions like APAC, EU, LATAM.
  - `dim_product`: Product details, including categories and types (e.g., Notebook, Desktop).
  
- **Fact Tables**:
  - `fact_forecast_monthly`: Forecasted demand data to enhance satisfaction and reduce warehouse costs.
  - `fact_sales_monthly`: Sales data, formatted similarly to the forecast table.

- **Cost Tables**:
  - `freight_cost`, `gross_price`, `manufacturing_cost`, `pre_invoice_deductions`, `post_invoice_deductions`: Detailing costs and deductions per market, product code, and year.



## Data Import and Modeling
Data was imported from MySQL, with a Snowflake schema for optimal performance. Following good modeling practices ensured a reliable foundation for visuals.


![Screenshot 2024-10-25 131223](https://github.com/user-attachments/assets/b598d9cd-8eef-4b11-81b3-8a9e6d89f27b)




## Dashboard Design
Mockups informed a design focused on clear navigation and segmented views for different departments.

### Home View
The central hub with buttons for each view, allowing users to quickly access specific sections.

### Views Included
- **Info**
- **Finance View**
- **Sales View**
- **Marketing View**
- **Supply Chain View**
- **Executive Overview**
- **Support**



## Project Outcome

This report empowers decision-makers to make informed choices driven by data insights. By utilizing this dashboard, stakeholders can explore various metrics and respond to numerous "why" questions related to their specific situations. It facilitates a deeper understanding of performance across key areas such as finance, sales, marketing, and supply chain, ultimately enhancing the organization's strategic initiatives and operational effectiveness.


### Dashboard Link
If you're interested in exploring and interacting with the dashboard,[click here](https://app.powerbi.com/view?r=eyJrIjoiNGE5MDRmNmUtZWQyNy00ZWNkLTk2ZGQtYWZhZWFiYjE3NzI4IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Contact
For any questions or further information, please contact    [Jeevitha D J](https://www.linkedin.com/in/jeevitha-dj/)


