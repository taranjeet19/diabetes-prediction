# Diabetes Prediction using Machine Learning (SVM)

This project aims to predict whether a person is diabetic or not based on diagnostic medical features. It utilizes the **PIMA Indian Diabetes dataset** and builds a machine learning model using the **Support Vector Machine (SVM)** algorithm.

---

## Dataset Overview

- **Source**: [PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Rows**: 768
- **Columns**: 9 (8 input features + 1 target)

### Features:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

### Target:
- `Outcome`: 1 (Diabetic), 0 (Non-diabetic)

---

##  Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## Workflow

1. **Data Loading**  
   Loaded the dataset using Pandas and printed key statistics.

2. **Data Analysis**  
   Used `.describe()` and `.value_counts()` to understand data distribution.

3. **Feature and Label Separation**  
   Split the dataset into input features `X` and target labels `Y`.

4. **Data Standardization**  
   Scaled features using `StandardScaler` to normalize value ranges.

5. **Train-Test Split**  
   Split dataset into training (80%) and testing (20%) sets.

6. **Model Training**  
   Trained an SVM (Support Vector Machine) classifier with a linear kernel.

7. **Accuracy Evaluation**  
   Evaluated accuracy on both training and test data using `accuracy_score`.

---

## Results

| Dataset       | Accuracy |
|---------------|----------|
| Training Data | ~79.8%   |
| Test Data     | ~77.9%   |

The model shows decent accuracy and serves as a good starting point for diabetes prediction using ML.

---

## How to Run

1. Clone this repo or download the `.ipynb` file.
2. Open it in **Google Colab** or **Jupyter Notebook**.
3. Run all cells to see the prediction pipeline in action.

---



