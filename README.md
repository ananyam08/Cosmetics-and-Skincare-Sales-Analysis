# Cosmetics-and-Skincare-Sales-Analysis
Overview
This dataset contains sales records for various cosmetic products. It includes key details such as product category, sales date, sales amount, and location. It is suitable for sales analysis, trend identification, and visualization in tools like Excel, Power BI, or Python.

Dataset Name: Cosmetics Sales Data — A sales transactions dataset for cosmetic products.
File Name: cosmetics_sales_data_excel.xlsx — The original data source.
Total Records: 1,626 rows of transaction-level data.
Date Range: From 12 July 2021 to 12 February 2023, covering about 1.5 years of sales.
Top 5 Products:
Tea Tree Moisturizer
Hydrating Face Serum
Anti-Aging Serum
Body Butter Cream
Hair Repair Oil
Columns: sale_Id, Sales Person, Country, Product, shipped Date, Amount ($), Boxes Shipped, Month.

1 .EDA and Dashboard using  Excel
  
   data cleaning
   For shipped Date: Fill with correct date from records or remove row if unknown.
   For Amount ($): Fill with 0 or estimate based on similar transactions (if logical).
   Convert shipped Date to Date format.
   Ensure Amount ($) and Boxes Shipped are numeric (remove $ symbols if present).
   Add category of for box shipped as high,medium and low

   EDA task
   Identified top products, countries, and salespersons using pivot table
   calculated key satisticts 
   mean,median,mode for shipped order and also Revenue and order insights by adding total orders ,total revenue,min sale,max sale ,average sale

   Dashboard creation:
   key matrics(KPIS)
   line,pie,bar,colums for charts
   filters (slicers) to visualize sales of product,month and country

2. EDA and visualization using python
   objectives:This Jupyter Notebook contains Python-based data cleaning, analysis, and visualization for a cosmetics sales dataset.

   steps to follow:
   libraries 
   pandas
   numpy
   matplotlib
   seaborn

   install dependencies

   Data Import & Inspection
   Loads the cosmetics sales dataset (Excel/CSV).
   Displays basic structure (rows, columns, and data types).
   Shows initial sample rows for inspection.

   Data Cleaning
   Missing Values Handling – Checked for null values in shipped Date, Amount ($), and Boxes Shipped, filled or removed as appropriate.
   Data Type Conversion – Ensured shipped Date is in proper date format, Amount ($) is numeric, and sale_Id is integer.
   Duplicate Removal – Removed duplicate sales records to avoid skewed analysis.
   Column Standardization – Renamed columns for consistency (no trailing spaces, proper case).
   Derived Column Creation – Extracted Month for trend analysis.

   perform data description (head,info,character)

   data and data visualization
   Identified sales trends over time.
   Recognized high-value customers and top-selling products.
   Observed seasonal and category-based variations in purchases.
   plotting of bar graph,heat map,scatter plot,histplot
   
3.EDA and Visualization using power BI
  objectives:This Power BI dashboard provides a comprehensive analysis of cosmetics sales, customer behavior, and market performance. It is designed to help businesses in the beauty and personal care industry       make data-driven decisions by visualizing key performance metrics and trends.

  data import & inspection
  data cleaning 
  dashboard creation using differ type of charts for visualization
  slicers for country to filter the visualization
  new measures of mix,max,total,average 
  DAX to find top selling products 


