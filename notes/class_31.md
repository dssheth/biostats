---
April 6
---

## Models and their Selection

Models- simplified representations of real world phenomena
too complex- over fatigue
too simple - no group predictive value
selection- trade-off

### Regression

- estimating the relationships among variables
eg, how 2/3 variables are related. x and y
- statistical modelling
- similar to ML based approaches
- Parameric methods
    - Linear regression
    - Ordinary least sqares(OLS)
- Non- parametric methods
    - Large no. of datapoints


## Types of Variables

Independent: The one thing you change. Limit to only one in an expt.
Dependent

## Linear Regression
- Simple LR (1 explanatory variable)
- Multiple LR (>1 explanatory variable)

slope: y = mx + c
y = dep. variable
x = indep. variable

residual change
SSR- as less as possible
regression line change

2 variables:
y = B1x + B2z + c

In R:
1. Estimation: lm ->linear model
- slope and intercept
2. Prediction: predict

### Interaction model
Interaction: have its own slope

AIC
BIC

AIC(regg_mode1)

eg. info about yeaer, month, interest rate, unemployment rate, stock index price

which gives strong prediction