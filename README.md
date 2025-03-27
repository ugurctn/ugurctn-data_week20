# ugurctn-data_week20

# Credit Risk Classification

This project applies logistic regression to classify loan applications as either **healthy loans (0)** or **high-risk loans (1)** using historical credit data. The goal is to build a predictive model that assists in identifying potentially risky borrowers.

## 📁 Project Structure

- `credit_risk_classification-BOOOOOTH.ipynb` – Jupyter notebook containing the full workflow: data preparation, model training, evaluation, and results.
- `README.md` – Project overview and instructions.

## 📊 Dataset

The dataset includes information about individual loan applications, such as:

- Loan amount
- Interest rate
- Borrower income
- Credit history
- Loan status (target variable)

## 🚀 Technologies Used

- Python
- Pandas
- scikit-learn
- Jupyter Notebook

## 🧠 Machine Learning Model

**Logistic Regression** was used for binary classification of loan risk status.

### Steps:

1. **Data Preprocessing**:
   - Features (`X`) and target (`y`) separated
   - Data split into training and testing sets
2. **Model Training**:
   - Logistic Regression model instantiated with `random_state=1`
   - Model trained on training data
3. **Prediction & Evaluation**:
   - Predictions made on the testing set
   - Model performance evaluated using:
     - Confusion Matrix
     - Classification Report

### Model Performance

| Metric           | Class 0 (Healthy) | Class 1 (High-Risk) |
|------------------|------------------|----------------------|
| Precision        | 1.00             | 0.84                 |
| Recall           | 0.99             | 0.94                 |
| F1-score         | 1.00             | 0.89                 |
| Overall Accuracy | **99%**          |                      |

## 🔍 Insights

- The model performs extremely well at identifying healthy loans.
- It also performs well for high-risk loans but with slightly lower precision, meaning some healthy loans may be misclassified as high-risk.
- The high accuracy is likely due in part to class imbalance; further work could include oversampling or ensemble models.

## 📌 Future Improvements

- Address class imbalance using SMOTE or undersampling.
- Try other models (Random Forest, XGBoost, etc.).
- Perform feature scaling and selection.
- Deploy the model in a web app (e.g., using Flask or Streamlit).

## 📬 Contact

For questions or collaboration, feel free to reach out!

---

