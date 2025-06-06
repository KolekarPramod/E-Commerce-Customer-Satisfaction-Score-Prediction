<h1 align="center">📊 Predicting Customer Satisfaction (CSAT) Scores Using Deep Learning</h1>
<h3 align="center">Deep Learning Artificial Neural Network (ANN) on E-Commerce Interaction Data</h3>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🧭 Overview

This project focuses on predicting **Customer Satisfaction (CSAT) scores** using **Deep Learning Artificial Neural Networks (ANN)**. In the context of **e-commerce**, understanding satisfaction from customer interactions and feedback is critical to driving **retention, service improvement**, and **business growth**.

By leveraging advanced neural networks trained on detailed interaction data, we aim to forecast CSAT scores with high precision, offering **real-time operational insights** for support teams.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🧱 Project Background

In today’s fast-paced digital retail landscape, **customer satisfaction** is a vital KPI. Traditionally measured through surveys, this method is limited by low response rates and latency.

This project seeks to replace passive feedback collection with **predictive modeling**, enabling **instant satisfaction scoring** based on behavioral and interactional data—unlocking real-time decision-making for **support optimization** and **resource allocation**.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📦 Dataset Overview

The dataset spans a one-month period of interactions on an e-commerce platform called **Shopzilla**. It captures a rich variety of features relevant to customer support, such as:

Unique id: Unique identifier for each record (integer).

Channel name: Name of the customer service channel (object/string).

Category: Category of the interaction (object/string).

Sub-category: Sub-category of the interaction (object/string).

Customer Remarks: Feedback provided by the customer (object/string).

Order id: Identifier for the order associated with the interaction (integer).

Order date time: Date and time of the order (datetime).

Issue reported at: Timestamp when the issue was reported (datetime).

Issue responded: Timestamp when the issue was responded to (datetime).

Survey response date: Date of the customer survey response (datetime).

Customer city: City of the customer (object/string).

Product category: Category of the product (object/string).

Item price: Price of the item (float).

Connected handling time: Time taken to handle the interaction (float).

Agent name: Name of the customer service agent (object/string).

Supervisor: Name of the supervisor (object/string).

Manager: Name of the manager (object/string).

Tenure Bucket: Bucket categorizing agent tenure (object/string).

Agent Shift: Shift timing of the agent (object/string).

CSAT Score: Customer Satisfaction (CSAT) score (integer).

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🎯 Project Goal

Build a robust **deep learning model** that predicts CSAT scores from customer interaction data, helping businesses:

- Proactively address pain points
- Benchmark support agent performance
- Adapt service flows dynamically

Ultimately, we aim to move **from reaction to prediction**, transforming static metrics into actionable feedback loops.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📝 Specific Objectives

1. **🧹 Data Preparation:** Clean, normalize, and structure the dataset for training.
2. **🧠 Feature Engineering:** Extract and transform key predictive indicators from raw fields.
3. **🔧 Model Development:** Train an **Artificial Neural Network (ANN)** with multi-class output for CSAT categories.
4. **📏 Evaluation:** Use accuracy, precision, recall, and F1-score to assess model performance.
5. **📈 Insight Generation:** Interpret predictions to generate meaningful operational insights.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📊 Model Performance

The ANN model was trained and evaluated on the Shopzilla CSAT dataset with the following results:

### ✅ Accuracy Metrics
- **Train Accuracy:** `0.9136`
- **Test Accuracy:** `0.8784`

### 📄 Classification Report

           precision    recall  f1-score   support

       0       0.90      0.79      0.84     13935
       1       0.99      0.98      0.98     13935
       2       0.97      0.96      0.96     13935
       3       0.92      0.74      0.82     13936
       4       0.69      0.93      0.79     13935

accuracy                           0.88     69676



### 📌 Key Observations
- **Class 1 (Satisfied)** and **Class 2 (Very Satisfied)** are predicted with very high confidence.
- **Class 4 (Neutral)** shows a strong recall, indicating the model captures ambivalence well.
- Slight drop in recall for **Class 3 (Dissatisfied)** suggests some class overlap, possibly due to ambiguous feedback or edge cases.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🧠 Technologies Used

- **Programming Language:** Python 3.10+
- **Deep Learning Framework:** TensorFlow / Keras
- **Data Handling:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Model Evaluation:** Scikit-learn metrics

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🚀 Future Enhancements

- 🤖 Upgrade to Transformer-based architectures (BERT for sentiment-rich fields)
- 🌐 Build a real-time dashboard using Streamlit
- 🔍 Explainability with SHAP or LIME
- 📡 Integrate with live chat systems for real-time CSAT scoring
- 📈 Monthly retraining using fresh data

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)





