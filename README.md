# An easy way to guarantee the quality of your data

In this series, we'll delve into the world of data analytics and explore real-world scenarios to learn how data quality plays a pivotal role in making informed decisions. Today, we start with the fundamental question: What is data quality and why does it matter?

"Data quality is defined as data's dependability, accuracy, consistency, and completeness."

Consider your data to be the foundation of a building. High data quality ensures the trustworthiness of your insights and judgements, much as a good foundation provides the durability of a construction. Poor data quality can lead to incorrect conclusions, ill-advised initiatives, and missed opportunities.

Let's have a practice to identify your data quality, Here is a sample case study you may consider to learn. Case Study: Data of Mall Customers

Scenario:
Imagine you are working for a shopping mall and have access to a dataset containing customer information, including CustomerID, Gender, Age, Annual Income, and Spending Score. Your task is to perform a comprehensive analysis to better understand your customers and tailor your marketing strategies accordingly. However, the dataset has some issues that need to be addressed.

Problem:
Upon inspecting the dataset, you discover several data quality challenges:

1. Missing Values: Some rows in the dataset have missing values, particularly in the Annual Income column.
2. Duplicate Entries: The dataset contains duplicate customer entries, which can skew your analysis.
3. Outliers: There appear to be outliers in the Spending Score column that might affect your segmentation.

To address these challenges and ensure the quality of your analysis, you follow these steps:

1. Data Profiling: Using Python, you perform data profiling on the dataset. You calculate summary statistics for each column, including mean, median, and standard deviation. Additionally, you identify the percentage of missing values in the Annual Income column and explore the distribution of data points in the Age and Spending Score columns.
2. Data Cleaning: Armed with insights from data profiling, you start cleaning the dataset. You handle missing values in the Annual Income column by imputing them with the median value. To deal with duplicate entries, you remove any repeated CustomerID records. To address outliers in the Spending Score column, you apply appropriate outlier detection and handling techniques.
