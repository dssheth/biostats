# Permutation Tests, Resampling, and Bootstrap

How they compare to parametric and non-parametric
better than para and non para

1. Research Question
2. Collect some data, compute test statistic
3. Key Data

assumed the distribution, resampling and then check the dist

# Resampling 

Permutation and Bootstrap
3p3 = n! = n(n-1)(n-2)

in n all 3 possible if one used, two values possible so n-1 and then two used and only one possible so n-2

eg.
|3|5|7|
|3|7|5|
|5|3|7|
|5|7|3|
|7|5|3|
|7|3|5|

Permutaton test: Tests a hypothesis about group labels (significance)
1. Assume the null hypo is true (no group effect)
2.


### Bootstrap
data sampling with replacement. create replicates of it, repeat many times to make bootstrap distribution

- Parametric:
normal dist assumed
rely on parametric

f-test: variances are equal

- Non-para
fewer assumptions
based on rank, signs, or ordering 

Mann Whitney 
spearman, kandle

- Permutation test
calculate significance threshold
no ranks calculation
shuffle the data
based on null obs where the data 
check the significantly difference on the null obs

- Bootstrap
few assumptions
no p value but confidence interval

## When to use what

data approx normal, simple design -> parametric
unknown dist, ordinal data and small samples -> non para
complex design, and small sample, no distributional assumptions -> permutation
need confidence intervals or sd with minimal assumptions (no p value require) -> bootstrap

Resampling methods are flexible and rely on the data rather than strict models.
Permutation tests assess significance 


given permutation test, calculate the p value
where assumptions are met and somewhere not met
permutation test, compare with para and non para
regression, model choice
PCA, non para, para, plotting, 
compare pre midsem and end sem