# Project: Image Classification with TensorFlow

## Objective
This project focuses on building a series of models to classify a series of images into one of ten classes. These images are pretty small ( 32×32×3). This can make classification a bit tricky—human performance is only about 94%.

## Data
CIFAR-10 data set will be used in the project.

Size: 60,000 images, (Train: 50,000, Test: 10,000)
The image is in 32×32 color pixels, each belongs to one of the Ten classes
Data are in NumPy's .npy format.

## Classification models
Smallest Delta Model
Fully-connected NN model
Convolutional NN model
Transfer learning NN model

## Model validation

The validation of this project is using a set of reference models to score the test data accuracy. 
**The accuracy of model prediction = Score * reference model accuracy**

Reference model accuracy:
Smallest Delta Model: reference solution achieves an accuracy of about 44% on a training set and 41% on a test set. 
Fully-connected NN model： train set - 44% on a test set - 41%
Convolutional NN model:  train set - 80% on a test set - 70%
Transfer learning NN model:  train set - 87% on a test set - 85%
