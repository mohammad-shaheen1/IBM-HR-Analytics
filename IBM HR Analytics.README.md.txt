# IBM HR Analytics - Employee Attrition Prediction

## 📌 Project Overview
This project focuses on predicting employee attrition using **Machine Learning** techniques. By analyzing IBM HR Analytics data, we aim to identify key factors contributing to employee turnover and build a predictive model using **Logistic Regression**.

## 📂 Dataset
- **Source:** [Kaggle - IBM HR Analytics Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Description:** The dataset contains employee details such as age, department, job role, salary, work environment, and attrition status (Yes/No).
- **Target Variable:** `Attrition` (Binary: Yes/No)

## 🚀 Project Workflow
### 1️⃣ Data Preprocessing
✅ Loaded the dataset and checked for missing values.
✅ Applied **One-Hot Encoding** to categorical features.
✅ Standardized numerical features using **StandardScaler**.

### 2️⃣ Model Training
✅ Split data into **Training (80%)** and **Testing (20%)** sets.
✅ Implemented **Logistic Regression** for classification.
✅ Trained the model using scaled features.

### 3️⃣ Model Evaluation
✅ Predicted attrition on the test set.
✅ Evaluated model performance using:
   - **Confusion Matrix** 📊
   - **Accuracy Score** 📈
✅ Visualized results using **Seaborn Heatmap**.

## 🔥 Results
- The model successfully predicts employee attrition with a decent accuracy.
- Key features influencing attrition include **Job Satisfaction, Overtime, Work-Life Balance, and Years at Company**.
- Further improvements can be achieved by testing more complex models like **Random Forest or XGBoost**.

🚀 **Stay tuned for more updates!**


