# CQ4-CSCI160-01

#Runtime and space analysis for camelCase
The runtime of camelCase is O(n) where n is the length of the string s, because the algorithm consists of a loop that iterates n times and constant work within it. The Space complexity is again O(n) since the the amount of storage required is at most one string of length n.

#Correctness and loop Invariant
The bug is that the algorithm assumes that the first element in the array is sorted. Unfortunately I was unable to find a solution. The runtime of the algorithm is O(n^2) because of the 2 nested loops where the first runs for A.length-1 time and the second runs in the worst case for A.length - 2 times. The space complexity is O(n) since the amount of storage required is one array.
