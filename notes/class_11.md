30 Jan

## Data: 
Types, 
structures, 
distribution: ND, PD, UD, BD

Estimation: 
i. height: u1 = 160, sigma1 = 6
ii. weight: u2 = 70, sig2 = 10
iii. marks: u3 = 80, sig3 = 10

for i:
(166 - 160)x/6 = 170
z = 1
here, z = x-u/sigma = 1.67

if -1 to +1 from 0 = 34
from 1 to % of 166: 50%
50+34= 84 % covered

### For a ND plot:
1 to -1: 65%
2 to -2 : 95 %
3 to -3 : 99.7%


Total distribution = 1
thus, final probability will be one
z value can be more than 1

For a height 166, what is the proportion of people having height less than or equal to 166?

The 84% population has the height till?? 166

###
pnorm
qnorm
dnorm

A point doesnt have area to it. so no probability

pnorm gives area of probability

dnorm gives density per cm/ the prob. area cm
prob for very small span. eg. find the population within 166 + 0.05 and 166 - 0.05

0.04 * 0.1 = 0.004
dnorm is 0.04
0.1 is small width the interval what is to be found (0.05*2 = 0.1)

### Probability distribution function
dnorm:
f(x)= 1 e^-(x-u/sigma)^2/ (sigma (2pi)^0.5)


## Central limit theorem:

4 distribution : all not normal or bell shaped
multiple sample and calculate mean and they will be Normally distributed.

for test: stat test
give p value, a test of normality
null hyp is, Null = N(u, sigma)
alt hyp  = Null not true


if p > 0.05 = accept the null hypothesis
if p < 0.05 = reject the null hypothesis

shapiro has one assumption of more data points, 
In what conditions shapiro fails, histo fail, or qqplot/qqline fail to know why all 3 are required

reject null hyp, not normally distribution

### Q. why the means will always be normally distributed

The mean will concentrate all the outliers, when plot that mean, given that the sample size is enought for the exp., it will give normal distribution
If sample size increase, the SD decrease


- from any distribution, the sample means around the distribution mean is std error.
- SE will never break in pattern

Q. check CLT for other distributions