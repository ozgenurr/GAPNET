## Data
Classification was performed on apple, grape, potato plant leaves in the Plant Village data set.
The experiments were first performed separately on each data set, then three data sets were combined and studied on 11 classes. 
In order to eliminate data imbalance between classes within the data sets, data augmentation was performed with the SMOTE method.

Data sets and data numbers used for Leaf Disease Classification are given in the table below.

![data sayilari](https://github.com/user-attachments/assets/7759cbbc-06d7-4626-a8d4-db8d362014e9)

## Environment
All experiments in this study were conducted using the Google Colab environment. A100 GPU was used.

## Code
A lightweight SqueezeNet model, GAPNet, is proposed for Grape, Apple and Potato leaf disease classification. Pre-trained convolutional neural networks VGG16, ResNet50, SqueezeNet, Xception, ShuffleNet, DenseNet121 and MobileNetV2 are used to compare model performance.
