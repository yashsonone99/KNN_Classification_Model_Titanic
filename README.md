# KNN_Classification_Model_Titanic
“Predicting Titanic passenger survival using the K-Nearest Neighbors algorith a distance-based classification approach with complete preprocessing, EDA, and model evaluation.” 
# ⚓ Titanic Survival Prediction using K-Nearest Neighbors (KNN)

> “Implementing a distance-based machine learning algorithm to classify Titanic passengers’ survival outcomes through detailed preprocessing, scaling, and evaluation.”

---

## 💡 Project Overview  
This project focuses on applying the **K-Nearest Neighbors (KNN)** algorithm to the **Titanic dataset** for binary classification — predicting whether a passenger survived or not.  
Through **data cleaning**, **EDA**, **feature scaling**, and **model evaluation**, this notebook demonstrates how KNN works for real-world data.

---

## 🎯 Objectives  
- Perform **data preprocessing** and handle missing values  
- Conduct **Exploratory Data Analysis (EDA)** to identify survival trends  
- Apply **feature scaling** for distance-based learning  
- Build and train a **KNN classifier**  
- Evaluate performance using accuracy, precision, recall, and F1-score  
- Visualize decision boundaries and confusion matrix  

---

## ⚙️ Technologies Used  
- **Python** 🐍  
- **pandas**, **NumPy** — data manipulation  
- **matplotlib**, **seaborn** — visualization  
- **scikit-learn** — ML model & preprocessing tools  

---

## 📂 Files Included  

| File | Description |
|------|-------------|
| `KNN_Model.ipynb` | Complete notebook implementing KNN on Titanic dataset |
| `Titanic_train.csv` | Dataset used for training and testing |
| `README.md` | Project documentation file |

---

## 🧪 Key Steps  

### 1️⃣ Data Loading & Cleaning  
- Loaded Titanic dataset and checked data structure  
- Filled missing values using mean/mode imputation  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Visualized survival rates by **gender, class, and age**  
- Generated histograms and count plots for major features  

### 3️⃣ Feature Engineering  
- Encoded categorical columns (Sex, Embarked, etc.)  
- Scaled numerical features using **StandardScaler**  

### 4️⃣ Model Training  
- Split data into training and test sets (80–20)  
- Trained a **KNN classifier** with optimal `k` using GridSearchCV  

### 5️⃣ Model Evaluation  
- Computed **Accuracy, Precision, Recall, and F1-score**  
- Visualized **Confusion Matrix** and **ROC Curve**  

---

## 📊 Model Performance Summary  

| Metric | Score |
|---------|-------|
| Accuracy | ~0.80 |
| Precision | ~0.78 |
| Recall | ~0.75 |
| F1-Score | ~0.76 |

> 💡 **Insight:** The KNN model achieved strong classification results after proper scaling and parameter tuning, showing its effectiveness for distance-based prediction.

---

## 🖼️ Visual Outputs  
Upload visuals like:  
- 📈 Histograms and Countplots (EDA)  
- 🔢 K-value vs Accuracy Plot  
- 📊 Confusion Matrix  
- 🩵 ROC-AUC Curve  

---

## 🚀 How to Run  

1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/KNN_Classification_Model_Titanic.git
   cd KNN_Classification_Model_Titanic
