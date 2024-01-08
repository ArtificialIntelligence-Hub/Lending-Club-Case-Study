# Lending Club Case Study
> This project centers around the application of Exploratory Data Analysis (EDA) to tackle genuine business concerns in risk analytics within the banking and financial services sector. Through the utilization of EDA techniques, participants will delve into the intricacies of minimizing financial risks associated with lending. The primary objective is to offer a foundational understanding of how data analysis is leveraged to mitigate the risk of monetary losses and make informed decisions in the lending process.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Business Objectives:

As the largest online loan marketplace, the company aims to leverage EDA to identify and understand the factors contributing to loan defaults, known as credit loss. By distinguishing risky loan applicants, the company intends to minimize credit loss, enhance risk assessment, and optimize its lending portfolio. The overarching goal is to develop insights into driver variables behind loan default and utilize this knowledge for improved risk management.
- Project Background:

This project revolves around employing Exploratory Data Analysis (EDA) techniques to address real-world challenges in risk analytics within the consumer finance and lending domain. Focusing on a dataset from a leading online loan marketplace, the objective is to uncover patterns and indicators influencing loan default tendencies, enabling the company to make informed decisions and minimize financial risks.
- Business Problem:

The consumer finance company faces the dual challenge of approving loans to creditworthy applicants while avoiding potential defaults that could lead to financial losses. The business problem centers on identifying patterns within applicant profiles and loan attributes that can predict the likelihood of default, empowering the company to take strategic actions such as adjusting interest rates or denying loans to high-risk individuals.

- Dataset:

The dataset contains comprehensive information about past loan applicants, including their credit history, loan status, and repayment behavior. It covers the time period from 2007 to 2011 and provides insights into various scenarios, including fully paid loans, ongoing repayments, and charged-off loans. The dataset serves as the foundation for conducting EDA and extracting meaningful patterns to enhance risk assessment.
The dataset, spanning from 2007 to 2011, is provided for analysis. It includes details on loan applicants, their creditworthiness, and the outcome of their loan applications. A data dictionary is available to understand the meaning of each variable in the dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
## - Loan Status Comparison:

1. The number of defaulted loans is significantly lower (7 times) than fully paid loans.
2. Loans predominantly have a term of 36 months, as opposed to 60 months.
3. Interest rates cluster around 5-10 and 10-15, with a slight dip near 10.
4. Most loans are of high grade ('A' and 'B').
5. The majority of borrowers have work experience exceeding 10 years.
6. Many borrowers lack property ownership, relying on mortgage or rent.
7. About 50% of borrowers are verified or source-verified by the company.
8. Annual income distribution is left-skewed, indicating a prevalence of lower incomes.
9. Debt consolidation is the primary loan purpose, followed by credit card usage.
10. Borrowers mainly hail from large urban cities like California, New York, Texas, and Florida.
11. Debt-to-Income ratio (DTI) is concentrated in the 10-15 range.
12. Most borrowers have no record of public recorded bankruptcy.
13. Loans are predominantly approved in the last quarter of the year.
14. Loan approval rates exhibit an exponential increase over time.
## - Segmented Univariate Analysis:

1. Debt consolidation is the most popular loan purpose, with both the highest fully paid and defaulted loans.
2. Defaulted loans show a higher 75% value, indicating larger loan amounts are more likely to default.
3. The 60-month term carries a higher default risk, while the 36-month term is associated with a higher chance of full repayment.
4. Grade A and B loans primarily constitute the 36-month term, while grade B, C, and D loans dominate the 60-month term.
5. Loan status varies with DTI ratio, with higher DTI showing a higher number of defaulted loans.
6. Property ownership correlates with lower default rates.
7. Borrowers with annual income less than $50,000 are more likely to default.
8. Fully paid loans exhibit exponential growth over time, contrasting with defaulted loans.
9. Defaulted loan amounts increase with interest rates, declining after 17.5%.
10. Borrowers with 10+ years of experience are more likely to default but also more likely to fully pay the loan.
## - Risk Factors:
1. Grades represent risk, with higher grades associated with lower default rates.
2. Lower DTI ratios are linked to higher-grade loans, indicating lower risk.
3. Borrowers without a record of public recorded bankruptcy are considered safer choices for loan issuance
## - Recommendations:

1. Focus on DTI, grades, verification status, annual income, and public recorded bankruptcies.
2. Caution with borrowers outside large urban cities.
3. Attention to borrowers with annual incomes between  50,000 and 100,000.
4. Scrutiny of borrowers with public recorded bankruptcy, lower grades (E, F, G), and high Debt-to-Income values.
5. Consideration of borrowers with 10+ years of work experience.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy      - version 1.21.5
- pandas     - version 1.4.3
- seaborn    - version 0.11.2
- matplotlib - version 3.5.2
- plotly     - version 5.6.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.
- References - [Pandas](https://pandas.pydata.org/pandas-docs/version/1.4.3/) , [Numpy](https://numpy.org/doc/stable/user/index.html) , [Seaborn](https://pypi.org/project/seaborn/0.11.2/), [Matplotlib](https://pypi.org/project/matplotlib/3.5.2/), [Plotly](https://pypi.org/project/plotly/)


## Contact
Created by [@ArtificialIntelligence-Hub] - feel free to contact me!

## Team
- [Kunal Nimje](https://github.com/ArtificialIntelligence-Hub) - Group Facilitator
- [Mahesh Koilada]() - Team Member
