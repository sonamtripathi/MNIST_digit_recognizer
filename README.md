# MNIST Digit Recognizer
This Repository contains MNIST problem solved using 3 Method(Logistic Regression, Simple Neural network, Deep Learning Model)

### Softmax Regression:
First we have use Simple Multinominal Logistic Regression or Softmax Regression.
It is a generalization of Logistic regression for those cases where we want to handle multiple classes.

In Logistic Regression we assumed that the labels are binary: ![](https://latex.codecogs.com/gif.latex?y%5E%7B%28i%29%7D%20%5Cin%20%5C%7B0%2C1%5C%7D). We used such a classifier to distinguish between two kinds of hand-written digits.

Softmax Regression allows us to handle ![](https://latex.codecogs.com/gif.latex?y%5E%7B%28i%29%7D%20%5Cin%20%5C%7B1%2C%5Cldots%2CK%5C%7D) where K is the number of Classes.

In Logistic Regression, we had a training set ![](https://latex.codecogs.com/gif.latex?%5C%7B%20%28x%5E%7B%281%29%7D%2C%20y%5E%7B%281%29%7D%29%2C%20%5Cldots%2C%20%28x%5E%7B%28m%29%7D%2C%20y%5E%7B%28m%29%7D%29%20%5C%7D) of m labeled examples, where the input features are ![](https://latex.codecogs.com/gif.latex?x%5E%7B%28i%29%7D%20%5Cin%20%5CRe%5E%7Bn%7D). With logistic Regression, we were in the binary classification setting, so the labels were ![](https://latex.codecogs.com/gif.latex?y%5E%7B%28i%29%7D%20%5Cin%20%5C%7B0%2C1%5C%7D).Our hypothesis took the form: 

![](http://www.sciweavers.org/upload/Tex2Img_1543849469/render.png)

and the model parameter ![](http://www.sciweavers.org/upload/Tex2Img_1543849637/render.png) were trained to minimise the cost function

![](http://www.sciweavers.org/upload/Tex2Img_1543849698/render.png)

In the softmax regression, we are interested in multi-class classification and so the label y can take K different values, rather than only two. Thus, in our training set ![](http://www.sciweavers.org/upload/Tex2Img_1543849843/render.png), we now have that ![](http://www.sciweavers.org/upload/Tex2Img_1543849930/render.png).In our MNIST digit recognition task, we would have K = 10 different classes.

For K output classes our hypothesis ![](http://www.sciweavers.org/upload/Tex2Img_1543850109/render.png) takes the form:

![](http://www.sciweavers.org/upload/Tex2Img_1543850170/render.png)

Here ![](http://www.sciweavers.org/upload/Tex2Img_1543850216/render.png) are  the parameters of our model. Notice that the term ![](http://www.sciweavers.org/upload/Tex2Img_1543850281/render.png) normalizes the distribution, so that it sums to one.


### Simple Neural Network:
Second we have also implemented Simple feed forward neural network for classificationwe have used softmax layer for classifying the digits to one of the 10 categories.

### Deep Learning Model:
Lastly we have used Deep Neural model with "ReLU" activation function and "softmax" loss function.


Note: Copy the "notebook_importer.py" file which is used for importing the models from different ipython file.

#### References:
1. https://github.com/akshaybahadur21

2. http://deeplearning.stanford.edu/tutorial/supervised/SoftmaxRegression/


