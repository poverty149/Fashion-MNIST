# Fashion-MNIST

## Introduction
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. We intend Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.
The below picture provides us a glimpse of the contents of the dataset.
![input](https://user-images.githubusercontent.com/49677872/150699525-b3d7fa27-b830-4485-97fb-d31b97ed3edf.PNG)

## Requirements
* TensorFlow 2.x
* Keras
* Numpy

##  Model
The diagram below illustrates the model I used to train the dataset.
![sequential](https://user-images.githubusercontent.com/49677872/150699451-727035fa-80c0-41e7-968f-23df6adf976c.PNG)

## Training
I split the dataset into 60000 image files into training and 10000 image files into test. Batch sizes of 128 pictures were trained for 25 epochs.
