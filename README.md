# Comparing Wages Across Occupational Groups in the United States

## Project Scaffold Table

| Component | Project Plan |
|---|---|
| Research Question | Do computer and mathematical occupations have higher annual mean wages than business and financial operations occupations across U.S. states? |
| Data Source | U.S. Bureau of Labor Statistics (BLS), May 2025 Occupational Employment and Wage Statistics |
| Unit of Analysis | U.S. state, with one paired wage comparison per state |
| Primary Hypothesis | Computer and mathematical occupations have higher state-level annual mean wages than business and financial operations occupations. |
| Data Preparation | Download official BLS data, filter the two major occupational groups, match states, and check for missing data. |
| Primary Test | Paired permutation test using the mean of state-level wage differences and sign flipping. |
| Bootstrap Metrics | Mean and median paired state wage differences, with bootstrap confidence intervals. |
| BS-Audit | Evaluate source reliability, group comparability, unexpected results, magnitude, and confirmation bias. |

## 1. Research Question

Do computer and mathematical occupations have higher annual mean wages than business and financial operations occupations across the United States?

I have an undergraduate degree in Finance and am currently pursuing a master's degree in Data Science. I am interested in understanding the differences in earning potential between these two career fields. This project will help me explore that question using real-world occupational wage data and statistical methods.

## 2. Hypothesis

**Null Hypothesis (H0):** The paired state-level wage differences are centered at zero under the sign-flip null model.

**Alternative Hypothesis (H1):** Computer and mathematical occupations have higher state-level annual mean wages than business and financial operations occupations.

## 3. Data Description

**Source:** U.S. Bureau of Labor Statistics (BLS), Occupational Employment and Wage Statistics (OEWS).

**URL:** https://www.bls.gov/oes/tables.htm

**Reference period:** May 2025.

**Unit of analysis:** U.S. state. Each observation will contain a matched pair of occupational wage estimates.

**Key variables:** State, occupational group, annual mean wage, and annual median wage.

**Data preparation:** Download the original BLS data, select the two occupational groups, check missing values, and match state-level observations.

**Number of observations:** To be determined after data acquisition and cleaning.

## 4. Methods

The primary analysis will use a paired permutation test to compare state-level annual mean wages between the two occupational groups.

The test statistic will be the mean of the paired wage differences. Under the null model, the signs of the state-level differences will be randomly flipped to generate a reference distribution.

Bootstrapping will estimate confidence intervals for the mean and median paired wage differences. The median is included because the classical Central Limit Theorem for sample means does not directly provide its sampling distribution.

## 5. Results

To be completed after data analysis.

## 6. Uncertainty Estimation

To be completed after permutation testing and bootstrapping.

## 7. Limitations

Potential limitations include differences in occupational composition, regional labor markets, missing or suppressed wage estimates, and differences between occupational wage statistics and individual career earnings.

## 8. References

U.S. Bureau of Labor Statistics. Occupational Employment and Wage Statistics (OEWS). https://www.bls.gov/oes/tables.htm

Additional software and references will be documented as the analysis progresses.

## BS-Audit

The final project will evaluate data provenance, fairness of comparisons, potentially misleading results, plausibility of observed wage differences, and confirmation bias.

## Project Status

Module 8: Topic Check-in. Initial research plan prepared; data acquisition and analysis are pending.
