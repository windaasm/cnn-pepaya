# Papaya Ripeness Detection Using CNN

## Overview
This project implements a Convolutional Neural Network (CNN) to classify papaya ripeness into three categories: immature, partially mature, and fully mature. The system improves accuracy and efficiency compared to manual methods.

## Dataset
- 633 images of papayas (211 images per class: immature, partially mature, fully mature).
- Images resized to 500x500 pixels.
- Data split into training (80%) and testing (20%).
- Dataset can be downloaded from [Google Drive](<https://drive.google.com/drive/folders/1m9wPvL4BwIvpHD24B2w7pgP5m9sKjMtg?usp=sharing>).

## Methods
- **Feature Extraction:**
  - Color (HSV)
  - Texture (GLCM)
  - Shape (Gaussian)
- **Classification:**
  - CNN model with dense layers, ReLU, Softmax, and dropout layers to reduce overfitting.

## Results
- **Accuracy:** 96% on the test set.
- CNN outperformed SVM, which achieved 91% accuracy.

## Conclusion
CNNs are effective for automating papaya ripeness detection, achieving high accuracy and consistency. This approach can replace traditional methods in practical applications.
