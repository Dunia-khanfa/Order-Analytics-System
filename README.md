# Order-Analytics-System
Restaurant Order Management System built with MySQL. Manages order details, menu items, and calculates total spending per order. Includes queries for total spend calculation, grouping orders by spend, and generating insights such as the most expensive items and average spend per category.

Overview:

The Order Analytics System is a database project designed to manage and analyze restaurant order data. It allows efficient tracking and querying of menu items and order details, offering valuable insights into order trends, item popularity, and customer preferences. The system is built using MySQL as the relational database management system (RDBMS), and SQL queries are used for analysis and reporting.

Key Features:

🍔 Menu Item Management: Organize menu items, including their categories and prices.

🛒 Order Tracking: Track each order’s details, including items purchased, order date, and time.

📊 Analytical Queries: Run queries to analyze the data, such as calculating total spending, finding the most/least ordered items, and analyzing order frequency.

🔒 Data Integrity: The database uses foreign key constraints and indexes to ensure data consistency and performance.

Project Structure:

The system is composed of two main tables:

order_details: Stores details of each order, such as the order date, time, and items ordered.

menu_items: Contains information about each menu item, such as item name, category, and price.

Sample Menu Items:
Hamburger: Category - American, Price - $12.95

Tofu Pad Thai: Category - Asian, Price - $14.5

Spaghetti & Meatballs: Category - Italian, Price - $17.95

Analytical Capabilities
The system is designed to help analyze and draw conclusions from the restaurant's data. Some key queries and analyses include:

Counting the total number of items available in the menu

Finding the cheapest and most expensive items on the menu

Categorizing dishes and calculating the average price within each category

Analyzing the order dates to track customer trends and behavior

Identifying the most frequent and least ordered items

Data Optimization
To improve performance and ensure data integrity, the system uses the following techniques:

Indexes: Efficient indexing on critical fields like order_date and item_id to speed up searches and queries.

Foreign Key Constraints: These constraints ensure that relationships between orders and menu items are maintained accurately and consistently.

Technologies Used:

MySQL: The relational database management system (RDBMS) used to store, organize, and query data.

SQL: The language used to perform data manipulation, queries, and reporting.

Indexes & Foreign Key Constraints: To optimize performance and maintain data integrity.

