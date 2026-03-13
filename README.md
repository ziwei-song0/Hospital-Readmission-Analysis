# Hospital-Readmission-Analysis
Hospital Readmission Analysis: A Statistical Approach
This project employs statistical methods to conduct an in-depth analysis of 25,000 medical records of diabetic patients, aiming to identify the core risk factors leading to readmission within 30 days.

Data cleaning and preprocessing binarized the readmitted target variable. Outliers were handled and missing entries in medical_specialty were corrected, marked as “Unknown”.

Statistical Findings Chi-Square Test: Results indicate a significant association between missing medical_specialty status and readmission rate ($p < 0.001$), suggesting missing records may relate to specific admission processes or emergency scenarios.

Independent T-test: Confirmed a significant difference in time_in_hospital between readmitted and non-readmitted groups. Effect Size Analysis: Calculated Cohen's d for time_in_hospital was approximately 0.15, indicating a small effect size. This suggests that while statistically significant, length of hospital stay is not the sole decisive factor.

Feature Association Analysis
Numeric features were analyzed using heatmaps and correlation matrices. Boxplots visualized the distribution of different lengths of hospital stay and readmission risk.
