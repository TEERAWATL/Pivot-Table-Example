# Pivot-Table-Example

This project demonstrates how to create a pivot table and visualize sales data using Python's pandas, matplotlib, and seaborn libraries.

Dataset
The dataset used in this project contains sales information for three products (A, B, and C) across three dates (2023-01-01, 2023-01-02, 2023-01-03) and three regions (East, West, North).

## Pivot Table
We create a pivot table to summarize the sales data by date and product using the pivot_table() function in pandas. The pivot table shows the total sales for each product on each date.

Product       A   B   C
Date                    
2023-01-01   10  15  12
2023-01-02   20  25  22
2023-01-03   15  20  18

## Data Visualization
Two types of visualizations are created to represent the sales data:

Bar plot of the original dataset: This plot shows the sales for each product on each date using a bar plot. The x-axis represents the dates, the y-axis represents the sales, and different colors represent different products.

Stacked bar plot of the pivot table: This plot shows the sales for each product on each date using a stacked bar plot. Each bar represents a date, and the colored segments within each bar represent the sales of each product. The height of the segments indicates the sales value.

## Dependencies
To run the code, you need to have the following libraries installed:

pandas
seaborn
matplotlib
