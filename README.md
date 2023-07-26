# **XOR Neural Networks (NNs)**

This project focuses on building and training neural networks to understand and predict XOR logic. The project contains two main parts: a single-layer perceptron and a multi-layer perceptron (MLP). The project is referenced from **[this article](https://towardsdatascience.com/how-neural-networks-solve-the-xor-problem-59763136bdd7)**.

## **Single-layer Perceptron**

The single-layer perceptron is defined in the **`Perceptron`** class. The perceptron is trained to classify inputs based on different logical gates (OR, AND, NAND). Each perceptron object includes the training data, target outputs, learning rate, weights, bias, and node values. The perceptron is trained using the **`train()`** method, which updates the weights and biases based on the gradients.

The perceptron's performance and decision boundary can be visualized using the **`plot()`** method.

## **Multi-layer Perceptron (MLP)**

The MLP is defined in the **`MLP`** class. The MLP is also trained to classify inputs based on XOR logic. Each MLP object includes the training data, target outputs, learning rate, number of epochs, weights, biases, and number of nodes in the input, hidden, and output layers.

The MLP is trained using the **`train()`** method, which performs a forward pass through the network, calculates the error, and then performs a backward pass (backpropagation) to update the weights and biases.

The MLP's performance and decision boundary can be visualized using the **`plot()`** method.

## **Usage**

To use this project, you should initialize the training data and target outputs, create a **`Perceptron`** or **`MLP`** object with the data, and then call the **`train()`** method to train the network. You can use the **`classify()`** method to classify new data points and the **`plot()`** method to visualize the decision boundary.