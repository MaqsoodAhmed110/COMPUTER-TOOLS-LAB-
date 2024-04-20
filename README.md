# COMPUTER-TOOLS-LAB-
This repository is about the learning to upload git and updating it.
SELECING EXISTING AI MODEL 
Convolutional Neural Network (CNN) for Image Classification

This code implements a CNN using TensorFlow's Keras API to classify images from the CIFAR-10 dataset.

Model Architecture:

Input Shape: (32, 32, 3) - representing 32x32 RGB images.
Layers:
Convolutional Layer 1:
Filters: 32
Filter Size: (3, 3)
Activation: ReLU
Kernel Initializer: He uniform
Max Pooling Layer 1:
Pool Size: (2, 2)
Convolutional Layer 2:
Filters: 64
Filter Size: (3, 3)
Activation: ReLU
Kernel Initializer: He uniform
Max Pooling Layer 2:
Pool Size: (2, 2)
Flatten Layer
Dense Layer:
Units: 128
Activation: ReLU
Kernel Initializer: He uniform
Output Layer:
Units: 10 (for 10 classes)
Activation: Softmax
Training Specifications:

Loss Function: Categorical Cross-Entropy
Optimizer: Adam
Metrics: Accuracy
Epochs: 4
Initial Accuracy:

The initial accuracy on the test data is about 60%.
