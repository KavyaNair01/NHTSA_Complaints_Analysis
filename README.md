# 🚗 Predictive Vehicle Recall Risk Classification

![Project Banner](https://via.placeholder.com/1200x400/2D3748/FFFFFF?text=Vehicle+Recall+Prediction+System)

## 📌 Project Overview
**A machine learning system** that classifies vehicle complaints into risk categories to enable proactive recalls and enhance automotive safety.

🔹 **Goal:** Predict high-risk defects before they escalate  
🔹 **Impact:** Reduce recall delays by 30-50% and prevent accidents  
🔹 **Tech Stack:** Python, BERT, XGBoost, Scikit-learn  

---

## 📊 Workflow Architecture

```mermaid
graph TD
    A[Complaints Data] --> D[Data Cleaning]
    B[Recall Data] --> D
    C[Investigation Data] --> D
    D --> E[Exploratory Analysis]
    E --> F[Feature Engineering]
    F --> G[Data Aggregation]
    G --> H[BERT Text Scoring]
    H --> I[Combine Features]
    I --> J[Tree-Based ML Model]
    J --> K[Risk Classification]
    
