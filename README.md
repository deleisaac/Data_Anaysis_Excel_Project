# Data_Anaysis_Excel_Project
## Project Overview
This project involves the analysis of coffee order data. The data is organized into various sheets that provide insights into total sales, orders, customers, products, and more. The project aims to analyze the sales performance, identify top customers, and visualize sales data using Excel's tools and formulas.

## Sheets Description
### 1. Total Sales
- Description: Summarizes the total sales of different coffee types over various months and years.
Formulas Used:
SUMIFS: Used to calculate the total sales for each coffee type and month.
Pivot Table: Summarizes data for easy analysis.
### 2. Orders
Description: Contains detailed information on individual coffee orders including order ID, date, customer ID, product ID, quantity, customer name, email, country, coffee type, roast type, size, unit price, sales, and more.
Formulas Used:
XLOOKUP: To fetch customer and product details.
IF: Used for conditional calculations.
SUMPRODUCT: Calculates total sales and quantities.
### 3. Customers
Description: Lists customer details including customer ID, name, email, phone number, address, city, country, postcode, and loyalty card status.
Tools Used:
Data Validation: Ensures consistency in customer data entry.
Conditional Formatting: Highlights customers with loyalty cards.
### 4. Products
Description: Provides details of coffee products including product ID, coffee type, roast type, size, unit price, price per 100g, and profit.
Formulas Used:
Price per 100g Calculation: Unit Price / Size
Profit Calculation: Unit Price * Profit Margin
### 5. CountryBarChart
Description: A bar chart representing the sum of sales by country.
Tools Used:
Bar Chart: Visualizes the sales data by country.
### 6. Top5Customers
Description: Lists the top 5 customers based on the sum of their sales.
Tools Used:
Ranking: Identifies the top customers by sales.
Pivot Table: Summarizes sales data for easy ranking.
### 7. Dashboard
Description: An interactive dashboard that provides a high-level overview of the sales data, including key metrics and visualizations.
Tools Used:
Charts and Graphs: Visualizes key data points.
Slicers: Allows for interactive filtering of data.
Tools and Features Used
Excel Formulas: SUMIFS, XLOOKUP, IF, SUMPRODUCT, etc.
Pivot Tables: For summarizing and analyzing data.
Charts and Graphs: For visualizing data trends and summaries.
Conditional Formatting: To highlight important data points.
Data Validation: Ensures data integrity.
Slicers: For interactive data analysis on the dashboard.
## How to Use
Open the Excel File: Load the coffeeOrderData.xlsx file in Microsoft Excel.
Navigate the Sheets: Explore each sheet to understand the structure and data.
Interact with the Dashboard: Use the slicers and charts on the Dashboard sheet to filter and view different aspects of the sales data.
Analyze Data: Utilize pivot tables and charts to gain insights into sales performance, customer behavior, and product popularity.
## Conclusion
This Excel project provides a comprehensive analysis of coffee order data, utilizing various Excel tools and formulas to derive meaningful insights. The interactive dashboard and visualizations make it easy to interpret and explore the data.

