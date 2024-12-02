Matrix 
======
A special case of nested matrix lists. 
These are rectangular tables filled with some kind of values, usually numbers.
----
rows, cols = int(input()), int(input())
matrix = [[0]*cols for _ in range (rows)]
for i in range (rows):
    for j in range (cols):
        matrix [i][j] = input()
for k in range (rows):
    print (*matrix[k], end = "\n")
print()
    
for j in range (cols):
    for i in range (rows):
        print (matrix[i][j], end = " ")
    print ()
```` ruby
