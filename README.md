---
title: Melanoma Risk App
emoji: 🩺
colorFrom: blue
colorTo: red
sdk: gradio
sdk_version: "4.44.1"
python_version: "3.10"
app_file: app.py
pinned: false
---

# Melanoma Risk Classification App

This application predicts melanoma risk using a machine learning pipeline trained on the ISIC 2020 skin lesion dataset.

The model combines:
- Image-based features extracted using a pretrained ResNet CNN
- Patient metadata
- Logistic Regression optimized for imbalanced medical classification

## Features

- Upload a skin lesion image
- Enter patient metadata
- Generate melanoma risk prediction
- Displays prediction probability

## Model Pipeline

The final model includes:
- CNN feature extraction
- Feature selection
- Controlled oversampling
- Feature scaling
- Logistic Regression with class weighting
- Threshold tuning for improved melanoma recall

## Important Disclaimer

This application is for educational and research purposes only.

It is **NOT** a medical diagnostic tool and should not be used for clinical decision-making.

Always consult a qualified healthcare professional for medical advice.
