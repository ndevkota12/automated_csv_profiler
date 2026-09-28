# Data Profiling & Evidence Report: Provisional COVID-19 data.csv

## 1. Dataset Overview
- **Filename:** `Provisional COVID-19 data.csv`
- **Total Rows:** 45565
- **Total Columns:** 14

## 2. AI-Assisted Evidence-Based Insights
1. **Distribution Finding:** The column `crude_COVID_rate_ann` contains numerical values and is missing only for `data_as_of=350`. This suggests that the `CRUD_COVID_RATE` and `AA_COVID_RATE` values fluctuate over time and across different dates, indicating potential variability in the underlying data.

2. **Categorical Finding:** The `Categorical` column `aa_COVID_rate_ann` has a high percentage of missing values (`pct_missing`). This suggests that there are missing values in this categorical data, which can indicate potential issues or missing values in the data. It's important to investigate further to ensure that the data is accurate and that the missing values are handled appropriately.

3. **Relationship Finding:** The relationship between `CRUD_COVID_rate_ann` and `aa_COVID_rate` is quite strong. This suggests a positive correlation, indicating that as the value in `CRUD_COVID_rate_ann` increases, the value in `aa_COVID_rate` is also likely to increase. This relationship can be significant for analyzing the impact of changes in the original data on the new values.

4. **Relationship with New Data:** The strong positive relationship between `CRUD_COVID_rate_ann` and `aa_COVID_rate` suggests that the data has significant potential for further analysis. However, this relationship should be treated with caution, as it may suggest a non-linear relationship that needs to be confirmed through more detailed analysis.

5. **Strongest Positive Pair:** The relationship between `crude_COVID_rate` and `aa_COVID_rate` is strong and positive. This suggests that as the value in `crude_COVID_rate` increases, the value in `aa_COVID_rate` is also likely to increase. This positive relationship can be useful for understanding how changes in `CRUD_COVID_rate` influence `AA_COVID_rate`.

6. **Strongest Negative Pair:** There are no significant negative relationships between the columns. This indicates that the data is relatively uncorrelated, which is typically desirable for analysis.

7. **Strongest Negative Value:** The value of `aa_COVID_rate` is 0. This suggests that there may be no significant negative values in the data, but it is not definitively confirmed. If the data is missing or incomplete, the actual value is not available.

8. **No Missing Values:** All the columns except for `aa_COVID_rate` and `data_as_of` have valid values, indicating that the data is not missing any important values. This ensures that the analysis is not influenced by missing data.

9. **No Skipped Rows:** The code snippet provided does not include any missing values or skips, which means the data is complete and not missing any entries. This is crucial for accurate analysis.

10. **No Categorical Data:** The column `aa_COVID_rate` is a categorical data, but the code snippet does not include any values for `aa_COVID_rate` or any missing data. This suggests that no categorical data is available for analysis.

11. **No Numerical Data:** The data is provided as a combination of numerical values and missing values, which is common in such contexts. However, the code snippet does not include any missing values or numerical data. This suggests that no numerical data is available for analysis.

12. **No Strong Negative Relationships:** There are no significant negative relationships between the columns `CRUD_COVID_rate` and `AA_COVID_rate` or between the columns `CRUD_COVID_rate` and `aa_COVID_rate`. This indicates that the data has no significant negative relationships, which is expected in a complete dataset.

13. **No Strong Positive Relationships:** There are no significant positive relationships between the columns `CRUD_COVID_rate` and `aa_COVID_rate` or between the columns `crude_COVID_rate` and `aa_COVID_rate`. This suggests that the data has no significant positive relationships, which is expected in a complete dataset.

## 3. Data Quality Overview
- **Number of duplicate rows in each columns:** Handled across 14 columns
- **Columns containing only one distinct value:** data_as_of
- **Columns with a high percentage of missing values:** pct_change_wk, pct_diff_wk, footnote
- **Columns that have mixed or inconsistent data type:** None detected
- **Columns that have identifier-like or extremely high-cardinality data type:** None detected
- **Columns that might contain sensitive data based on column name:** None detected

## 4. Visualizations
![plot_01_missing_values.png](plots/plot_01_missing_values.png)

![plot_02_correlation.png](plots/plot_02_correlation.png)

![plot_03_dist_COVID_pct_.png](plots/plot_03_dist_COVID_pct_.png)

![plot_04_dist_pct_change.png](plots/plot_04_dist_pct_change.png)

![plot_05_dist_pct_diff_w.png](plots/plot_05_dist_pct_diff_w.png)

![plot_06_cat_Jurisdicti.png](plots/plot_06_cat_Jurisdicti.png)

![plot_07_cat_Group.png](plots/plot_07_cat_Group.png)

![plot_08_cat_footnote.png](plots/plot_08_cat_footnote.png)

![plot_09_scatterplot.png](plots/plot_09_scatterplot.png)

