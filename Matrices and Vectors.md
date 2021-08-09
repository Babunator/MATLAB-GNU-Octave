# Basic defintions & Indexing
```
#Matrices:
% The ; denotes we are going back to a new row.
A = [1, 2, 3; 4, 5, 6; 7, 8, 9; 10, 11, 12]
% or write:
A = [1, 2, 3;
4, 5, 6;
7, 8, 9;
10, 11, 12]

% 2x3 matrix with just ones:
ones(2,3)

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
# Addition and Scalar Multiplication

```
% Initialize matrix A and B 
A = [1, 2, 4; 5, 3, 2]
B = [1, 3, 4; 1, 1, 1]

% Initialize constant s 
s = 2

% See how element-wise addition works
add_AB = A + B 

% See how element-wise subtraction works
sub_AB = A - B

% See how scalar multiplication works
mult_As = A * s

% Divide A by s
div_As = A / s

% Matrix + scala 
add_As = A + s
```

# Matrix-Vector Multiplication
```
% Initialize matrix A 
A = [1, 2, 3; 4, 5, 6;7, 8, 9] 

% Initialize vector v 
v = [1; 1; 1] 

% Multiply A * v
Av = A * v
```

# Matrix-Matrix Multiplication
```
% Initialize a 3 by 2 matrix 
A = [1, 2; 3, 4;5, 6]

% Initialize a 2 by 1 matrix 
B = [1; 2] 

% We expect a resulting matrix of (3 by 2)*(2 by 1) = (3 by 1) 
mult_AB = A*B
```
# Identity matrix
```
% Initialize a 2 by 2 identity matrix
I = eye(2)

% The above notation is the same as I = [1,0;0,1]
```
# Inverse and Transpose
```
% Initialize matrix A 
A = [1,2,0;0,5,6;7,0,9]

% Transpose A 
A_trans = A' 

% Take the inverse of A 
A_inv = inv(A)
```
