# 🏥 ML Prediction of Acute Respiratory Infections (ARI) in Bangladesh  
**Rural vs. Urban Analysis for Under-Five Children**  

## 📌 Overview  
This project applies **machine learning (ML) techniques** to predict **Acute Respiratory Infections (ARI)** among children under five in **Bangladesh**, comparing urban and rural areas. ARI remains a leading cause of child mortality, and early detection can help policymakers and healthcare providers take preventive measures.

---

## 📂 Dataset  
- **Source:** ARI dataset from Bangladesh  
- **Format:** CSV  
- **Key Features:**
  - Demographic variables (age, gender, household location)
  - Socioeconomic factors (parental education, income levels)
  - Environmental factors (air quality, household cooking fuel)
  - Health indicators (previous infections, vaccination status)
  - **Target Variable:** `ARI` (0 = No ARI, 1 = ARI Present)

---

## 🏗️ Methodology  
### 🔍 Data Preprocessing  
- Handling **missing values**
- Encoding **categorical variables**
- **Feature scaling** using `StandardScaler`
- Splitting data into **training & testing sets**

### 📊 Exploratory Data Analysis (EDA)  
- **Class distribution analysis**
- **Correlation heatmaps**
- **Feature importance analysis**
- **Urban vs. Rural ARI prevalence comparison**

### 🔧 Machine Learning Models  
The following models were implemented and evaluated:  
| Model | Description |
|--------|------------|
| **Logistic Regression** | Baseline model for classification |
| **Random Forest** | Handles non-linearity and feature importance |
| **Gradient Boosting (XGBoost)** | Advanced tree-based method for better accuracy |
| **Neural Networks** | Deep learning approach for complex feature interactions |

### 🏆 Model Evaluation  
- **Accuracy, Precision, Recall, F1-Score**
- **ROC-AUC Curve for performance comparison**
- **Feature importance ranking**

---

## 🚀 Installation & Usage  
### 🔥 Prerequisites  
Ensure you have the following installed:  
- Python 3.8+  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn, XGBoost, TensorFlow  

### 📥 Clone Repository  
```bash
git clone https://github.com/your-username/ML-Prediction-of-Acute-Respiratory-Infections.git
cd ML-Prediction-of-Acute-Respiratory-Infections

