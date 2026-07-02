# Iris Flower Classification using Logistic Regression

## Project Description

This project uses the Iris flower dataset from Scikit-learn to train a Logistic Regression model that classifies iris flowers into three species:

- Setosa
- Versicolor
- Virginica

The trained model is saved as `model.pkl`.

---

## Project Structure

```
irisproject/
│
├── train.py
├── requirements.txt
├── model.pkl
├── README.md
└── venv/
```

---

## Create Virtual Environment

Windows

```bash
python -m venv venv
```

Activate

PowerShell

```bash
.\venv\Scripts\Activate
```

Command Prompt

```bash
venv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run the Model

```bash
python train.py
```

---

## Expected Output

```
====================================
Logistic Regression on Iris Dataset
====================================

Model Accuracy: 96.67%

Classification Report

Confusion Matrix

Model saved successfully as model.pkl
```

---

## Model File

After training, the model is saved as

```
model.pkl
```

You can load it later for prediction.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib