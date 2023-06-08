# Breast-Histopathology-Classification

## Description
A project to solve Kaggle's Breast Histopathology Images Dataset using CNN
- https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images

## Model
Model is inspired by the architecture of the AlexNet, with layers of pooling and batch normalization throughout, due to training (and patience) limits, a smaller network was used, however, if a bigger network was employed, better results could be obtained.

## Results
Evaluated by the confusion matrix at the bottom with an accuracy of 87.4% on the test set.

## Potential Improvements
- Data Augmentation (Stain normalisation / PCA colour)
- **Longer Training (More epochs)**
- Deeper network (more layers / channels)
- Different NN architecture (MobileNet)
- Using different optimizers / loss functions
- Different activation functions (Leaky ReLU, Tanh)
- More diverse convolution frames 