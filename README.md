## Pneumonia detection from chest Xrays(CNN)

## Overview : 
This project implements a Convolutional Neural Network (CNN) to classify chest X-ray images as pneumonia or normal. The model uses data augmentation, normalization, dropout and transfer learning (MobileNetV2) to improve performance.

Prior to any overfitting prevention techniques, the model was trained using a learning rate of o.oo1 and a batch size of 32. The training accuracy was high but validation accuracy was too low.The opposite case is seen in the loss curves indicating overfitting (image - model_performance_1).

Later keeping the batch size and learning rate same, dropout and regularization techniques were applied to reduce overfitting. Though accuracy did not show any significant improvement, loss decreased, indicating less overfit and model was learning better (image - model_performance_2). 

Lastly, The model was trained using a batch size of 64 and a learning rate of 0.0005. Data augmentation and Transfer learning using MobileNetV2 as a pre-trained backbone was employed, improving feature extraction but training time inceased significantly almost 3 hrs. After training, the loss decreased sharply, indicating improved model stability.  Accuracy showed steady performance, suggesting that the model had become more confident in its predictions. However the curves are not fully ideal yet (image - model_performance_3).

## Improvements :
Fine tuning, evaluating with metrics, experimenting with different pre-trained models can be performed to improve convergence and overall performance.



