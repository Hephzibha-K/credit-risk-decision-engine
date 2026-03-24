# Credit Risk Decision Engine & Financial Impact Dashboard

## 📌 Problem
Financial institutions face significant losses due to loan defaults. The challenge is to accurately identify high-risk applicants and make better lending decisions.

---

## 🚀 Solution
Developed a credit risk prediction system using machine learning to estimate the probability of loan default. Built a rule-based decision engine to classify loan applications into:
- Approve
- Review
- Reject

---

## 📊 Key Results
- Reduced expected financial loss by ~58%
- Achieved ROC-AUC score of 0.68
- Processed and analyzed 260K+ loan records
- Identified key drivers of default risk

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)
- Power BI

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Cleaned missing values
- Encoded categorical variables
- Removed irrelevant features

### 2. Feature Engineering
- Created risk-related variables
- Processed financial indicators like DTI, income, interest rate

### 3. Model Building
- Used Logistic Regression to predict default probability
- Evaluated using ROC-AUC metric

### 4. Decision System
- Applied thresholds on predicted risk:
  - Low risk → Approve
  - Medium risk → Review
  - High risk → Reject

### 5. Business Impact Analysis
- Compared expected loss before and after applying decision rules
- Achieved significant loss reduction

---

## 📈 Dashboard
Developed an interactive Power BI dashboard to:
- Visualize loan decisions
- Analyze risk patterns
- Identify key drivers of default

(Add your dashboard screenshot here)

---

## 🔍 Key Insights
- Higher interest rates are associated with increased default risk
- Borrowers with high debt-to-income ratios are more likely to default
- Lower income groups show higher average risk
- Rejecting high-risk loans significantly reduces financial loss

---

## 📂 Project Structure
- Data preprocessing & modeling notebook
- Final processed dataset
- Power BI dashboard
- Output predictions

---

## 📢 Conclusion
This project demonstrates how machine learning can be used to support financial decision-making and reduce risk through data-driven strategies.