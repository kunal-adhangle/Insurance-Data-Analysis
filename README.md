# Insurance Data Analysis Project

## Overview

This project analyzes insurance data using SQL Server and Power BI to provide insights into policy types, claims, and customer demographics. The dataset is imported into SQL Server using the Import Flat File feature, and Power BI is connected through the SQL Server option. The project includes various visualizations, interactive features, and security measures to enhance data analysis and decision-making.

## Dashboard Link:
https://app.powerbi.com/groups/b2df58d6-e19f-4c9a-9851-8bfd96681a1d/dashboards/3e2fad65-1fff-4f35-bd66-fe18115195ef?experience=power-bi

## Source: 
- **SSMS Database**
  
## Features
- **Data Import & Connectivity**
  - Imported CSV data into SQL Server using the Import Flat File feature.
  - Connected Power BI Desktop to SQL Server via the SQL Server connector.

- **Visualizations & Interactivity**
  - Implemented slicers for dynamic filtering.
  - Used multi-row cards and new card visuals for key insights.
  - Designed a ribbon chart to display trends.
  - Added drill-through functionality on policy type for deeper insights.
  - Incorporated bar chart, area chart, pie chart, and matrix for comprehensive data representation.

- **Security & Performance**
  - Configured row-level security (RLS) to restrict access based on user roles.
  - Scheduled automatic data refresh to keep the dashboard up-to-date.

## Setup Instructions

1. **Database Setup**
    - Import the CSV file into SQL Server using the Import Flat File feature.
    - Verify the data is loaded correctly in SSMS.

2. **Power BI Configuration**
    - Open Power BI Desktop and connect to SQL Server.
    - Load the data and ensure relationships are correctly established.

3. **Deployment & Refresh**
    - Publish the report to Power BI Service.
    - Configure scheduled refresh to ensure real-time data updates.
    - Implement Row-Level Security (RLS) for controlled access.

## Power BI Service Dashboard Screenshots

<img width="959" alt="Insurance Dashboard" src="https://github.com/user-attachments/assets/6a945975-ec0d-4f4f-9828-b92e9d657fda" />

## Power BI Desktop Screenshots

<img width="953" alt="Insurance Power Main Page" src="https://github.com/user-attachments/assets/ed0dc93d-332a-4d3a-a353-d016bd50b564" />

<img width="955" alt="Insurance 2nd Page" src="https://github.com/user-attachments/assets/36eafe78-2314-4cd3-9558-0d186eee7e45" />

## Conclusion
This project provides valuable insights into insurance data, enabling better decision-making through interactive visualizations and secured access. The combination of SQL Server and Power BI ensures efficient data management and reporting.
