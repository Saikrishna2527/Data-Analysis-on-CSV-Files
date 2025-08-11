1) Imports libraries

pandas for data manipulation and analysis.

matplotlib.pyplot for creating plots and charts.

2) Load CSV Data

Reads the sales_data.csv file into a DataFrame called df.

Prints the first few rows (head()) to give a preview of the data structure and content.

3) Group and Summarize Sales

Uses groupby("Product")["Sales"].sum() to calculate total sales for each product category.

Uses groupby("Region")["Sales"].sum() to calculate total sales for each region.

Prints these summaries so you see the total sales numbers by product and by region.

4) Visualize the Data with Bar Charts

Creates a bar chart for sales by product:

Bars represent total sales amount per product.

The X-axis shows the product names, rotated for readability.

The Y-axis shows total sales values.

Chart title is “Sales by Product”.

Creates a bar chart for sales by region:

Bars represent total sales amount per sales region.

X-axis shows region names, Y-axis total sales.

Chart title is “Sales by Region”.

5) Enhancements for Display

plt.tight_layout() to adjust spacing for clear, non-overlapping labels.

Different colors for charts (skyblue for products, coral for regions) to visually distinguish them.
