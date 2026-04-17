---
April 1
---

## Rank order correlation
use rank instead of absolute values 
if same values, same rank for all, not resolve the ties
alternative: Kandel's rank correlation

Degree of cocordance and discordance
even if ties, fine

Kandall's tau: 

Multiple testing coreelation

- Correlation is not causation
eg. Fresh Lemons Imported to USA from Mexico: reduced in 1998-99 due to political issues
correlated with total US highway fatality rate

eg. ice cream sale increase, shark attacks increase in summer time, confound temperature

eg. increase in organic food sales, inc. in autism

### effect of outliers

with outlier, correln = 0.4
without outlier, corr = 0.7

Always report the corr of with outlier

## Partial and semi- partial correlation

### Partial corr:

- remove Z's effect from both x and y
- measure direct relationship

is x related to y independent of z?

study hours:x
exam score: y
IQ: Z

does studying affect scores independent of IQ?


### Semi-partial Correlation

Controls Z in x only

removes Z's effect from X only
measures unique contribution

How much does X uniquely contribute to y beyond Z

How much does IQ boost the marks?


In R:
homo and heteroscedascity

vertical outliers, corr drops

leverage points: at extreme points of distribution, can be real data that drives the correln, beyond threshold
strong effect than any other outliers

### Simpsons paradox

pooled corrln: negative

## Pearson corr:

Distribution of Pearson r across repeated simulations

- chance of contamination is high, one side corr

## Residuals:

the points outside correln line, the distance between the point to line, residuals

package ppcor
residuals after regression, also function is there.
