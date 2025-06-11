# Telco Customer Churn – ML + NLP + Power BI

This project reimagines the classic Telco Churn dataset by enriching it with AI-generated customer feedback. It allows for advanced use cases involving:

- 🌟 Churn prediction (ML model)
- 💬 Sentiment classification from reviews (NLP)
- 📊 Interactive dashboard (Power BI)
- 💡 Exploratory analysis (Python + PySpark)

## 📁 Project Structure

```
telco-churn-prediction-nlp/
│
├── data/
│   └── telco_churn_with_all_feedback.csv
├── eda/
│   ├── telco_eda_python.ipynb
│   └── telco_eda_spark.dbc
├── models/
│   ├── churn_model.pkl
│   └── feedback_classifier.ipynb
├── dashboards/
│   └── powerbi_screenshot.png
├── utils.py
└── README.md
```

## 📍 Highlights

- Feedbacks generated using `gpt-3.5-turbo` (OpenAI API)
- Feedbacks are realistic, diverse, and matched to customer profile
- Prepared for classification, topic modeling, or embeddings

## 🧠 Techniques Used

- OpenAI API (`gpt-3.5-turbo`) for customer feedback generation
- TextBlob for sentiment analysis
- Pandas / Seaborn for EDA
- Planned: TF-IDF, classification, clustering, embeddings

## 🔗 Related Links

- 📂 Kaggle Dataset: https://www.kaggle.com/datasets/beatafaron/telco-customer-churn-realistic-customer-feedback
- 📓 Kaggle EDA Notebook: (https://www.kaggle.com/code/beatafaron/exploring-customer-churn-gpt-generated-feedback)
- 📄 LinkedIn Post: (https://www.linkedin.com/posts/activity-7338521353328717825-4HZo?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAAbbo1cBVAX0dyPMHKA7g7F3wzkcP133cAI)

---

Stay tuned for notebooks, Power BI dashboard, and sentiment analysis coming next!
