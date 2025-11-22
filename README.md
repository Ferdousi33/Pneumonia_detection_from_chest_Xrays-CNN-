## Pneumonia detection from chest Xrays(CNN)

## Overview : 
This project implements a Convolutional Neural Network (CNN) to classify chest X-ray images as pneumonia or normal. The model uses data augmentation, normalization, dropout and transfer learning (MobileNetV2) to improve performance.

Prior to any overfitting prevention techniques, the model was trained using a learning rate of o.oo1 and a batch size of 32. The training accuracy was high but validation accuracy was too low.The opposite case is seen in the loss curves indicating overfitting (image - model_performance_1).

Later keeping the batch size and learning rate same, dropout and regularization techniques were applied to reduce overfitting. 
