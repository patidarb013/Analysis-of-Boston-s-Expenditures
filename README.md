# City of Boston Expenditure Analysis
# Project Overview
This project analyzes the City of Boston’s financial expenditures using data from the Checkbook Explorer dataset. The dataset, spanning from July 2011, contains transaction details that provide insights into spending patterns, vendor relationships, and budget allocation across different departments. The goal is to enhance transparency, optimize budget planning, and forecast future spending trends.

# Dataset Information
1. Source: City of Boston - Checkbook Explorer
2. Rows: 111,905
3. Columns: 16
4. Key Fields: Voucher, Vendor Name, Account Description, Department Name, Fiscal Year, Monetary Amount

# Business Questions Addressed
1. What are the main spending categories over the years?
2. Are there seasonal trends in expenditure?
3. Which departments spend the most and the least?
4. What is the relationship between vendor categories and expenditures?
5. Can we forecast future spending based on historical data?

# Methodology and Techniques
## Exploratory Data Analysis (EDA)
1. Data Cleaning: Checked missing values, formatted dates, removed redundant columns.
2. Visualizations: Histograms, line plots, bar charts, and box plots to analyze spending distribution.
3. Correlation Analysis: Heatmaps to identify relationships between variables.

## Predictive Models Used
1. ARIMA: Forecasts future spending trends.
2. Decision Trees: Identifies key spending categories and vendor relationships.
3. K-Means Clustering: Groups departments based on spending patterns.

# Key Findings
1. Spending Trends: No strong seasonal trend, but certain months like October show spikes.
2. Top Departments: Boston Public Schools had the highest expenditures.
3. Vendor Concentration: A few vendors account for a significant portion of city spending.
4. Forecasting Feasibility: ARIMA provides reasonable predictions, aiding budget planning.

# Tools & Libraries Used
1. Python Libraries: pandas, matplotlib, seaborn, statsmodels, scikit-learn
2. Development Environment: Jupyter Notebook / Anaconda

# Recommendations
1. Optimize budget allocations based on spending patterns.
2. Use forecasting models for better financial planning.
3. Strengthen vendor management strategies to control costs.
4. Implement data-driven policies for greater transparency and accountability.

# Contributors
Bhavesh Patidar
Tanishq Bakliwal

## Advisor: Prof. Daya Rudhramoorthi

# References
[City of Boston - Checkbook Explorer Dataset](https://data.boston.gov/dataset/checkbook-explorer)
[Machine Learning Mastery - ARIMA](https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/)
[Scikit-learn - Decision Trees](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
