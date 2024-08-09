<h2 align="center">11 Introduction to Neural Networks</h2>

## Material:

Ch 10 + 11 until (but not including) “Faster Optimizers” (pp. 357 – 378)

For background and as reference: Ch 12

[3Blue1Brown: Neural networks (video series)](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)

Session material: In this folder

You will need to install tensorflow and (optionally) tensorboard before this lesson. Specifically, you need tensorflow 2.0 or higher to be able to use all the functionalities in the notebooks. If you don't know whether you have these packages installed, you can open an anaconda prompt and type

```
pip freeze
```

to see which packages you have and which versions.  
You can run the following commands in the anaconda prompt to get the necessary packages:

```
pip install tensorflow  
pip install tensorboard
```
(If you have an older version of tensorflow, you can upgrade with ```pip install tensorflow --upgrade```).

In addition to this, Tensorflow 2 requires you to install this visual studio package: [https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads) (if you don't have windows or would like to read more, you can do so here: [https://www.tensorflow.org/install/pip](https://www.tensorflow.org/install/pip)).

## Topics
This lecture covers the fundamental aspects of neural networks. 


After attending this lecture, reading the corresponding part of the book and doing exercises, I expect you to be able to:

- Explain what is meant by artificial neurons, and how these are linked to form artificial neural networks.
- Explain what a perceptron is, and how it transforms an input vector to an output, including the importance of weights and biases.
- Discuss how to structure a neural network.
- Discuss and summarize the method of (stochastic) gradient descent and how it is used to train a neural network, including how the learning rate influences results.
- Reflect upon the problems caused by using (a) perceptrons as artificial neurons and (b) the accuracy as the metric to optimize during model training, including how these problems can be solved using activation and loss functions, respectively.
- Sketch different activation functions, including the sigmoid, tanh and ReLU functions, and discuss why the softmax activation function is generally used in the output layer.
- Implement a neural network in python using the tensorflow.keras module.

