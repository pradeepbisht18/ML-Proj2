# ML-Proj2
Handwritten Image Recognition

This project is to implement and evaluate classification algorithms. The classification task will be to
recognize a 28 x 28 grayscale handwritten digit image and identify it as a digit among 0, 1, 2, ... , 9.
You are required to do the following three tasks.
1. Implement logistic regression, train it on the MNIST digit images and tune hyperparameters
2. Implement single hidden layer neural network, train it on the MNIST digit images and tune
hyperparameters such as the number of units in the hidden layer
3. Use a publicly available convolutional neural network package, train it on the MNIST digit images
and tune hyperparameters


Plan of Work
1. Extract feature values and labels from the data: Download the MNIST dataset from the
Internet and process the original data file into a Numpy array that contains the feature vectors
and a Numpy array that contains the labels.
2. Data Partition: The MNIST dataset is originally partitioned into a training set and a testing
set. You will use this partition and train your model on the training set.
3. Train model parameter: For a given group of hyper-parameters such as the number of layers
and the number of nodes in each layer, train the model parameters on the training set.
4. Tune hyper-parameters: Validate the classfication performance of your model on the vali-
dation set. Change your hyper-parameters and repeat step 3. Try to find what values those
hyper-parameters should take so as to give better performance on the testing set.
