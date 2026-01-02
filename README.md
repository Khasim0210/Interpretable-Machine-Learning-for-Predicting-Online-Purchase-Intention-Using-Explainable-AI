# 🧠 Interpretable Machine Learning for Predicting Online Purchase Intention

## 📌 Project Overview
This project focuses on building interpretable machine learning models to predict online purchase intention using real-world e-commerce session data.  
Beyond achieving high prediction accuracy, the primary objective is to understand *why* users convert, enabling transparent, trustworthy, and business-ready decision-making.

The project combines data mining, classification modeling, and explainable machine learning concepts to deliver actionable insights rather than black-box predictions.

---

## 🎯 Objectives
- Predict whether an online shopping session will result in a purchase
- Perform exploratory data analysis (EDA) on user behavior data
- Handle class imbalance in conversion prediction
- Compare multiple classification models
- Interpret model behavior for business understanding

---

## 📂 Repository Structure
├── 01_eda_online_shoppers.ipynb # Data cleaning, EDA, and feature analysis
├── online_shoppers_intention.csv # Raw dataset
├── model_comparison.csv # Model evaluation results
├── README.md # Project documentation

---

## 📊 Dataset Description
- **Source**: UCI Machine Learning Repository  
- **Records**: ~12,000 online shopping sessions  
- **Target Variable**: `Revenue` (Purchase: Yes / No)  

### Key Features
- Page visit durations
- Bounce rate and exit rate
- Visitor type (New vs Returning)
- Traffic source
- Session timing and behavioral metrics

The dataset is highly imbalanced, with purchase sessions forming a small portion of total observations, making recall and ROC-AUC critical metrics.

---

## 🔍 Exploratory Data Analysis (EDA)
The EDA process includes:
- Data validation and missing value checks
- Distribution analysis of numerical variables
- Conversion rate comparison across visitor types
- Correlation analysis between features
- Visualization of class imbalance

📘 Notebook: `01_eda_online_shoppers.ipynb`

---

## 🤖 Machine Learning Models
The following classification models were trained and evaluated:

- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost / LightGBM (if applicable)

---

## 📈 Model Evaluation
Models were compared using:
- Accuracy
- Recall (Purchase class)
- ROC-AUC score

Detailed performance metrics are available in:
📊 `model_comparison.csv`

---

## 🧠 Model Interpretability
To ensure transparency and explainability:
- Feature importance analysis was conducted
- Model decisions were interpreted to identify key drivers of purchase behavior
- Insights were translated into business-friendly explanations

This approach makes the model suitable for real-world deployment and decision-making.

---

## 📌 Key Insights
- Returning visitors are significantly more likely to make a purchase
- Higher page value strongly increases conversion probability
- Long engagement on product pages correlates with higher intent
- High bounce and exit rates negatively affect purchase likelihood

---

## 🛠️ Tools & Technologies
- **Language**: Python  
- **Libraries**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn  
- **Environment**: Jupyter Notebook

---

## 🚀 Future Improvements
- Integrate SHAP for advanced explainability
- Perform hyperparameter tuning and cross-validation
- Deploy the model using Streamlit or FastAPI
- Extend analysis for real-time user session prediction

---

## 👤 Author
**Khasim Shaik**  
Graduate Student | Data Science & Machine Learning  

🔗 GitHub: https://github.com/Khasim0210  


---
