# Eye Prediction Model (Eye/Non-Eye Image Classification)

## Introduction

The Eye Prediction Model is a machine learning (ML) model developed to classify whether an input image contains a human eye or not. The model serves as a validation layer for eye disease diagnosis systems by ensuring that only valid eye images proceed to the disease detection stage.

The project was developed using Python in Google Colab and utilizes transfer learning with the MobileNetV2 Convolutional Neural Network (CNN) architecture. TensorFlow and Keras were used for model development, training, and evaluation.

This model addresses a common challenge in eye disease detection applications, where users may accidentally upload irrelevant images. By automatically filtering out non-eye images, the system can improve the reliability and efficiency of downstream eye disease classification models.

---

## Dataset

A custom dataset was collected and prepared from publicly available sources, such as Kaggle and Roboflow. The dataset consists of two classes:

* **Eye Images** – Images containing human eyes from various conditions, angles, and lighting environments.
* **Non-Eye Images** – Images that do not contain human eyes, including everyday objects, scenery, animals, buildings, indoor scenes, and etc.

The dataset was divided into training and testing sets to evaluate the model's performance. Data preprocessing and augmentation techniques were applied to improve model generalization and robustness.

---

## Link to Baseline Model

**GitHub Repository:**
[https://github.com/praths71018/Eye_Disease_Prediction/]

---

## Acknowledgements

This project was developed using TensorFlow, Keras, and the MobileNetV2 architecture. The initial training and testing code structure was adapted from an open-source GitHub repository (by @praths71018) and subsequently modified to suit the eye/non-eye image classification task. Significant changes were made to the dataset, preprocessing pipeline, model configuration, and evaluation process to meet the objectives of this project.

Special thanks to the open-source community for providing valuable resources, documentation, and reference implementations that supported the development of this work.
