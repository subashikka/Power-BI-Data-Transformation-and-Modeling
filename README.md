# Power BI Assignment 1 – Data Transformation & Data Modeling

## Project Overview

This project focuses on data transformation, data cleaning, and data modeling using **Microsoft Power BI** and **Power Query Editor**. The objective is to prepare raw sales datasets, create calculated columns, perform data aggregation, and establish relationships between multiple tables for effective data analysis.

## Tools Used

- Microsoft Power BI Desktop
- Power Query Editor
- Power BI Data Model

## Datasets

The project uses three datasets:

| Dataset | Description |
|---|---|
| List of Orders | Contains order IDs, order dates, customer details, location, category, amount, and profit |
| Order Details | Contains order IDs, categories, sub-categories, quantity, amount, and profit |
| Sales Target | Contains category, order month, and sales target |

## Project Tasks & Implementation

### 1. Data Import
- Imported all three CSV datasets into Power Query Editor.
- Reviewed the structure and column names of each dataset.

### 2. Data Transformation
- Retained the first 500 rows in the List of Orders dataset.
- Changed Order Date to Date format.
- Changed Amount and Target to Fixed Decimal Number.
- Applied Proper Case formatting to customer names.

### 3. Custom Column Creation
Created the following calculated columns:

- **Location:** Combined City and State into a single column.
- **Profit Margin:** Calculated profit as a percentage of sales amount.
- **Profit Status:** Classified transactions into Profit, Loss, and Break-Even categories using conditional logic.

### 4. Data Cleaning
- Identified and removed duplicate records where appropriate.
- Checked for missing and null values.
- Reviewed data consistency and column formats.

### 5. Merge Queries
- Merged List of Orders and Order Details using Order ID.
- Created a combined query named **Orders Data**.

### 6. Sorting and Filtering
- Sorted Order Date in descending order.
- Applied state-level filtering to analyze selected locations.

### 7. Group By and Aggregation
Performed data aggregation using Group By:

**Order Details**
- Count of Order ID.
- Average Profit by Category.
- Total Amount by Sub-Category.

**Sales Target**
- Summed Target by Month.

### 8. Data Modeling
Created relationships between the datasets:

- List of Orders and Order Details – Order ID.
- Order Details and Sales Target – Category.

Verified the relationships using the Manage Relationships option.

## Key Skills Demonstrated

- Data Import and Transformation
- Data Cleaning and Duplicate Removal
- Handling Missing Values
- Custom and Conditional Columns
- Data Type Conversion
- Merge Queries
- Group By and Aggregation
- Sorting and Filtering
- Data Modeling and Relationships
- Power Query Editor

## Project Outcome

Successfully transformed and prepared multiple sales datasets using Power Query. Created calculated columns, performed data aggregation, and established relationships between tables to build a structured data model for further analysis in Power BI.

## Author

**Subashini RK**

Aspiring Data Analyst | Excel | Power BI | Data Cleaning | Data Transformation
