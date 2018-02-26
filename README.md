# AI-asssignment

This assignment gives the basic neural network implementaion of digit recognizer using MNIST Dataset.

We trained our model with all kinds ofoptimizers available in Keras such as SGD(using momentum), Adagrad, Adamax, Adam, Adadelta, RMSprop,Nadam.

Out of all of them Adam is giving the best accuracy for this dataset.
We experimentd on the number of hidden layers.

if we choose 1 hidden layer with 784 neurons with Relu as activation function.
  #Accuracy = 98.25%
  
if we choose 2 hidden layers with 1st layer has 784 neurons and other has 600 neurons with "Relu" activation function.
  #Accuracy = 97.96%
  
if we choose 3 hidden layer with 1st layer has 784 neurons and other 2 layers as 600 neurons with "Relu" as activation function.
  #Accuracy = 98.06%
  

final output layer has 10 neurons with "softmax" as activation function,


**So final model has 1 hidden layer with accuracy 98.25%**
  
**1st hidden layer => 784 neurons  "Relu"**

**Output Layer =>     10 neurons  "softmax"**

So we plotted the history of Adam optimizers and analyze the converging relationship with number of epochs.

So 10 epochs were found to be enough for this model.
