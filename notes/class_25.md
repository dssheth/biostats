--- 
March 17
---

## t-test
signal/noise:
1. Normal Dist
2. Homo var
3. Indi obs 

### Parametric test
1. more power
2. assumptions
3. sensitive to outliers

eg. Group A: 1,2,3
Group B: 4,5,100

one number pull the mean away from the data

outliers: the data point away from certain threshold
based on means and variances
t= mean diff/ SE

### Non-Parametric test
1. less power
2. fewer assumptions
3. no so sensitive to outliers

based on ranks and order
eg. Group A: Ranks: 1,2,3
Group B: Ranks: 4,5,6

so even if 100, 1000 the rank will become 6 (groupB- compare to example in parametric test)
ranks combined
magnitude of difference is reduced based on ranks
Order of values: in correlation order used in test statistic

Test statistic: Man whittney U-test (order not important)
combined rank - number of obs(n +1)
U = R-n(n+1)/2
U = 0 (test statistic)

out of lesser U value in both groups is compared and measured

robust to outliers
assess distribution shift

Data not met the assumptions of non parametric test: transformations


## Transformation:
data vector x, not normal dist, x not normally dist -> log dist -> normal dist.
then do non-parametric test

x -> log(x) -> y

Parametric work for skewed data, ordinal data, small data
Parameters refers to population parameters: mean, variance, etc.

Non parametric: compares medians, ranks or categories


Individuals t-test

| Type of test | Parametric test | Non - Parametric alternative|
|--------------|-----------------|-----------------------------|
|Two indi groups|Independent samples t-test | Mann-WHitney U test |
|Paired samples | paired t-test| wilcoxon signed-ranked test |
|more than two indi groups| One-way ANOVA| Kruskal-Wallis test|

Effect size: the actual difference or how large is the difference
less effect size: no large difference
more effect size:: large difference

50: more
15: less

less data, less effect size
vary the data sample, change the effect size


Task: Take a,b,c : change effect size, from 10 to 50 for eg. step size of 10, 4 diff values of mean
do parametric test, and non parametric test
t-test, anova in parametric
for non parametric

check p val, test-statistic, effect size more affect on the parametric or non parametric
outliers: keep same rnorm, after it add 10 values to a,b,c and put some extreme outliers
do parametric and non parametric test
which is sensitive to outliers