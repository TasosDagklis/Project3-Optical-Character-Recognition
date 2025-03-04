# Project3-Optical-Character-Recognition
This repository contains a machine learning-based **Optical Character Recognition (OCR) system** that classifies handwritten or printed characters from images. The system takes character images as input and predicts the corresponding letter using **image processing techniques** and **machine learning models**.

## 📌 Project Overview

Optical Character Recognition (OCR) is a fundamental task in **computer vision** that enables the automatic reading of text from images. In this project, the OCR problem is **simplified** by applying **preprocessing techniques** to isolate individual characters and extract **invariant features** before classification.

The dataset and more details can be found here:  
[UCI Letter Recognition Dataset](https://archive.ics.uci.edu/ml/datasets/letter+recognition).

## 🚀 Approach

### 1️⃣ Data Preprocessing
- **Character isolation**: Extracting individual characters from images  
- **Feature extraction**: Computing statistical properties of **spatial pixel distributions**  
- **Normalization**: Scaling features to improve model performance  

### 2️⃣ Model Development
- Implementing **machine learning models**:
  - Support Vector Machines (SVM)
  - Random Forest
  - Convolutional Neural Networks (CNNs)  
- Training models using **labeled character images**  

### 3️⃣ Evaluation & Testing
- Comparing model accuracy using **precision, recall, F1-score**  
- Testing on unseen character images  
- Visualizing misclassified characters for **error analysis**  

## 📊 Dataset

The dataset consists of:
- **Isolated character images**: Preprocessed and labeled  
- **Feature vectors**: Extracted **spatial pixel statistics** for each character  
- **Training and testing sets**: Used for model training and evaluation 
