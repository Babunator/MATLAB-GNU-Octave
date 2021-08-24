## Example Vectorization for linear regression
![alt_text](https://i.imgur.com/OoSeneG.png)\
Here's the hypothesis for linear regression.\
If you want to compute h(x) yu could  compute the sum from j = 0 to j = n yourself.\
Or use h(x) as theta transpose x, and compute the inner product between two vectors `theta =[theta0; theta1; theta2 ]` and `x =[x0; x1; x2]`. \
These two views can give you two different implementations:\
![alt_text](https://i.imgur.com/IEm2Hd6.png)\
Using Octaves highly optimized numerical linear algebra routines to compute this inner product between the two vectors is implementation simpler and will run much more efficiently.
***Note: because MATLAB/Octave is one index, theta 0 in that MATLAB, we would end up representing as theta 1 and the second element ends up as theta 2 and this third element may end up as theta 3 ***
