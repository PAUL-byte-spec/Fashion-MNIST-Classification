# Fashion MNIST Classification with Convolutional Neural Network (CNN)
This project aims to train a convolutional neural network (CNN) using Keras to classify images from the Fashion MNIST dataset. The Fashion MNIST dataset consists of 60,000 training images and 10,000 testing images, each of size 28x28 pixels, belonging to 10 different fashion categories.

# Getting Started
Prerequisites
To run the code, you need to have the following installed:

 * Python (version 3.x)
 * TensorFlow
 * Keras

# Install the required dependencies using pip:
 pip install tensorflow keras

# Clone this repository to your local machine:

https://github.com/PAUL-byte-spec/Fashion-MNIST-Classification.git
Navigate to the project directory:

cd fashion-mnist-cnn
Run the Python script:

fashion mnist classification_1.ipynb
Expected Output
After running the script, you should see the training progress and the evaluation results, including the test accuracy of the trained model.

# Understanding the Code
fashion mnist classification_1.ipynb: This is the main Python script containing the code to load the Fashion MNIST dataset, define and train the CNN model, and evaluate its performance.
# Dataset
The Fashion MNIST dataset is automatically downloaded and loaded using Keras's built-in dataset module. It consists of images representing 10 different fashion categories, including T-shirts, trousers, dresses, etc.

# Model Architecture
The CNN model architecture used in this project consists of three convolutional layers with ReLU activation followed by max-pooling layers, and two fully connected (dense) layers with ReLU and softmax activation functions.

# Results
After training the model for a certain number of epochs, the script evaluates the model on the test set and prints out the test accuracy.

# Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
