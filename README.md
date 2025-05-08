# churn-prediction-logistic
Machine learning project for predicting customer churn using Logistic Regression, Decision Tree, and Random Forest models. Includes full model comparison, evaluation metrics (accuracy, recall, precision, AUC), and feature importance analysis. Final selected model: Logistic Regression.
# 💼 Customer Churn Prediction

This project uses Logistic Regression, Decision Tree, and Random Forest models to predict customer churn.  
The final selected model is **Logistic Regression**, which provided the best balance between recall and precision.

---

## 📊 Features Used
- `Age`
- `Total_Purchase`
- `Account_Manager` (1 = has manager, 0 = no)
- `Years` (customer lifetime)
- `Num_Sites` (web portal usage)

---

## ✅ Final Model Performance (Logistic Regression)
| Metric     | Score |
|------------|-------|
| Accuracy   | 0.90  |
| Precision  | 0.72  |
| Recall     | 0.60  |
| F1-score   | 0.66  |
| AUC        | 0.89  |

---

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/churn-prediction.git
   cd churn-prediction

