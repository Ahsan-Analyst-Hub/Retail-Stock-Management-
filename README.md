# Food Retail Stock Management Dashboard
A Food Retail Stock Management Analytics Project built using SQL Server for data preparation and cleaning, and Power BI for interactive dashboard reporting. The project uses a dataset of approximately 10,000 rows designed to simulate real-world retail inventory and sales operations.
## Project Overview
This project focuses on analysing food retail stock data to support inventory control, sales monitoring, and operational decision-making. The sample dataset was intentionally created with a realistic business structure and includes common data quality issues so the cleaning process can be practised and demonstrated.
## The workflow for this project includes:
- Generating and structuring a food retail dataset.
- Importing and analysing the data in SQL Server.
- Cleaning data quality issues using SQL queries.
- Building an interactive Power BI dashboard.
- Creating meaningful DAX measures and visuals for business insights.
## Project Objective
The main objective of this project is to simulate a real-world food retail stock management system and create an analytical dashboard that helps answer key business questions, such as:
- Which products are running low in stock?
- Which items are out of stock?
- Which categories perform best?
- What is the total inventory value?
- Which suppliers or locations need attention?
- How does stock movement affect sales and replenishment?
## Tools and Technologies Used
- SQL Server – for data storage, transformation, and cleaning.
- Power BI – for dashboard creation and data visualisation.
- DAX – for calculated measures and business KPIs.
- Power Query Editor – for additional data preparation and shaping.
- GitHub – for project version control and documentation.
## Dataset Summary
The dataset contains approximately 10,000 records representing food retail stock and sales activity. It is designed to support stock management analysis and Power BI reporting.
## Dataset Features
The dataset includes fields such as:
- Transaction ID
- Transaction Date
- Store ID
- Store Name
- Product ID
- Product Name
- Category
- Supplier ID
- Supplier Name
- Opening Stock
- Quantity Sold
- Quantity Received
- Closing Stock
- Reorder Level
- Unit Cost
- Unit Price
- Sales Amount
- Cost Amount
- Expiry Date
- Batch Number
- City
- Region
- Payment Type
## Data Quality Issues Included
To make the project more realistic and useful for learning data cleaning, the dataset includes several intentional data issues:
- Duplicate records.
- Missing values in selected columns.
- Inconsistent category names.
- Invalid dates.
- Negative quantities.
- Outlier values in the price and stock columns.
- Mixed text casing.
- Extra spaces in text fields.
- Null or incomplete supplier and store values.

These issues were cleaned using SQL Server, making the dataset more reliable for analysis and dashboard creation.
## Data Cleaning Process
The data cleaning stage was completed in SQL Server before loading the final dataset into Power BI. The following cleaning tasks were performed:
- Removed duplicate rows.
- Handled missing values.
- Standardised category and product names.
- Corrected invalid date values.
- Treated negative quantities where necessary.
- Identified and reviewed outliers.
- Trimmed extra spaces.
- Standardised text casing.
- Validated stock and sales-related fields.

This step ensured that the final dataset was accurate enough for meaningful reporting and KPI calculation.
## Dashboard Overview
The Power BI dashboard was designed to provide a clear view of stock performance, sales activity, and inventory health. It includes interactive visuals and DAX-based KPIs to help users explore the data efficiently.
The dashboard was built across two pages, with KPIs on each page.

### Page 1: Stock Overview

- This page focuses on inventory monitoring and stock control.
<img width="1178" height="670" alt="Image" src="https://github.com/user-attachments/assets/7e9fe870-cb22-4d7f-a214-aa1cfcb5ae81" />

### Page 2: Sales and Supplier Performance

- This page focuses on sales analysis and replenishment performance.
<img width="1180" height="670" alt="Image" src="https://github.com/user-attachments/assets/aae28ad1-c744-48dd-9edc-df21ce016951" />

## Key Business KPIs

The project was designed to support the following business KPIs:
- Total Inventory Value – Measures the total worth of stock on hand.
- Total Units in Stock – Shows the overall stock quantity available.
- Low Stock Items – Identifies products that need replenishment.
- Out-of-Stock Products – Highlights products that are unavailable.
- Stock Turnover Rate – Measures how quickly inventory is sold and replaced.
- Total Sales Value – Tracks revenue generated from product sales.
- Gross Profit – Measures profit after subtracting cost.
- Gross Margin % – Shows profit efficiency as a percentage.
- Reorder Compliance % – Evaluates how well stock replenishment is managed.
- Shrinkage Rate – Measures loss due to discrepancies between expected and actual stock.

## DAX Measures Used

The dashboard uses custom DAX measures to calculate business metrics. Examples include:
- Total Sales Value
- Total Cost
- Gross Profit
- Gross Margin %
- Total Units Sold
- Total Units in Stock
- Inventory Value
- Low Stock Items
- Out-of-Stock Items
- Shrinkage Rate

  These measures were used to power cards, charts, and other visuals in the dashboard.

  ## Project Features
- Realistic food retail stock dataset.
- Around 10,000 rows of data.
- Deliberate data quality issues for practice.
- SQL-based data cleaning and preparation.
- Power BI dashboard with interactive visuals.
- KPI-focused reporting for inventory and sales analysis.
## Folder Structure
<img width="945" height="618" alt="Image" src="https://github.com/user-attachments/assets/35e452b7-c707-43a4-83c2-1dfb34fa6b6c" />

## Conclusion
This project shows how SQL Server and Power BI can be combined to build a practical stock management analytics solution for a food retail business. The dataset, cleaning process, and dashboard together provide a strong end-to-end example of data analysis, data preparation, and business intelligence reporting.
