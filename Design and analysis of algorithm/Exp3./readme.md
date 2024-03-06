Experiment no - 01 Implementation of Binary search algorithm using Divide & Conquer method.

Title: Implementation of Binary search algorithm using Divide & Conquer method. Theory/Description:

Binary search:- can be performed on a sorted array. In this approach, the index of an element x is determined if the element belongs to the list of elements. If the array is unsorted, linear search is used to determine the position.
In this algorithm, we want to find whether element x belongs to a set of numbers stored in an array numbers[]. Where l and r represent the left and right index of a sub-array in which searching operation should be performed.
Algorithm:

Binary-Search (numbers[], x, l, r)
if l = r then
return l
else
m := ⌊(l + r) / 2⌋
if x ≤ numbers[m] then
return Binary-Search(numbers[], x, l, m)
else
return Binary-Search(numbers[], x, m+1, r)

Example:

In this example, we are going to search element 63. 
Screenshot 2024-03-02 231603
[image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/de4b2154-3d57-4d34-9e73-08d571b02027)

Conclusion( must include analysis of program):

Analysis: Linear search runs in O(n) time. Whereas binary search produces the result in O(logn) time. Let T(n) be the number of comparisons in worst-case in an array of nelements.
Hence,T(n)={0.....................fn=1 T(n/2)+1 ........otherwise Using this recurrence relation T(n)=(logn).
Therefore, binary search uses O(logn)time.
VIVA-VOCE QUESTIONS:

Differentiate between recursive approach than an iterative approach?
What is the worst case complexity of binary search using recursion?
What are the applications of binary search?
