# Computer Tools Lab: Convolutional Neural Network (CNN) for Image Classification

This repository focuses on learning to use Git, including uploading and updating repositories, while implementing a **Convolutional Neural Network (CNN)** for image classification. The model uses TensorFlow's Keras API to classify images from the **CIFAR-10** dataset.

---

## Model Overview

The code implements a CNN designed for classifying 32x32 RGB images into 10 distinct classes (e.g., airplanes, cars, birds, etc.). Below is the detailed architecture of the model.

### Model Architecture

- **Input Shape:** (32, 32, 3) - representing 32x32 RGB images.

#### Layers
1. **Convolutional Layer 1:**
   - Filters: 32
   - Filter Size: (3, 3)
   - Activation: ReLU
   - Kernel Initializer: He uniform

2. **Max Pooling Layer 1:**
   - Pool Size: (2, 2)

3. **Convolutional Layer 2:**
   - Filters: 64
   - Filter Size: (3, 3)
   - Activation: ReLU
   - Kernel Initializer: He uniform

4. **Max Pooling Layer 2:**
   - Pool Size: (2, 2)

5. **Flatten Layer**

6. **Dense Layer:**
   - Units: 128
   - Activation: ReLU
   - Kernel Initializer: He uniform

7. **Output Layer:**
   - Units: 10 (one for each class in CIFAR-10)
   - Activation: Softmax

---

## Training Specifications

- **Loss Function:** Categorical Cross-Entropy
- **Optimizer:** Adam
- **Metrics:** Accuracy
- **Epochs:** 4

---

## Initial Results

- **Initial Accuracy:** The initial accuracy on the test data is approximately 60%.

This project showcases the fundamental steps in CNN architecture for image classification and provides hands-on experience with Git for version control. Explore, experiment, and update the code as you learn more about CNNs and image classification techniques!
