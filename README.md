# Sales-Performance-Analysis-Power-BI-Dashboard

#  Project Overview
This project presents a comprehensive interactive dashboard built using Power BI, designed to analyze retail sales data. The aim is to provide key insights into sales performance, customer behavior, and profitability, enabling stakeholders to make informed, data-driven decisions. The dashboard visualizes trends, highlights top performers, and identifies areas for potential improvement within the retail operations.

# Features & Analysis Capabilities
The Power BI dashboard offers the following key analytical capabilities:

1. Executive Sales Summary: An high-level overview of total revenue, average order value, and overall profit to quickly grasp business health.

2. Sales Performance by Category: Visualize sales distribution across different product categories, highlighting the most profitable or popular segments.

3. Customer Demographics & Behavior: Analyze sales by gender and age groups, helping to understand target customer segments and their purchasing habits.

4. Top Customers Identification: Easily identify high-value customers based on their total sales contribution.

5. Time-Series Trends: Track sales performance over time (e.g., monthly sales trends, best-selling months per year) to understand seasonality and growth.

6. Operational Insights (Shift Analysis): Break down sales by time shifts (Morning, Afternoon, Evening) to optimize staffing or marketing efforts during peak hours.

7. Profitability Insights: Directly view the profit generated from each sale and overall, allowing for a clear understanding of financial performance.

8. Interactive Filtering: Utilize various slicers and filters (e.g., date, category, gender) to drill down into specific data segments and gain granular insights.

# Dashboard Pages
The Power BI report is structured into intuitive pages for easy navigation and focused analysis:


Sales Overview (Page 1): Provides an executive summary of key sales metrics, overall revenue, profit, and top-level trends. 

<img width="1299" height="721" alt="Sales Overview(page 1)" src="https://github.com/user-attachments/assets/b3a9acc0-028a-4ea1-b122-ff4edcc25abc" />



Category & Customer Deep Dive (Page 2): Detailed analysis of sales performance across different categories and insights into customer demographics and their buying patterns.

<img width="1287" height="720" alt="sale performance (page 2)" src="https://github.com/user-attachments/assets/18601c46-17bc-469e-904b-ffef63acfa71" />


Operational Performance (Page 3): Focuses on time-based sales, shift analysis, and other operational metrics relevant to daily store management.

<img width="1279" height="722" alt="trends analysis (page 3)" src="https://github.com/user-attachments/assets/5969fac2-7754-4890-a093-88165f995c01" />


# Data Source
The analysis is based on retail sales data provided in a CSV format.

sales data.csv: Contains transactional information including transaction_id, sale_date, sale_time, customer_id, gender, age, category, quantity, price_per_unit, cogs, and total_sale.

# Technologies Used
Power BI Desktop: For data modeling, transformation (Power Query/M), DAX calculations, and dashboard visualization.


CSV: Data storage format.

Setup and Usage
To view and interact with the dashboard:

# Prerequisites:

Install Power BI Desktop: Download from Microsoft

Get the Project Files:

Clone this repository to your local machine.

Open the Power BI Report:

Navigate to the cloned directory and open the .pbix file (e.g., Retail_Sales_Analysis.pbix).

Data Refresh:

The report is configured to connect to the sales data.csv file. Ensure sales data.csv is in the same folder as the .pbix file, or update the data source settings in Power BI Desktop if moved.

Click "Refresh" in Power BI Desktop to load the latest data.

#  Data Model & Transformations
The sales data.csv was loaded into Power BI. Standard data cleaning and transformation steps were applied using Power Query (M language) to ensure data quality and usability for analysis. This included:

Data Type Correction: Ensuring all columns have appropriate data types (e.g., sale_date as Date, sale_time as Time, price_per_unit as Decimal Number).

Handling Missing Values: Rows with NULL values in critical columns were identified and removed during the data loading process to maintain data integrity and accuracy of calculations.


# Key Insights from the Dashboard

The dashboard provides actionable insights such as:

1. Profitability by Product Category: Quickly identifies which categories are driving the most profit versus just high revenue.

2. Customer Segmentation: Provides a basis for targeted marketing campaigns by understanding the demographic profiles of purchasers in different categories.

3. Operational Efficiency: The shift analysis helps management understand peak hours for sales, assisting in optimizing staffing schedules and inventory replenishment.

4. Sales Trend Analysis: Monitoring monthly and yearly trends allows for proactive planning for inventory, promotions, and resource allocation.

# Future Enhancements

1. Integration with a live SQL database for real-time data updates.

2. Implementation of advanced DAX measures for year-over-year growth, rolling averages, and more complex customer segmentation (e.g., RFM analysis).

3. Addition of forecasting models to predict future sales trends.

4. Incorporation of external data sources (e.g., marketing spend, customer reviews) for a more holistic analysis.
