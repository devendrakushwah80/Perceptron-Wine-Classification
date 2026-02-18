# 🍷 Wine Classification using Perceptron (Scikit-learn)

This project implements a **Perceptron Classifier** on the **Wine Dataset** using Scikit-learn.  
It includes complete **EDA (Exploratory Data Analysis)**, **Data Preprocessing**, **Model Training**, and **Performance Evaluation using multiple metrics**.

---

## 📌 Project Overview

The goal of this project is to classify different types of wine based on their chemical properties using a linear classification algorithm — **Perceptron**.

The project follows a complete Machine Learning pipeline:

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Feature Scaling
4. Train-Test Split
5. Model Training (Perceptron)
6. Model Evaluation (All major metrics)
7. Confusion Matrix Visualization

---

## 📊 Dataset Information

- Dataset: **Wine Dataset**
- Source: `sklearn.datasets.load_wine()`
- Samples: 178
- Features: 13 numerical features
- Target Classes: 3 wine categories

---

## 🔍 Exploratory Data Analysis (EDA)

The notebook includes:

- First few rows preview
- Dataset shape
- Statistical summary
- Target distribution
- Correlation heatmap
- Feature visualization using seaborn

---

## ⚙️ Data Preprocessing

- Feature Scaling using `StandardScaler`
- Train-Test Split using `train_test_split`
- Random state used for reproducibility

---

## 🤖 Model Used

### Perceptron Classifier

- Library: `sklearn.linear_model.Perceptron`
- Type: Linear classification algorithm
- Suitable for linearly separable data

---

## 📈 Model Evaluation Metrics

The model performance is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

All metrics are computed using `sklearn.metrics`.

---

## 📊 Confusion Matrix Visualization

- Heatmap plotted using Seaborn
- Helps visualize classification performance across classes

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

Perceptron-Wine-Classification/
│
├── Perceptron3.ipynb
├── README.md
└── requirements.txt


---

## ▶️ How to Run

1. Clone the repository



git clone https://github.com/your-username/Perceptron-Wine-Classification.git


2. Install dependencies



pip install -r requirements.txt


3. Open Jupyter Notebook



jupyter notebook


4. Run `Perceptron3.ipynb`

---

## 🎯 Key Learning Outcomes

- Understanding Perceptron algorithm
- Performing EDA on structured datasets
- Feature scaling importance
- Model evaluation using multiple metrics
- Confusion matrix interpretation

---

## 📌 Author

Devendra Kushwah

---

⭐ If you found this useful, give this repo a star!
