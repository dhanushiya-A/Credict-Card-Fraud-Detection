
# Credit Card Fraud Detection

## 📌 Description
A machine learning project for detecting fraudulent credit card transactions using Logistic Regression. The dataset is balanced by sampling legitimate transactions, then trained and tested to evaluate accuracy in fraud detection.

---

## ⚙️ Project Workflow
1. **Import Libraries** – NumPy, Pandas, Scikit-learn  
2. **Load Dataset** – `creditcard.csv`  
3. **Explore Data** – check missing values, class distribution, transaction statistics  
4. **Balance Dataset** – sample legitimate transactions equal to fraud cases  
5. **Prepare Features & Labels** – drop `Class` column for features, keep `Class` as target  
6. **Train-Test Split** – 80% training, 20% testing with stratification  
7. **Model Training** – Logistic Regression  
8. **Evaluation** – accuracy on training and test data  

---

## 📊 Results
- Accuracy on Training Data: ~**0.9504447268106735**  
- Accuracy on Test Data: ~**0.9289340101522843** 

---

## 🚀 How to Run
# 1. Clone the repository:
   git clone https://github.com/dhanushiya-A/Credict-Card-Fraud-Detection.git
# 2. Navigate to the project folder:
cd credit-card-fraud-detection
# 3. Run the script:
  python fraud_detection.py
# 📂 Files

credit fraud prediction.ipynb→ jupyter file with model code

README.md → Documentation

# 📌 Requirements
Python 3.x

NumPy

Pandas

Scikit-learn

# Install dependencies:
pip install numpy pandas scikit-learn
