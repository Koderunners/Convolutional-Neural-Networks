# Alexnet
AlexNet is the name of a convolutional neural network, invented by *Alex Krizhevsky*, *Ilya Sutskever* and *Geoffrey Hinton*. AlexNet has had a large impact on the field of machine learning, specifically in the application of deep learning to machine vision. As of 2018 it has been cited over 25,000 times.

AlexNet competed in the [ImageNet Large Scale Visual Recognition Challenge](https://en.wikipedia.org/wiki/ImageNet#ImageNet_Challenge) in 2012. The network achieved a top-5 error of 15.3%, more than 10.8 percentage points lower than that of the runner up. The original paper's primary result was that the depth of the model was essential for its high performance, which was computationally expensive, but made feasible due to the utilization of GPUs during training.

## Architecture
AlexNet contained eight layers; the first five were convolutional layers, and the last three were fully connected layers. It used the non-saturating `ReLU` activation function, which showed improved training performance over `tanh` and `sigmoid`.
The current implementation has been made using Tensorflow which utilizes 6 GB of Nvidia Tesla K80 GPU provided in Kaggle Kernels.

![Alexnet Architecture](https://github.com/Koderunners/Convolutional-Neural-Networks/blob/master/Images/Alexnet.png)

## Authors
* Soumik Rakshit ([Kaggle](https://www.kaggle.com/soumikrakshit)) ([Github](https://github.com/soumik12345))
* Sohom Dey ([Kaggle](https://www.kaggle.com/sohom17d)) ([Github](https://github.com/sohom17d))

## Instructions for Runnnig The Notebook
Link to the notebook on
* [Kaggle](https://www.kaggle.com/soumikrakshit/asl-translation-using-alexnet)
* [Github](https://github.com/Koderunners/Convolutional-Neural-Networks/blob/master/Alexnet/kernel.ipynb)

The Notebook uses the [ASL Alphabet][https://www.kaggle.com/grassknoted/asl-alphabet] dataset.

It is adviced to run the notebook in a Kaggle Kernel with a GPU.
