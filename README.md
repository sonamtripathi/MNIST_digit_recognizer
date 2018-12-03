# MNIST Digit Recognizer
This Repository contains MNIST problem solved using 3 Method(Logistic Regression, Simple Neural network, Deep Learning Model)

### Softmax Regression:
First we have use Simple Multinominal Logistic Regression or Softmax Regression.
It is a generalization of Logistic regression for those cases where we want to handle multiple classes.

In Logistic Regression we assumed that the labels are binary: ![](https://latex.codecogs.com/gif.latex?y%5E%7B%28i%29%7D%20%5Cin%20%5C%7B0%2C1%5C%7D). We used such a classifier to distinguish between two kinds of hand-written digits.

Softmax Regression allows us to handle ![](https://latex.codecogs.com/gif.latex?y%5E%7B%28i%29%7D%20%5Cin%20%5C%7B1%2C%5Cldots%2CK%5C%7D) where K is the number of Classes.

In Logistic Regression, we had a training set ![](https://latex.codecogs.com/gif.latex?%5C%7B%20%28x%5E%7B%281%29%7D%2C%20y%5E%7B%281%29%7D%29%2C%20%5Cldots%2C%20%28x%5E%7B%28m%29%7D%2C%20y%5E%7B%28m%29%7D%29%20%5C%7D) of m labeled examples, where the input features are ![](https://latex.codecogs.com/gif.latex?x%5E%7B%28i%29%7D%20%5Cin%20%5CRe%5E%7Bn%7D). With logistic Regression, we were in the binary classification setting, so the labels were ![](https://latex.codecogs.com/gif.latex?y%5E%7B%28i%29%7D%20%5Cin%20%5C%7B0%2C1%5C%7D). Our hypothesis took the form:![](https://latex.codecogs.com/gif.latex?%5Cbegin%7Balign%7D%20h_%5Ctheta%28x%29%20%3D%20%5Cfrac%7B1%7D%7B1&plus;%5Cexp%28-%5Ctheta%5E%5Ctop%20x%29%7D%2C%20%5Cend%7Balign%7D) and the model parameters ![](https://latex.codecogs.com/gif.latex?%5Ctheta) were trained to minimize the cost function.
![](https://latex.codecogs.com/gif.latex?%5Cbegin%7Balign%7D%20J%28%5Ctheta%29%20%3D%20-%5Cleft%5B%20%5Csum_%7Bi%3D1%7D%5Em%20y%5E%7B%28i%29%7D%20%5Clog%20h_%5Ctheta%28x%5E%7B%28i%29%7D%29%20&plus;%20%281-y%5E%7B%28i%29%7D%29%20%5Clog%20%281-h_%5Ctheta%28x%5E%7B%28i%29%7D%29%29%20%5Cright%5D%20%5Cend%7Balign%7D)


### Simple Neural Network:

### Deep Learning Model:

