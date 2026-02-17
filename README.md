# Bank Customer Churn Modelling

This project focuses on predicting **bank customer churn** using Machine Learning techniques. The objective is to identify customers who are likely to leave the bank based on historical customer data. Churn prediction helps banks take proactive steps to retain valuable customers and improve overall business performance.

---

## 📌 Project Objective

The main goal of this project is to build a predictive model that can classify whether a customer will **exit (churn)** or **stay** with the bank.

By analyzing customer attributes such as credit score, geography, age, balance, and activity status, we can identify patterns that influence customer churn.

---

## 📊 Dataset Information

The dataset contains bank customer details with multiple features that influence churn behavior.

### Important Features:

* **CreditScore** – Customer credit score
* **Geography** – Country of the customer
* **Gender** – Male/Female
* **Age** – Customer age
* **Tenure** – Number of years with the bank
* **Balance** – Account balance
* **NumOfProducts** – Number of bank products used
* **HasCrCard** – Credit card holder (1 = Yes, 0 = No)
* **IsActiveMember** – Active member status (1 = Yes, 0 = No)
* **EstimatedSalary** – Estimated annual salary
* **Exited** – Target variable (1 = Churned, 0 = Not Churned)

---

## 🛠️ Project Workflow

### 1️⃣ Data Preprocessing

* Checked for missing values
* Encoded categorical variables
* Scaled numerical features
* Separated features (X) and target variable (y)
* Split dataset into training and testing sets

### 2️⃣ Exploratory Data Analysis (EDA)

* Analyzed customer distribution
* Visualized churn vs non-churn
* Studied impact of age, balance, and geography on churn

### 3️⃣ Model Building

Machine Learning models were trained to predict churn. Examples include:

* Logistic Regression
* Random Forest
* Support Vector Machine
* K-Nearest Neighbors

### 4️⃣ Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

The best-performing model was selected based on evaluation metrics.

---

## 🚀 How to Run the Project

1. Clone this repository:

   ```
   git clone https://github.com/AlluManojreddy/Bank-Customer-Churn-Modelling-YBI-main.git
   ```

2. Open the Jupyter Notebook file.

3. Run all cells step-by-step to see:

   * Data analysis
   * Model training
   * Model evaluation
   * Predictions

---

## 💡 Key Insights

* Customers with higher age tend to churn more.
* Inactive members are more likely to leave the bank.
* Geography plays a role in churn behavior.
* Customers with fewer products are more likely to exit.

---

## 📈 Future Improvements

* Hyperparameter tuning for better accuracy
* Use advanced algorithms like XGBoost
* Deploy the model using Streamlit or Flask
* Add real-time prediction capability

---

## 📚 Conclusion

This project demonstrates how Machine Learning can be applied to solve real-world business problems like customer churn prediction. It follows a complete data science pipeline from data preprocessing to model evaluation.

---

⭐ If you found this project helpful, consider giving it a star!
