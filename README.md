# Bank-analytics-finance-domain
Finance Domain | Bank Loan Analysis.
This project is an in-depth analysis of bank loan data, aimed at uncovering key insights in to loan issuance trends, customer credit behaviour, and financial performance metrics. The analysis combines SQL, Tableau, Excel and Power BI for data extraction and transformation into data visualization,providing a comprehensive overview of loan trends over time, the financial health of different customer segments and risk assessment across various loan grades. This projects serves as a crucial tool for understanding the dynamics of loan portfolios and guiding strategic decision-making in the financial sector.

Project Goal
-:The primary objective was to transform key performance indicators (KPIs) into meaningful result using SQL. The aim was to create clear and comprehensive result that addressed the specified KPIs, making it easy for everyone to understand the company’s performance. This goal challenged me to refine my SQL data analysis skills and effectively communicate database, thereby facilitating better-informed decision-making based on the data.

KPIs
1)Year wise loan amount Stats
2)Grade and sub grade wise revol_bal
3)Total Payment for Verified Status Vs Total Payment for Non-Verified Status
4)State wise and month wise loan status
5)Home ownership Vs last payment date stats
Analysis

In preparing our dataset for analysis, performed process of cleaning and transforming raw data prior to processing and analysis, the initial and crucial step involved merging the two datasets. This was followed by meticulous data cleaning to ensure the integrity and relevance of the information. Here are the key actions taken:

1. Merging Datasets: Combined Finance_1 and Finance_2 using the common ID column.

2. Handling Missing (Empty or Null) Values: Identified and addressed any missing data to prevent biases. In cases where the proportion of missing data was high and imputation was not feasible, removed those columns or records to maintain data quality.

Such as:

i. Null value settled: emp_length (here n/a to NA)

ii. Null value: revol_util, last_pymnt_d, next_pymnt_d, last_credit_pull_d

3. Removed Duplicate or Irrelevant Column: Removed any columns that were exact duplicates of others to avoid redundancy. Eliminated columns that did not contribute valuable information to the analysis or were outside the scope of the project goals.

Such as: emp_title, Pymnt_plan, desc, purpose and title

4. Removing Redundant Columns: Removed columns that were deemed redundant or provided no additional value to the analysis.

Such as: Pymnt_plan

5. Data Consistency: Ensured consistency in data formats and units across the dataset.

These data cleaning steps were essential in making sure the dataset was devoid of redundancies, irrelevant data, and missing values. This meticulous preparation paved the way for a more precise and meaningful analysis of the selected key performance indicators.


The primary objective was to transform key performance indicators (KPIs) into meaningful result using SQL. The aim was to create clear and comprehensive result that addressed the specified KPIs, making it easy for everyone to understand the company’s performance. This goal challenged me to refine my SQL data analysis skills and effectively communicate database, thereby facilitating better-informed decision-making based on the data.

KPIs
Year wise loan amount Stats
Grade and sub grade wise revol_bal
Total Payment for Verified Status Vs Total Payment for Non-Verified Status
State wise and month wise loan status
Home ownership Vs last payment date stats
Analysis

In preparing our dataset for analysis, performed process of cleaning and transforming raw data prior to processing and analysis, the initial and crucial step involved merging the two datasets. This was followed by meticulous data cleaning to ensure the integrity and relevance of the information. Here are the key actions taken:

1. Merging Datasets: Combined Finance_1 and Finance_2 using the common ID column.

2. Handling Missing (Empty or Null) Values: Identified and addressed any missing data to prevent biases. In cases where the proportion of missing data was high and imputation was not feasible, removed those columns or records to maintain data quality.

Such as:

i. Null value settled: emp_length (here n/a to NA)

ii. Null value: revol_util, last_pymnt_d, next_pymnt_d, last_credit_pull_d

3. Removed Duplicate or Irrelevant Column: Removed any columns that were exact duplicates of others to avoid redundancy. Eliminated columns that did not contribute valuable information to the analysis or were outside the scope of the project goals.

Such as: emp_title, Pymnt_plan, desc, purpose and title

4. Removing Redundant Columns: Removed columns that were deemed redundant or provided no additional value to the analysis.

Such as: Pymnt_plan

5. Data Consistency: Ensured consistency in data formats and units across the dataset.

These data cleaning steps were essential in making sure the dataset was devoid of redundancies, irrelevant data, and missing values. This meticulous preparation paved the way for a more precise and meaningful analysis of the selected key performance indicators.

