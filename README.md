# 🌳 Tree-Species-Classifier

**Tree-Species-Classifier** is a deep learning-based project aimed at identifying different species of trees from images using Convolutional Neural Networks. The project leverages both a custom-built CNN and a pre-trained **EfficientNet** model to achieve accurate and efficient image classification.

## 📌 Project Overview

This project focuses on automating the classification of tree species based on visual features from leaf or bark images. It's designed to support biodiversity research, forestry management, and environmental monitoring efforts using AI.

## 🧠 Models Used

### 1. 🔹 Basic CNN Model

A custom Convolutional Neural Network built from scratch using TensorFlow/Keras. This model serves as a baseline for performance comparison.

### 2. 🔹 EfficientNet

A high-performing transfer learning model (EfficientNetB0) fine-tuned on the dataset for improved accuracy and generalization, especially on small or complex datasets.

## 📂 Dataset

* Images of various tree species
* Preprocessed with resizing, normalization, and augmentation techniques
* Split into training, validation, and testing sets

## 🔧 Tech Stack

* **Python**
* **TensorFlow / Keras**
* **NumPy, Pandas, Matplotlib**
* **EfficientNet from `tensorflow.keras.applications`**
  
## 🔗 Model Training File
You can view the complete training code for this project in the Jupyter Notebook linked below:

https://drive.google.com/file/d/1p4MV2s7r7O7PW3kS9V-HkPu_vO3uBzd6/view?usp=drive_link
https://drive.google.com/file/d/1tPI3RSwCQ9i5pbHgQdhDrkfeysHPmACr/view?usp=drive_link

This notebook includes data loading, preprocessing, CNN model building, training, and evaluation using the Tree Species Identification dataset.


## 🧪 Performance Metrics

* Accuracy, Precision, Recall, and F1-score were used to evaluate both models.
* EfficientNet outperformed the basic CNN in both accuracy and generalization.

## 📌 Future Enhancements

* Expand dataset to include more species
* Integrate with mobile app for real-time predictions
* Add explainability (Grad-CAM visualizations)


