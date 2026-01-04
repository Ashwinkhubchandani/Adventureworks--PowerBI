# Adventureworks--PowerBI
Power BI sales dashboard built using the AdventureWorks dataset. The project uses cloud technology with data stored in AWS S3.

Overview

Developed a comprehensive BI solution for AdventureWorks Cycles, a fictional global bicycle manufacturer and retailer using Power BI. The project involved transforming raw sales and returns data into meaningful insights through data extraction, modeling, calculation, and visualization.

1. Connecting & Shaping Data
Imported raw data from multiple sources, including CSV files and databases.
Performed data cleaning and transformation in Power Query—renamed columns, set proper data types, removed inconsistencies and handled missing values.

2. Creating a Relational Data Model
Built a star-schema or relational model connecting fact tables (Sales, Returns) with dimension/lookup tables.
Defined one-to-many relationships to enable robust data slicing and analysis.

3. Adding Calculated Fields with DAX
Developed key metrics using DAX, such as Revenue, Profit, Total Orders, and Return Rate.
Employed advanced functions like SUMX, CALCULATE, RELATED, and date intelligence functions (DATEADD, DATESINPERIOD) to drive dynamic calculations—for example, rolling 90-day profits and previous-month comparisons. Medium

4. Visualizing Data with Reports
Created a four-page interactive Power BI dashboard with drill-through and filtering capabilities:
Executive Dashboard
Displayed high-level KPIs, trending revenue, total orders, and top-selling products. Included slicers for region and year filtering.

Map View
Showed geographical distribution of orders by region or continent. Revealed that while the U.S. led in orders, the Pacific region also accounted for a significant share—highlighting growth opportunities. Medium

Product Detail Page
Illustrated performance and trends for individual products (e.g., Road Tire Tube), revealing challenges such as elevated return rates that impacted monthly revenue and targets. Medium

Customer Detail Page
Offered insights into customer demographics and behaviors. For example, a few customers generated high revenue with few orders (e.g., Mr. Shan), while others placed many orders with lower spend—indicating variable customer value. Medium

5. Course Context from Udemy
Based on a Power BI Desktop course exploring the SQL Server Adventure Works Data Warehouse, this project provides hands-on experience with real business scenarios, data modeling, and DAX metrics—all rooted in an end-to-end BI workflow. Students gain the capability to collect, clean, model, and present data effectively.

6. Project Highlights
Integrated 4 Interconnected Pages: Enabled seamless navigation between executive, geographic, product, and customer views—enhancing story flow and drill-down ability.
Real-World Relevance: Modeled complex business problems like tracking KPIs, regional performance, product-level trends, and customer segmentation.
Self-Service BI: Demonstrated proficiency in Power BI Desktop tools—Power Query, Modeling, DAX, and Dashboard design.
