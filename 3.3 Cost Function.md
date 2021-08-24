## Example Cost function
- Data set with data points at 1, 1, 2, 2, 3, 3.\
![alt_text](https://i.imgur.com/ZxQYUrV.png)
- Define an octave function to compute the cost function J of theta for different values of theta
- Put the data into octave and set a design matrix as `X = [1,1; 2,2; 3,3]` with x0 in the first colum and x-values of my three training examples in the second cloumn
- Set the y axis values as `y= [1; 2; 3]`
- Assumption that `theta = [0; 1]`
- Cost funktion J:\
![alt_text](https://i.imgur.com/XOKl6S5.png)
- Let's run it in octave: `j = costfunctionJ(X,y,theta)`
