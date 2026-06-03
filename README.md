# Customer Churn Analysis Using Python

## Objective

This project focuses on customer churn analysis using Python, Pandas,
NumPy, Matplotlib, and Seaborn. A synthetic dataset containing 100,000
customer records was generated to study customer behavior and identify
churn patterns.

## Tools and Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook / Google Colab

## Dataset Description

The dataset includes: - Customer ID - Age - Gender - Tenure - Account
Balance - Credit Score - Estimated Salary - Number of Products - Active
Membership Status - Churn Status

Random values were generated using NumPy to simulate a realistic banking
customer dataset for analysis and visualization purposes.

## Project Workflow

### Data Generation and Preprocessing

-   Generated 100,000 synthetic customer records.
-   Checked for missing values.
-   Verified data types for consistency and quality.

### Descriptive Analysis

-   Analyzed distributions of:
    -   Age
    -   Account Balance
    -   Estimated Salary
    -   Credit Score
-   Examined customer churn distribution.

### Customer Behavior Analysis

-   Studied churn rates across different age groups.
-   Compared customer retention and customer exit patterns.

### Data Visualization

The following visualizations were created: - Bar Chart for churn
counts. - Histogram for age distribution. - Scatter Plot showing balance
versus churn status. - Correlation Heatmap for numerical variables.

### Issue Encountered

During heatmap generation, a `NameError` occurred because Seaborn was
not imported before calling `sns.heatmap()`.

**Solution:**

``` python
import seaborn as sns
```

Importing Seaborn before creating the heatmap resolves the issue.

## Features of the Project

-   Large-scale synthetic customer dataset generation.
-   Customer churn analysis.
-   Statistical data exploration.
-   Data visualization using Matplotlib and Seaborn.
-   Age-wise churn analysis.
-   Correlation analysis between customer attributes.

## Results and Findings

-   Customer churn was almost equally distributed between retained and
    exited customers.
-   Age-wise churn analysis showed slight variations among different age
    groups.
-   Visualizations helped identify customer behavior patterns.
-   Correlation analysis provided insights into relationships between
    numerical variables.

## Conclusion

This project demonstrates how customer data can be generated, processed,
analyzed, and visualized effectively using Python-based data science
tools. The analysis helps understand customer retention patterns and
provides a foundation for future predictive modeling and churn
prediction systems.
