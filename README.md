VEHICLE LOAN DEFAULT PREDICTION

1. INTRODUCTION
Financial institutions face substantial losses due to vehicle loan defaults. In recent years, this has driven stricter underwriting practices,
resulting in higher rejection rates for vehicle loan applications. Consequently, there is a pressing need for an improved credit risk scoring model
to more accurately assess the probability of loan defaults. This project aims to identify and analyze the factors influencing vehicle loan default rates
and leverage these insights to build a predictive model that can identify potential defaulters.

3. OBJECTIVES
•	Identify determinants of vehicle loan defaults through statistical analysis and exploratory data analysis (EDA).
•	Develop a predictive model to classify potential defaulters and non-defaulters.
•	Visualize the findings in an interactive dashboard to aid decision-making for stakeholders.

4. DATA OVERVIEW
•	The dataset provided contains 41 attributes relating to customer demographics, employment details, loan application details, credit bureau history, and loan performance metrics.

5. METHODOLOGY
Step 1: Data Importing, Understanding, and Inspection
•	Performed preliminary inspection to assess data structure, missing values, duplicates, and variable types.
•	Standardized variable names to comply with Python naming conventions.
•	Identified and analyzed missing values, implementing appropriate imputation strategies (mean/median replacement, categorical mode filling, or domain-driven assumptions).
Step 2: Exploratory Data Analysis (EDA)
1.Statistical Description
•	Generated descriptive statistics (mean, median, standard deviation) for quantitative variables to understand central tendency and spread.
2.Target Variable Distribution
•	Studied the overall distribution of the loan default variable to assess dataset balance.
3.Category-Wise Analysis
•	Analyzed default rates across attributes like branch, city, state, supplier, and manufacturer.
4.Employment Type Impact
•	Examined the distribution of employment types among defaulters and non-defaulters.
•	Created pie charts to visualize employment category proportions.
•	Developed imputation strategies for missing employment type values.
5.Age Factor
•	Assessed age distribution for both defaulters and non-defaulters to determine correlation with default probability.
6.Customer ID Proof Analysis
•	Determined the most commonly presented ID type for loan applications.
Step 3: Credit and Loan Performance Analysis
•	Credit Bureau Score: Compared distributions of credit scores for defaulters vs. non-defaulters.
•	Primary & Secondary Loan Accounts: Studied account details for potential default correlations.
•	Sanctioned vs. Disbursed Amounts: Examined discrepancies between approved and disbursed amounts for both primary and secondary loans.
•	Loan Enquiry Frequency: Analyzed if a higher number of loan enquiries corresponds to increased default risk.
•	Credit History Features: Investigated recent loan activities (last 6 months), past defaults, and time since first loan to evaluate their predictive strength.

Step 4: Modeling
•	Applied Logistic Regression to classify potential defaulters.
•	Split data into training and test sets, trained the model, and predicted outcomes.
•	Evaluated results using a confusion matrix and performance metrics (accuracy, precision, recall, F1-score).

Step 5: Dashboarding
•	Created an interactive Tableau dashboard to visualize:
•	Default rates across regions, suppliers, and customer profiles.
•	Relationships between credit scores, loan amounts, and defaults.
•	Key factors influencing loan default probability.
•	Enabled stakeholders to filter and explore data dynamically for better insights.

5. EXPECTED OUTCOMES
•	A data-driven understanding of the primary factors influencing vehicle loan defaults.
•	A predictive scoring model to identify high-risk loan applicants.
•	An interactive visualization tool to support decision-making and risk management.

6. IMPACT
This project will help financial institutions:
•	Reduce loan defaults by improving credit risk assessment.
•	Optimize loan approval strategies.
•	Enhance operational efficiency through data-driven underwriting policies.
