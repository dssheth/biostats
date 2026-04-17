Session-4: Distributions of random variables

- Biostatistics with R
- Understanding biological variability

### Why distributions matter

- BIological measurement vary
- Dist. summarize variability
- FOundation of interference

Galton- measuring height (a distribution) (bell shaped graph)
Normal distribution, gaussian distribution

Central Limit Theorem: 

WHat is random variable

- A numerical outcome of a random process
- Eg. height, gene expression

not all are normal distribution

Other distributions:
Poisson 
gamma 
exponential
log normal


### Types of Random Variables

- Discrete: counts (mutations)
- Continuous: Measurements (height)


Probability Dist.

- Describe likelihood of outcomes
- Shape, center, spread

variability of dist. required to understand
shape or more than one parameter
based on this the dist. have different properties

not data of one particular dist. and use various stats.


### Key Distriibutions in Biology

- Normal
- Binomial
- Poisson

gene data: -ve binomial dist.

### Normal Dist

bell shaped
mean and sd 
common in biological traits

### Binomial

success/failure outcomes
eg. survival, infection

### Poisson

rare events
eg. mutations per gene

### Visualizing dist  in R

-hist(): plot histogram
- dnorm(), dbinom(), dpois() : normal, binomial and poisson respectively.

- calculate mean, sd: summary stats calculation
- all possible sorts of distribution and compare with these 3 and egs in biology.

### R demo
rbinom() and rpois()

sample(): give random number
eg. computer game- if events going to change use random numbers
use starting point from random numbers generator
in WW-2, people send ciphers (coded msgs)- require random starting point, random, the idea started there
random number generators, later became complex, have algorithm

### WHy this matters
inference about dist


rnorm is easy to use