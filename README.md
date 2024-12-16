# Pneumonia Detection Using CNN
Pneumonia is a serious lung infection caused by bacteria, viruses, or fungi, and it is a significant cause of death, particularly in children under five years old and in the elderly. Chest X-rays are the primary tool used by radiologists to detect pneumonia and identify the affected areas in the lungs.


The main objective of this project is to develop a deep learning model, specifically a Convolutional Neural Network (CNN), to accurately detect pneumonia from chest X-ray images. This model aims to assist doctors by providing a quick and reliable diagnosis, enabling timely treatment for patients. By training the CNN on a well-curated dataset of chest X-ray images, the model can learn to distinguish between healthy and infected lungs with high accuracy.

## Table of Contents

- [Project Description](#project-description)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Results](#results)
- [Acknowledgement](#acknowledgement)

## Project Description

This project utilizes deep learning techniques to classify chest X-rays into two categories:
- **Normal**
- **Pneumonia**

The notebook includes all key steps, from loading and preprocessing data to model training and evaluation.

## Dependencies

The following libraries are used in the project:

- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV (cv2)
- OS (for file management)

## Dataset

The dataset used for this project is the [Chest X-Ray Images (Pneumonia)](https://universe.roboflow.com/mohamed-traore-2ekkp/chest-x-rays-qjmia/dataset/4) dataset available on Robo flow. It contains:

- **Training Set**: Images used for training the CNN.
- **Validation Set**: Images used for hyperparameter tuning.
- **Test Set**: Images used to evaluate the model's performance.

## Results

| Metric               | Value       |
|----------------------|-------------|
| **Training Accuracy** | 98.16%      |
| **Validation Accuracy** | 100.00%    |
| **Test Data**         | 582 images  |

## Acknowledgement
This project is done under guidance of [Dr Agughasi Victor Ikechukwu](Victor-Ikechukwu) and Prof.Shashanka H P
