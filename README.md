# pyradox
A Deep Learning framework built on top of Keras containing implementations of Artificial Neural Network Architectures

These implementations neither have a start nor an end just an interesting middle
___
# Installation

    pip install git+https://github.com/Ritvik19/pyradox.git
___

# Usage

1. Modules
   1. [Convolution2D](tutorials/Convolution2D.ipynb) Applies 2D Convolution followed by Batch Normalization (optional) and Dropout (optional)
   2. [DenselyConnected](tutorials/DenselyConnected.ipynb) Densely Connected Layer followed by Batch Normalization (optional) and Dropout (optional)
   3. [DenseNetConvolutionBlock](tutorials/DenseNetConvolutionBlock.ipynb) A Convolution block for DenseNets
   4. [DenseNetTransitionBlock](tutorials/DenseNetTransitionBlock.ipynb) A Transition block for DenseNets
   5. [VGGModule](tutorials/VGG-Module.ipynb) Implementation of VGG Modules with slight modifications, Applies multiple 2D Convolution followed by Batch Normalization (optional), Dropout (optional) and MaxPooling
2. ConvNets
   1.  [GeneralizedDenseNets](tutorials/GeneralizedDenseNets.ipynb) A generalization of Densely Connected Convolutional Networks (Dense Nets)
   2.  [DenselyConnectedConvolutionalNetwork121](tutorials/DenselyConnectedConvolutionalNetwork121.ipynb) AA modified implementation of Densely Connected Convolutional Network 121
   3.  [DenselyConnectedConvolutionalNetwork169](tutorials/DenselyConnectedConvolutionalNetwork169.ipynb) AA modified implementation of Densely Connected Convolutional Network 169
   4.  [DenselyConnectedConvolutionalNetwork169](tutorials/DenselyConnectedConvolutionalNetwork169.ipynb) AA modified implementation of Densely Connected Convolutional Network 169
   5. [GeneralizedVGG](tutorials/GeneralizedVGG-1.ipynb) A generalization of VGG networks, check another [Usage Example](tutorials/GeneralizedVGG-2.ipynb)
   6. [VGG16](tutorials/VGG16-1.ipynb) A modified implementation of VGG16 network, check another [Usage Example](tutorials/VGG16-2.ipynb)
   7. [VGG19](tutorials/VGG19-1.ipynb) A modified implementation of VGG19 network, check another [Usage Example](tutorials/VGG19-2.ipynb)
3. DenseNets
   1. [DenselyConnectedNetwork](tutorials/DenselyConnectedNetwork.ipynb) Network of Densely Connected Layers followed by Batch Normalization (optional) and Dropout (optional)