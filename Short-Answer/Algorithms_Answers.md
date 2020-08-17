#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n^3)


b) O(n^2)


c) O(n)

## Exercise II


Drop the first egg at intervals of n^1/2 if it breaks start dropping the second egg floor by floor starting at the floor above the last floor the first egg was dropped from and didn't break. if it breaks return the previous floor. if neither egg breaks return n. maybe reduce the interval each attempt. O(log n) A better starting floor can be found by solving x(x+1)/2 = n, which would also be the maximum number of drops to find a solution.s