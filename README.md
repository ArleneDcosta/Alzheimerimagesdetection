# Alzheimer's Disease Detection with Automation

## Overview
This project is a **Node.js** application built with **Express.js** for automating the detection of **Alzheimer's Disease (AD)** using medical images. The images used in this project are sourced from the **OASIS (Open Access Series of Imaging Studies) Database**, a well-known dataset for Alzheimer's research.

For the **front-end**, we have utilized **Flask**, while the machine learning model is developed using **Fastai** with a **DenseNet** architecture for image classification.

## Features
- **Automated Image Processing**: Streamlines the detection process using deep learning.
- **Fastai & DenseNet**: A powerful convolutional neural network model optimized for medical image classification.
- **Flask Front-end**: Provides an intuitive and user-friendly interface for healthcare professionals.
- **Express.js & Node.js Backend**: Ensures smooth automation and integration with databases or external systems.

## Technology Stack
- **Front-end**: Flask (Python-based)
- **Back-end**: Node.js with Express.js
- **Machine Learning**: Fastai with DenseNet
- **Database**: OASIS Dataset

## Installation & Setup
1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-repo/alzheimers-detection.git
   cd alzheimers-detection

2. **Front end Setup (Flask Application) :**
   ```sh
   pip install -r requirements.txt
   python app.py

3. **Model setup :**
   ```sh
   Access the notebook in resources section to access the training notebook. Fine tune model parameters for your application

   # Business Impact of Alzheimer's Disease Detection System

## Business Impact

- **Early Detection:** Helps in identifying Alzheimer's disease at an early stage, leading to better treatment options.
- **Improved Accuracy:** Automated analysis minimizes human errors in diagnosis.
- **Scalability:** Can be deployed in hospitals and research centers for real-world usage.
- **Cost Reduction:** Reduces the cost of diagnosis by automating the classification process.

## Confusion Matrix Output

The model's performance is illustrated below:

**Classification Results:**
- **True Positives (Alzheimer's detected correctly):** 427
- **False Positives (Incorrectly classified as Alzheimer's):** 213
- **False Negatives (Missed Alzheimer's cases):** 84
- **True Negatives (Correctly classified as non-Alzheimer's):** 556

## Future Enhancements

- Implementing more advanced deep learning models for improved accuracy.
- Expanding the dataset for better generalization.
- Deploying the model on cloud platforms for accessibility.
   
