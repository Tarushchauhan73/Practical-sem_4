Experiment no - 03 Implementation of Strassen’s Matrix multiplication.

Title: Implementation of Strassen’s Matrix multiplication.
Theory/Description: using Strassen’s Matrix multiplication algorithm, the time consumption can be improved a little bit. Strassen’s Matrix multiplication can be performed only on square matriceswhere n is a power of 2. Order of both of the matrices are n × n. Divide X, Y and Z into four (n/2)×(n/2) matrices as represented below −
Z=[IKJL]Z=[IJKL] X=[ACBD]X=[ABCD] and Y=[EGFH]Y=[EFGH]

Using Strassen’s Algorithm compute the following −
Screenshot 2024-03-06 105816
Analysis:

T(n)={c ...............fn=1
7xT(n2)+dxn2otherwise,
where c and d are constants Using this recurrence relation, we get T(n)=O(nlog7)T(n)=O(nlog7) Hence, the complexity of Strassen’s matrix multiplication algorithm is O(nlog7)O(nlog7). C code of two 2 by 2 matrix multiplication using Strassen's algorithm
