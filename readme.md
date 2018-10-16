# LeNet-5
LeNet-5, a pioneering 7-level convolutional network by LeCun et al. in 1998, that classifies digits, was applied by several banks to recognise hand-written numbers on checks (cheques) digitized in 32x32 pixel images. The ability to process higher resolution images requires larger and more layers of convolutional neural networks, so this technique is constrained by the availability of computing resources.

The LeNet architecture is straightforward and small, (in terms of memory footprint), making it perfect for teaching the basics of CNNs — it can even run on the CPU (if your system does not have a suitable GPU), making it a great “first CNN”.

## Architecture
INPUT => CONV => RELU => POOL => CONV => RELU => POOL => FC => RELU => FC
In the original paper tanh activation function was used but in modern times relu activation function provides better results.
The current implementation has been made using Tensorflow which utilizes 6 GB of Nvidia Tesla K80 GPU provided in Kaggle Kernels.

![Alexnet Architecture](https://github.com/Koderunners/Convolutional-Neural-Networks/blob/master/Images/LeNet-5.jpg)

## Authors
* Soumik Rakshit ([Kaggle](https://www.kaggle.com/soumikrakshit)) ([Github](https://github.com/soumik12345))
* Sohom Dey ([Kaggle](https://www.kaggle.com/sohom17d)) ([Github](https://github.com/sohom17d))

## Instructions for Runnnig The Notebook
Link to the notebook on
* [Kaggle](https://www.kaggle.com/soumikrakshit/asl-translation-using-alexnet)
* [Github](https://github.com/Koderunners/Convolutional-Neural-Networks/blob/master/Alexnet/kernel.ipynb)

The Notebook uses the [MNIST Digit Recognition](https://www.kaggle.com/c/digit-recognizer/data) dataset.

It is adviced to run the notebook in a Kaggle Kernel with a GPU.
