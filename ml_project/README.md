# First ML Project

This project compares two machine learning models — \*\*Linear Regression\*\* and \*\*Random Forest Regressor\*\* — using a solubility dataset.



\## 📁 Dataset



\- \*\*Source\*\*: \[Delaney Solubility Dataset](https://raw.githubusercontent.com/dataprofessor/data/refs/heads/master/delaney\_solubility\_with\_descriptors.csv)

\- \*\*Goal\*\*: Predict water solubility based on molecular structure descriptors.



\## 🧠 Models Used



\- Linear Regression

\- Random Forest Regressor



\## 📊 Evaluation Metrics



| Model            | Training MSE | Training R² | Test MSE | Test R² |

|------------------|--------------|-------------|----------|---------|

| Linear Regression| 1.0075       | 0.7645      | 1.0207   | 0.7892  |

| Random Forest    | 1.0282       | 0.7597      | 1.4077   | 0.7092  |



\## ✅ Summary



\- Linear Regression performed slightly better on the test set.

\- Random Forest had lower generalization performance, possibly due to overfitting.



---



> 🧪 This is a learning project created using Google Colab and pandas/sklearn. Future versions may include hyperparameter tuning and visualization.



