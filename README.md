# Deep-Learning-Basics
Explore ANN, CNN, RNN, and Transfer Learning in this deep learning repository. Implement cutting-edge models for diverse tasks. Perfect for learners and practitioners. Contribute to enhancing its richness!  
Usage: Ideal for hands-on learning, experimentation, and staying updated on the latest in deep learning.

##**CODE 1: Basics of Tensorflow**

The given Python code implements a basic neural network from scratch using NumPy and pandas. It begins by loading the Iris dataset and performing data preprocessing, including one-hot encoding of the target variable. The neural network is then constructed with an input layer, a hidden layer, and an output layer. The code iteratively updates the weights through backpropagation and gradient descent, aiming to minimize the mean squared error. The training results, including the mean squared error and accuracy, are recorded over iterations and visualized using matplotlib. Finally, the results are saved to a CSV file. The code serves as a hands-on example for understanding the fundamentals of neural network implementation and training.

**CODE 2: ANN Feedforwarding without Tensorflow on Iris Dataset**

The provided Python code utilizes the Iris dataset to implement a simple neural network for multi-output regression. It starts by loading the dataset and preprocessing it, including one-hot encoding the 'Species' column and standardizing the feature values. The neural network architecture involves an input layer, two hidden layers with sigmoid activation, and three output neurons. Weights and biases are initialized, and the sigmoid activation function is defined. The code then calculates the forward pass, computing the output for each neuron. The target values are extracted, and errors are calculated. The total error is determined as the sum of squared errors for each output neuron. This code serves as an introductory example for building a neural network for regression tasks using NumPy and pandas.

**CODE 3: Implementation of Activation Functions**

The provided Python code explores and visualizes various activation functions and their derivatives. It starts with a linear function, calculating its derivative and plotting both the function and its derivative. Next, it demonstrates the sigmoid function and its derivative, followed by the hyperbolic tangent (tanh) function and its derivative. Finally, it covers the rectified linear unit (ReLU) function and its derivative, employing conditional statements for the piecewise definition of ReLU. The code utilizes NumPy and Matplotlib to generate graphs that illustrate the behavior of each function and its derivative, offering a visual understanding of common activation functions used in neural networks.

**CODE 4: ANN Feedforwarding and Back Propagation on Iris Dataset**

The provided Python code implements a simple neural network using the Iris dataset. It begins by preprocessing the data, including one-hot encoding the 'Species' column and standardizing the feature values. The neural network has an input layer of size 4, a hidden layer of size 2, and an output layer of size 3, representing the three species in the Iris dataset. The sigmoid activation function is used. The weights and biases are initialized randomly, and the network is trained through iterations using mean squared error as the loss function. The code also plots the mean squared error over iterations and prints the final mean squared error and accuracy. The results are saved to a CSV file. Note that there are some issues in the code, such as incorrect use of the sigmoid function and potential discrepancies in the dimensions of arrays during backpropagation.

**CODE 5: ANN using Keras with Fashionmnist Dataset**

The provided Python code is for building and training multi-layer perceptron (MLP) models using different activation functions (Sigmoid, ReLU, Leaky ReLU) on the Fashion MNIST dataset. It utilizes the Keras library with TensorFlow as the backend. The code first loads and preprocesses the dataset, reshaping the input images and normalizing pixel values. It then defines MLP models with varying depths and uses stochastic gradient descent (SGD) as the optimizer.

For each activation function (Sigmoid, ReLU, Leaky ReLU), the code trains both shallow and deep MLP models, records their test loss and accuracy, and appends the results to a DataFrame. The final table displays a comparison of the test loss and accuracy for each model configuration. The code makes use of functions provided by Keras, such as Sequential for defining the model architecture and Dense for creating fully connected layers. Additionally, it utilizes the train_test_split function from scikit-learn for splitting the dataset into training and validation sets. The code demonstrates a structured approach to evaluating and comparing the performance of different activation functions in shallow and deep MLPs on the Fashion MNIST dataset.
