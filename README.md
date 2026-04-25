# 💳 Online Payments Fraud Detection System

## 📌 1. Introduction

🔹 Project Overview: 

This project focuses on identifying fraudulent online financial transactions using Machine Learning techniques. With the rapid growth of digital payments, ensuring transaction security has become critically important.
The system uses a trained classification model integrated into a Flask-based web application. Users can input transaction details and instantly receive predictions indicating whether a transaction is Fraudulent or Legitimate.

🎯 Purpose

The primary objective of this project is to classify online transactions based on transaction attributes. Since fraud detection is a classification problem, the system predicts categorical outcomes:

Fraud
Not Fraud

This helps enhance digital payment security and reduce financial risks.

## 📚 2. Literature Survey

⚠️ Existing Problem
Traditional fraud detection systems:
Generate high false positives
Fail to adapt to new fraud patterns
Reduce customer trust

Machine Learning solves this by learning patterns from historical data.

📖 References
PaySim Synthetic Dataset
Algorithms studied:
Decision Tree
Random Forest
Support Vector Machine (SVM)
Extra Trees Classifier

🧠 Problem Statement
Design a Machine Learning system to classify transactions using:

Transaction step
Type
Amount
Account balances

## 💡 3. Ideation & Proposed Solution
🧍 Empathy Map
Users fear financial loss
Demand secure systems
Need fast and accurate fraud detection
⚙️ Proposed Solution

#### 1.	Problem	Detect fraud in increasing online transactions
#### 2.	Solution	ML model + Flask web app for real-time prediction
#### 3.	Uniqueness	Simple UI + accurate ML predictions
#### 4.	Impact	Reduces fraud & increases trust
#### 5.	Business Model	API / Subscription for banks
#### 6.	Scalability	Cloud deployment support

## 📋 4. Requirement Analysis
✅ Functional Requirements
Accept transaction details
Process and transform data
Predict fraud
Display results

⚡ Non-Functional Requirements
Fast performance
User-friendly UI
Reliable system
Secure data handling

## 🏗 5. Project Design
🔄 Data Flow

User → Web UI → Flask Backend → ML Model → Result

👤 User Stories
ID	Story	Priority
#### US-1	View Home Page	High
#### US-2	Open Prediction Page	High
#### US-3	Enter Data	High
#### US-4	Submit Data	High
#### US-5	View Result	High
#### US-6	Input Validation	Medium
🧩 Architecture

Three-Tier Architecture:

Frontend (HTML, CSS)
Backend (Flask)
ML Model (.pkl)

## ⚙️ 6. Project Planning
🛠 Tech Stack
Python
Flask
Pandas, NumPy
Scikit-learn
HTML, CSS
📅 Timeline
Phase	Task	Duration
1	Data & EDA	5 Days
2	Model Training	7 Days
3	Backend	5 Days
4	Frontend	4 Days
5	Testing	3 Days

## 💻 7. Implementation
🔹 Features
Prediction API (/pred)
Data preprocessing
Log transformation
Web interface
📊 Dataset
PaySim synthetic dataset
Features:
Step
Type
Amount
Balance

## 📈 8. Performance Metrics
Accuracy
Precision
Recall
F1-Score

⚠️ Focus on Recall & F1-score due to imbalanced data.

## 📊 9. Results

The system successfully predicts fraud transactions.

Outputs:

Home Page
Prediction Page
Result Page

## ✅ 10. Advantages & Disadvantages
✔ Advantages
Real-time prediction
Easy to use
Automated fraud detection

❌ Disadvantages
Needs retraining
Possible false positives
Model performance may degrade

## 🏁 11. Conclusion

This project demonstrates how Machine Learning improves financial security by detecting fraud efficiently through a web-based system.

## 🔮 12. Future Scope
Real-time streaming detection
Banking system integration
Admin dashboard
Cloud deployment (AWS/Heroku)
Database integration

📊 Dataset
Dataset not included due to size. Download from:
👉 https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset

Place inside:

data/
 └── PS_20174392719_1491204439457_log.csv
 
🚀 How to Run
git clone <your-repo-link>
cd project-folder
pip install -r requirements.txt
python app.py
⭐ Author

Siddhesh D. Patil
