```
March 11
Dhruvi Sheth
```

T-test: paired, unpaired, single sample, variance (var test)


## Multiple Testing Correction Demonstration

alpha = 0.05, false positives is error rate in one test
if 20,000 test, 0.05*20000 = 1000 false positives

eg. in chocolates, 5% are poisonous, picking each chocolate and it being poisonour is error
more the tests, more false positive chances, correct for multiple test, each chocolate, is one test

if not correct for multiple test, more errors

More the tests, more false positives

As n increases the family-wise error rate, the false positive increases, after crossing a threshold.
when more tests, like 5 or 50, or above 100 tests, the chances of false positives is very high.

alpha very stringent to begin with or if 0.05, will have false positives. 
within same kind of tests it is done in fwer.

Q. Why multiple testing and increase in false positives?

# Bonferroni Correction

p.adjust: takes two values, vector of two values and other is method for multiple testing correction

each give p- value and then vector of it
take p values, distribution of p values, and correct and give new values

if everything become 1, it is not significant test, if true positives are those also removed in correction?
it moves them closer to 1 after the correction. it corrects for the number of tests, to remove the false positives and towards the correct values

Q. Simulate p value distribution, use runif, can add true positives use p.adjust, use different correction, how dist changes with different tests of pval dist, how is the plot changing in this two methods chaning the dist of p values