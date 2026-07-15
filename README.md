# Machine Learning-Based Incipient Fault Diagnosis in Power Transformers

A machine learning project that predicts incipient transformer faults using Dissolved Gas Analysis (DGA) data. The project focuses on preprocessing transformer gas data, performing exploratory data analysis, training machine learning models, and evaluating their performance for accurate fault classification.

---

## Project Overview

Power transformers are among the most critical components of an electrical power system. Internal insulation failures generate characteristic gases dissolved in transformer oil. By analyzing these gases, early-stage transformer faults can be detected before catastrophic failures occur.

This project uses machine learning techniques to automate transformer fault diagnosis based on Dissolved Gas Analysis (DGA).

---

## Objectives

- Clean and preprocess raw DGA data
- Handle missing values and duplicate records
- Perform Exploratory Data Analysis (EDA)
- Train machine learning classification models
- Predict transformer fault categories
- Evaluate model performance using standard classification metrics

---

## Dataset

The dataset contains transformer oil gas measurements obtained through Dissolved Gas Analysis.

### Features

- H₂
- CH₄
- C₂H₂
- C₂H₄
- C₂H₆
- CO
- CO₂

### Target Classes

- Partial Discharge (PD)
- Low Energy Discharge (D1)
- High Energy Discharge (D2)
- Low Temperature Thermal Fault (T1)
- Medium Temperature Thermal Fault (T2)
- High Temperature Thermal Fault (T3)
- Normal

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

---

## Project Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Handling Missing Values
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Machine Learning Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Transformer Fault Prediction
```

---

## Visualizations

The project includes various visualizations such as:

- Class Distribution
- Correlation Heatmap
- Confusion Matrix
- Feature Importance
- Model Performance Metrics

Visual outputs are available inside the **visuals/** folder.

---

## Repository Structure

```
data/
notebooks/
visuals/
models/
report/
README.md
requirements.txt
```

---

## Future Improvements

- Deep Learning based classification
- Real-time IoT sensor integration
- Transformer health dashboard
- Cloud deployment
- Larger industrial datasets

---

## Author

Arjun Dhaka

B.Tech Electrical & Electronics Engineering

Galgotias College of Engineering & Technology
