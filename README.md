# Axons-Sales-Data-Analysis
 Axon, a classic car retailer, seeks to enhance decision-making by implementing a Business Intelligence solution using Microsoft PowerBI and SQL. The project aims to centralize sales data, enabling efficient management, analysis, and informed decision-making.

# Problem Statement
A small company Axon, which is a retailer selling classic cars, is facing issues in managing and analyzing their sales data. The sales team is struggling to make sense of the data and they do not have a centralized system to manage and analyze the data. The management is unable to get accurate and up-to-date sales reports, which is affecting the decision-making process.

To address this issue, the company has decided to implement a Business Intelligence (BI) tool that can help them manage and analyze their sales data effectively. They have shortlisted Microsoft PowerBI and SQL as the BI tools for this project.

The goal of the capstone project is to design and implement a BI solution using PowerBI and SQL that can help the company manage and analyze their sales data effectively. The solution should be able to:

Import and integrate the data from MySQL database into PowerBI
Watch this video to know how to connect MYSQL database to PowerBI

Clean and transform the data to make it ready for analysis.

Build interactive dashboards and reports using PowerBI that can help the sales team and management make sense of the data.

Use SQL to perform advanced analytics on the data and extract insights that can help the company improve its sales (if needed).

Enable the management to access the dashboards and reports in real-time and make data-driven decisions.

The solution should be user-friendly and easy to use for the sales team and management. The project will be successful if it helps the company effectively manage and analyze their sales data and improve their decision-making process.


To solve the above capstone project, the given steps can be followed:

Use the data source provided: Use the MySQL database provided as a data source.

Extract and clean the data: The next step is to extract the data from the identified sources and clean it to make it ready for analysis. This may involve tasks such as removing duplicates, handling missing values, and ensuring data consistency.

Load the data into a PowerBI: The cleaned data can then be loaded into a centralized database.

Design the dashboards and reports: Using PowerBI, data can be visualized in the form of interactive dashboards and reports. These dashboards and reports can be designed to provide useful insights and information to the management.

Perform advanced analytics: Using SQL, advanced analytics can be performed on the sales data to extract insights and inform decision-making. This may involve tasks such as creating pivot tables, running queries, and creating views.

Deploy the solution: The final step is to deploy the BI solution, including the dashboards, reports, and advanced analytics, to the sales team and management. The solution should be user-friendly and easy to use to ensure adoption and success.


Database Description:

Here is a short description of the data tables included that contains typical business data such as customers, products, sales orders, sales order line items, etc.


MySQL Sample Database Schema

The MySQL sample database schema consists of the following 8 tables:

Customers: stores customer’s data.

Products: stores a list of scale model cars.

ProductLines: stores a list of product line categories.

Orders: stores sales orders placed by customers.

OrderDetails: stores sales order line items for each sales order.

Payments: stores payments made by customers based on their accounts.

Employees: stores all employee information as well as the organization structure such as who reports to whom.

Offices: stores sales office data


Hints:

Start by creating a new database as classicmodels in MySQL using below link:https://drive.google.com/file/d/1OB_iGw6vVS5KS7QwiwVChbeTfR4WvUy3/view?usp=share_link and load it in Power BI desktop using appropriate features and do the necessary data transformations. Briefly capture the features used for loading the data and for data transformation and mention all the steps clearly.

Clean and transform the data to make it ready for analysis. This may involve tasks such as removing duplicates, handling missing values, and ensuring data consistency.

Use PowerBI to design interactive dashboards and reports that can help the management make sense of the data. This should involve creating charts, graphs, and tables to visualize the data and using DAX functions to analyze the data.

Test and debug the BI solution to ensure that it is working as expected and address any issues that may arise.

Deploy the BI solution to the management and document the entire process to ensure adoption and success.

By following these hints, you should be able to successfully solve the capstone project and implement a BI solution using PowerBI and SQL that can help the company manage and analyze their sales data effectively.

# Methodology 
ETL --> Data Modeling --> KPI's --> Data Visualization --> Interactive Dashboard

# Deliverables
1. Cleaned Data:
Extracted and cleaned sales data ready for analysis.
Documented data cleaning process.

2.PowerBI Dashboards and Reports:
Interactive dashboards and reports designed in PowerBI.
Clear visualization of sales data insights.

3.SQL Analytics:
Advanced analytics results from SQL queries.
Insights extracted for decision-making.

4.Testing Report:
Detailed testing report ensuring BI solution accuracy.
Documentation of debugging processes.

5.Deployment Documentation:
Clear documentation on deploying the BI solution.
User-friendly guide for accessing dashboards and reports.

6.Project Summary:
Comprehensive summary capturing the project's success.
Recommendations for ongoing data management and analysis.

![image](https://github.com/nipunraj8/Axons-Sales-Data-Analysis/assets/121822594/51dced5f-811f-4039-981f-b6292bb5bc46)


# Conclusion
Through comprehensive data visualization, Axon's sales performance came alive, revealing critical Key Performance Indicators (KPIs) and insightful charts:

1. Key Performance Indicators:
Total Customers: 122
Total Orders: 312
Avg. Product Price: $54.40
Avg. Order Value: $33,970
Avg. Order Processing Time: 3.77 days
Total Sales Amount: $10.60M
Visual Insights:

2.Sales Trend Over Time (Line Chart):
2004 peak: $4.91M
2005 low: $2.21M
Product Line vs Order Count vs Sales (Table):

"2001 Ferrari Enzo" leads with $1.03M.
"1968 Ford Mustang" reports $811K.
Top 5 Selling Products (Bar Chart):

"2001 Ferrari Enzo" dominates at $1.03M.
Orders vs Status (Tree Map):

Unveils order distribution by status.
Top 3 Countries by Sales (Bar Chart):

USA leads at $4.28M.
Slicers for Time Analysis:

Facilitates in-depth analysis by year and quarter.

Conclusion:
The Power BI solution successfully provides clarity to Axon's sales data, empowering decision-making through interactive dashboards. The journey concludes with Axon equipped to navigate their sales landscape with precision and insight.
