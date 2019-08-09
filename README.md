# FashionMNIST_Ensembling_OctaveCNN-TPU  

author: **Khuong Vo**  

Building a convolutional neural network that learns to predict one of the 10 classes of the Fashion-MNIST dataset which comprises grayscale images of 10 different classes of clothes.

This notebook is based on the **fast.ai** course v1  

Run on **TPUs** in **Google Colab**  

**Fashion MNIST image classification with different approaches:**  
  1. **Linear model**
  2. **Single dense layer**
  3. **Basic 'VGG-style' CNN**
  4. **Data augmentation**
  5. **Batchnorm + data augmentation**
  6. **Batchnorm + dropout + data augmentation**
  7. **Octave Convolution + (6)** (No registered 'ResizeNearestNeighborGrad' error, currenly not supported on TPU)
  9. **Ensembling**
    
**Each approach is run with different learning rates (.1, .01, .001, .0001)**
