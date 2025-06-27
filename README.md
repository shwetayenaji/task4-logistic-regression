# 🧠 Logistic Regression Binary Classifier

This project demonstrates how to build a **binary classification model** using **Logistic Regression**. The dataset used is the **Breast Cancer Wisconsin Diagnostic Dataset** from `scikit-learn`.

---

## 📌 Objective
To train a binary classifier that predicts whether a tumor is **malignant (1)** or **benign (0)** based on several features using **logistic regression**.

---

## 📁 Dataset
- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Target**: Binary classification — `0` (benign), `1` (malignant)

---

## 🛠️ Tools & Libraries
- Python
- Scikit-learn
- Pandas
- Matplotlib
- NumPy

---

## 🧪 Steps Performed

1. **Dataset loading**  
   Loaded the Breast Cancer dataset from `sklearn`.

2. **Preprocessing**  
   - Train-test split (80/20)
   - Feature standardization using `StandardScaler`

3. **Model Training**  
   - Logistic Regression model using `LogisticRegression()`

4. **Evaluation**  
   - Confusion Matrix
   - Precision & Recall
   - ROC-AUC Score
   - ROC Curve Visualization

5. **Threshold Tuning**  
   - Explained the sigmoid function
   - Tuned decision threshold based on precision-recall trade-off

---

## 📈 Model Evaluation Metrics

- **Confusion Matrix**
- **Precision**
- **Recall**
- **ROC-AUC Score**
- **Threshold Tuning** with F1/ROC analysis

---

## 📊 Visualizations

- ROC Curve  
- Precision-Recall vs Threshold Curve

---

## 🔍 How to Run

1. Clone this repository or open in Jupyter/Colab.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib scikit-learn

## 👩‍💻 Author
Shweta Yenaji
