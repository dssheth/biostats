---
March 25
---

## Sign Test

John: 
|Year| M | F | Difference | Rank |
| 1629| 100 | 70 | +30 | +3 |
| 1630| 70| 100 | -30 | -3 |
| 1631| 100 | 100 | 0 |   |
| 1632 | 60 | 40 | +20 | +1 | 
| 1633 | 20 | 80 | -60 | -5 |
| 1634 | 100 | 70 | +30 | +3 |



total combindation 2 and 3
probability of combination: binominal equation 
3 success or 2 failure or vice versa

if positives are more than negatives, conclude M more than F.

mulitply by total number of combinations

p = (5 2) * p^2 * q^3

= 5!/ 2! (5-2)! * (0.5)^2 * (0.5)^2

even though 3 is greater than 2 in combination, it will be considered equal as there is 31% chance of F greater than M

## Sign Wilcoxin rank test:

- to look for magnitude of the differences
- if 3 values are same: put the possible ranks/ the number of positions
= 2+3+4 / 3 = 3 given 3 to all 3 same values  and assign sign to them, 4 is inclusive, so next values is 5.

- higher rank more magnitude
- w+ w- test
- the lower rank will be calculated by the critical table
- pvalue check

### critical limit table

-w = -3 + -5 = -8
+w = 3+ 1 + 3 = 7

-++++
--+++
---++

if p > 0.05, it can be said to be by chance.

total number of combinations: 2^5 = 32
smallest w / total numner of observation for symmetry.

-- use both in one or two sample test

- when not rank the data: nominal data - use sign test
- if rank, go for wilcox sign rank test
- if data not paired - wilcox rank sum test

### Man Whitney U test/ Wilcox rank sum test

sum of ranks from Group-1 showing magnitude : R1
sum of ranks from Group-2 showing magnitude : R2

U1 = n1n2 + n1(n1+1)/2 - R1
U2 = n1n2 + n2(n2+1)/2 - R2

gives total number of ranks possible

lower values, check p stat and significance.
