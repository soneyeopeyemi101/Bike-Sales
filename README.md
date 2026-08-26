# Bike-Sales Analysis

### Project Overview
Bike Sales Dashboard (Excel): $85.3M revenue, $32.2M profit, 113K orders, 11.9 avg order qty (2011–2016). Breaks down revenue/profit by category (Accessories, Bikes, Clothing), by country (US, UK, Germany, France), and sub-category order volume, with slicers for age, gender, year, quarter.

### Dataset Description
A 6-year (2011–2016) bike sales dataset capturing transactions across multiple regions, used to analyze revenue, profit, and order trends by category, country, and customer demographics.
| Column            | Description                |
|-------------------|----------------------|
| Date              | Order Date           |
| Customer_Age      | Age of each Customer | 
| Product_Category  | Category of Product  |
| Sub_Category      | Product Sub Category |

## Tools Used

- Microsoft Power Query
      - Data Cleaning
- Microsoft Excel
      - Data Analysis, Pivot Tables & Visualization

### SQL
### Data Cleaning
``` SQL
select product, unitprice, (UnitPrice + UnitPrice*0.1) as New_Unit_Price from orders;
 update orders
 set unitprice = UnitPrice + UnitPrice*0.1;
 select product, unitprice from orders;
 ``` SQL



