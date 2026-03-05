
This project predicts whether a loan application will be approved or rejected using machine learning classification algorithms. The model is trained on historical loan application data and learns patterns based on applicant information.

Dataset Features
The dataset contains the following features:

Loan_ID
Gender
Married
Dependents
Education
Self_Employed
ApplicantIncome
CoapplicantIncome
LoanAmount
Loan_Amount_Term
Credit_History
Property_Area
Loan_Status

Loan_Status is the target variable used for classification.

Machine Learning Algorithms Used

The following classification algorithms were implemented and compared:

Random Forest Classifier
K-Nearest Neighbors (KNN)
Decision Tree Classifier
Gaussian Naive Bayes

These models were trained on the processed dataset to predict loan approval status.

Data Preprocessing
The following preprocessing steps were performed:

Handling missing values
Encoding categorical variables
Feature scaling using StandardScaler
Train and test split


Libraries Used

Python
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn

Project Objective

This project demonstrates how machine learning can be applied to real-world financial problems.  
By comparing multiple models, we identified an effective approach for predicting loan approval status.



How to Run the Project
1. Clone the repository: git clone https://github.com/mathdevruvaishnavi97-collab/Loan-Approval.git


2. Navigate to the project folder: cd Loan-Approval


3. Install required libraries: pip install -r requirements.txt 

4. Open the Jupyter Notebook and run all cells.


Author
Vaishnavi Mathdevru