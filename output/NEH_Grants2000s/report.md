# Data Profiling & Evidence Report: NEH_Grants2000s.csv

## 1. Dataset Overview
- **Filename:** `NEH_Grants2000s.csv`
- **Total Rows:** 9402
- **Total Columns:** 33

## 2. AI-Assisted Evidence-Based Insights
Here is the extracted information:

1. **Total Amount:**
   - **Original Amount:** 1.0
   - **Supplement Amount:** 0.9151003100695548
   - **Supplement Count:** 0.8026034370679531
   - **Participant Count:** 0.578549189772242

2. **Award Amount:**
   - **Approved Outright:** 0.41171166452691865
   - **Award Matching:** 1.0

3. **Supplement Amount:**
   - **Approved Outright:** 0.9151003100695548
   - **Supplement Count:** 0.8648981553889843
   - **Supplement Amount:** 1.0
   - **Supplement Count:** 0.669675525670967

4. **Supplement Values:**
   - **Supplement Amount:** 0.5996283817439071
   - **Supplement Count:** 0.669675525670967
   - **Supplement Count:** 1.0
   - **Supplement Count:** -0.027236143416549456

5. **Positive and Negative Values:**
   - **Positive Values:**
     - **CongressionalDistrict:** 0.02550877038547125
     - **ParticipantCount:** 0.06881638091645147
   - **Negative Values:**
     - **ApprovedOutright:** 0.030972012615112388
     - **AwardOutright:** 0.09618019257632353
     - **SupplementAmount:** 0.022653569086179787
     - **SupplementCount:** 0.023299147737213578

6. **Positive and Negative Pairs:**
   - **Positive Pairs:**
     - **ApprovedOutright and AwardOutright**
   - **Negative Pairs:**
     - **CongressionalDistrict and ParticipantCount**

This information provides a summary of the key financial and administrative data for a specific dataset.

## 3. Data Quality Overview
- **Number of duplicate rows in each columns:** Handled across 33 columns
- **Columns containing only one distinct value:** None detected
- **Columns with a high percentage of missing values:** Supplements
- **Columns that have mixed or inconsistent data type:** None detected
- **Columns that have identifier-like or extremely high-cardinality data type:** AppNumber, Supplements
- **Columns that might contain sensitive data based on column name:** None detected

## 4. Visualizations
![plot_01_missing_values.png](plots/plot_01_missing_values.png)

![plot_02_correlation.png](plots/plot_02_correlation.png)

![plot_03_dist_Congressio.png](plots/plot_03_dist_Congressio.png)

![plot_04_dist_YearAwarde.png](plots/plot_04_dist_YearAwarde.png)

![plot_05_dist_ApprovedOu.png](plots/plot_05_dist_ApprovedOu.png)

![plot_06_cat_ApplicantT.png](plots/plot_06_cat_ApplicantT.png)

![plot_07_cat_Organizati.png](plots/plot_07_cat_Organizati.png)

![plot_08_cat_InstState.png](plots/plot_08_cat_InstState.png)

![plot_09_scatterplot.png](plots/plot_09_scatterplot.png)

