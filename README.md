# MNIST

About the dataset -

1.  The MNIST dataset is a set of 70k small images of digits handwritten by high school students and employees of US Census bureau. 
2.  Each image has 784 features.
3.  Each image is 28 * 28  pixels and each feature simply represents one pixel intensity from 0 (white) to 255 (black).
4.  Each image can be classified into one of the 10 possible outputs (0,1,2,3,4,5,6,7,8,9,10). Hence, it is a multi-classification problem. 

Structure of Neural Network

1.  Input layer having 784 input features
2.  2 hidden layers, each with 256 units and 1 bias. 
3.  1 output layer with 10 units. 
4.  Softmax layer. 

Cross entropy loss function is used to calculate the error for a single training example. The cost is then calculated as the average of the losses of the entire training set. 
