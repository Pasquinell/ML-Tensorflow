# Machine Learning with Tensorflow


The purpose of this project is to help data science and machine learning students to use TensorFlow to solve common machine learning problems. Usually, many examples can be found of TensorFlow being applied to convolutional and recurrent neural networks for solving problems of image recognition and natural language processing. But TensorFlow can be also implemented in a day-to-day machine learning problems.

In this opportunity, we will learn how to implement logistic regression with softmax function, stochastic gradient descent and L2Loss and dropout regularization. On top of this, the data preprocessing will be implemented with numpy, pandas and sklearn. For this we will use the titanic dataset from [kaggle titanic challenge](https://www.kaggle.com/c/titanic/data)

Each code presents a fast and accurate way to preprocess the data with pandas, numpy and sklearn. Then we will explore diferent models and its features, increasing the degree of complexity:

1_LogReg_OneHotEncoder.ipynb: explores how to implement logistic regression not using the sigmoid function, but implementing one-hot-encoding, a useful tool for working with more than two categories.

2_LogReg_SGD.ipynb: explores how to implement stochastic gradient descent.

3_NeuralNet_one_hidden_layer.ipynb: explores how to build a one-hidden-layer neural network.


In the next edditions, we will explore one of the most important concepts in machine learning: regularization and validation.

## Docker 

If you don't want to install TensorFlow in your computer I suggest downloading Docker and executing the folowing command


```shell
docker run -it -p 8888:8888 gcr.io/tensorflow/tensorflow
```

