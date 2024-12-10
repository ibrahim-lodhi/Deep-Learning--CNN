# Deep-Learning--CNN

**Dataset Overview**
The CIFAR-10 dataset consists of 60,000 color images, each of size 32x32 pixels, divided into 10 distinct classes, including vehicles and animals. It is split into 50,000 training images and 10,000 test images, with balanced samples across all categories.

**CNN Implementation**

**Architecture Design:**

The CNN was constructed with multiple layers to extract hierarchical image features:
Convolutional Layers: Extract spatial features using filters.
Pooling Layers: Reduce the spatial dimensions and retain essential information.
Fully Connected Layers: Map features to class probabilities.
Additional techniques such as batch normalization were used to stabilize and accelerate training.

**Training Process:**

The CNN was trained using the Adam optimizer, which adapts learning rates dynamically.
A categorical cross-entropy loss function quantified classification performance.
Data augmentation techniques (e.g., flips, crops) were employed to improve model generalization.
Training ran for multiple epochs with real-time accuracy and loss tracking.

**Results:**

Achieved a **78% accuracy** on the CIFAR-10 dataset.
The model effectively distinguished between classes, showcasing the power of CNNs for image classification.


The CNN successfully leveraged spatial feature extraction to classify images in CIFAR-10 with high accuracy, demonstrating its capability to solve complex image recognition tasks efficiently.
