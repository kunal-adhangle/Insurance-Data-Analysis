**Insurance Data Analysis Project**

Overview

This project analyzes insurance data using SQL Server and Power BI to provide insights into policy types, claims, and customer demographics. The dataset is imported into SQL Server using the Import Flat File feature, and Power BI is connected through the SQL Server option. The project includes various visualizations, interactive features, and security measures to enhance data analysis and decision-making.

Features

Data Import & Connectivity

Imported CSV data into SQL Server using the Import Flat File feature.

Connected Power BI Desktop to SQL Server via the SQL Server connector.

Visualizations & Interactivity

Implemented slicers for dynamic filtering.

Used multi-row cards and new card visuals for key insights.

Designed a ribbon chart to display trends.

Added drill-through functionality on policy type for deeper insights.

Security & Performance

Configured row-level security (RLS) to restrict access based on user roles.

Scheduled automatic data refresh to keep the dashboard up-to-date.

Setup Instructions

Database Setup

Import the CSV file into SQL Server using the Import Flat File feature.

Verify the data is loaded correctly in SSMS.

Power BI Configuration

Open Power BI Desktop and connect to SQL Server.

Load the data and ensure relationships are correctly established.

Apply necessary transformations and create visualizations.

Deployment & Refresh

Publish the report to Power BI Service.

Configure scheduled refresh to ensure real-time data updates.

Implement Row-Level Security (RLS) for controlled access.

Screenshots

(Add your Power BI dashboard images here)

![Dashboard Overview](images/dashboard_overview.png)
![Slicers](images/slicers.png)

Conclusion

This project provides valuable insights into insurance data, enabling better decision-making through interactive visualizations and secured access. The combination of SQL Server and Power BI ensures efficient data management and reporting.
