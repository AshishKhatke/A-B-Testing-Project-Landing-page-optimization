A/B Testing Project: Landing Page Optimization
This project demonstrates A/B testing techniques to evaluate the effectiveness of a new landing page in increasing conversion rates. It combines statistical analysis using Python, data visualization in Tableau.showcasing a comprehensive approach to data-driven decision-making in marketing.

Project Objective
To determine whether a new landing page design leads to a higher conversion rate compared to the existing page using A/B testing methodology.

 Problem Statement
A company is considering replacing its existing landing page with a new version. Before rollout, they conducted an A/B test:

Control Group: Old landing page

Treatment Group: New landing page

Goal: Measure if the new page significantly increases conversions.

 Methodology
Data Collection

Source: Kaggle dataset
Fields: id, time, con-treat, page, converted

Data Cleaning

Removed inconsistencies (e.g., users in control but saw treatment page)

Ensured balanced test and control groups

Exploratory Data Analysis

Checked conversion distribution

Visualized group-wise performance

Statistical Testing

Z-Test for proportions using statsmodels

Tested null hypothesis: Conversion rates are equal

Visualization

Created interactive Tableau dashboard

Summary table, bar chart, and trend line comparisons

 Key Results
Metric	Control Group	Treatment Group
Conversion Rate	0.120%	0.118%
Z-Statistic	1.24	—
P-Value	0.2161	—
Result	Not Significant	—

Interpretation: With a p-value of 0.2161 (above the 0.05 threshold), we fail to reject the null hypothesis. There is no significant improvement in conversion rate with the new landing page.

 Tools & Technologies
Python: pandas, statsmodels, scipy

Tableau: For visualizing A/B testing outcomes

 Tableau Dashboard
 Contains:

Conversion rate by group (Bar chart)

Statistical summary (Z-score, p-value)

Conversion trends over time (Line chart)

 Conclusion
The new landing page does not lead to a statistically significant improvement in conversion rates.

Recommendation: Do not deploy the new landing page based on current test results.

 Connect with Me
LinkedIn: www.linkedin.com/in/ashishkhatke

GitHub: https://github.com/AshishKhatke

Email: aashukhatke007@gmail.com
