# School District Analysis

## Project Overview

Provide insight on performance trends from standardized testing across the city school system. Use these insights to help make data-backed decisions on funding strategy in upcoming discussion with school board and super intendant.

## Results

**Note:** In each of the comparisons below v1 is our baseline with all data and v2 we have replaced all Thomas High School 9 grade data with NaN.

### How is the district summary affected?
 - Average Math Score decreased from 79.0 in v1 to 78.9 in v2
 - Average Reading Score was flat at 81.9 in v1 to v2
 - % Passing Math decreased from 75% in v1 to 74.8% in v2
 - % Passing Reading decreased from 86% in v1 to 85.7%
 - % Overall Passing decreased from 65% in v1 to 64.9% in v2

**v1 District Summary:**

![district_summary_df_v1](https://github.com/krisnagoda/School_District_Analysis/blob/30196bcd846e22f4fb2d6d8c6c987ef072ec4449/Resources/distict_summary_df_v1.png)

**v2 District Summary:**

![district_summary_df v2](https://github.com/krisnagoda/School_District_Analysis/blob/698fc18429a64debdb90dba5e9ed939710aa56d9/Resources/distict_summary_df_v2%20(THS%209th%20NaN).png)

### How is the school summary affected?

Thomas High School had changes in the following scores and passing percentages:
 - Average Math Score decreased from 83.42 in v1 to 83.35 in v2
 - Average Reading Score increased from 83.85 in v1 to 83.90 in v2
 - % Passing Math decreased from 93.27% in v1 to 66.91% in v2
 - % Passing Reading decreased from 97.31% in v1 to 69.66%
 - % Overall Passing decreased from 90.95% in v1 to 65.08% in v2

**v1 School Summary:**

![per_school_summary_df_v1](https://github.com/krisnagoda/School_District_Analysis/blob/a66409c43aa88b304ae5fc8475a60c4e37af2f42/Resources/per_school_summary_df_v1.png)

**v2 School Summary:**

![per_school_summary_df_v2](https://github.com/krisnagoda/School_District_Analysis/blob/a66409c43aa88b304ae5fc8475a60c4e37af2f42/Resources/per_school_summary_df_v2.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The changes to the Thomas High School 9 grade data caused a significant decline in their % Passing Math, % Passing Reading, and % Overall Passing scores. Placing Thomas High School in the lower quartile with other schools with much larger student populations.  

### How does replacing the ninth-grade scores affect the following:

  **Math and reading scores by grade**
  
  **v1 Math & Reading Scores by Grade**
  
  ![Resources/math_reading_scores_by_grade_v1.png](https://github.com/krisnagoda/School_District_Analysis/blob/175d42c6b9713545bf6243734b6343f234a81af1/Resources/math_reading_scores_by_grade_v1.png)
  
  **v2 Math & Reading Scores by Grade**
  
  ![Resources/math_reading_scores_by_grade_v1.png](https://github.com/krisnagoda/School_District_Analysis/blob/175d42c6b9713545bf6243734b6343f234a81af1/Resources/math_reading_scores_by_grade_v2.png)
  
  **Scores by school spending**
  
  **Spending Summary v1**
  
  ![spending_summary_df_v1](https://github.com/krisnagoda/School_District_Analysis/blob/671a551373ec25b165b942fb99a9c359d517147a/Resources/spending_summary_df_v1.png)
  
  **Spending Summary v2**
  
  ![spending_summary_df_v2](https://github.com/krisnagoda/School_District_Analysis/blob/671a551373ec25b165b942fb99a9c359d517147a/Resources/spending_summary_df_v2.png)
    
  **Scores by school size**
  
  Text and screenshots here
  
  **Scores by school type**
  
  Text and screenshots here

## Summary

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
