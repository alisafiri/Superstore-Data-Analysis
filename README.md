📊 Superstore Sales Analysis

Comprehensive Exploratory Data Analysis (EDA) using Python, Pandas, and Matplotlib

📌 Overview

This project performs a complete exploratory data analysis (EDA) on the Superstore Sales dataset.
The objective is to uncover business insights, identify high-profit and low-profit segments, evaluate discount strategies, analyze customer behavior, and understand sales trends across time and regions.

🧹 Data Cleaning & Preparation

The following steps were performed before analysis:

- Converted Order Date and Ship Date to datetime format
- Created new calculated features:
 - Shipping Days
 - Unit Price
 - Year
 - Month

- Verified missing values (none found)
- Sorted data by order date
- Basic statistical summary of Sales, Profit, Discount, Quantity, and others

🔍 Exploratory Data Analysis (EDA)

1. Sales Analysis
- Top-performing categories and sub-categories
- Monthly and yearly sales trends
- City/state/region-level sales performance

2. Profitability Analysis
- Most profitable categories
- Least profitable (loss-making) sub-categories
- Identifying products with high sales but low profit

3. Discount Analysis
- Relationship between discount percentage and profit
- Impact of heavy discounting on overall performance

4. Shipping Analysis
- Distribution of shipping days
- Correlation between long shipping times and lower profits

5. Customer Insights
- Profit contribution by customer segment
- Customer purchase behavior patterns

📊 Visualizations

All charts are stored inside the images/ directory.

Included plots:

- Monthly Sales Trend
- Profit by Category
- Shipping Days vs Profit
- Regional Sales
- Sales Share by Catefory

📈 Key Insights

Some of the important findings from the analysis:

- Technology is the most profitable category, although Office Supplies has higher sales volume.
- Several sub-categories in Furniture generate negative profit → pricing strategy issues.
- High discounts strongly reduce profit, especially in Furniture products.
- Shipping times longer than 5 days tend to correlate with lower profitability.
- Sales peak during Q4 (seasonal behavior).

🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

🚀 How to Run the Project

1. Clone the repository
2. Install the required libraries
3. Run the notebook:
jupyter notebook notebooks/superstore_analysis.ipynb

📬 Contact

If you have questions or want to collaborate, feel free to reach out.