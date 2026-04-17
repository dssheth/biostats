## df

two diff types of data in a structure

data.frame = function to make df.
data in csv or tsv

head() - first few rows are seen and not others if large database 

small dataset <- view
real biological data: 1st head
then str()

in vectors- 1D call by []

in df - 2D rows and column

[1,2] 1st column of row 2
[,2] all the whole 2nd column and all rows

for bioinfo: matrices
warning: to check the data
put equal number of values for all rows or all the columns to make proper matrix


if more than data matrix, repeat the data

## Blastn 

ATGC - Query
ATCC - sample

give score based on similarity, the bit score, give a matrix 
eg. if A and A is 1, if A and T is 0.5 as in matching and not making gap but score is different
if same, compare their identity and bit score 


Determinance- determinant of the matrix

Function better than blast: diamond
solve matrix using determinance

matrix- is 2D rows and columns, no $, subsetting is same
Matrix is vector with dimension component
matrix (c(1:10), 2, 5)
c(1:10) is a vector and 2, 5 is dimension component

## Arrays

higher dimension of same data structure
have double matrices, can be multidimensional data

## List
any type of data structure can be stored in a list
give algorithm 