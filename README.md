# 🩺 Heart Disease Prediction using Logistic Regression

This project implements a **Logistic Regression** model to predict the likelihood of heart disease based on patient health data.  
It uses **Python**, **Pandas**, **NumPy**, and **Scikit-learn** for data processing, model training, and evaluation.

---

## 📌 Table of Contents
- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [How to Run](#how-to-run)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 📖 About the Project
Heart disease is one of the leading causes of death worldwide.  
Early prediction can save lives by enabling timely medical intervention.  

This project:
- Trains a **Logistic Regression** classifier on medical records.
- Uses patient data such as age, cholesterol, blood pressure, etc.
- Predicts whether a patient is likely to have heart disease (`1`) or not (`0`).

---

## 📂 Dataset
- **Source:**  "heart_disease_data.csv" 
- **Features:**
  - `age`: Age of the patient
  - `sex`: Gender (1 = male, 0 = female)
  - `cp`: Chest pain type
  - `trestbps`: Resting blood pressure
  - `chol`: Serum cholesterol in mg/dl
  - `fbs`: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
  - `restecg`: Resting electrocardiographic results
  - `thalach`: Maximum heart rate achieved
  - `exang`: Exercise-induced angina (1 = yes, 0 = no)
  - `oldpeak`: ST depression induced by exercise
  - `slope`: Slope of the peak exercise ST segment
  - `ca`: Number of major vessels colored by fluoroscopy
  - `thal`: Thalassemia type
  - `target`: (1 = heart disease present, 0 = not present)

---

## 🛠 Technologies Used
- **Python 3**
- **Pandas** – Data loading & preprocessing
- **NumPy** – Numerical operations
- **Scikit-learn** – Machine learning algorithms & metrics
- **Google Colab / Jupyter Notebook** – Code execution environment

---

## 🚀 Project Workflow
1. **Import Libraries** – Load all required Python libraries.
2. **Load Dataset** – Read the CSV file into a Pandas DataFrame.
3. **Data Exploration** – Inspect dataset shape, missing values, and first few rows.
4. **Data Splitting** – Separate features (`X`) and target (`Y`).
5. **Train-Test Split** – Use `train_test_split` with stratification for balanced classes.
6. **Model Creation** – Initialize the `LogisticRegression` model.
7. **Model Training** – Fit the model using the training dataset.
8. **Prediction & Evaluation** – Use `accuracy_score` to measure performance.
9. **Prediction System** – Allow users to input custom data for prediction.

---

## ▶️ How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Mohmad-Yaqoob/heart-disease-prediction.git
cd heart-disease-prediction
