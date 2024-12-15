Matrix 
======
A special case of nested matrix lists. 
These are rectangular tables filled with some kind of values, usually numbers.
----
````ruby
rows, cols = int(input()), int(input())
matrix = [[0]*cols for _ in range (rows)]
for i in range (rows):
    for j in range (cols
    
        matrix [i][j] = input()
for k in range (rows):
    print (*matrix[k], end = "\n")
print()
    
for j in range (cols):
    for i in range (rows):
        print (matrix[i][j], end = " ")
    print ()
````
````python
n = int(input())
matrix = [[int(num) for num in input().split()] for _ in range(n)] 
for i in range(n):
    cnt = 0
    average = sum(matrix[i]) / n 
    for j in range(n):
        if matrix[i][j] > average:
            cnt += 1
    print(cnt)
````
Matrix addition
----
Properties of matrix addition:
1. Commutativity – the result of matrix addition does not depend on their permutation.
2. Associativity – the result of matrix addition does not depend on the placement of brackets.
3. Addition with a 0 matrix – for any matrix, there is a neutral element, which is the zero matrix, addition with which does not change the original matrix.
4. The existence of an opposite matrix – for a non−zero matrix A, there is always a matrix −A, addition from which will result in a 0 matrix.
----
Multiplying a matrix by a number
----
Properties of matrix multiplication by a number:
1. One is the neutral number of multiplication of any matrix, the result is the original matrix.
2. The result of multiplying any matrix by 0 is a zero matrix.
3. For matrices of the same size and a real number, the distributivity property of multiplication with respect to addition is fulfilled.
4. For any matrix and the sum of real numbers, the distributivity property holds.
5. For any matrix and the product of any real numbers, the associativity property of multiplication holds.
----
Multiplying a matrix by a matrix
----
Multiplication of two matrices A & B is the calculation of the resulting matrix C, each element of which c[i][j] is equal to the sum of the products of the elements corresponding to the row of the first matrix a[i][r] and the column of the second matrix b[r][j].
One matrix can be multiplied by another only when the number of columns in the first matrix matches the number of rows in the second matrix.
----
