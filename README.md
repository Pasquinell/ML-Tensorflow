# Machine Learning with Tensorflow


The purpose of this project is to help data science and machine learning students how to use Tensorflow to solve common machine learning problems. Is common to find examples of tensorflow applied to convolutional and recurrent neural networks for solving problems of image recognition and natural language processing. But tensorflow can be also implemented in a day-to-day machine learning problems.

In this opportunity, we will learn how to implement logistic regression with sigmoid function and softmax, how to implement stochastic gradient descent and implement L2Loss and dropout regularization. On top of this, the data preprocessing will be implemented with numpy, pandas and sklearn. For this we will use the titanic dataset from [kaggle titanic challenge](https://www.kaggle.com/c/titanic/data)

Each code presents a fast and accurate way to preprocess the data with pandas, numpy and sklearn. Then we will explore diferent model and model features, increasing the degree of complexity, in particular

1_LogReg_OneHotEncoder.ipynb: explores how to implement logistic regression but not using the sigmoid function, but implementing one-hot-encoding a useful tool for working with more than two categories.

2_LogReg_SGD.ipynb: explores how to implement stochastic gradient descent

3_NeuralNet_one_hidden_layer.ipynb: explores how to build a one-hidden-layer neural network and then show the power of it


In the next edditions, we will explore one of the most important concepts in machine learning: regularization and validation.

## Docker 

If you don't want to install tensorflow in your computer I suggest downloading Docker and executing the folowing image


```shell
docker run -it -p 8888:8888 gcr.io/tensorflow/tensorflow
```

