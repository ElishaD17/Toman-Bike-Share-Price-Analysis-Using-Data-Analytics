# Toman Bike Share Price Analysis Using Data Analytics

## Overview
This project aims to analyze bike share usage data to determine the feasibility of a price increase. It utilizes SQL for database management and querying, and Power BI for dashboard creation and data visualization. The project covers the full workflow from data preparation to making strategic pricing recommendations.

## Table of Contents
- Introduction
- Technologies Used
- Data Description
- Data Preparation
- Analysis and Visualization
- Strategic Recommendations
- Conclusion
- Future Work
- How to Use
- References

## Introduction
The goal of this project is to assess the potential impact of a price increase on bike share usage and revenue. The analysis leverages SQL for managing and querying the data and Power BI for creating insightful dashboards.

## Technologies Used
- **SQL**: For database management and querying.
- **Power BI**: For data visualization and dashboard creation.
- **Microsoft SQL Server**: As the database management system.

## Data Description
The dataset includes bike share usage records with key features such as:
- **Trip ID**: Unique identifier for each trip
- **Start Time**: Start time of the trip
- **End Time**: End time of the trip
- **Start Station**: Starting station of the trip
- **End Station**: Ending station of the trip
- **User Type**: Type of user (e.g., subscriber or casual)
- **Trip Duration**: Duration of the trip in minutes

## Data Preparation
Data preparation involves:
- Importing the data into Microsoft SQL Server.
- Cleaning the data by handling missing values and outliers.
- Creating relevant features for analysis (e.g., trip duration, user segmentation).

## Analysis and Visualization
The analysis involves using SQL queries to extract insights and Power BI to visualize the results. Key analyses include:
- Usage patterns by time of day, day of the week, and season.
- User segmentation and behavior analysis.
- Revenue analysis and the impact of different pricing scenarios.

## Strategic Recommendations
Based on the analysis, strategic recommendations are made regarding the feasibility of a price increase. This includes:
- Identifying optimal pricing points.
- Assessing the potential impact on different user segments.
- Forecasting revenue changes.

## Conclusion
The analysis provides actionable insights into the bike share usage patterns and the potential impact of a price increase. It helps in making data-driven decisions for strategic pricing.

## Future Work
Future enhancements could include:
- Incorporating additional data sources such as weather conditions.
- Applying machine learning models for more advanced forecasting.
- Enhancing the dashboard with real-time data updates.

## How to Use
1. **Set up the database**:
   - Import the dataset into Microsoft SQL Server.
   - Execute the SQL scripts provided to prepare the data.

2. **Install Power BI** if not already installed:
   ```bash
   https://powerbi.microsoft.com/
   ```

3. **Load the data into Power BI**:
   - Connect Power BI to your SQL Server instance.
   - Load the prepared data tables.

4. **Explore and customize the dashboard** to suit your specific analysis needs.

## References
- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [Microsoft SQL Server Documentation](https://docs.microsoft.com/en-us/sql/sql-server/)
- [SQL Tutorial](https://www.w3schools.com/sql/)

## License
This project is licensed under the Apache 2.0 License. See the LICENSE file for more details.
