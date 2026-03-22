# 📊 Customer Churn Prediction using KNIME

## 👥 Team Members

* Rupak Manikonda
* Monish Jayaprakash Seelam

---

## 📌 Project Overview

This project focuses on predicting customer churn using machine learning models built in KNIME. By analyzing customer behavior and service usage patterns, the goal is to identify customers who are likely to leave and provide actionable insights to improve retention strategies.

---

## 🎯 Objective

* Predict customers who are likely to churn
* Identify key factors driving churn
* Provide data-driven insights for business decision-making

---

## 📂 Dataset

* **Source:** Telco Customer Churn Dataset (Kaggle)
* **Records:** 7032 customers
* **Features:** ~60 features after preprocessing
* Includes:

  * Customer tenure
  * Contract type
  * Monthly charges
  * Internet service
  * Payment methods

---

## 🔍 Key Insights from Data

* Customers with **tenure < 10 months** have the highest churn
* **Month-to-month contracts** show significantly higher churn
* Customers with **higher monthly charges** are more likely to churn
* **Electronic check payments** are associated with higher churn
* **Fiber optic users** churn more compared to DSL users

---

## ⚙️ Methodology

The project was implemented using KNIME workflows:

1. Data preprocessing and feature engineering
2. Exploratory Data Analysis (EDA)
3. Feature creation (e.g., tenure-to-total ratio)
4. Model building and evaluation

---

## 🤖 Models Used

| Model               | Recall | Precision | F1 Score | Cohen’s Kappa |
| ------------------- | ------ | --------- | -------- | ------------- |
| Logistic Regression | 0.646  | 0.494     | 0.560    | 0.428         |
| Random Forest       | 0.415  | 0.683     | 0.517    | 0.395         |
| XGBoost             | 0.515  | 0.631     | 0.567    | **0.431**     |

---

## 🏆 Best Model: XGBoost

XGBoost was selected as the final model because:

* Highest Cohen’s Kappa (best agreement)
* Balanced precision and recall
* Strong overall performance

---

## 📊 Key Features Driving Churn

* **Tenure:** Short tenure → high churn risk
* **Contract Type:** Month-to-month → high churn
* **Monthly Charges:** Higher charges → higher churn
* **Total Charges:** Lower total → early-stage customers
* **Payment Method:** Electronic check → higher churn
* **Internet Service:** Fiber optic users churn more

---

## 📈 Business Insights

* Churn is highest among **new customers (<10 months)**
* Customers paying more monthly but with low total spend are at risk
* Contract type plays a major role in customer retention

---

## 🚀 Strategic Recommendations

* 🎯 Target high-risk customers (low tenure + high charges)
* 💡 Offer incentives for long-term contracts
* 💰 Improve pricing strategies for high-paying customers
* 🤝 Strengthen early customer engagement (first 3–6 months)

---

## 🛠 Tools & Technologies

* KNIME Analytics Platform
* Machine Learning Models (Logistic Regression, Random Forest, XGBoost)
* Data Visualization

---

## 📸 Project Workflow & Visualizations

(Add screenshots of your KNIME workflow and charts here)

---

## 🔮 Future Improvements

* Real-time churn prediction system
* Integration with customer CRM systems
* Advanced ML models and hyperparameter tuning
* Customer segmentation for personalized marketing

---

## 🙏 Acknowledgements

Dataset sourced from Kaggle:
Telco Customer Churn Dataset

---

## 📬 Contact

For any queries or collaboration opportunities, feel free to connect!
