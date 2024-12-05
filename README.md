# Sagaya_Portfolio
Data Analyst Portfolio
## Published Click-to-Code (C2C) KPI for Stakeholder Review
1. Objective: Measure NLP performance on C2C charts and analyze the autocoding acceptance rate by coders, using metrics like Dx, HCC, DOS, Enc from/To and Provider.
2. Challenge: Inconsistencies in HCC categorization between NLP predictions and CRP.
3. Solution: Collaborated with the QA team to align NLP logic with CRP methodology for consistent metric calculation and prepared a detailed documentation with examples for future reference.
4. Impact: Improved efficiency in performance tracking and clearer insights for identifying areas of improvement.

## NLP Performance Analysis on Single Dx in Salesforce
1. Objective: Establish baseline error metrics (Precision/Recall) for HCC autocoding in single diagnosis charts.
2. Challenge: Precision/recall for a few charts were shown as BLANK.
3. Solution: Optimized SNF queries and tableau calculated field
4. Impact: Helped in making the decision whether to go with autocoding single Dx.

## KPI Dashboard Development
1. Objective: Create a comprehensive KPI dashboard for real-time stakeholder review.
2. Challenge: Overcame maintenance issues caused by 27 data connections in a single worksheet as informed by Manoj, So had to REWORK on all 27 data connections.
3. Solution: Explored one and came up with a solution to consolidated queries to streamline data connections, redesigned the dashboard following Tableau standards.
4. Impact: Successfully built a refreshed, responsive KPI dashboard that improved data accessibility and real-time decision-making.
Note: The Dashboard isn’t completely ready but has optimized few of the data connections and important metrics are ready.

## Analysis of Gender-Specific Code Contribution to False Positives (FP)
1. Objective: To understand the current impact of gender-specific codes on FP rates and assess potential reductions by removing these codes.
2. Challenge: was to label each code (74k ICD codes) as per their gender.
3. Solution: The data was scraped from ICD10data.com website for female and male specific codes which was then used to label all 74K codes.
4. Impact: Identified that removing gender-specific codes could reduce FPs by ~6-8%

## Hypothesis Testing on Precision/Recall Metrics with Gender-Specific Codes Removed
1. Objective: Evaluate the impact of excluding gender-specific FPs on P/R metrics for improved accuracy in production charts.
2. Challenge: was to label each code (74k ICD codes) as per their gender.
3. Solution: The data was scraped from ICD10data.com website for female and male specific codes which was then used to label all 74K codes.
4. Impact: Estimated a 2% reduction in FPs, supporting prioritization of gender-specific code adjustments in quarterly goals.

## P/R metrics on OODS codes FPs elimination
1. Objective: Evaluate the impact of excluding OODS (Out of DOS scopes) FPs on P/R metrics for improved accuracy in production charts.
2. Challenge: Flatten each code (ie FPs, TPs and FNs) and label them appropriately .
3. Solution:Optimized the query.
4. Impact: Estimated a 5% reduction in FPs, supporting prioritization of OODS projects in upcoming quarters.

## Shortlisted NEW PR projects
1. Objective: To shortlist a diverse set of projects for PR (Pull Request) runs to evaluate the performance of NLP developments and to get rid of older PR Inactive projects.
2. Challenge: was to shortlist projects from different coding types, code capture methodology etc.
3. Solution:Shortlisted projects based on the client and their contribution to overall Project volume.
4. Impact: 
  Minimize potential bias in testing datasets.
  Detects changes in Precision/Recall metrics effectively.
  Ensure diverse testing scenarios, reflecting real-world complexities.
