# ❤️ Heart Disease Prediction using Machine Learning

This project applies **Machine Learning algorithms** to predict whether a person has **heart disease** based on clinical data such as age, blood pressure, cholesterol levels, chest pain type, and more.  

It uses the **UCI Heart Disease Dataset** (303 records, 14 features) and compares multiple models to evaluate performance.  

---

## 📊 Dataset  
- **Rows:** 303  
- **Columns:** 14  
- **Target Variable:** `target`  
  - `1` → Presence of heart disease  
  - `0` → No heart disease  

---

## ⚙️ Steps in the Project  

1. **Data Exploration (EDA)**  
   - Checked missing values (none found ✅)  
   - Visualized correlations with a heatmap  
   - Balanced dataset check for target distribution  

2. **Data Preprocessing**  
   - Converted categorical variables into dummy variables  
   - Standardized numerical features for fair ML training  

3. **Model Training & Evaluation**  
   - K-Nearest Neighbors (KNN)  
   - Random Forest Classifier  
   - Logistic Regression  
   - Support Vector Machine (SVM)  
   - XGBoost Classifier  

4. **Model Comparison**  
   - Cross-validation used for reliable accuracy scores  
   - K optimization done for KNN  

---

## 🏆 Results  

- **KNN (best k=12):** ~84% accuracy  
- **Random Forest:** ~81% accuracy  
- **Logistic Regression:** ~85% accuracy  
- **SVM:** ~86% accuracy  
- **XGBoost:** ~87% accuracy (best performer 🚀)  

---

## 📌 How to Run  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   cd heart-disease-prediction
   ```

2. Install requirements:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook heart_disease.ipynb
   ```

---

## 🔮 Future Improvements  
- Hyperparameter tuning with GridSearchCV / RandomizedSearchCV  
- Try deep learning models (ANN)  
- Deploy model using Flask/Django or Streamlit for a web app  

---

## 👨‍💻 Author  
Developed by **Surya S** as part of Final Year Project 🚀  
