# Diabetes Prediction System for Pima Women

This project aims to build a predictive model for diagnosing diabetes in female patients of Pima Indian heritage. The system uses various diagnostic measurements to predict whether a patient is likely to have diabetes.

## Created By:
* **Ghulam Mustafa Tariq (660)**
* **Muhammad Abdullah (319)**
* **Tayyab Akram (530)**

## Project Overview

The objective is to predict the occurrence of diabetes (Outcome = 1) or its absence (Outcome = 0) based on clinical data. The dataset used is the Pima Indians Diabetes Dataset.

### Dataset Description

The dataset includes the following features:
1. **Pregnancies**: Number of pregnancies
2. **Glucose**: Plasma glucose concentration
3. **BloodPressure**: Diastolic blood pressure (mm Hg)
4. **SkinThickness**: Triceps skin fold thickness (mm)
5. **Insulin**: 2-Hour serum insulin (mu U/ml)
6. **BMI**: Body mass index (weight in kg/(height in m)^2)
7. **DiabetesPedigreeFunction**: Diabetes pedigree function (genetic score)
8. **Age**: Age in years
9. **Outcome**: Class variable (0 or 1)

## System Architecture

The project follows a standard machine learning workflow:
- **Data Exploration**: Understanding the data distribution and relationships.
- **Data Visualization**: Boxplots, histograms, and correlation analysis.
- **Data Preprocessing**: Handling outliers and scaling features.
- **Modeling**: Training models like Support Vector Machine (SVM).
- **Evaluation**: Assessing model performance using accuracy scores.

## Installation

To run this project, make sure you have Python installed. You can install the required dependencies using:

```bash
pip install -r requirements.txt
```

## How to Run

1. Clone or download the repository.
2. Ensure `diabetes.csv` is in the same directory as the notebook.
3. Open `Diabetes Prediction System.ipynb` in VS Code or Jupyter Notebook.
4. Run all cells to see the analysis and model training results.

## Technologies Used

- Python
- Pandas & NumPy (Data Manipulation)
- Matplotlib & Seaborn (Data Visualization)
- Scikit-Learn (Machine Learning)
- Joblib (Model Persistence)

## Conclusion

The system successfully processes clinical data and provides a prediction using a Support Vector Machine model, showing promising results for early diabetes screening.
