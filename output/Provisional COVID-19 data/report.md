# Data Profiling & Evidence Report: Provisional COVID-19 data.csv

## 1. Dataset Overview
- **Filename:** `Provisional COVID-19 data.csv`
- **Total Rows:** 45565
- **Total Columns:** 14

## 2. AI-Assisted Evidence-Based Insights
Certainly! Here are 5 to 8 evidence-based insights derived from the provided dataset summary, descriptive statistics, and relationships.

1. **At least one data-quality finding:**
    - The dataset contains a significant number of missing values (e.g., 14 columns with missing percentages). This indicates potential data quality issues such as incomplete or unreliable data.

2. **Distribution of unique categories in the "data_as_of" column:**
    - The "data_as_of" column contains unique categories, which is a positive sign indicating a clean and well-distributed dataset. However, the distribution of unique categories can be misleading due to the presence of the "Jurisdiction_Residence" column.

3. **Categorical columns with high percentage of missing values:**
    - The "data_as_of" column contains unique categories, but the "Jurisdiction_Residence" column contains unique categories as well. This suggests that some of the categorical columns might contain a high percentage of missing values due to overlap with the "Jurisdiction_Residence" column.

4. **Correlation matrix for "COVID_pct_of_total":**
    - The correlation coefficient between "COVID_pct_of_total" and "pct_change_wk" is 0.9919. This high correlation coefficient indicates a strong positive correlation. However, the value of 0.9919 suggests that the relationship is more complex and may require further analysis to understand the underlying patterns.

5. **Relationships between the variables:**
    - The dataset reveals that there is a positive correlation between "pct_change_wk" and "CRude_COVID_rate", with a correlation coefficient of 0.9918. This indicates that as "pct_change_wk" increases, "CRude_COVID_rate" also increases, which is a positive trend. However, it also shows a negative correlation between "pct_change_wk" and "aa_COVID_rate", with a correlation coefficient of -0.1555, suggesting that as "pct_change_wk" decreases, "aa_COVID_rate" decreases.

6. **Strategic recommendation:**
    - For improved data quality and accuracy, a thorough reprocessing and cleaning of the dataset should be conducted. Investigating the potential impact of these missing values and the high correlation coefficients on the "pct_change_wk" variable would provide valuable insights for developing effective data cleaning and preprocessing strategies.

By addressing these findings, organizations can ensure that their data-driven decisions are informed by accurate and reliable data, leading to more informed and effective decision-making processes.

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

