# NN_Fashion_MNIST-vs-CNN_Fashion_MNIST
This two simple model training the same database from keras.database 
with the simple purpose of showing to you how more efficient is the Convolutional neural network 
when we are working in image classification.

This happend because CNN worked with the concept of dimensionality reduction.
As a result we need much less computing power as the parameters increased.

As i mentioned before we have used Keras framework and the database consisti of 60,000 training set examples and 
10,000 test examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.
In our NN model we have 1 hidden layers and 10 nodes , our input layer has as many input as the pixels of our images 784 in this database 
On the other hand in CNN we used a LeNet model with the clasic stracture like in Layer 1 C1 is a convolution layer with 30 convolution kernels of 5x5
Layer 2 S2 is the pooling layer with a 2x2 size that outputs  feature graphs of size 12x12.
Layer 3 C3 is a convolution layer with 15 3x3 convolution kernels.
Layer 4 S4 is similar to S2, with size of 2x2 and output of 15 5x5 feature graphs.
Layer 5 is flatten layer with 375 nodes and fully connected to next layer which has 500 nodes.
Output Layer has 10 calsses.
0	T-shirt/top
1	Trouser
2	Pullover
3	Dress
4	Coat
5	Sandal
6	Shirt
7	Sneaker
8	Bag
9	Ankle boot




