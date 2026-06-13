# Objective:
To develop a data-driven inventory management system that optimizes inventory levels and safety stock by analyzing demand patterns. The project aims to reduce stockouts and excess inventory while improving product availability and operational efficiency.
# Project Structure:
    Automation.ipynb:
        Purpose: Automates data extraction cleaning and ingestion process.
        Functions: Automatically fetches the Inventory data , clean the dataset and save the cleaned data in .csv file.
    Analysis.ipynb:
        Purpose: Performs analytics,visualizations.
        Functions: Reads the cleaned data, run analysis, and plots the final trends.
# Tools and Technologies Used:
    Automation : Python
    Data Manipulation: pandas,scipy
    Data Visualization : Matplotlib, Seaborn
    Environment: Jupyter Notebook.
# Key Insights & Results:
# Demand Analysis: 
Demand variability is analyzed using time series decomposition. There is no clear upward or downward trend, but it have fluctuations.
Notable drop occured around early 2023, where demand falls close to 200k. After sharp dropdowns demand rebound quickly during early 2023.
overall we can observe a sharp dip and recovery twice a year. In August Months we had high Demand. and in February Month we had dropdown of                       Demand.<br>
# Bottlenecks    : 
The residual is flat.but in late 2023 we have an unusual spike.
because, The unusual spike is likely driven by changes in competitor pricing and weather conditions,possibly interacting with discount strategy.<br>
# ABC Analysis   :
we had 15 critical products out of 20 total products.so we again filtered the most critical products from the A category products.
And we have Top 6 such products that need more safety stock. so out of 15 products we need to maintain more safety stock for 6 products
to optimize the safety stock.<br>
# Recommendations: 
1.By our Analysis the A1 category products should be maintained more safety stock.
2.There are 15 critical products that should maintain more safety stock,but we extracted most critical products from that to optimize the safety                  stock.
                 3.If the Lead time is less,then we could optimize some more safety stock.
