# MarketingAnalytics_HW3

# Survival Analysis and Customer Lifetime Value (CLV)

## Introduction
This repository explores survival analysis and customer lifetime value (CLV) in the context of telecom customer churn. The dataset includes various subscriber attributes such as age, income, education level, and churn status. The analysis involves building parametric models, comparing their performance, and deriving insights into factors influencing churn risk.

## Parametric Models
We constructed Accelerated Time Failure (ATF) models with different distributions, comparing their goodness of fit. The models were visualized in a single plot to provide a comprehensive view of survival curves. After careful evaluation, the most suitable model was chosen, considering not only statistical metrics but also practical decision-making factors.

## Customer Lifetime Value (CLV)
CLV was calculated based on the final survival model, utilizing the provided logic. The analysis delves into CLV variations within different subscriber segments, shedding light on valuable customer groups.

## Findings
Interpreting coefficients revealed significant predictors of churn risk, offering actionable insights. Valuable segments were identified, emphasizing subscribers with characteristics associated with lower churn risk and higher CLV. Assuming the dataset represents the population, the annual retention budget can be optimized by targeting at-risk subscribers, guided by CLV and survival probabilities.