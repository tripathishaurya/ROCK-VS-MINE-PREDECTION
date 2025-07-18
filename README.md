# ROCK-VS-MINE-PREDECTION
"Classifying sonar signals using Logistic Regression (76% accuracy)"


This is my first machine learning project where I built a binary classification model to distinguish between **sonar signals reflected by rocks** and **mines** using **Logistic Regression**.

---

## 📂 Dataset

- **Source:** UCI Machine Learning Repository – Sonar Dataset
- **Samples:** 208
- **Features:** 60 numerical attributes
- **Labels:**  
  - `R` = Rock  
  - `M` = Mine

---

## 🔧 Preprocessing Steps

- Encoded string labels (`R`, `M`) to numerical using `LabelEncoder`
- Split data into train/test sets using `train_test_split`
- Scaled features using `StandardScaler`

---

## 🧠 Model Info

- Algorithm: `LogisticRegression` from `scikit-learn`
- Accuracy achieved: **76%**
- Trained on Google Colab

---

## 📊 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 🧪 Libraries Used

- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib` (optional)
- Environment: Google Colab

---

## 🚀 Try it Yourself

> Open the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fO6EgoJ-0tfDvDrJwlvudgdtcfiMwdPN?usp=sharing)

---

## 🙋‍♂️ What I Learned

- Basic data preprocessing
- Label encoding and feature scaling
- Building and evaluating a binary classifier
- Understanding confusion matrix and classification report

---

## 👨‍💻 Author

Shaurya tripathi

---

## 📌 Note

This is a beginner-level project made for learning purposes. Feel free to fork, star, or suggest improvements!
