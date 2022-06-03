# Multiclass classification on Stanford Dog Breeds dataset

## Background

Deep learning provides many successful machine learning results to solve real world problems.
Among all those problems, image classification is a crucial part in computer vision. It can be
implemented using both unsupervised learning methods such as hierarchical clustering, k-means
clustering, maximum likelihood algorithms, which tries to find patterns in a dataset without labels. And
supervised learning methods, which learns to map a function from the labeled training data to an output.
In our project, we built convolutional neural network-based image classifiers to identify and
separate images of different breeds of dogs. We first defined a model that defeats the baseline and then
applied 3 different pretrained models: EfficientNet, VGG16 and Xception to better classify the images
and make predictions using the test data. Those pre-trained neural networks were useful for transfer
learning, but the training process could take expensive computation power. The objects of the project
were to show how to build a real-world convolutional neural network, and to compare the pretrained
model based on their performance on the prediction task.
