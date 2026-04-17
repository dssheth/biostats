# Parameteric Tests:
z test
t test
anova (analysis of variance)


3 groups: A,B and C
look for mean being statistically significant. 
t-test: set confidence level of 95%, and 5% of error in that assumption.
confidence 0.95
error 0.05 

When all 3 groups compared, the value will be compond, thus cubed, require anova here.
probability of confidence= (0.95)^3 = 0.85
probability of error [1-(0.95)^3] = 1-0.857 = 0.14

### When to use anova: (for all the parametric tests, this assumptions are made)
- When more than two groups.
- data normally distributed, normality (histogram, qqplot, shapiro-wilk test)
- Homogenity in variances (levene test)
- Independence of observation: when samples from population, probability of every observation would be same.

### Rational behind Anova:
some distribution by some t stat., analyze the value inside the critical threshold or beyond it. the p value: reject, accept null hypothesis.
When many population, random variables, A.B and C, have some variance 

Variance: The spread of data, the central value of all data points, mean, median, mode
variance of SD: for spread of data points from central value

3 samples. of equal size from a pop. with a variance of V, random samples from a population A,B,C , the variance should be equal.
Natural variation of the population, irrespective of treatment given, example, age or height.
on natural variation, give treatment, if changes, can be measured.
can't separate the variation with treatment from the natural variation.

#### Variations within group and between groups

Mean and spread of every group.
within and between group variantion will be same in all 3 samples as they were from same population, without treatment.
suppose A got treatmentnt, in all 3 groups the within group variation will be same, but the between group variation may change (increase, or decrease, or none).

A: 4,5,6 , nean= 5
B: 6,7,8 , mean = 7
C: 8,9,10, nean = 9

grand mean = 5+7+9/3 = 7

Find variance:
In between group:

SSB: sum of squares between groups: total variation between groups = 24
SSB: sum(n(sample mean -grand mean)^2)
        = n(xi-x)^2 
        n= no. of observation

variances of samples
A: 3(5-7)^2 = 12
B: 3(7-7)^2 = 0
C: 3(9-7)^2 = 12

A+B+C = 24 = SSB


SSE: sum of squares within group (for error)

from a sample, sum(data points - mean of the sample)^2

A = (4-5)^2 + 0 + (6-5)^2 = 2
B = 2
C = 2

SSE = 6

SSE will impacted, the observations are more than the groups.

SSB and SSE divide by DoF
if divide by n, can give minor error.

## Degrees of Freedom:
given a group of 3 obs, with a mean of 5, how many values can be changed to come to the mean of 5.
DoF = n-1, can change only two values, constraint of mean

changing within group variability if mean changes.
divide with DoF 

In between group: two means can be changed to get the grand mean
if k groups, DoF = k-1
SSB/DoF = 24/2 = 12

MSB = SSB/k-1 = 12

In within group: n obs, groups k, n-k, every group 1 DoF:
n = 9, k = 3
n-k = 9-3 = 6

MSE = SSE/ n-k = 6/6 = 1

F = MSB/MSE = 12/1 = 12, >1
if 1, both variability is equal and treatment didnt work.
if >1, effect of treatment
if between group variation less than within group, the ratio will be <1, very rare.
or if no between group variability and all 3 samples have same mean. 

for ratio, require F distribution

function: aov

