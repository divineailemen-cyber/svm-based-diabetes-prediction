# Diabetes Prediction using Support Vector Machine (SVM)

## Project Overview

This project builds a machine learning model to predict whether a patient has diabetes based on medical diagnostic data. The model is implemented using a Support Vector Machine (SVM), a supervised learning algorithm commonly used for classification tasks.

The entire workflow — including data preprocessing, model training, and evaluation — is carried out in a Jupyter Notebook.

---

## Dataset

The dataset used in this project is as `diabetes.csv`.

It contains medical features such as:

*Pregnancies
*Glucose
*BloodPressure
*SkinThickness
*Insulin
*BMI
*DiabetesPedigreeFunction
*Age
*Outcome

**Target Variable:**

* `Outcome` → 1 (Diabetic), 0 (Not Diabetic)

---

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Scikit-learn

---

## Model Workflow

The project follows these steps:

1. Data loading using Pandas
2. Feature and target separation
3. Train-test split
4. Feature scaling using StandardScaler
5. Training the SVM model
6. Model evaluation using accuracy score and classification report

---

## Project Structure

/data
  diabetes.csv

/notebooks
  diabetes_svm_model.ipynb

README.md
.gitignore

---

## How to Run

1. Clone the repository:
   git clone <https://github.com/divineailemen-cyber/svm-based-diabetes-prediction/tree/main>

2. Navigate into the project folder:
   cd <svm-based-diabetes-prediction>

3. Install dependencies:
   pip install numpy pandas scikit-learn notebook

4. Launch Jupyter Notebook:
   jupyter notebook

5. Open and run:
   notebooks/diabetes_svm_model.ipynb

---

## Results

The SVM model was trained and evaluated on the dataset.
The model achieved 77.27% accuracy on the test data.

---

## Objective

The goal of this project is to apply machine learning techniques to a healthcare dataset in order to build a predictive model for early detection of diabetes.

---

## Future Improvements

* Hyperparameter tuning for improved accuracy
* Testing other models (e.g., Decision Trees, Random Forest)
* Adding data visualization
* Deploying the model as a web application

---

## Contribution

Contributions are welcome. Feel free to fork the repository and submit a pull request.

---

## Contact

For questions or collaboration, feel free to reach out.

