# SUPERSTORE-SALES-DATASET-CASE-STUDY-DAY5-PYTHON-PANDAS-DATA-VISUALISATION
SUPERSTORE-SALES-DATASET-CASE-STUDY-DAY5-PYTHON-PANDAS-DATA-VISUALISATION
# Superstore Sales Dataset Analysis with Pandas and Data Visualization

This project explores the **Superstore Sales Dataset**, leveraging **Pandas** for data manipulation and analysis, and **Matplotlib/Seaborn** for visualizations. The dataset contains information on sales, profits, discounts, and other attributes related to orders from a superstore. The analysis aims to uncover insights into sales performance, regional trends, product categories, and more.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Pandas Analysis](#pandas-analysis)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Data Cleaning](#data-cleaning)
  - [Aggregation and Grouping](#aggregation-and-grouping)
  - [Advanced Operations](#advanced-operations)
- [Data Visualization](#data-visualization)
- [Conclusion](#conclusion)
- [Contact](#contact)

## Project Overview

The **Superstore Sales Dataset** is a popular dataset for performing retail analytics. This project uses **Pandas** for data analysis and **Matplotlib** and **Seaborn** for data visualization to explore sales patterns, regional performance, and product categories. The project covers data cleaning, aggregation, grouping, and advanced operations, followed by visualization techniques to represent key findings.

## Dataset

The dataset includes the following columns:
- `Order ID`: Unique identifier for each order
- `Order Date`: Date the order was placed
- `Ship Mode`: Mode of shipment
- `Customer ID`: Unique identifier for each customer
- `Segment`: Customer segment (e.g., Consumer, Corporate)
- `Category`: Product category (e.g., Furniture, Technology)
- `Sales`: Sales amount for the order
- `Profit`: Profit generated from the order
- `Discount`: Discount applied to the order
- `Region`: Geographical region of the order
- `Sub-Category`: Sub-category of the product
- And more...

## Pandas Analysis

### Exploratory Data Analysis (EDA)
1. **Dataset Loading and Inspection**: The dataset was loaded into a Pandas DataFrame, and the first few rows were displayed to understand the structure.
2. **Shape of the Data**: The dataset contains thousands of rows and multiple columns, giving insights into sales data.
3. **Column Names**: All column names were listed to understand the available features.

### Data Cleaning
1. **Missing Values**: Missing values were identified and handled appropriately (e.g., filling with mean values or removing rows).
2. **Duplicates**: Duplicate rows were removed to ensure data integrity.
3. **Datetime Conversion**: The `Order Date` column was converted to datetime format to facilitate time-series analysis.

### Aggregation and Grouping
1. **Total Sales per Region**: Aggregated sales figures by region to understand regional performance.
2. **Average Discount per Category**: Calculated the average discount provided for each product category.
3. **Profit Distribution**: Analyzed the maximum and minimum profit by sub-category.

### Advanced Operations
1. **New Columns**: Created new columns, such as `Profit Margin` and `Sales Category`, to categorize and calculate key metrics.
2. **Custom Functions**: Applied custom functions for normalizing sales data and calculating rolling averages.
3. **Merging and Joining**: Performed merges and joins between different datasets to enrich the analysis (e.g., joining orders with returns data).

## Data Visualization

### Key Visualizations
1. **Sales Distribution**: A histogram was created to visualize the distribution of sales values.
2. **Bar Chart of Sales by Region**: Displayed total sales by region to compare regional performance.
3. **Time Series of Sales**: Plotted a time series to visualize sales trends over time.
4. **Boxplot of Profit by Category**: Showcased the distribution of profit across different product categories.
5. **Pie Chart of Sales by Category**: Visualized the percentage contribution of each category to total sales.
6. **Scatter Plot of Sales vs. Profit**: Highlighted the relationship between sales and profit for each order.
7. **Correlation Heatmap**: Used a heatmap to visualize correlations between numerical columns in the dataset.
8. **Sales Trend by Category**: Plotted sales trends for each category over time using a line plot.
9. **Average Discount by Ship Mode**: Bar plot showing the average discount for each shipping mode.
10. **Stacked Bar Chart of Ship Mode by Region**: Visualized the distribution of shipping modes across different regions.

### Visualization Tools
- **Matplotlib**: Used for basic plotting and customization.
- **Seaborn**: Used for more advanced visualizations, including heatmaps and boxplots.

## Conclusion

This project provided valuable insights into the **Superstore Sales Dataset**, uncovering patterns in sales performance, regional trends, product category distributions, and customer segments. Through data cleaning, aggregation, and visualization, we gained a deeper understanding of the dataset's key aspects.

## Contact

For questions, comments, or collaboration, feel free to reach out via [LinkedIn](https://www.linkedin.com) or check out my [GitHub profile](https://github.com).

---

**License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
