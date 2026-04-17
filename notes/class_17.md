## confidence interval

95% in normal dist.: 95% confidence of a point
Distance of data point of a mean.
mean of one sample vs mean of other sample.


## Tests of Significance

normally dist: parametric
not normal: non parametric


### Parametric
calculate Normality: Do qq plot, shapiro wilk test

1. z test: known SD (sigma):when sample size > 30
When SD was known, and mean is known of one sample.
- sample vs population
- 2 samples
mean is considered
Mode, median in non-parametric test

z = mu - mean (x1bar) / (sigma/sqrt(n))

Within 95% population, not datapoints , 2.5% data points at each side, population 
population mean and sample mean is different

probability of alpha: critical region, the 2.5% 
Hypothesis:
H0: mu = mean
Ha: mu != mean

if H0 false, reject H0 and accept Ha.

Something that was true and was falsified : Type I error
Something was false and was proved true: Type II error

in 0.05% probability was missed. Increase limit of distribution, unable to reject that was false, thus go mostly with 95%.

2. T-test
if SD not known
Many types:
- One sample Independent
- Two sample

One sample
SD of sample not known, use SD of population, come with some degree of freedom
given it is normall distributed, mean not known

t = (X1bar - X2bar)/ (sqrt(S^2/n))

Dof: n-1


Two sample
- paired 
- unpaired 

They are equal or not. 
The observation, whether same subject or not: Paired vs unpaired.

- paired:
both samples, same length
from sample 1 - sample 2, get the mean 

t = dnbar (difference mean)/(sqrt(S^2/n))
mean of the differences

- unpaired:
two different subjects, equal size or unequal size
SD and variances might not be equal
t = (x1bar - y1bar)/ [(sqrt(S2^2/n1)) + (sqrt(S2^2/n2))]

if repeated use of t-test: some probability of error mostly Type I error
