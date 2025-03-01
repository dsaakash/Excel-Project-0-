# Coffee Shop Sales Data Analysis

## Project Overview
This data analytics project focuses on analyzing retail sales data from a coffee shop to gain actionable business insights. By examining various aspects of the sales data, this project aims to provide valuable information that can enhance the performance and operational efficiency of the coffee shop business.

## Objective
The primary objective is to perform a comprehensive analysis of coffee shop sales data to identify patterns, trends, and opportunities for business improvement. By understanding customer behavior, product performance, and operational patterns, the business can make data-driven decisions to optimize offerings, staffing, and marketing strategies.

## Dataset
The analysis is based on the coffee shop sales dataset from Maven Analytics (https://app.mavenanalytics.io/datasets). This dataset contains transaction details including:
- Transaction dates and times
- Store locations
- Product categories and types
- Product sizes (Small, Regular, Large)
- Quantities sold
- Unit prices
- Customer information

## Analysis Focus Areas

### 1. Temporal Analysis
- **Daily and Hourly Sales Patterns**: Examining how sales volume and revenue vary by day of the week and hour of the day
- **Peak Time Identification**: Determining peak periods of sales activity to optimize staffing and inventory management
- **Monthly Revenue Trends**: Analyzing total sales revenue for each month to identify seasonal patterns and growth trends

### 2. Spatial Analysis
- **Store Performance Comparison**: Evaluating how sales vary across different store locations
- **Location-specific Product Preferences**: Identifying if certain products perform better at specific locations

### 3. Customer Analysis
- **Average Order Value**: Calculating the average price/order per customer
- **Customer Purchase Behavior**: Analyzing patterns in customer orders and preferences

### 4. Product Analysis
- **Best-selling Products**: Identifying the top-performing products in terms of quantity sold and revenue generated
- **Product Category Performance**: Analyzing how sales vary by product category and type
- **Size Preferences**: Determining customer preferences for different product sizes (Small, Regular, Large)

## Methodology

### Data Preparation
1. **Data Import**: Loading the dataset into Excel
2. **Data Cleaning and Transformation**:
   - Creating a size category column based on product details (Sm, Rg, Lg)
   - Trimming whitespace and standardizing product names
   - Extracting date components (month, day of week) for temporal analysis
   - Extracting time components (hour) for time-of-day analysis
   - Calculating total bill amounts (quantity × unit price)
   - Handling any null or inconsistent values

### Data Analysis and Visualization
1. **Pivot Tables**: Creating pivot tables to aggregate sales data by various dimensions
2. **Time Series Analysis**: Examining sales patterns over different time periods
3. **Product Performance Metrics**: Calculating sales metrics by product category and type
4. **Store Comparison**: Comparing performance across different store locations
5. **Visualization**: Creating charts and graphs to visualize findings, including:
   - Line charts for hourly sales patterns
   - Bar charts for day-of-week performance
   - Heat maps for identifying peak sales times
   - Comparative visualizations for store and product performance

## Dashboard Creation
The project includes the creation of a comprehensive dashboard in Excel that visualizes key insights and allows for interactive exploration of the data. The dashboard features:
- Sales by hour of day
- Sales by day of week
- Monthly revenue trends
- Top-performing products
- Store location comparison
- Custom filters for dynamic analysis

## Business Insights and Recommendations
Based on the analysis, the project provides actionable recommendations for:
- Optimal operating hours
- Staffing allocation during peak times
- Inventory management
- Product mix optimization
- Location-specific strategies
- Pricing strategies
- Marketing and promotion opportunities

## Tools and Technologies Used
- Excel for data cleaning, transformation, analysis, and visualization
- Power Query for data transformation
- Excel Pivot Tables for data aggregation and exploration
- Power Pivot for advanced data modeling
- Excel Charts for visualization

## How to Use This Project
1. **Data Import**: Use the provided Excel file with the cleaned and transformed data
2. **Explore the Dashboard**: Navigate through the dashboard sheets to view different aspects of the analysis
3. **Customize Analysis**: Utilize the filters and slicers to focus on specific time periods, products, or stores
4. **Review Insights**: Examine the insights and recommendations provided in the analysis summary

## Future Work
- Incorporate customer demographic data for more targeted analysis
- Develop predictive models for sales forecasting
- Expand analysis to include external factors (weather, local events, etc.)
- Implement a more dynamic dashboard using Power BI or Tableau
- Conduct basket analysis to identify product affinities

## Project Structure
- `Coffee Shop Sales.xlsx`: Main Excel file containing the raw data, transformed data, and analysis
- `Dashboard.xlsx`: Excel file containing the final dashboard and visualizations
- Documentation folder: Contains project documentation and methodology details
- Images folder: Contains screenshots of key visualizations

## Author
Aakash Savant
