A/B Testing Project: Landing Page Optimization

This project demonstrates A/B testing techniques to evaluate the effectiveness of a new landing page in increasing conversion rates. It combines statistical analysis using Python and data visualization in Tableau, showcasing a comprehensive approach to data-driven decision-making in marketing.

Project Objective

To determine whether a new landing page design leads to a higher conversion rate compared to the existing page using A/B testing methodology.

Problem Statement

A company is considering replacing its existing landing page with a new version. Before the rollout, they conducted an A/B test:

Control Group: Old landing page
Treatment Group: New landing page
Goal: Measure whether the new page significantly improves conversion rates.

Methodology

Data Collection

Source: Kaggle dataset

Fields: id, time, con_treat, page, converted

Data Cleaning

Removed inconsistencies (e.g., users in the control group who saw the treatment page)

Ensured a balanced distribution between test and control groups

Exploratory Data Analysis

Checked overall conversion rate distributions

Visualized conversion performance by group

Statistical Testing

Performed Z-Test for Proportions using statsmodels

Null Hypothesis: Conversion rates are equal between the two groups

Alternative Hypothesis: Conversion rates differ

Visualization

Created an interactive Tableau dashboard

Included summary table, bar chart (conversion rates), and trend line over time

Interpretation: With a p-value of 0.2161 (above the 0.05 threshold), we fail to reject the null hypothesis. The new landing page does not show a statistically significant improvement in conversions.

Tools and Technologies Used

Python: pandas, statsmodels, scipy
Tableau: Used for visualizing A/B test results

Tableau Dashboard Overview

The Tableau dashboard includes:

Conversion rate by group (Bar chart)

Z-score, P-value, and statistical result (Summary table)

Conversion trends over time (Line chart)


Conclusion and Recommendation

The A/B test results show no statistically significant difference in conversion rates between the old and new landing pages.

Recommendation: Based on the current results, the company should not deploy the new landing page.


 Connect with Me
LinkedIn: www.linkedin.com/in/ashishkhatke

GitHub: https://github.com/AshishKhatke

Email: aashukhatke007@gmail.com
