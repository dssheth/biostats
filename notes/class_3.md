# Vectors
Collections of same-type values
Examples: heights,weights

- are like arrays, collection of values in order
-Eg. a[0], a[1], a[2]


# Data Frames
Rows = observations
Columns = varibales

- like 2D arrays

# Basic R Demo

declare a variable
variable can be changes throughout
declare the variables as int, char, long...

in R:
x <- 10
y<- 5
x+y
declared and initialised



Built-in Dataset

data(iris)
head(iris) to see initial rows
str(iris) to see structure of the datset

# Visualisation

histogram:
hist(iris$Sepal.Width)

#Exercise
Create vectors


# Vectors
heights <- c(150, 160, 170, 165)
heights[0]
In R, actual value starts from 1. 0 will be numeric 0.
mean(heights)

use "attach(students)"
All vectors in studets will be become global
```r
students$height
students[,3]
```

Tibles
used now a days

    