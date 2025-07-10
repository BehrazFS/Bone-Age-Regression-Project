# Bone-Age-Regression-Project : Bone Age Prediction from Hand X-ray Images using PyTorch
## 📌 Project Overview
This project implements a deep learning model that predicts the bone age of pediatric patients from hand X-ray images. Using a convolutional neural network (CNN) trained on medical imaging data, the model estimates the bone age in months, helping provide a non-invasive and fast second opinion to radiologists. The solution leverages the RSNA Bone Age Challenge Dataset and is built with PyTorch.

## 🔍 Features
✅ Preprocessing of grayscale medical images (normalization, resizing, augmentation).

✅ Custom PyTorch Dataset and DataLoader pipeline.

✅ Regression CNN model for predicting bone age in months.

✅ Training loop with validation and learning rate scheduling.

✅ MSE and MAE loss tracking during training.

✅ Visualization of predictions vs actual bone ages.

## 📊 Dataset
Source: RSNA Pediatric Bone Age Challenge Dataset

Images: 12,000+ pediatric hand X-rays

Labels: Bone age in months (continuous values)

Preprocessing: Cropping, resizing (e.g., 224x224), intensity normalization

## 📈 Evaluation Metric
Mean Absolute Error (MAE) in months is the primary evaluation metric, matching clinical practice.

Other metrics: MSE, R²
## Team membbers:
https://github.com/BehrazFS <br>
https://github.com/Alireza-Sobhdoost <br>
https://github.com/Wnpkmi
