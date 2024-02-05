# 🚀 CIFAR10 dataset

Task: Training a neural network for classification on the CIFAR10 dataset.

[Link to kaggle](https://www.kaggle.com/code/anastasiakorotkova/mnist)

## Metric : Accuracy

## Results:
Four models were trained with gradual complication:
1. 2 convolutional layers, max pooling, 3 linears
2. 6 convolutional layers, 3 max pooling, 2 linears
3. 6 convolutional layers, 3 max pooling, 7 batch normalization, 2 linears
4. 6 convolutional layers, 3 max pooling, 7 batch normalization, 2 linears, 4 dropout (for regularization NN)

Data augmentation was done in several ways:
1. custom data augmentation
2. random data augmentation
3. best learned augmentation

Finally selected the fourth model with the best learned augmentations and increased the number of epochs to 40(this allowed us to achieve excellent quality of 85 percent)