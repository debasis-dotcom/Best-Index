# Best-Index
Given an array A of N elements. Need to choose the best index of this array A. An index of the array is called best if the special sum of this index is maximum across the special sum of all the other indices. To calculate the special sum for any index i, pick the first element that is A[i] and add it to the sum. Now pick next two elements i.e. A[i+1] and A[i+2] and add both of them to the sum. Now pick the next  elements and this continues till the index for which it is possible to pick the elements. 

For example:  
If the array contains 10 elements and one chooses index to be 3 then the special sum is denoted by - (A[3]) + (A[4] + A[5]) + (A[6] + A[7] + A[8]) , beyond this its not possible to add further elements as the index value will cross the value 10.

Find the best index and in the output print its corresponding special sum. Note that there may be more than one best indices but need to only print the maximum special sum.  
