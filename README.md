# 🏦 Loan Prediction using Machine Learning

A Machine Learning project that predicts whether a loan application will be approved or rejected based on applicant details such as income, education, credit history, marital status, and more.

---

## 📌 Project Overview

This project uses Machine Learning algorithms to automate the loan approval prediction process for banks and financial institutions.

The model is trained using historical loan application data and predicts:

- ✅ Loan Approved
- ❌ Loan Rejected

---

## 🚀 Features

- Data preprocessing and cleaning
- Handling missing values
- Exploratory Data Analysis (EDA)
- Feature encoding
- Model training and testing
- Loan eligibility prediction
- Beginner-friendly implementation

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

```bash
loan-prediction/
│
├── data/
│   └── loan_data.csv
│
├── notebooks/
│   └── loan_prediction.ipynb
│
├── models/
│   └── model.pkl
│
├── app.py
├── requirements.txt
└── README.md
```

---

## 📊 Dataset Features

The dataset contains the following features:

| Feature | Description |
|----------|-------------|
| Gender | Male/Female |
| Married | Marital status |
| Dependents | Number of dependents |
| Education | Graduate/Not Graduate |
| Self_Employed | Employment status |
| ApplicantIncome | Applicant income |
| CoapplicantIncome | Co-applicant income |
| LoanAmount | Loan amount |
| Loan_Amount_Term | Loan term |
| Credit_History | Credit history record |
| Property_Area | Urban/Rural/Semiurban |

### 🎯 Target Variable

- `Loan_Status`

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/loan-prediction.git
```

### 2️⃣ Navigate to Project Directory

```bash
cd loan-prediction
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

### Run Jupyter Notebook

```bash
jupyter notebook
```

### OR Run Python Application

```bash
python app.py
```

---

## 🤖 Machine Learning Workflow

1. Load the dataset
2. Clean and preprocess data
3. Handle missing values
4. Encode categorical features
5. Split dataset into train and test sets
6. Train Machine Learning model
7. Evaluate model performance
8. Make predictions
9. 80% test accuracy

---

## 📈 Algorithms Used

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

### Example

```python
from sklearn.linear_model import LogisticRegression

model = LogisticRegression()
model.fit(X_train, y_train)
```

---

## 📉 Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Classification Report

### Example

```python
from sklearn.metrics import accuracy_score

accuracy = accuracy_score(y_test, y_pred)
print("Accuracy:", accuracy)
```

---

## 🧪 Sample Prediction

### Input

```python
sample = [[1, 1, 0, 1, 0, 5000, 0, 120, 360, 1, 2]]
```

### Output

```bash
Loan Approved
```

---

## 📸 Future Improvements

- Add Flask/Django web application
- Deploy on cloud platforms
- Improve model accuracy
- Add user authentication
- Use Deep Learning models

---

## 🤝 Contributing

Contributions are welcome.

Feel free to fork this repository and submit pull requests.

---

