# Personal Finance Analysis – India

A data analysis project on the personal finance and spending habits of 20,000 individuals in India. It compares disposable income, rent and potential savings by **city tier** and **occupation**.

## Table of contents
- [About the dataset](#about-the-dataset)
- [Project goal](#project-goal)
- [Tools used](#tools-used)
- [Methodology](#methodology)
- [Key findings](#key-findings)
- [Repository contents](#repository-contents)
- [Licence and credits](#licence-and-credits)

## About the dataset

The dataset comes from Kaggle. It holds financial and demographic data for 20,000 individuals in India, covering:

| Group | Fields |
|---|---|
| Income & demographics | Income, Age, Dependents, Occupation, City_Tier |
| Monthly expenses | Rent, Loan_Repayment, Insurance, Groceries, Transport, Eating_Out, Entertainment, Utilities, Healthcare, Education, Miscellaneous |
| Financial goals & savings | Desired_Savings_Percentage, Desired_Savings, Disposable_Income |
| Potential savings | Estimated potential savings for Groceries, Transport, Eating_Out, Entertainment, Utilities, Healthcare, Education and Miscellaneous |

## Project goal

Analyse the financial parameters in the dataset by city tier and by occupation.

## Tools used

- **Power Query (Power BI)** for editing and cleaning the data
- **Power BI** for analysis and visualisation

## Methodology

1. **Ask:** define the problem, which is to analyse the data by city tier and occupation.
2. **Prepare:** source the data from Kaggle and check its licence.
3. **Process:** clean the data in Power Query. The `Dependents` column was changed from number to string, and the cleaned data was checked before analysis.
4. **Analyse:** explore the data through visualisations in Power BI.

## Key findings

- **Disposable income:** Tier 3 is highest, followed by Tier 2. Tier 1 is lowest.
- **Rent:** professionals pay the most, followed by students. Retired individuals pay the least.
- **Potential savings by occupation:** nearly the same across all occupations, with only small differences.
- **Potential savings by city tier:** Tier 2 leads in healthcare, transportation, utilities and education. Tier 3 is lowest in each.

  ## Dashboard preview
  ![Dashboard 1](Images/img%201.png)

![Dashboard 2](Images/img%202.png)

![Dashboard 3](Images/img%203.png)

## Repository contents

| File | Description |
|---|---|
| `Project_Documentation.docx` | Full project documentation, including the data dictionary and methodology |
| `CHANGELOG.md` | Record of changes to the project |
| `README.md` | This file |

## Licence and credits

The dataset is published on Kaggle under the [Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/) licence. Credit the original dataset author, and share any derived work under the same licence.
