# 🛡️ Insider Threat Detection using Machine Learning

## 📌 Project Overview

This project aims to detect insider threats using Machine Learning classification algorithms. The employee activity dataset was cleaned and preprocessed before training the models. The objective is to classify employee behavior as either **Malicious** or **Non-Malicious**.

---

## 🎯 Objectives

- Detect insider threats using machine learning.
- Compare the performance of multiple classification models.
- Evaluate models using different performance metrics.
- Identify the best-performing classification model.

---

## 📂 Dataset

**Dataset File:** `insider_threat_clean_dataset.xlsx`

The dataset contains employee activity records and was cleaned before applying machine learning algorithms.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- GitHub

---

## 🤖 Machine Learning Models

- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP)

---

## 📊 Evaluation Metrics

The models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- AUC Score
- Confusion Matrix
- ROC Curve

---

## 📈 Model Performance

Final Model Comparison Table ---
       Model  Accuracy  AUC Score
         MLP      0.97       0.99
RandomForest      0.97       0.98
         SVM      0.97       0.91
DecisionTree      0.97       0.79


---

# 📷 Results

## 1️⃣ Multi-Layer Perceptron (MLP)

### Confusion Matrix
![MLP Confusion Matrix](comparision%20matrix%20heaTmap%20MLP.png)

### ROC Curve

![MLP ROC Curve](ROC%20curve%20MLP.png)

### Actual vs Predicted Distribution

![MLP Prediction](actual%20us%20precdicted%20distribution%20MLP.png)

---

## 2️⃣ Random Forest

### Confusion Matrix
![RF Confusion Matrix](conparison%20matrix%20heatmap%20random%20forest.png)
### ROC Curve
![RF ROC Curve](ROC%20curve%20Randomforest.png)

### Actual vs Predicted Distribution

![Random Forest Prediction](actual%20vs%20predicted%20and%20distribution%20Randon%20forest.png)

---

## 3️⃣ Support Vector Machine (SVM)

### Confusion Matrix
![SVM Confusion Matrix](comparison%20matrix%20heatmat%20SVM.png)
### ROC Curve
![SVM ROC Curve](ROC%20curve%20SVM.png)
### Actual vs Predicted Distribution

![SVM Prediction](actual%20vs%20predicted%20distribution%20SVM%20.png)

---

## 4️⃣ Decision Tree

### Confusion Matrix

![DT Confusion Matrix](comparison%20matrix%20heatmap%20decision%20tree%20.png)

### ROC Curve

![DT ROC Curve](ROC%20curve%20decision%20tree.png)

### Actual vs Predicted Distribution

![Decision Tree Prediction](actual%20vs%20predicted%20distribution%20decision%20treee.png)
---

## 📁 Project Files

- `threat_detection.ipynb`
- `insider_threat_clean_dataset.xlsx`
- `README.md`

---

## ✅ Conclusion

This project successfully compares four machine learning classification algorithms for insider threat detection. Based on the experimental results, the **Multi-Layer Perceptron (MLP)** achieved the highest **AUC Score (0.99)**, making it the best-performing model for this dataset. Random Forest also produced excellent results, while SVM and Decision Tree provided competitive performance.

---

## 👩‍💻 Author

**Nayab Shafique**

Machine Learning Project
