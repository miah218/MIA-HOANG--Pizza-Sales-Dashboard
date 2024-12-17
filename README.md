# Pizza Sales Analysis

The following data analysis tasks were carried out using the provided datasets:<br />

1. Data Preparation <br />
Data Loading: Imported Data_pizza.xlsx <br />
Data Cleaning:<br />
Checked for missing values and corrected data inconsistencies. <br />
Renamed columns for clarity based on the data dictionary. <br />
Converted date and time columns to appropriate datetime formats for accurate time-series analysis. <br />

2. Data Modelling <br />
Eliminated redundancy by ensuring each order and product had unique identifiers. <br />
Parsed date and time fields into appropriate formats.<br />
Computed derived attributes like total_sales = quantity * price.<br />
Aggregated sales by day, week, month, product category, and customer order patterns.
Joined relevant tables using keys to create a consolidated view for analysis. <br /> <br />
Data Models Used:
Star Schema <br />
Fact Table: Fact_Sales <br />
Dimension Tables: OrderType, Product, Date, Time, Ingrdients, Category <br />
Time-Series Model:
Built using sales data to explore time-based trends (daily, weekly, monthly). <br />
Regression Model: To predict future sales based on past trends and seasonality. <br />

3. Sales Trend Analysis <br />
Daily, Weekly, and Monthly Sales Aggregation:<br />
Grouped data by date, week, and month to compute total sales using sales revenue. <br />
Created time-series plots to display daily, weekly, and monthly trends. <br /> <br />
Peak Sales Periods and Seasonality: 
Identified peak sales dates and analysed them in context with public holidays and promotions. <br /> <br />
Sales by Day of the Week and Time of Day: 
Aggregated sales by day of the week and time of day. <br />
Generated heatmaps and bar charts to visualise sales performance by time slots. <br /> 

3. Product Performance Analysis <br />
Pizza Category Rankings:
Aggregated sales by pizza categories and ranked them by revenue and total quantity sold. <br /> <br />
Top & Bottom Performing Pizzas:
Ranked pizzas by revenue and total quantity sold. <br />
Identified the best and worst-performing pizzas. <br /> <br />
Pizza Size and Sales Correlation:
Analysed sales patterns by pizza size across categories. <br />
Created bar chart to demonstrate size preferences in different categories. <br /> 

4. Customer Purchase Patterns Analysis <br />
Popular Pizza Sizes:
Identified the most frequently ordered pizza sizes. <br /> <br />
Single vs. Multi-item Orders:
Counted single-item and multi-item orders.<br />
Created pie chart for comparison. <br /> 

5. Ingredient Analysis <br />
Ingredient Frequency Analysis:
Counted occurrences of ingredients in all pizzas.<br />
Ranked ingredients by frequency of use.<br /> <br />
Ingredient-Sales Correlation:
Analysed the relationship between specific ingredients and sales volume.<br /> 

6. Price-Sales Correlation Analysis
Computed the correlation between pizza prices and total sales revenue. <br /> <br />
Average Order Time Interval:
Calculated average intervals between orders based on timestamp data. <br /> 
