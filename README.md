# Married Women Labor Force Participation Analysis

This project analyzes the factors influencing married women's labor force participation using the Mroz dataset, which consists of 753 observations. The analysis applies **logistic regression** to model the probability of a married woman participating in the labor force based on various socioeconomic and demographic factors.

## Dataset Overview

The dataset includes the following variables:

- **lfp**: Labor-force participation of married white women (Categorical: 0/1)
- **k5**: Number of children younger than 6 years old (Positive integer)
- **k618**: Number of children aged 6-18 (Positive integer)
- **age**: Age of the wife (Positive integer)
- **wc**: Wife's college attendance (Categorical: 0/1)
- **hc**: Husband's college attendance (Categorical: 0/1)
- **lwg**: Log expected wage rate for women in the labor force (Numerical)
- **inc**: Family income excluding the wife’s income (Numerical)

## Objectives

The main objectives of the analysis are:

1. **Assess the influence of children on labor force participation**: Examine how the number of children, especially young children, affects the likelihood of participation.
2. **Analyze the role of education**: Study the impact of both the wife’s and husband’s education levels on the wife’s labor force participation.
3. **Investigate the effect of age**: Analyze how age influences labor force participation.
4. **Evaluate the impact of wages and family income**: Understand how expected wage rates and family income without the wife’s earnings affect her decision to participate in the labor force.

## Results

- **Number of Young Children**: A strong negative relationship between having young children and labor force participation. Each additional child younger than 6 decreases the odds of participating in the labor force by about 76.8%.
  
- **Education**: A woman who attended college has 2.24 times higher odds of participating in the labor force. The husband's education was not found to have a statistically significant effect.
  
- **Age**: As a woman’s age increases, the probability of labor force participation decreases by about 6.1% per year.

- **Wage and Income**: Higher expected wages positively influence participation, while higher family income without the wife’s earnings reduces the likelihood of participation.

You can read the full analysis in [Married Women Labor Force Participation.pdf](Married Women Labor Force Participation Analysis.pdf)
