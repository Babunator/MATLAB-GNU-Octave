# Basic defintions & Indexing
```
#Matrices:
% The ; denotes we are going back to a new row.
A = [1, 2, 3; 4, 5, 6; 7, 8, 9; 10, 11, 12]

#Vectors:
% Initialize a vector 
v = [1;2;3] 

% Get the dimension of the matrix A where m = rows and n = columns
[m,n] = size(A)
Output: m =  4
        n =  3

% You could also store it this way (mxn)
dim_A = size(A)
Output:  dim_A =
         4   3

% Get the dimension of the vector v (mxn)
dim_v = size(v)
Output:  dim_v =
         3   1
         
% Now let's index into the 2nd row 3rd column of matrix A --> you get the output 
A_23 = A(2,3)
Output: A_23 =  6

```
