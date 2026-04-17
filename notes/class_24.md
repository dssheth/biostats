---
16th March
---

### One way anova
can be more than one group
alt hyp, H0: uA = uB = uB

| Marks | Dept. (Major)|
|-------|--------------|
|20 | BIO |
|32 | CHM |
|51 | BIO |
|90 | BIO |
|85 | ECO |
|60 | BIO |


To find the differences in which groups:
1. Pairwise t-test
2. Tukey Post-Hoc 

## Two Way ANOVA

have one more group, two variables and values
Interaction between variable-1 and 2
additive or multiplicative interaction effects, BIO + PhD, BIO * BSMS

| Values| variable-1 | variable-2 |
| Marks | Dept. (Major)| PhD, BS, BS-MS |
|-------|--------------|----------------|
|20 | BIO |PhD |
|32 | CHM |BSMS |
|51 | BIO |MS |
|90 | BIO |MS |
|85 | ECO |PhD |
|60 | BIO |BSMS |


## Multi-way ANOVA (Manova)

combination of variables, ends up getting what marks

```r
(val~var-1)
val~var1+var2
val~var1*var2
```
