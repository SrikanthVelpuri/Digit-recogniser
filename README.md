# Digit-recogniser

Importing required libraries,loading data,checking for null values.No missing values so we can proceed.

Normalization : Normalisation of values is done.CNN converge faster on [0...1] than [0..255]

Reshaping the image in 3 dimensions.

Label Encoding: Encode labels to one hot vectors.

Splitting the training and validation set.

Choose the CNN model.

CNN architechture is In -> [[Conv2D->relu]*2 -> MaxPool2D -> Dropout]*2 -> Flatten -> Dense -> Dropout -> Out

Select the optimiser as RMSprop

Compile the model with loss fuction as categorical_crossentropy

Learning rate reduction wheen there is no improvement in accuracy.

data augmentation to prevent overfitting

Fit the model

Validation Accuracy = 99.57

Plotting Confusion matrix for checking out the results.

Displaying some errors for checking proable errors.

For complete analysis of this please refer the ipython notebook "Digit recogniser".


# Capsule Network Implementation of MNIST dataset using keras

Keras implementation of CapsNet in Hinton's paper Dynamic Routing Between Capsules. Code adapted from https://github.com/XifengGuo/CapsNet-Keras/blob/master/capsulenet.py






