# Telco Churn Prediction with NLP & Fallback Strategy

This project simulates a real-world churn prediction scenario in the telecom industry, enriched with GPT-generated customer feedback. It evaluates both structured-only models and hybrid models that incorporate noisy textual feedback. The pipeline includes a fallback mechanism and production-style features such as a Feature Store.

---

## 📦 Dataset

The data is available on Kaggle:  
👉 [Telco Customer Churn – Realistic Customer Feedback](https://www.kaggle.com/datasets/beatafaron/telco-customer-churn-realistic-customer-feedback)

It contains:
- Clean & noisy versions of customer feedback
- Structured telco data (contract, usage, payments)
- Churn labels

---

## 📘 Project Structure

All notebooks are available in the [`notebooks/`](notebooks) folder.

| Notebook | Description |
|----------|-------------|
| **01** – Exploration & Feedback Insights | EDA + exploration of GPT-generated feedback |
| **02** – Simulate Feedback Noise | Introduces real-world text noise and tests fallback conditions |
| **03** – Fallback Models Comparison | Logistic Regression vs XGBoost vs Random Forest vs Neural Net (structured-only) |
| **04** – Model with Feedback | Combines structured data with customer feedback (TF-IDF + ML) |
| **05** – Feedback Knowledge Transfer | Simulates passing textual signal to fallback model via proxy features |
| **06** – Feature Store & Weekly Prediction Job | Simulates a production scenario with registered features & automated inference |
| **Extra** – How to Build a Scoring Card | Tutorial-style notebook for scorecards (WoE, IV, scaling, PSI) |

---

## 🧠 What You’ll Learn

- How to simulate noisy NLP data in churn prediction
- How to implement a hybrid model with fallback logic
- How to compute WoE, IV, PSI and build logistic regression scorecards
- How to use Databricks Feature Store & MLflow for model deployment
- How to design structured yet flexible pipelines for production

---

## 🧰 Tech Stack

`Python`, `Pandas`, `Scikit-learn`, `XGBoost`, `TF-IDF`,  
`Databricks`, `MLflow`, `PySpark`, `Feature Store`,  
`WoE / IV`, `PSI`, `Regex`, `EDA`, `matplotlib`, `shap`

---

## 👩‍💻 Author

Beata Faron  
- 💼 [LinkedIn](https://www.linkedin.com/in/beata-faron-24764832/)  
- 🧠 [Kaggle](https://www.kaggle.com/beatafaron)  
- 📂 [GitHub Projects](https://github.com/BeataFaron)

---

⭐ If you found this project useful or interesting, feel free to star the repo!
