# Customer-Churn-Telecom-Data-Analysis
Exploratory Data Analysis - Customer Churn in Telecom<br>
In this repository, I have taken Customer Churn in Telecom Industry data from Kaggle and I have done:

1. Data Integration: <br>If the analysis involves data from multiple sources (e.g., customer demographics, billing information, service usage), this step would combine these sources into a unified dataset for a holistic view of customer behavior.<br>

2.Data Cleaning: <br>Addressing data quality issues is crucial. This might include:<br>
Handling inconsistencies in data formats (e.g., dates, phone numbers)<br>
Correcting data entry errors or typos<br>
Dealing with invalid or illogical values in customer attributes<br>

3.Missing Value Handling:<br>Telecom datasets often have missing values. Strategies in the notebook might include:<br>
Imputation using methods like mean, median, or mode for numerical features.<br>
Filling missing categorical values with the most frequent category or a separate "unknown" category.<br>
Dropping rows or columns with excessive missing data if appropriate and justified.<br>

4. Duplicate Removal:<br>Identifying and removing duplicate customer records ensures accurate representation and prevents bias in the analysis.<br>
5. Outlier Detection and Removal:<br> This step aims to identify and handle unusual customer behavior or data points that could skew the analysis. Techniques might include:<br>
Visual inspection using box plots or scatter plots to identify extreme values.<br>
Statistical methods like z-score or IQR to detect outliers based on data distribution.<br>
Domain expertise to determine if outliers represent legitimate customer behavior or data errors.<br>

6. Data Normalization: <br>While not always necessary for EDA, if the data will be used for machine learning models, normalization may be applied to numerical features to improve model performance. Common methods include:<br>
Min-max scaling to bring values within a specific range (e.g., 0 to 1).<br>
Standardization (z-score normalization) to center data around a mean of 0 and standard deviation of 1.<br>

7. Data Visualization:<br> Visualizations are key to gaining insights into customer churn patterns. The notebook might include:<br>
Histograms and density plots to understand the distribution of customer attributes.<br>
Bar charts to compare churn rates across different demographics or service plans.<br>
Line charts to visualize trends in churn over time.<br>
Scatter plots to explore relationships between numerical features and churn.<br>
Heatmaps to visualize correlations between variables.<br>

Feel free to download the code and data.
