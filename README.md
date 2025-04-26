# Heart Disease Classification

This project implements a machine learning solution to predict the presence or absence of heart disease based on various clinical features using **Logistic Regression**. The model is trained using the **Heart Disease Dataset** from the UCI repository.

## Dataset

The dataset contains information about patients' clinical features and their heart disease status. It includes **age**, **sex**, **chest pain type**, **blood pressure**, **cholesterol**, and other relevant features.

- **Dataset source**: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease)

### Features:

| Feature Name       | Description                                                  |
|--------------------|--------------------------------------------------------------|
| `age`              | Age of the patient (in years)                                |
| `sex`              | Gender (1 = male; 0 = female)                                |
| `cp`               | Chest pain type (4 categories)                               |
| `trestbps`         | Resting blood pressure (in mm Hg)                            |
| `chol`             | Serum cholesterol level (in mg/dl)                           |
| `fbs`              | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)         |
| `restecg`          | Resting electrocardiographic results (3 categories)          |
| `thalach`          | Maximum heart rate achieved                                  |
| `exang`            | Exercise induced angina (1 = yes; 0 = no)                    |
| `oldpeak`          | ST depression induced by exercise relative to rest           |
| `slope`            | Slope of the peak exercise ST segment                        |
| `ca`               | Number of major vessels colored by fluoroscopy               |
| `thal`             | Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect) |

## Objective

The goal of this project is to build a **binary classification** model that predicts the presence or absence of heart disease in a patient, based on their clinical data. Additionally, a **multiclass classification** model is used to predict the **severity** of the disease.

## Steps

1. **Data Preprocessing**  
   - Handle missing values  
   - Feature scaling using `StandardScaler`
   - Split data into training and testing sets

2. **Modeling**  
   - Logistic Regression (Binary and Multiclass)
   - Evaluation using **Accuracy**, **Precision**, **Recall**, **F1 Score**, and **ROC-AUC**

3. **Results**  
   - Confusion Matrix  
   - ROC Curves (for multiclass classification)
   - Classification Report (Precision, Recall, F1-Score)

## Installation

To run the project locally, clone this repository and install the necessary dependencies using `pip`:

```bash
git clone https://github.com/DheerajSingh02/classification_using_logistic_regression.git

