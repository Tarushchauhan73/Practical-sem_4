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
https://private-user-images.githubusercontent.com/123314058/309491255-97d947b9-7664-493f-991e-68baedae1a4c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDk3MTkyNjIsIm5iZiI6MTcwOTcxODk2MiwicGF0aCI6Ii8xMjMzMTQwNTgvMzA5NDkxMjU1LTk3ZDk0N2I5LTc2NjQtNDkzZi05OTFlLTY4YmFlZGFlMWE0Yy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMzA2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDMwNlQwOTU2MDJaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yY2JjNTBlODJlMzFhOGVkNTY0NDBlMzM0YWIyNjQzZDY1MjQ1YjA5ZmUzY2VhMTMyMzQzZjRlMjgxZjczM2VkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.Pv0Kp9yisuxIWq1cU_dA2H7dr7K-VeSscaMvfanVWSQ![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/de4b2154-3d57-4d34-9e73-08d571b02027)

Conclusion( must include analysis of program):

Analysis: Linear search runs in O(n) time. Whereas binary search produces the result in O(logn) time. Let T(n) be the number of comparisons in worst-case in an array of nelements.
Hence,T(n)={0.....................fn=1 T(n/2)+1 ........otherwise Using this recurrence relation T(n)=(logn).
Therefore, binary search uses O(logn)time.
VIVA-VOCE QUESTIONS:

Differentiate between recursive approach than an iterative approach?
What is the worst case complexity of binary search using recursion?
What are the applications of binary search?
