# Brain Tumor Detection using CNN

## Summary

This project implements a Convolutional Neural Network (CNN) for the binary classification of brain tumor images. The model aims to accurately distinguish between tumor and non-tumor images by leveraging advanced neural network techniques.

## Architecture and Techniques

- **Convolutional Layers**: The architecture includes **three convolutional layers** designed to extract meaningful features from the input images.

- **Max Pooling Layers**: There are **three max pooling layers** that reduce the spatial dimensions of the feature maps, aiding in the control of overfitting and improving model efficiency.

- **Dense Layer**: The model features a **single dense layer** with **256 units**, which facilitates the learning of complex patterns after feature extraction.

- **Regularization Techniques**: 
  - **L2 Regularization**: Implemented with values of **0.5** and **0.0001** in different configurations to prevent overfitting by penalizing large weights.
  - **Dropout**: Applied with rates of **0.20** and **0.10** in specific configurations, enhancing the model's robustness by randomly setting a fraction of input units to 0 during training.

The model employs **ImageDataGenerator** for real-time data augmentation and preprocessing, significantly enhancing its generalization capabilities. This combination of techniques has resulted in achieving an impressive **F1-score of 0.97**, indicating high accuracy in classifying brain tumor images.
