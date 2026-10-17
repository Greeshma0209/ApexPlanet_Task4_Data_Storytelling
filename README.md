# ApexPlanet Task 4: Data Storytelling & Statistical Validation

## Project Overview
This project focuses on data storytelling and statistical hypothesis testing as part of the ApexPlanet Data Science Internship.

## Objectives
- Analyze the cleaned dataset.
- Summarize sales data by gender.
- Test whether the difference in average sales between male and female groups is statistically significant.
- Present findings and business recommendations.

## Dataset
- Rows: 1,000
- Columns: 13
- Data source: Cleaned dataset from Task 1.

## Hypothesis Testing
- **Null Hypothesis (H₀):** There is no significant difference in mean sales between male and female groups.
- **Alternative Hypothesis (H₁):** There is a significant difference in mean sales between male and female groups.
- **Statistical test:** Welch’s independent two-sample t-test.
- **Significance level:** 0.05
- **p-value:** 0.4950
- **95% Confidence Interval:** Approximately (-9,231.58, 19,079.85)

## Conclusion
The p-value is greater than 0.05. Therefore, we fail to reject the null hypothesis. The analysis does not provide sufficient statistical evidence of a difference in mean sales between the two groups.

## Project Files
- `ApexPlanet_Task4_Data_Storytelling_Statistical_Validation.pdf` — Presentation PDF
- `ApexPlanet_Task4_Hypothesis_Testing_Summary.csv` — Hypothesis testing summary
- Google Colab notebook — Task 4 analysis

## Tools Used
Python, Pandas, SciPy, Google Colab, GitHub.

## Internship
ApexPlanet Data Science Internship
