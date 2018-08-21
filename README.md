# Learning
Notes on Online Course


### Linear regression  
Fit data to a line y = mx + b , where the slope m and y intercept b are fit from the data.  Uses some form of error computation, such a sum of squred errors.  Can also use gradient descent with a learning rate for each coefficient.

### Logistic Regression
Good for binary classification.  Uses the logisitic function with has a minimum and a saturation value.  
(f(x)=1/1+exp(-x)).  Gives log/exponential outputs for probabilities of being one or the other of the binary pair.

### Regularization
Used to avoid overfitting.  Implemented bydding an additional cost term that depends on the complexity of the model, such as the sum squares of the parameter weights
