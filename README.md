# employee-attrition-mlflow

Employee Attrition Prediction

Overview:
This project aims to predict employee attrition using machine learning techniques. Employee attrition, the phenomenon of employees leaving an organization, can significantly impact productivity, morale, and financial performance. By leveraging a dataset comprising various attributes such as demographics, job roles, and satisfaction levels, we explore the application of machine learning algorithms to predict and mitigate attrition risks.

Features:

Dataset: The dataset used in this project contains information about employee demographics, job roles, satisfaction levels, and work environment attributes.
Models: We employ multiple machine learning algorithms, including Random Forest, Logistic Regression, Support Vector Machine (SVM), and XGBoost, to predict employee attrition.
Evaluation: The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score.
Experimentation: We utilize MLflow, an open-source platform for managing the machine learning lifecycle, to streamline the experimentation process and track model performance.
Setup:
To run this project locally, follow these steps:

Clone the repository: git clone https://github.com/your_username/employee-attrition-prediction.git
Navigate to the project directory: cd employee-attrition-prediction
Install the required dependencies: pip install -r requirements.txt
Run the Jupyter Notebook or Python script to train and evaluate the models.
Usage:

Load the dataset: employee_data.csv
Preprocess the data: Handle missing values, encode categorical variables, and standardize features.
Train and evaluate models: Run the provided Jupyter Notebook or Python script to train different machine learning models and evaluate their performance.
Experiment with hyperparameters: Adjust hyperparameters such as the number of estimators, maximum depth, and regularization strength to optimize model performance.
Track experiments: Utilize MLflow to log parameters, metrics, and artifacts for each experiment and compare different models' performance.
Results:
The project results demonstrate the effectiveness of machine learning algorithms in predicting employee attrition. XGBoost with a maximum depth of 5 and 100 estimators achieved the highest accuracy of 85.71%. The findings offer valuable insights into addressing attrition challenges and improving human resource management practices.
