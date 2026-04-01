# 🩺 Pneumonia Detection Using CNN

## 📌 Introduction

This project is based on building a Convolutional Neural Network (CNN)
model to classify chest X-ray images into two categories: - Normal -
Pneumonia

The goal is to help in early detection of pneumonia using deep learning
techniques.

## 📂 Dataset

The dataset contains 5,863 chest X-ray images of children aged 1--5
years.

It is divided into: - Training set\
- Validation set\
- Testing set

Each folder contains two subfolders: - Normal\
- Pneumonia

## ⚙️ Approach

### 1. Data Preprocessing

-   All images are resized to 150 × 150
-   Pixel values are normalized (0 to 1)
-   Data is loaded using ImageDataGenerator

### 2. Model Building

A simple CNN model is used with: - Convolution layers (feature
extraction) - MaxPooling layers (reduce size) - Dense layers
(classification)

Final layer uses sigmoid activation for binary classification.

### 3. Training

-   Optimizer: Adam\
-   Loss Function: Binary Crossentropy\
-   Epochs: 5\
-   Batch Size: 32

## 📊 Results

-   The model was successfully trained on the dataset.
-   It achieved good accuracy on validation and test data.
-   The accuracy graph shows steady improvement during training.

## 📈 Observations

-   CNN works well for image classification problems.
-   Increasing epochs may improve accuracy.
-   More data or better models can give even better results.

## 🚀 Future Improvements

-   Use advanced models like VGG16 or ResNet
-   Increase training epochs
-   Apply more data augmentation
-   Deploy as a real-world healthcare application

## 🛠️ Tools Used

-   Python\
-   TensorFlow / Keras\
-   Google Colab\
-   Matplotlib

## ✅ Conclusion

This project shows that CNN models can effectively classify chest X-ray
images and help detect pneumonia. It demonstrates how deep learning can
be useful in the healthcare field.
