# Classifier
Result or Output of a dataset which will fall into a category is described as Classifier.  
Ex: Exclusive Product in a mall, the customers weather they take it or not.In these example there are two category They take it or 
not take it. 

Instead of predicting the result or predicting wether ther'r going to take it up or not we will predict the probability of(or state of
likelihood) that they will take the product.

# Logistic Regression
It is a function which gives us prob or value between 0 and 1.

We Know,

In Linear Regression: Y = b0 + b1*x
but after applying sigmoid function in these equation we get the equation for logistic regression.

Sigmoid Function: P = 1/(1 + e^-x)

After Applying 

ln[ p / (1 - p) ] = b0 + b1*x 

p = 1/[ 1 + e^-( b0 + b1*x ) ]

These will give us a smooth curve which will lie between 0 and 1. For each Input we get a value of p or we can say
probability.

If p > = 0.5 that means they have buyed the product.

If p < 0.5 that means they have not buyed the product.
