# 📊 Telco Customer Churn Analysis & Prediction

An end-to-end **Machine Learning project** focused on analyzing customer behavior and predicting **customer churn** in the telecom industry.

This project combines **Exploratory Data Analysis (EDA)**, **feature engineering**, and **classification modeling** to identify the major factors driving churn and help businesses take proactive retention actions.

---

## 🚀 Project Objective

Customer churn is one of the most critical business challenges in subscription-based industries like telecom.

The goal of this project is to:

- Analyze customer behavior patterns
- Identify key churn drivers
- Build predictive models to classify churn risk
- Generate business insights for customer retention strategies

---

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset includes customer information such as:

- Demographics
- Subscription details
- Contract type
- Payment method
- Monthly and total charges
- Churn status

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

## ⚙️ Project Workflow

### 1. Data Cleaning
- Converted `TotalCharges` to numeric
- Handled missing values
- Removed unnecessary identifiers

### 2. Feature Engineering
- Created a new feature: `AvgCharges`

### 3. Data Preprocessing
- Encoded categorical variables using one-hot encoding
- Scaled features for Logistic Regression

### 4. Exploratory Data Analysis
- Churn distribution analysis
- Correlation heatmap
- Feature relationship exploration

### 5. Model Building
Built and evaluated:

- **Logistic Regression**
- **Random Forest Classifier**

### 6. Model Evaluation
Used:
- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance

---

## 📈 Key Insights

- Customers on **month-to-month contracts** are more likely to churn
- Customers with **low tenure** show higher churn risk
- **Higher monthly charges** are associated with increased churn probability
- Customers without **tech support** or **online security** are more likely to leave

---

## 🤖 Models Used

| Model | Purpose |
|------|---------|
| Logistic Regression | Baseline interpretable classification model |
| Random Forest | Non-linear classification and feature importance |

---

## 📊 Visualizations

### Churn Distribution
![Churn Distribution](images/churn_distribution.png)

### Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

### Feature Importance
![Feature Importance](images/feature_importance.png)

---

## 📌 Business Value

This project demonstrates how machine learning can be applied to:

- Predict customers at risk of churning
- Support retention campaigns
- Improve customer lifetime value
- Enable data-driven decision making

---

## 📁 Project Structure

```bash
telco-customer-churn-analysis-ml/
│
├── data/
├── notebooks/
├── images/
├── src/
├── README.md
├── requirements.txt
└── LICENSE
```

---

## ▶️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/telco-customer-churn-analysis-ml.git
cd telco-customer-churn-analysis-ml
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook or script
```bash
jupyter notebook
```

---

## 📚 Future Improvements

- Hyperparameter tuning
- Cross-validation
- ROC-AUC analysis
- Precision-Recall optimization
- Deployment using Streamlit / Flask
- Customer churn dashboard integration

---

## 👤 Author

**Pritam Dan**  
Aspiring Data Analyst / Data Science Enthusiast

- GitHub: [Pritam7421](https://github.com/Pritam7421)
- LinkedIn: https://www.linkedin.com/in/pritam-dan/

---

## ⭐ If you found this project useful, consider giving it a star!
