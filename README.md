# 🔬 Cancer Risk Classification Using Machine Learning (Barranquilla, Colombia)

## 📌 Overview

This project develops and evaluates Machine Learning models to classify the type of cancer (breast cancer or cervical cancer) based on sociodemographic and clinical variables.  
The study focuses on patients over 18 years old in Barranquilla, Colombia, and aims to support early diagnosis and improve decision-making in the public health sector.

The work was conducted as part of the **Master’s Thesis in Data Science** at Universidad Icesi.

---

## 🎯 Objectives

**General Objective:**  
Identify sociodemographic patterns associated with the incidence of breast cancer and cervical cancer.

**Specific Objectives:**  
- Explore and analyze demographic and clinical variables related to cancer risk.  
- Develop predictive models using classification algorithms.  
- Evaluate and optimize model performance using appropriate metrics.  
- Provide actionable insights to assist healthcare decision-makers.

---

## 🗂 Data Description

- **Source:** Public health records provided by the Alcaldía de Barranquilla.  
- **Period covered:** 2022 – 2024  
- **Target variable:** Cancer type (1 = Breast Cancer, 2 = Cervical Cancer).  
- **Features:** Age, locality, socioeconomic status, occupation, biopsy results, treatment types (e.g., chemotherapy, radiotherapy), among others.

**Preprocessing applied:**  
- Data cleaning and missing value imputation.  
- Feature encoding (Label Encoding / One-Hot Encoding).  
- Class balancing using SMOTE.

---

## 🔍 Methodology

Methodological framework: **CRISP-DM**

**Workflow:**  
1. Business and data understanding.  
2. Data preparation and exploratory analysis.  
3. Feature selection and dimensionality reduction.  
4. Model development using:
   - Random Forest
   - XGBoost
   - Support Vector Machines (SVM)
   - Multi-layer Perceptron (MLP)
5. Hyperparameter tuning.  
6. Model evaluation and comparison.  
7. Deployment recommendations.

---

## 🤖 Results

| Cancer Type | Best Model | Key Metric |
|-------------|------------|------------|
| Cervical Cancer | **XGBoost** | Highest precision and interpretability. |
| Breast Cancer | **MLP Neural Network** | Highest Recall and F1-Score. |

**Key Findings:**  
- Sociodemographic variables (age, locality, occupation) and clinical data were significant predictors.  
- XGBoost handled class imbalance effectively for cervical cancer.  
- MLP Neural Network captured complex patterns for breast cancer classification.

---

## 🧠 Key Insights

- Machine Learning can support public health initiatives by improving early cancer detection.
- Regular meetings with stakeholders (health authorities) were essential for data validation and understanding.
- Limitations included missing data and lack of certain clinical variables.

---

## 📚 Technologies Used

- **Python (Scikit-learn, XGBoost, imbalanced-learn)**  
- **Pandas, NumPy, Matplotlib, Seaborn**  
- **SMOTE for class balancing**  
- **CRISP-DM methodology**  
- **Jupyter Notebooks**

---

## 👥 Collaborators

**Álvaro José Cabrera Lozano**  
Data Scientist | Economist | AI Specialist  
[LinkedIn](https://www.linkedin.com/in/alvarojcabrera)

**Claudia Lorena Aragón Payán**  
[Co-author]

---

## 🔗 Acknowledgments

Special thanks to the **Alcaldía de Barranquilla** for providing data access and ongoing support.  
This research was developed in partial fulfillment of the requirements for the **Master’s in Data Science** at Universidad Icesi.

---

*"Empowering healthcare decisions through data and AI."*

