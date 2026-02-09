# Syntecxhub_Statistical_Plots_Distribution_Analysis.
This project explores distributions of sales, profit, quantity, and discounts for a retail dataset, with a focus on detecting outliers, identifying skewness, and comparing patterns across Regions, Segments, and Shipping Modes.
## Project Overview

The dataset contains 9,999 transactions from 2021 to 2025, with variables including Sales, Profit, Quantity, Discount, Age, Region, Segment, and Ship_Mode.  

This project includes:
- Distribution analysis using *histograms, KDEs, and boxplots*
- Detection of *outliers*
- Comparison across *Regions, Segments, and Shipping Modes*
- Exporting plots and a *summary text file*  

---

## Repository Structure
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

**Key Insights**

Sales and Profit: Right-skewed distributions with noticeable outliers.
Quantity & Discount: Mostly low values with occasional extremes.
Age: Fairly symmetric, suitable for segmentation.
Regions & Segments: Variability differs across groups; West region and Consumer segment show higher variability.
Outliers: Identified in Sales (high values) and Profit (both high profits and some losses).
