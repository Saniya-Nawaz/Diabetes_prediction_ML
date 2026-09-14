# 🩺 Diabetes Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting whether a person is likely to have diabetes using **Machine Learning** techniques.

The model uses medical and diagnostic features such as glucose level, blood pressure, BMI, age, insulin, and other health-related parameters to classify individuals into:

* **0 → Non-Diabetic**
* **1 → Diabetic**

The project demonstrates the complete Machine Learning workflow, from data preprocessing and exploratory data analysis to model training, evaluation, and prediction.

---

## 🎯 Objectives

* Analyze diabetes-related medical data.
* Perform data preprocessing and exploratory data analysis (EDA).
* Identify important factors associated with diabetes.
* Train Machine Learning classification models.
* Evaluate model performance using suitable metrics.
* Predict diabetes outcomes for new input data.

---

## 📊 Dataset

The project uses the **Pima Indians Diabetes Dataset**.

### Features

| Feature                  | Description                    |
| ------------------------ | ------------------------------ |
| Pregnancies              | Number of pregnancies          |
| Glucose                  | Plasma glucose concentration   |
| BloodPressure            | Diastolic blood pressure       |
| SkinThickness            | Triceps skin fold thickness    |
| Insulin                  | 2-hour serum insulin           |
| BMI                      | Body Mass Index                |
| DiabetesPedigreeFunction | Diabetes hereditary risk score |
| Age                      | Age of the person              |
| Outcome                  | Diabetes prediction target     |

### Target Variable

`Outcome`

* `0` → No diabetes
* `1` → Diabetes

---

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook / Google Colab**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Collection
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis (EDA)
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Diabetes Prediction
```

---

## 🤖 Machine Learning

This project uses supervised Machine Learning for **binary classification**.

The dataset is divided into:

* **Training Data** → Used to train the model
* **Testing Data** → Used to evaluate the model

The trained model learns patterns between the input medical features and the diabetes outcome.

---

## 📈 Model Evaluation

The model can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help determine how effectively the model distinguishes between diabetic and non-diabetic cases.

---

## 💻 Project Structure

```text
Diabetes-Prediction/
│
├── diabetes_prediction.ipynb
├── diabetes.csv
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the project folder

```bash
cd Diabetes-Prediction
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Run the notebook

Open:

```text
diabetes_prediction.ipynb
```

using **Jupyter Notebook** or **Google Colab**.

---

## 🔮 Prediction

After training, the Machine Learning model can take a person's medical measurements as input and predict whether the individual falls into the diabetic or non-diabetic class.

**Note:** This project is intended for educational and research purposes and should not be used as a substitute for professional medical diagnosis.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing
* Exploratory Data Analysis
* Data visualization
* Feature selection and scaling
* Supervised Machine Learning
* Classification
* Model evaluation
* Working with healthcare datasets
* Building an end-to-end ML workflow

---

## 👩‍💻 Author

**Saniya Nawaz**
**Sathya S**
**Tanzila Siddiqa S**
**Tasmiya A**

Machine Learning Mini Project
