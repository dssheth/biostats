---
March 30
---

## Correlation

if x increases, y also increases : positive correlation
if x increase, ty decrease: negative correlation

if no difference: no correlation, no trend seen

eg. the infectivity ratio by SERINC5 expression plot: +ve correlation

prediction from that.

- slope
- co-variation

strong or weak correlation based on the co-variation
confuse correlation with slope, due to the sign.

more spread out, no correlation.
variance formula: 

Variance vs Covariance:
- variance: S^2 = sum (i = 1 to n)(xi - x)^2/n
- covariance (two variables):

if more than 2 variables: covariance across multiple variables by covariance matrix

### Pearson correlation

normalised by the variance within
denominator is correcting for the covariance within
- it is parametric test
- non parametric equivalent: spearman and Kendal correlation: rank based
significance: null hypothesis, correlation is zero
if enough power to reject the null hypo, correlation is significant

- not work in non linear relationships


### Different relationships between x and y
- monotonous: not change over time
- increase in correlation of x with y
- non monotonic

- non linear relationships: quadratic, exponential, polynomial

- requirements for the pearson correlation:
Homoscedasticity: no change in the relationship, only linear
Heteroscedasticity: at lower x, lower y, with increase in x, more varince in y, the variance increases.

increase sample size, more statistical power. even if trend weak, the correlation is seen due to more sample
correlation != causation


check how p value and correlations change
amount of noise is changed, the sd is changed, the correlation coefficient, become weaker with more spread and noise of data with same sample size.

Observed pearson correlation and p-values  across repeated simulations:
when calculate pearson corr. same data more times, correln coeff vary 
overall trend, the p-value is significant
trend is positive correlation and significant

eg. oif non linear relationship:
pearson and spearman correlation
pearson: 0.92


change the data and check change in slope and sampele size etc.

to check the correlation: 
```r
cor.test(x,y)
```
add method as well


## Simpson's paradox
if two data A and B, have positive correlation, put together, and see -ve correlation, for superset is -ve
confounding variable, driving the -ve correlation
look at partial and semi correlns.

package(corplot) for visualising correlations
then regression
dimensionality reduction
bootstrap