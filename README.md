# Prostate Cancer Prediction (Accuracy: 0.76%)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Table of Contents
| Section |
|-------- |
| [Introduction](#Introduction) |
| [Count for Malignant and Benign Cancer Cases](#Count-for-Malignant-and-Benign-Cancer-Cases) |
| [Correlation between Cancer Morphology](#Correlation-between-Cancer-Morphology) |
| [Dataset](#Dataset) |
| [Run Locally](#Run-Locally) |
| [Usage](#Usage) |
| [License](#License) |

## Introduction
This project aims to predict the likelihood of prostate cancer using machine learning techniques. The model achieved an accuracy of 0.76% on the test dataset. The dataset used for training and testing the model was obtained from Kaggle and contains various features relevant to prostate cancer diagnosis.

## Count for Malignant and Benign Cancer Cases
![Count for Malignant and Benign Cases](https://github.com/cgreenwood23/Prostate_Cancer_Predicition/assets/153872154/710b5479-b4d3-45f5-b2ab-a2aa41ecd7d0)

## Correlation between Cancer Morphology
![Cancer Morphology](https://github.com/cgreenwood23/Prostate_Cancer_Predicition/assets/153872154/4b004a6f-accc-41d2-88ad-e9dda11cabbb)

## Dataset
Downloaded from Kaggle: https://www.kaggle.com/datasets/sajidsaifi/prostate-cancer

## Run Locally
To run this project locally, follow these steps:

### Install dependencies
```bash
pip install -r requirements.txt
```
### Run the Application
```bash 
python main.py
```

### Usage 
After installing the dependencies and running the application, you can use the model to make predictions by providing the necessary input features. The input should include patient details such as age, PSA levels, and biopsy results.

### License
MIT License
