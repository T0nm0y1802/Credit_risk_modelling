# Credit Approval Predictor
This project aims to predict the likelihood of credit approval for borrowers based on various financial and personal attributes. The process involves data cleaning, exploratory data analysis (EDA), model training, hyperparameter tuning using GridSearchCV, and deployment using Streamlit. The project is managed using GitHub for version control.

## Problem Statement
The objective is to develop a predictive model that can assess the risk associated with loan applicants and classify them into different risk categories (e.g., P1, P2, P3, P4) based on their likelihood of credit approval. This will aid financial institutions in making informed decisions while approving loans, thereby minimizing the risk of default and optimizing their lending processes.

## Data Cleaning
The dataset undergoes thorough data cleaning processes, including handling missing values, removing duplicates, encoding categorical variables, and scaling numerical features. This ensures the data is suitable for model training and analysis.

## Exploratory Data Analysis (EDA)
EDA is performed to gain insights into the dataset's characteristics and relationships between variables. Visualizations such as histograms, box plots, and correlation matrices are used to understand the distribution of features, identify patterns, and detect anomalies.

## Model Training
Various machine learning models are trained on the cleaned dataset to predict credit approval. The models include logistic regression, decision trees, random forests, and gradient boosting classifiers. Performance metrics such as accuracy, precision, recall, and F1-score are used to evaluate the models.XgBoost b performed best giving 78% accuracy

## Hyperparameter Tuning
GridSearchCV is employed to fine-tune the hyperparameters of the selected model(s) and optimize their performance. This process involves systematically searching through a range of hyperparameter values to identify the best combination that maximizes the model's predictive accuracy.

## Deployment Using Streamlit
The final trained model is deployed using Streamlit, a Python library for creating interactive web applications. The Streamlit app allows users to upload borrower information and obtain predictions regarding their credit approval status. The app provides a user-friendly interface for accessing the predictive model's functionality.

## Version Control Using GitHub
GitHub is utilized for version control, enabling collaboration, code sharing, and tracking changes throughout the project's development lifecycle. The project repository contains the source code, data files, documentation, and other relevant resources.


1. Install Streamlit: pip install streamlit
2. Clone the repository: git clone [repository-url]
3. Navigate to the project directory: cd credit-risk-model
4. Run the Streamlit app: streamlit run app.py
5. Access the application in your browser at the provided URL (typically https://creditriskmodel.streamlit.app/)


1. Open the deployed Streamlit application in your web browser.
2. Input the relevant applicant information directly into the provided form fields, or upload an Excel/CSV file containing the required columns.
3. Click the "Predict" button to obtain the model's prediction on the likelihood of loan approval.
4. Review the predicted risk category (P1, P2, P3, or P4) and associated confidence score.
5. Optionally, download the predicted labels in an Excel file for further analysis or record-keeping.
Feel free to customize and expand upon this outline based on the specific details and requirements of your project!
