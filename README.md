Build the convolutional neural network model
We are now ready to construct a model to fit to the data. Using the Sequential API, build your CNN model according to the following spec:

The model should use the input_shape in the function argument to set the input size in the first layer.
A 2D convolutional layer with a 3x3 kernel and 8 filters. Use 'SAME' zero padding and ReLU activation functions. Make sure to provide the input_shape keyword argument in this first layer.
A max pooling layer, with a 2x2 window, and default strides.
A flatten layer, which unrolls the input into a one-dimensional tensor.
Two dense hidden layers, each with 64 units and ReLU activation functions.
A dense output layer with 10 units and the softmax activation function.# CNN_MNIST
CNN classifier for the MNIST dataset 
