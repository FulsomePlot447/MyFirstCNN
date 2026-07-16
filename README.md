# FashionNet: Clothing Image Classifier

A custom Convolutional Neural Network (CNN) trained to classify various clothing and fashion items using deep learning.

## Dataset
This model uses the **FashionMNIST** dataset, which is directly loaded from the `torchvision.llibrary`. It consists of 70,000 grayscale images (28x28 pixels) across 10 distinct clothing categories (e.g., T-shirts, trousers, sneakers, bags).

## Notebook Included
* **FashionNet.ipynb**: Contains the complete pipeline including data loading, preprocessing, custom CNN architecture definition, model training loops, and evaluation metrics.

## Model Architecture
The network is built using PyTorch, utilizing sequential convolutional layers (`Conv2d`), max pooling (`MaxPool2d`), and fully connected dense layers (`Linear`) to extract spatial features from the clothing images and classify them.
