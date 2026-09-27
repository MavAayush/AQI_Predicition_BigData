# AirSense: Intelligent Air Quality Prediction

AirSense is a **Big Data and Machine Learning project** that uses **Apache PySpark and MLlib** to classify Air Quality Index (AQI) categories from large-scale air-quality datasets.

The project implements a complete machine learning pipeline including data ingestion, preprocessing, feature engineering, model training, evaluation, and comparative analysis of multiple classification algorithms.

---

## Project Overview

Air pollution is a major environmental and public health concern. Traditional air-quality monitoring systems depend heavily on physical monitoring stations and sensors, which can be expensive and geographically limited.

AirSense explores how **distributed data processing and machine learning** can be used to analyze air-quality data and classify AQI categories efficiently.

The project uses **PySpark** to process air-quality datasets and evaluates five different machine learning classification algorithms.

### The pipeline includes:

```text
Raw AQI Data
     ↓
Data Loading
     ↓
Data Cleaning & Preprocessing
     ↓
Handling Missing Values
     ↓
Feature Engineering
     ↓
Train / Test Split
     ↓
ML Model Training
     ↓
Model Evaluation
     ↓
Model Comparison
     ↓
AQI Classification
