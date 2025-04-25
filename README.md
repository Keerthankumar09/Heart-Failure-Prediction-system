# 🫀 Heart Disease Classification

This project focuses on building machine learning models to classify the presence of heart disease using an **Artificial Neural Network (ANN)** and a **Decision Tree**. It uses Python libraries like **TensorFlow**, **Scikit-learn**, **Pandas**, and **Matplotlib** for implementation and visualization.

## 📌 Project Overview

- **Goal:** Predict whether a patient has heart disease based on clinical data.
- **Models Used:** 
  - Artificial Neural Network (ANN)
  - Decision Tree Classifier
- **Tools & Libraries:** 
  - Python, TensorFlow, Scikit-learn
  - Pandas, NumPy, Matplotlib, Seaborn

## 🧠 Dataset

- Dataset Source: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease) *(or mention your specific dataset)*
- Features include: age, sex, chest pain type, resting BP, cholesterol, fasting blood sugar, resting ECG, max heart rate, etc.

## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/heart-disease-classification.git
cd heart-disease-classification


pip install -r requirements.txt

heart-disease-classification/
│
├── data/                  # Dataset files
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── models/                # Saved trained models
├── plots/                 # Accuracy curves and confusion matrices
├── src/                   # Python scripts (preprocessing, training, evaluation)
├── README.md
└── requirements.txt

python src/train_ann.py
python src/train_decision_tree.py
