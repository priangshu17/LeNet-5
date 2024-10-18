# LeNet-5
LeNet-5 Architecture on the MNIST Dataset. The test accuracy was an astonishing 98.79
The 5 in the "LeNet-5" stands for the five layers that it uses.
We have 2 Convolution Layer, 2 FC Layer, and the output layer.
The First Convolution Layer. Let's call that ConV1, which has six filters with a size of 5x5 and "valid" padding and tanh as the activation function. It uses an Average Pooling layer of dimension 2x2 with "valid" padding and a stride size of 2.
The Second Convolution Layer. Let's call that ConV1, which has sixteen filters with a size of 5x5 and "valid" padding and tanh as the activation function. It uses an Average Pooling layer of dimension 2x2 with "valid" padding and a stride size of 2.
The first fully connected layer takes 120 neurons, and the second fully connected layer takes 84 neurons, both of which use the tanh activation function.
The output layers have ten neurons and use the Softmax activation function as it is a multi-class classification process.

The model uses the "Adam" Optimizer and "Sparse Categorical Cross Entropy" to calculate the loss.

The model was run for ten epochs with a batch size of 256.
