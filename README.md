# Pneumonia Detection with Transfer Learning

<a href="https://colab.research.google.com/github/suriyakumar99/Pneumonia-Detection-transferLearning/blob/main/final.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## Overview

This project focuses on detecting pneumonia using a convolutional neural network (CNN) model with transfer learning. The model is trained on chest X-ray images to classify between normal and pneumonia-affected lungs.

## Dataset

The dataset used in this project is organized into training and testing directories, with subdirectories for normal and pneumonia images. Images are preprocessed to ensure consistency and reliability in the model training phase.

## Preprocessing

Preprocessing steps include:
- Loading images from the specified directories.
- Resizing images to a consistent shape (150x150 pixels).
- Converting image data to numpy arrays for model input.
- One-hot encoding the labels for binary classification.

## Model Architecture

The CNN model architecture includes:
- Multiple convolutional layers with ReLU activation functions.
- MaxPooling layers for downsampling.
- Dropout layers to prevent overfitting.
- Fully connected Dense layers leading to the output.

## Training the Model

The model is trained using the ImageDataGenerator for data augmentation. This technique enhances the generalization capability of the model by applying random transformations to the training images.

## Evaluation

The model's performance is evaluated using metrics such as accuracy and F1-score. The evaluation process ensures that the model is not only accurate but also reliable in detecting pneumonia from chest X-ray images.

## Conclusion

This project demonstrates the application of transfer learning for pneumonia detection using CNNs. The model achieves competitive performance on the test dataset, making it a valuable tool for automated medical diagnosis. This approach shows promise for deployment in clinical settings to aid healthcare professionals in the early detection and treatment of pneumonia.

## Acknowledgements

We would like to acknowledge the dataset providers and the contributors of the various libraries and tools used in this project. Special thanks to the Colab team for providing a platform to train and test our models efficiently.

---

Feel free to further customize this README file to better fit your project's specifics and any additional details you'd like to include.
