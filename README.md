📌Overview

This project demonstrates the development of a Power BI reporting solution using data from SQL Server and local files. The data was extracted, transformed, modeled, and visualized to provide meaningful business insights through interactive dashboards and reports.



🧱Data Sources

The project uses multiple data sources:

SQL Server Database
Primary source for transactional and master data.
Data was retrieved using SQL queries and database connections.
Local Files
Excel/CSV files containing supplementary business data.
Used to enrich the dataset and support additional analysis.



🎯Data Preparation

Data preparation was performed using Power Query in Power BI:

Connected to SQL Server and imported required tables.
Imported local files and combined them with database data.
Cleaned and transformed data by:
Removing duplicates
Handling missing values
Renaming and formatting columns
Creating calculated columns where necessary
Merging and appending datasets



🛠️Data Modeling

A relational data model was created to support efficient reporting and analysis.

Model Features
Fact and dimension table structure
Relationships established between tables
Optimized model design for performance
DAX measures created for key business metrics

Examples of measures:

Total Sales
Profit
Sales Growth
Customer Count
Average Order Value

📊Dashboard & Reports

The Power BI report includes:

Executive Summary Dashboard
Sales Performance Analysis
Customer Insights
Product Performance Metrics
Trend and Time-Series Analysis
Key Features
Interactive filters and slicers
Drill-through functionality
Dynamic KPIs
Data-driven visualizations



📁Key Features

Interactive filters and slicers
Drill-through functionality
Dynamic KPIs
Data-driven visualizations
Tools & Technologies
Power BI Desktop
SQL Server
Power Query
DAX (Data Analysis Expressions)
Excel / CSV Files
Project Workflow
Extract data from SQL Server.
Import additional local files.
Perform data cleaning and transformation.
Build a data model and define relationships.
Create DAX measures and calculations.
Design dashboards and reports.
Publish and share insights.


Repository Contents
├── PowerBI_Report.pbix
├── SQL/
│   └── Queries.sql
├── Data/
│   └── Sample_Files
├── Screenshots/
│   └── Dashboard_Images
└── README.md
Screenshots

screenshots of your dashboards here.

Model (Digram)

<img width="1217" height="742" alt="image" src="https://github.com/user-attachments/assets/261b833c-4c2a-4a2f-85da-fc4fe2a94462" />

Dashboard

<img width="1372" height="716" alt="image" src="https://github.com/user-attachments/assets/fdc27198-e9d5-4405-9daf-dc5fd45ba5be" />

<img width="1373" height="687" alt="image" src="https://github.com/user-attachments/assets/0e48717f-be16-4d35-bdf3-ce932b7ed71e" />

<img width="1037" height="702" alt="image" src="https://github.com/user-attachments/assets/e916bf4a-507b-4c24-8c93-b26db506c579" />

<img width="1080" height="732" alt="image" src="https://github.com/user-attachments/assets/6e4dd009-d844-40af-934c-90b9816b2310" />





👤Author




Mostafa Shehata
