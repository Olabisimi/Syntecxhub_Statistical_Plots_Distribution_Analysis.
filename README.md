# Syntecxhub_Statistical_Plots_Distribution_Analysis.
This project explores distributions of sales, profit, quantity, and discounts for a retail dataset, with a focus on detecting outliers, identifying skewness, and comparing patterns across Regions, Segments, and Shipping Modes.
## Project Overview

The dataset contains 9,999 transactions from 2021 to 2025, with variables including Sales, Profit, Quantity, Discount, Age, Region, Segment, and Ship_Mode.  

This project includes:
- Distribution analysis using histograms, KDEs, and boxplots
- Detection of *outliers*
- Comparison across Regions, Segments, and Shipping Modes
- Exporting plots and a summary text file
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
│   └── distribut[Sales_Summary.txt](https://github.com/user-attachments/files/25189030/Sales_Summary.txt)
<img width="640" height="480" alt="sales_distribution" src="https://github.com/user-attachments/assets/fb240283-47d7-493d-a5d4-8b6aabfef61b" />
<img width="640" height="480" alt="sales_by_Ship_Mode_boxplot" src="https://github.com/user-attachments/assets/e85fd1d8-3cc6-4d55-a9a8-748bdfd45c1c" />
<img width="640" height="480" alt="sales_by_region_boxplot" src="https://github.com/user-attachments/assets/ec64ab7a-47f9-4ed2-8592-50b12773df5c" />
<img width="640" height="480" alt="sales_by_egment_boxplot" src="https://github.com/user-attachments/assets/beb6667a-7dd7-41c6-9844-fd6ba25de851" />
<img width="640" height="480" alt="sales_boxplot" src="https://github.com/user-attachments/assets/30fd2ce2-33b4-4ff9-a99d-6c608bf8c67a" />
<img width="640" height="480" alt="profit_distribution" src="https://github.com/user-attachments/assets/c2cf9a30-b39b-4e44-89ad-e96f94eacbe4" />
<img width="640" height="480" alt="profit_by_Ship_Mode_boxplot" src="https://github.com/user-attachments/assets/a21b49d0-a332-4733-9a68-c2968778b681" />
<img width="640" height="480" alt="profit_by_segment_boxplot" src="https://github.com/user-attachments/assets/06772a6f-fce8-4bd8-8103-349c48536427" />
<img width="640" height="480" alt="profit_by_region_boxplot" src="https://github.com/user-attachments/assets/293099fb-b62b-49f2-a6b4-a5e4bea1ad36" />
<img width="640" height="480" alt="Profit_boxplot" src="https://github.com/user-attachments/assets/99dc298d-9c2d-4330-94be-ac7caab6c736" />
<img width="640" height="480" alt="kde_east_vs_west" src="https://github.com/user-attachments/assets/633a6d6c-0e5a-45d7-a445-42de7c3ed3de" />
[distribution_summary.txt](https://github.com/user-attachments/files/25189020/distribution_summary.txt)
[Statistical.ipynb](https://github.com/user-attachments/files/25189013/Statistical.ipynb)
ion_summary.txt
└── README.md

**Key Insights**

Sales and Profit: Right-skewed distributions with noticeable outliers.
Quantity & Discount: Mostly low values with occasional extremes.
Age: Fairly symmetric, suitable for segmentation.
Regions & Segments: Variability differs across groups; West region and Consumer segment show higher variability.
Outliers: Identified in Sales (high values) and Profit (both high profits and some losses).
