# ❤️ Heart Disease Prediction using Machine Learning

Predicting the likelihood of heart disease using machine learning models trained on healthcare data. This project demonstrates a full data science workflow including data preprocessing, exploratory data analysis, model training, and feature importance analysis.

Dataset used: Heart Disease UCI Dataset

---

# 📌 Project Highlights

✔ Healthcare predictive analytics using real-world medical data
✔ Data cleaning and normalization of patient records
✔ Multiple machine learning classification models
✔ Model evaluation using performance metrics
✔ Feature importance analysis to identify key risk factors

---

# 📊 Dataset Overview

The dataset contains anonymized medical records used to predict heart disease.

| Feature  | Description                       |
| -------- | --------------------------------- |
| Age      | Age of the patient                |
| Sex      | Gender                            |
| CP       | Chest pain type                   |
| Trestbps | Resting blood pressure            |
| Chol     | Cholesterol level                 |
| Thalach  | Maximum heart rate                |
| Exang    | Exercise induced angina           |
| Oldpeak  | ST depression                     |
| Slope    | Slope of peak exercise ST segment |
| CA       | Number of major vessels           |
| Thal     | Thalassemia condition             |

**Target Variable**

| Value | Meaning                   |
| ----- | ------------------------- |
| 0     | No heart disease          |
| 1     | Presence of heart disease |

---

# 🛠 Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn

---

# 🤖 Machine Learning Models

The following classification algorithms were implemented:

| Model               | Purpose                       |
| ------------------- | ----------------------------- |
| Logistic Regression | Baseline classification model |
| Decision Tree       | Tree-based classification     |
| Random Forest       | Ensemble learning model       |

---

# ⚙️ Project Workflow

```
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Scaling & Normalization
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Feature Importance Analysis
```

---

# 📈 Model Evaluation

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision & Recall
* F1 Score
* ROC-AUC Curve

Among the tested models, **Random Forest provided the best predictive performance**.

---

# 🔎 Feature Importance Insights

Feature importance analysis revealed the most influential factors in predicting heart disease:

* Age
* Cholesterol levels
* Maximum heart rate
* Chest pain type
* Blood pressure

These features play a significant role in determining cardiovascular risk.

---

# ⚖️ Ethical Considerations

Healthcare data must be handled responsibly.

* Dataset used is **public and anonymized**
* No personally identifiable information is included
* Models are intended for **educational and analytical purposes**
* Real healthcare systems must comply with regulations such as
  HIPAA and GDPR

---

# 🚀 Future Improvements

Possible enhancements for this project include:

* Hyperparameter tuning
* Advanced models like XGBoost
* Deployment as a web application
* Integration with larger healthcare datasets

---

# 👨‍💻 Author

**Vansh Suvarna**
BSc Computer Science
Data Science | Machine Learning | Analytics
:

* adding **visual graphs directly into the README**
* adding **GitHub badges (very impressive for recruiters)**.
