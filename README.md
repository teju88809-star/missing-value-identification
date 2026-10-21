# missing-value-identification
Identified and analyzed missing values in the Titanic dataset using Python and Pandas. Calculated missing-value counts and percentages for each column, generated a summary report, and documented key findings as part of a Data Analytics task.
Missing Value Identification

Project Overview

This task focuses on identifying missing values in a dataset using Python and Pandas. The missing values are summarized by count and percentage to understand data quality before further analysis.

Objective

- Identify missing values in each column.
- Calculate the number and percentage of missing values.
- Generate a missing-value summary.
- Document findings and conclusions.

Tools and Technologies

- Python
- Pandas
- Jupyter Notebook / Google Colab

Dataset

Dataset: Titanic Dataset

The dataset contains passenger information and is used to demonstrate missing-value identification.

Methodology

1. Load the dataset using Pandas.
2. Inspect the dataset.
3. Count missing values using "isnull().sum()".
4. Calculate missing-value percentages.
5. Create a summary table.
6. Export the summary as a CSV file.

Key Findings

- Cabin contains a high proportion of missing values.
- Age contains some missing values.
- Embarked contains very few missing values.
- Missing data should be examined before cleaning or preprocessing.

Output

The task produces a missing-value summary containing:

- Column name
- Missing-value count
- Missing-value percentage

Conclusion

Missing-value identification is an important data-cleaning step. This analysis helps understand data completeness before performing further analysis or building machine-learning models.

Author

Data Analytics Task – Day 12
