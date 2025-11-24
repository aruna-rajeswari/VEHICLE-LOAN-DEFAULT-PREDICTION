# 🚗 Vehicle Loan Default Prediction

A comprehensive data analysis and predictive modeling project aimed at identifying high-risk vehicle loan applicants and understanding the factors influencing loan defaults. The project leverages **statistical analysis, machine learning, and interactive dashboards** to support data-driven decision-making for financial institutions.

---

## 📌 Introduction

Financial institutions face substantial losses due to vehicle loan defaults. Stricter underwriting practices have increased rejection rates, creating the need for improved credit risk scoring models.  
This project aims to **analyze key determinants of vehicle loan defaults** and **build a predictive model** to classify potential defaulters.

---

## 🎯 Objectives

- Identify determinants of vehicle loan defaults using statistical analysis and exploratory data analysis (EDA).  
- Develop a predictive model to classify potential defaulters and non-defaulters.  
- Visualize findings in an **interactive dashboard** to aid stakeholder decision-making.

---

## 📂 Data Overview

- Dataset contains **41 attributes** relating to:
  - Customer demographics
  - Employment details
  - Loan application details
  - Credit bureau history
  - Loan performance metrics

---

## 📝 Methodology

### **Step 1: Data Importing, Understanding & Inspection**
- Assessed data structure, missing values, duplicates, and variable types.  
- Standardized variable names for Python conventions.  
- Imputed missing values using mean, median, mode, or domain knowledge.

### **Step 2: Exploratory Data Analysis (EDA)**
1. **Statistical Description**: Descriptive stats (mean, median, std) for numerical variables.  
2. **Target Variable Distribution**: Examined default rates to assess dataset balance.  
3. **Category-wise Analysis**: Default rates by branch, city, state, supplier, manufacturer.  
4. **Employment Type Impact**: Analyzed employment type distribution among defaulters; visualized using pie charts.  
5. **Age Factor**: Studied correlation between age and default probability.  
6. **Customer ID Proof Analysis**: Identified common ID types submitted by applicants.

### **Step 3: Credit & Loan Performance Analysis**
- Compared credit bureau scores between defaulters and non-defaulters.  
- Studied primary and secondary loan accounts for default correlation.  
- Examined sanctioned vs. disbursed amounts for discrepancies.  
- Analyzed loan enquiry frequency and its relation to defaults.  
- Investigated recent loan activities, past defaults, and loan tenure.

### **Step 4: Modeling**
- Applied **Logistic Regression** to classify defaulters.  
- Split data into **train/test sets**, trained the model, and evaluated predictions.  
- Performance metrics used: **Accuracy, Precision, Recall, F1-score**.

### **Step 5: Dashboarding**
- Built an **interactive Tableau dashboard** showcasing:
  - Default rates by region, supplier, and customer profile.  
  - Relationship between credit scores, loan amounts, and defaults.  
  - Key factors influencing loan default probability.  
- Dynamic filtering for stakeholder exploration and insights.

---

## 🚀 Expected Outcomes

- Data-driven understanding of key factors influencing vehicle loan defaults.  
- Predictive scoring model to identify high-risk applicants.  
- Interactive visualization tool to support risk management and decision-making.

---

## 💡 Impact

This project helps financial institutions:

- Reduce loan defaults through better credit risk assessment.  
- Optimize loan approval strategies.  
- Enhance operational efficiency via data-driven underwriting policies.

---
---
