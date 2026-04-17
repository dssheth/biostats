## Multiple Testing

### P-hacKing
publish positive results, considered good
large no. of tests done (eg. 1 million, 50k will be significant), do multiple testing correction

Did 50000 tests, multiple testing correction for those, 25000 significant results and report them and other half wont be reported.
Q. How to find the actual no. of tests done? 
Chances of ambiguity.

- Descriptive test
- Inferential test: shapiro-wilk

When to use anova: (for all the parametric tests, this assumptions are made)
- When more than two groups.
- data normally distributed, normality (histogram, qqplot, shapiro-wilk test)
- Homogenity in variances (levene test)
- Independence of observation: when samples from population, probability of every observation would be same.

test the assumptions, if valid, do parametric test, or do non parametric test
do parametric tests, most of data not met assumptions
increase false positives, 


## one way anova

1. A=B=C
2. A>B=C
3. A>B>C
4. A>B<C
5. A=B>C
6. A=C>B

paired t-test: pairwise.t.test
pairwise: many test and then multiple testing correction