# Part 1: University-Predictive-Enrollment-Dynamics-Project

## Project Overview
This project, titled "Decoding Enrollment Dynamics: Unveiling Trends and Drivers of Student Matriculation," provides a comprehensive analysis of student enrollment trends and factors influencing matriculation decisions at Albers over the past four years. Our team utilized data analysis and predictive modeling to understand the dynamics of student enrollment and to forecast future enrollment patterns.

## Key Findings
Document : https://github.com/Amrapali03/University-predictive-Enrollment-Dynamics-Project/blob/main/Decoding%20Enrollment%20Trends%20for%20Matriculation.pdf

### Trends
A general decline in total student enrollment over the past four years, with a notable increase in the number of students deciding against enrollment after initial acceptance.
Specific programs such as Masters and MBA have seen significant declines, while Certificate programs have maintained relatively steady enrollment numbers.


### Influencing Factors
Demographic Factors: Females are slightly more likely to enroll than males. The majority of enrollments are individuals aged 25-34. There is a marked underrepresentation of Black students, suggesting a need for increased diversity and inclusion efforts.
Academic Factors: Medium to high GPAs are prevalent among enrolled students across various programs, with suggestions for programs to consider applicants with a broader range of GPAs.

## Insights from Data Analysis
Key insights include the low actual enrollment rate of 12.26%, despite a higher rate of acceptance decisions.
Financial aids and scholarships are critical, particularly in the MBA program, where increasing support could boost matriculation rates.

## Predictions
Using a Time Series Model (SARIMAX), we forecasted application outcomes for 2024 and 2025 across MBA, Masters, and Certificate Programs. The predictions aim to help in planning and resource allocation for upcoming academic sessions.

## Models Used
Decision Tree Model: Identified factors influencing the likelihood of matriculation, such as location (applicants from WA), scholarship availability, and referral sources.
Random Forest Model: Focused on predicting enrollments in main programs for the next two years.
Time Series Forecasting: Utilized to predict application numbers for various programs, aiding in strategic planning and operational adjustments.

## Conclusion
The analysis provided by the "Decoding Enrollment Dynamics" project aids in understanding the complex factors affecting student matriculation and offers actionable insights for enhancing program attractiveness and student diversity. These findings and predictions serve as a valuable resource for strategic decision-making in academic program management and marketing.

Appendix
Additional details, including assumptions of program categories, data cleaning methodologies, and model configurations, are provided to ensure transparency and reproducibility of the analysis.

# Part 2: Influence of Unfunded-Aid on Enrollment


Unfunded Aid Project
## Overview
The Unfunded Aid Project is an analytical study conducted to understand the impact of unfunded aid on student enrollment decisions at a higher education institution. The primary goal is to determine if offering unfunded aid at the time of admission significantly influences applicants to accept and enroll. This project leverages a dataset from 2020 to explore enrollment patterns based on various demographics such as citizenship, gender, and race.

## Hypothesis
The project is based on the hypothesis that applicants who receive an unfunded aid offer when they receive their letter of admission are more likely to accept and enroll.

## Key Findings
Document: https://github.com/Amrapali03/Influence-of-Unfunded-Aid-on-Enrollment/blob/main/Unfunded%20Aid%20Project.pdf
### Impact by Citizenship:

Permanent Residents are more likely to enroll even without aid.
International students are significantly influenced by aid (50.4%).
U.S. citizens are likely to enroll even without aid.
Impact by Gender and Race:

United States Citizens:
More females enrolled without aid.
White individuals enrolled more even without aid.
Asian-Asian American enroll more when given aid.
International:
More males enrolled without aid.
Asians tend to apply more when given aid.
Black individuals applied almost similarly with or without aid.
Permanent Residents:
Both females and males enrolled with or without aid, but females with aid are slightly more likely to enroll.
White individuals enroll more when provided aid.
Asians enroll more when given aid.
Black individuals enroll more with aid.

### Scholarship Tier Analysis:

Various scholarship tiers were analyzed, showing that higher levels of aid (G9, G10) were mostly awarded to international students, while lower levels (G1, G2, G3) had more domestic recipients.

### Program-Specific Insights:

Programs such as the Accounting Professional (MPAC Advanced) and Counseling (Clinical Mental Health Counseling specialization) showed high acceptance rates with aid.
Statistical Significance:

The Chi-square test of independence confirmed a significant association between receiving aid and accepting the offer, with a Chi-square statistic of 46.39 and a P-value of 9.6888e-12.

## Methodology
Data Analysis: The analysis included examining enrollment patterns based on demographic variables (citizenship, gender, race) and the amount of aid received.
Statistical Testing: The Chi-square test of independence was used to determine the statistical significance of the association between receiving aid and enrollment decisions.
Visualization: Data visualization tools were employed to illustrate the impact of unfunded aid across different demographics.

## Insights and Recommendations
Offering unfunded aid significantly impacts international students' enrollment decisions.
Domestic students, particularly females and white individuals, are more likely to enroll without aid.
Higher aid levels are effective in attracting international students, while lower aid levels suffice for domestic students.
The institution could strategically allocate aid to maximize enrollment, focusing on higher aid for international applicants and targeted lower aid for domestic applicants in specific programs.

## Conclusion
The Unfunded Aid Project highlights the importance of financial aid in influencing enrollment decisions. The analysis provides valuable insights for the institution to refine its aid allocation strategy, ensuring that financial aid offers effectively attract and retain students across diverse demographics.


