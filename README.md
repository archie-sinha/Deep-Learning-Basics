# Deep-Learning-Basics
Explore ANN, CNN, RNN, and Transfer Learning in this deep learning repository. Implement cutting-edge models for diverse tasks. Perfect for learners and practitioners. Contribute to enhancing its richness!  
Usage: Ideal for hands-on learning, experimentation, and staying updated on the latest in deep learning.

**CODE 1: Basics of Tensorflow**
The given Python code implements a basic neural network from scratch using NumPy and pandas. It begins by loading the Iris dataset and performing data preprocessing, including one-hot encoding of the target variable. The neural network is then constructed with an input layer, a hidden layer, and an output layer. The code iteratively updates the weights through backpropagation and gradient descent, aiming to minimize the mean squared error. The training results, including the mean squared error and accuracy, are recorded over iterations and visualized using matplotlib. Finally, the results are saved to a CSV file. The code serves as a hands-on example for understanding the fundamentals of neural network implementation and training.

**CODE 2: ANN Feedforwarding without Tensorflow on Iris Dataset**
The provided Python code utilizes the Iris dataset to implement a simple neural network for multi-output regression. It starts by loading the dataset and preprocessing it, including one-hot encoding the 'Species' column and standardizing the feature values. The neural network architecture involves an input layer, two hidden layers with sigmoid activation, and three output neurons. Weights and biases are initialized, and the sigmoid activation function is defined. The code then calculates the forward pass, computing the output for each neuron. The target values are extracted, and errors are calculated. The total error is determined as the sum of squared errors for each output neuron. This code serves as an introductory example for building a neural network for regression tasks using NumPy and pandas.

