# Syntecxhub_Statistical_Plots_Distribution_Analysis.
This project explores distributions of sales, profit, quantity, and discounts for a retail dataset, with a focus on detecting outliers, identifying skewness, and comparing patterns across Regions, Segments, and Shipping Modes.

## Project Overview

This project focuses on exploring the distribution and variability of key numerical variables within a retail sales dataset. Using statistical plots and descriptive analysis, the project investigates data spread, skewness, and outliers, as well as compares distributions across different customer and business groups. The analysis provides insights into sales performance, profitability, and customer behavior.
**Repository Structure**
statistical_analysis/
│
├── Statistical.ipynb   
├── datasets/                             
│   └── df.csv
│   └── sales_distribution.png
│   └── profit_distribution.png
|   └── sales_boxplot.png
|   └── profit_boxplot.png
│   └── sales_by_region.png
│   └── sales_by_segment.png
│   └── sales_by_ship_mode.png
│   └── profit_by_segment.png
│   └── profit_by_ship_mode.png
│   └── profit_by_region.png
│   └── kde_east_vs_west.png
│   └── distribution_summary.txt
└── README.md



**Dataset**

The dataset used in this project is a cleaned and merged sales dataset created from multiple regional customer files and sales records. It includes transactional, customer, and operational attributes such as:
Sales
Profit
Quantity
Discount
Segment
Region
Ship Mode
Customer Age
The dataset was reused from earlier preprocessing steps to ensure consistency across projects.

**Objectives**

The main goals of this project are to:
Inspect the distribution of numerical variables using statistical plots
Visualize distributions with histograms, KDEs, and boxplots
Compare distributions across groups such as region, segment, and shipping mode
Detect outliers and assess skewness and spread
Export visual outputs and provide concise interpretations

**Tools & Libraries**

Python
Pandas
NumPy
Matplotlib
Seaborn

**Analysis & Visualizations**

1. Distribution Analysis:
Histograms and KDE plots were used to analyze the shape of distributions for sales, profit, quantity, discount, and customer age.
Most variables display right-skewed distributions, with a small number of high-value observations influencing the mean.

2. Outlier Detection:
Boxplots were used to identify extreme values.
Sales shows significant high-end outliers, indicating a small number of very large transactions.
Profit includes both positive and negative outliers, reflecting high-gain orders as well as loss-making transactions.

3. Group-Based Comparisons
Distribution comparisons were performed across:
Regions
Customer segments
Shipping modes
These comparisons reveal differences in variability and central tendency, helping identify which groups contribute most to sales and profitability.

**Key Insights**
Sales and profit distributions are strongly right-skewed with notable outliers.
Discounts are generally low but have a noticeable impact on profit.
Customer age is relatively symmetric, suggesting balanced representation across age groups.
Certain regions and shipping modes exhibit higher variability in profit, indicating uneven performance.

**Outputs**

Histograms and KDE plots for key numeric variables
Boxplots highlighting outliers
Group-wise comparison plots
A short written summary exported as a text file

**Conclusion**

This project demonstrates the importance of distribution analysis in understanding business data beyond averages. By examining skewness, spread, and outliers, the analysis provides a deeper understanding of sales behavior and profitability drivers, forming a strong foundation for correlation and predictive analysis in subsequent projects.

