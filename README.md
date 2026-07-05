#  AI Customer Segmentation and Churn Prediction System

> An AI-powered customer analytics system that segments customers, predicts churn risk, detects fraudulent transactions, and provides personalized business recommendations using Machine Learning and Deep Learning techniques.

---

##  Overview

The **AI Customer Segmentation and Churn Prediction System** is designed to help businesses understand customer behavior by analyzing transaction data. The system performs RFM-based customer segmentation, predicts customer churn, detects anomalies in transactions, and recommends customer-specific marketing strategies.

The project combines Machine Learning, Deep Learning, and Business Analytics to generate actionable customer insights.

---

##  Objectives

- Segment customers based on purchasing behavior.
- Identify high-value and at-risk customers.
- Predict customer churn.
- Detect suspicious or fraudulent transactions.
- Generate personalized customer engagement strategies.
- Visualize customer insights for business decision-making.

---

##  Features

-  RFM (Recency, Frequency, Monetary) Analysis
-  Customer Segmentation
-  K-Means Clustering
-  Deep Learning Autoencoder
-  Customer Churn Prediction
-  Fraud Detection using Isolation Forest
-  Strategy & Recommendation Engine
-  Interactive Visualizations
-  Streamlit Dashboard

---

##  Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Streamlit
- Pickle

---

##  Machine Learning Models

| Model | Purpose |
|--------|---------|
| RFM Analysis | Customer Behavior Analysis |
| K-Means Clustering | Customer Segmentation |
| Autoencoder (Deep Learning) | Feature Extraction |
| Random Forest Classifier | Churn Prediction |
| Isolation Forest | Fraud Detection |
| PCA | Cluster Visualization |

---

##  Project Workflow

```
Transaction Dataset
        │
        ▼
Data Preprocessing
        │
        ▼
RFM Feature Engineering
        │
        ▼
Customer Segmentation
        │
        ▼
Feature Scaling
        │
        ▼
K-Means Clustering
        │
        ▼
Autoencoder Feature Learning
        │
        ▼
Random Forest Churn Prediction
        │
        ▼
Fraud Detection
        │
        ▼
Business Recommendations
        │
        ▼
Streamlit Dashboard
```

---

##  Project Structure

```
AI-Customer-Segmentation-and-Churn-Prediction-System/
│
├── transaction_data.csv
├── ai_customer_segmentation_and_churn_prediction_system.py
├── kmeans.pkl
├── scaler.pkl
├── churn_model.pkl
├── top_customers.csv
├── dl_clusters.png
├── README.md
```

---

##  Visualizations

The project generates multiple visual insights including:

- Customer Segment Distribution
- Spending Analysis by Customer Segment
- Frequency vs Monetary Distribution
- K-Means Cluster Visualization
- Deep Learning Cluster Visualization
- Churn Distribution
- Customer Churn Analysis
- Fraud Detection Histogram

---

##  Dataset

The project uses a customer transaction dataset containing:

- Customer ID
- Transaction ID
- Transaction Date
- Transaction Amount

From this data, RFM features are generated for customer analytics.

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/AI-Customer-Segmentation-and-Churn-Prediction-System.git
```

### Move into Project

```bash
cd AI-Customer-Segmentation-and-Churn-Prediction-System
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow streamlit
```

### Run the Application

```bash
streamlit run ai_customer_segmentation_and_churn_prediction_system.py
```

---

##  Business Applications

- Customer Relationship Management (CRM)
- Retail Analytics
- Banking & Finance
- E-Commerce
- Marketing Campaign Optimization
- Customer Retention
- Loyalty Programs
- Fraud Monitoring

---

##  Results

✔ Successfully segmented customers based on purchasing behavior.

✔ Identified customers with a high probability of churn.

✔ Detected anomalous transactions using Isolation Forest.

✔ Generated personalized marketing recommendations for different customer groups.

✔ Built an interactive dashboard for customer analytics.

---

##  Future Enhancements

- XGBoost for improved churn prediction
- Explainable AI (SHAP/LIME)
- Real-time customer analytics
- Cloud deployment (AWS/Azure/GCP)
- Database integration
- Live transaction monitoring
- Advanced business dashboards

---

##  Author

**Mrunmayee Gholap**

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

---

##  Support

If you found this project useful, consider giving it a ⭐ on GitHub!

---

##  License
This project is licensed under the MIT License.

