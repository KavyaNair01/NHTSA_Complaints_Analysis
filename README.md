# 🚗 Vehicle Recall Prediction System

## 📌 Project Overview
Machine learning system to classify vehicle complaints and predict recall risks using NHTSA data.

## 🔍 Key Features
- BERT-based text analysis of complaints
- Risk classification (High/Medium/Low)
- Recall prediction model

## 📊 Data Sources
| Dataset | Records | Period | Key Fields |
|---------|---------|--------|------------|
| Complaints | 1.2M+ | 1995-2024 | CMPLID, CRASH, COMPDESC |
| Recalls | 583K | 1967-2024 | CAMPNO, DESC_DEFECT |

## 🛠️ Installation
```bash
git clone https://github.com/yourusername/vehicle-recall-prediction.git
pip install -r requirements.txt
