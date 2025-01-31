# Sales Data Mart Project

## Project Overview
This project involves creating a **Sales Data Mart** using the **AdventureWorks 2022** database. The data was extracted, transformed, and loaded (ETL) using **SQL Server Integration Services (SSIS)**. The data mart is designed to support analytical reporting and future dashboard development.

## Tools & Technologies Used
- **SQL Server 2022** - Source database
- **SSIS (SQL Server Integration Services)** - ETL process
- **Dimensional Modeling** - Star Schema Design

## Implementation Details
1. **Data Extraction**: Retrieved sales data from the AdventureWorks database.
2. **Data Transformation**:
   - Cleaned and standardized data.
   - Implemented **Slowly Changing Dimensions (SCD)** (Type 1 & Type 2) for handling historical data.
3. **Data Loading**:
   - Loaded transformed data into the Data Mart.
   - Designed Fact and Dimension tables.

## Data Mart Schema
The Data Mart follows a **Star Schema** design with a central **fact_sales** table connected to multiple dimension tables:
- **Fact Table**: fact_sales (stores sales transactions)
- **Dimension Tables**:
  - dim_product
  - dim_customer
  - dim_date
  - dim_ship_method
  - dim_territory

## Next Steps
- Explore data visualization and reporting using **Power BI**.






