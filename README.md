# Personality-Changes-Associated-with-Organ-Transplants
This project gave me a great opportunity to combine data science skills with an intriguing medical and psychological question, exploring how patient demographics and awareness might relate to reported personality changes post-transplant.

#✅ STEP 1: Load and Inspect the Data

Basic checks: .info() for column types and missing values

.describe() for distributions (e.g., age)

.value_counts() for categorical variables (organ type, gender, etc.)

#✅ STEP 2: Demographic Breakdown

Age Distribution: Histogram overall & comparison by organ (Heart vs Other)

Gender & Ethnicity: Bar plots by organ type

Education & Marital Status: Proportion of college graduates and married patients per organ group

#✅ STEP 3: Awareness and Fear of Personality Changes

Bar plot showing % of patients who heard about personality changes vs % who feared them, grouped by organ type

Cross-analysis with crosstab/groupby to see if hearing about personality changes increases fear, and if fear is linked to number of reported changes

#✅ STEP 4: Number of Personality Changes (Excluding Physical Attributes)

Histogram of Num_Personality_Changes

Boxplot comparing changes by organ type

#✅ STEP 5: Save Visual Summary

Created a visual summary of key findings for quick insights
