# Insider Threat Detection using Machine Learning

## 📌 Project Overview
This project aims to detect insider threats using Machine Learning classification algorithms. The employee activity dataset was cleaned, preprocessed, and used to train multiple classification models. The objective is to classify employee behavior as either **Malicious** or **Non-Malicious**.

---

## 🎯 Objectives
- Detect insider threats using machine learning.
- Compare the performance of multiple classification models.
- Identify the best-performing model based on evaluation metrics.

---

## 📂 Dataset
**File:** `insider_threat_clean_dataset.xlsx`

The dataset contains employee activity records and was cleaned before training the models.

---

## 🛠 Technologies Used
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
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- AUC Score
- Confusion Matrix

---

## 📈 Model Performance

| Model | Accuracy | AUC Score |
Model  Accuracy  AUC Score
         MLP      0.97       0.99
RandomForest      0.97       0.98
         SVM      0.97       0.91
DecisionTree      0.97       0.79---

## 📷 Results

### 1. MLP Classifier
- **Confusion Matrix:** ![CM](comparision%20matrix%20he....png)
- **ROC Curve:** ![ROC](ROC%20curve%20MLP.png)
- **Prediction Plot:** ![Pred](actual%20vs%20predicted%20an....png)

### 2. Random Forest
- **Confusion Matrix:** ![CM](conparison%20matrix%20hea....png)
- **ROC Curve:** ![ROC](ROC%20curve%20Randomfor....png)
- **Prediction Plot:** ![Pred](actual%20vs%20predicted%20dis....png)

### 3. Support Vector Machine (SVM)
- **Confusion Matrix:** ![CM](comparision%20matrix%20he....png)
- **ROC Curve:** ![ROC](ROC%20curve%20SVM.png)
- **Prediction Plot:** ![Pred](actual%20vs%20predicted%20dis....png)

### 4. Decision Tree
- **Confusion Matrix:** ![CM](comparision%20matrix%20he....png)
- **ROC Curve:** ![ROC](ROC%20curve%20decision%20tr....png)
- **Prediction Plot:** ![Pred](actual%20us%20precdicted%20di....png)

---

## 📁 Project Files

- `threat_detection.ipynb`
- `insider_threat_clean_dataset.xlsx`
- `README.md`

---

## ✅ Conclusion

Among all the classification models, **MLP** achieved the highest AUC Score (0.99), making it the best-performing model for this dataset. Random Forest also performed exceptionally well, while SVM and Decision Tree showed comparatively lower AUC Scores.

---

## 👩‍💻 Author

**Nayab Shafique**
