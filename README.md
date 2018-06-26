# QSTP-Image-Recognition

I have made a 2 layer CNN with Batchnorm with p=0.5, Non-linear activation through ReLU, max pooling and one fully connected layer. The Loss Class I have used is Cross Entropy Loss, and the Optimizer Class used is SGD. The accuracy after 3000 iterations(5 epochs) is 88%.

I have used the Cross Entropy Loss, as it is useful for training classification problems. Also this criterion combines nn.LogSoftMax() and nn.NLLLoss() in one single class.

## About the dataset:

The Fashion-MNIST dataset conatains a total of 70K images(60K training dataset + 10K test dataset) of 10 types of fashion items like boots, t-shirts etc. It is similar to the MNIST dataset in terms of image size (28X28) and number of labels (10).
This is how the dataset looks like:
![fashionmnist](https://user-images.githubusercontent.com/33350121/41902212-863809e8-7950-11e8-9366-dc087aed49f9.jpg)
