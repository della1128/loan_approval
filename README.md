🏦 Loan Approval Prediction using Machine Learning
This project explores and predicts loan approval status using supervised machine learning models. It includes end-to-end steps: data cleaning, visualization, feature engineering, model training, and evaluation.

📁 Dataset
The dataset contains customer information such as:

Gender, Marital Status, Dependents

Education, Employment

Income, Loan Amount, Credit History

Property Area

Target: Loan_Status (Y/N)

📄 Data source: Uploaded manually (loan_prediction.csv)

📊 Project Workflow
Data Loading & Cleaning

Removed Loan_ID

Handled missing values

Encoded categorical variables

Exploratory Data Analysis (EDA)

Visualized trends using Plotly

Analyzed feature relationships with Loan_Status

Feature Engineering

Converted categorical variables to numeric using one-hot encoding

Engineered features like TotalIncome (Applicant + Coapplicant)

Model Building

Trained and evaluated multiple models:

Logistic Regression

Decision Tree

Random Forest Classifier

Model Evaluation

Used Accuracy, Confusion Matrix

Compared training vs test performance

🧪 Results
Best accuracy achieved with: Random Forest Classifier

Insight: Features like Credit_History, ApplicantIncome, and LoanAmount had a major impact on loan approval.

📌 Requirements
To install required Python packages:

bash
Copy
Edit
pip install -r requirements.txt
🚀 How to Run
Option 1: Open in Google Colab

Option 2: Run Locally
bash
Copy
Edit
git clone https://github.com/your-username/loan-approval-predictor.git
cd loan-approval-predictor
jupyter notebook Loan_Approval.ipynb
📷 Sample Visualizations
Income vs Loan Approval Rate

Credit History impact

Education-wise approval comparison

📁 See assets/ folder for saved charts

📦 Files in This Repo
File	Purpose
Loan_Approval.ipynb	Main notebook with full analysis
loan_prediction.csv	Input dataset
requirements.txt	Python dependencies
README.md	Project overview
assets/	Charts/images generated from analysis

👩‍💻 Author
Della Cherian
Data Science & AI Enthusiast
