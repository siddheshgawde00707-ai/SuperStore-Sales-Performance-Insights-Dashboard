# Super-Store-Sales-
<img width="1265" height="707" alt="Power BI" src="https://github.com/user-attachments/assets/3ef0a1be-bf43-448d-ab4a-8a5c12e42b17" />


1) Project Objective: The primary goal of this project was to analyze the sales and profitability of a "SuperStore" to identify key performance drivers, regional trends, and product category performance to help stakeholders make data-driven decisions.

2) Data Sourcing: The raw dataset was sourced via a YouTube educational resource, providing a comprehensive record of retail transactions including order details, customer segments, and geographic information across the United States.

3) Data Cleaning & Pre-processing (Excel): Initial data refining was performed in Microsoft Excel. This involved removing redundant columns (like ind1 and ind2), handling missing values in the Returns field, and ensuring date formats (Order Date, Ship Date) were consistent for time-series analysis.

4) Data Integration: The cleaned dataset was imported into Power BI, where I used the Power Query Editor to verify data types and perform final transformations, ensuring the "Sales" and "Profit" columns were correctly formatted as currency.

5) Data Modeling: I established a robust data model within Power BI. While the dataset was largely a flat table, I ensured all relationships and hierarchies (e.g., Region > State > City) were properly defined to enable "drill-down" capabilities in the report.

6) DAX Measures & KPIs: Developed custom measures using DAX (Data Analysis Expressions) to calculate critical business metrics, including Total Sales, Total Profit, Total Quantity Sold, and Profit Margin %.

7) Interactive Visualizations: Designed a dynamic dashboard featuring:
   
  Time-Series Analysis: Line charts to track sales and profit trends over years and months.
  
  Geographic Mapping: A map visual to identify high-performing states and regions.
  
  Product Performance: Bar charts showing the most and least profitable categories (e.g., Technology, Furniture, Office Supplies).

8) User Interactivity: Incorporated Slicers and Filters (Category, Region, Year, and Payment Mode) to allow users to customize their view and deep-dive into specific segments of the business.

9) Key Business Insights: The dashboard revealed significant findings, such as which Payment Modes (COD vs. Online) are preferred by customers and which Sub-Categories (like Binders or Phones) contribute the most to the bottom line.

10) Tools Used:
Excel: For initial data cleaning and structural audit.
Power BI: For data modeling, DAX development, and creating the final interactive dashboard.
