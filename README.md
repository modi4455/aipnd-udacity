# aipnd-udacity

In this project, you'll train an image classifier to recognize different species of flowers. You can imagine using something like this in a phone app that tells you the name of the flower your camera is looking at. In practice, you'd train this classifier, then export it for use in your application. We'll be using this dataset of 102 flower categories.

When you've completed this project, you'll have an application that can be trained on any set of labelled images. Here your network will be learning about flowers and end up as a command line application. But, what you do with your new skills depends on your imagination and effort in building a dataset.

This is the final Project of the Udacity AI with Python Nanodegree
## Prerequisites
The Code is written in Python 3.6
Additional Packages that are required are: Numpy, Pandas, MatplotLib, Pytorch, PIL and json.
## Json file
In order for the network to print out the name of the flower a .json file is required.
## GPU
As the network makes use of a sophisticated deep convolutional neural network the training process is impossible to be done by a common laptop. In order to train your models to your local machine you have three options

* Cuda -- If you have an NVIDIA GPU then you can install CUDA from here. With Cuda you will be able to train your model however the process will still be time consuming
* Cloud Services -- There are many paid cloud services that let you train your models like AWS or Google Cloud
