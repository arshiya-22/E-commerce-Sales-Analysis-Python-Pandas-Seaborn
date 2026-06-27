# E-commerce-Sales-Analysis-Python-Pandas-Seaborn
This project analyzes sales data to understand selling patterns and revenue trends. Using Python libraries like Pandas, Matplotlib, and Seaborn, the analysis covers monthly sales trends, city-wise revenue, and product performance across different price ranges, presented through various types of visualizations.

## Dataset

- Dataset used in this project can be found (https://www.kaggle.com/datasets/beekiran/sales-data-analysis?resource=download)
- It contains **185,950 entries** across **11 columns**.
- Key Information includes order date, product name, price, quantity ordered and sales.

## Tools used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## What I did
1. Firstly, I loaded and cleaned the data.
2. Converted the order date column to a proper datetime format for time-based analysis.
3. Created subsets of the data using selected columns for specific analyses.
4. Analyzed monthly sales by categorizing products into high, medium, and low revenue ranges to understand which products  drive the most revenue.
5. Created multiple visualizations (line, bar, pie, and scatter plots) to compare monthly sales trends across these revenue categories, as well as city-wise and product-wise performance.

## Key Insights
1. Sales were highest in December, likely due to the holiday season and year-end discount offers.
2. Products like MacBook Pro and iPhone generate the highest revenue despite having lower sales quantity, while items like batteries and charging cables sell in high quantity but contribute the least revenue.
3. Mid-range products, such as mobile phones and headphones, balance both — moderate quantity sold with moderate revenue generated.
4. San Francisco and Los Angeles generated the highest sales revenue among all cities.
5. The seasonal sales pattern (high in Oct-Dec, low in Jan) was consistent across high and medium revenue products, but low-revenue items like batteries showed a steady demand throughout the year, regardless of season.

## Visualizations

### Monthly Sales Trend
<img width="640" height="480" alt="monthly_sales_trend" src="https://github.com/user-attachments/assets/b8bc9226-9ff9-42d5-b95e-d7792d03dbf6" />

Sales peak in December and are lowest in January, showing a clear seasonal pattern.

### Sales by City
<img width="640" height="480" alt="sales_by_city" src="https://github.com/user-attachments/assets/1c06500e-553c-4ed9-83e2-5af41df2d834" />

San Francisco and Los Angeles generate the highest revenue among all cities.

### City Sales Distribution
<img width="640" height="480" alt="city_sales_pie" src="https://github.com/user-attachments/assets/27ebc5dc-cb75-4d19-9478-c8d2db99ebc1" />

A proportional view of how total sales are distributed across cities.

### High vs Medium vs Low Revenue Range Comparison
<img width="640" height="480" alt="range_comparison" src="https://github.com/user-attachments/assets/5a605978-9ee9-481c-ba2a-473ee70acec5" />

High and medium revenue products follow a seasonal trend, while low-revenue products show steady demand throughout the year.

### Quantity Ordered vs Price
<img width="640" height="480" alt="quantity_vs_price" src="https://github.com/user-attachments/assets/de9c1061-1758-4edb-adeb-9452944d4e8f" />

Lower-priced items are typically ordered in higher quantities, while expensive items are ordered individually.
