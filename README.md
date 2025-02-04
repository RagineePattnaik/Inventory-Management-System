# Inventory-Management-System
# Overview of the Dashboard
The dashboard serves as the main interface for our inventory management system. It provides real-time insights into various metrics such as:

Total number of customers
Total number of products
Purchase amount
Sales amount
Profit and loss
Stock amount
Top five products and customers
# Dashboard Features
Automatic Updates: The dashboard will automatically update as you enter data into the system.
Notification Board: Alerts will be generated when stock levels fall below a certain threshold (e.g., less than five units).
Setting Up the Workbook
To start, you need to create a new Excel workbook and add the following sheets:

Dashboard
Customers
Products
Vendors
New Entry
Purchases
Sales
Inventory
Pivot Tables (PVT)
# Creating the Dashboard Menu
Select Columns: Adjust the width of columns to create space for the menu.
Insert Icons: Use icons to represent different sections of the dashboard.
Link Sheets: Create hyperlinks in the dashboard to navigate to different sheets easily.
Data Entry Sheets
Customers Sheet
Data Fields: Include fields for Customer ID, Name, Email, and Address.
Table Format: Convert the data range into a table for better management.
Vendors Sheet
Data Fields: Include fields for Vendor ID, Name, Phone Number, and Address.
Table Format: Similar to the customers sheet, convert this data into a table.
Products Sheet
Data Fields: Include fields for HSN Code, Product Name, Cost Price, and Selling Price.
Table Format: Convert this data into a table as well.
New Entry Sheet
Purchase and Sales Entry: Create sections for entering new purchases and sales. Link these entries to the respective sheets for automatic updates.
Automating Data Entry
Purchase Entries
Dropdown Lists: Create dropdown lists for selecting products using data validation.
Automatic Updates: Use formulas like VLOOKUP to automatically fill in product names and costs based on the selected HSN code.
Sales Entries
Similar to purchase entries, set up dropdowns for customers and products, and automate the entry of customer names and product details.
Inventory Management
Inventory Sheet
Data Fields: Include fields for HSN Code, Product Name, Cost, Purchase Units, Sales Units, Stock, and Stock Amount.
Formulas: Use formulas to calculate stock levels based on purchases and sales.
Notification System
Alerts: Implement a formula to check stock levels and display vendor contact information when stock is low.
Pivot Tables for Insights
Creating Pivot Tables
Use pivot tables to summarize data for total customers, products, purchase amounts, sales amounts, and stock amounts.
Create visual representations (charts) of the top-selling products and customers.
Finalizing the Dashboard
# Displaying Insights
Insert the calculated values from pivot tables into the dashboard.
Format the dashboard for clarity and ease of use.
# Refreshing Data
Remember to refresh your pivot tables whenever new data is added to ensure the dashboard reflects the latest information.
# Conclusion
By following these steps, you will have a comprehensive automated inventory management system in Excel that can help streamline your business operations. This project not only enhances your Excel skills but also provides a practical tool for managing inventory effectively.
