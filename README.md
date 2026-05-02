🧠 Mental Health Prediction Model
📌 Project Overview

This project develops a machine learning model to predict whether an individual requires mental health treatment based on survey data. It analyzes various workplace and personal factors that may influence mental health conditions.

🎯 Objective

To build a predictive model using Logistic Regression that can classify whether a person is likely to seek mental health treatment.

📂 Dataset

The dataset consists of survey responses with features such as:

Age
Gender
Work environment factors
Company support for mental health
Personal mental health history
⚙️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
Google Colab
🔍 Steps Performed
1. Data Cleaning
Removed irrelevant columns such as comments, state, Timestamp, and Country
Standardized inconsistent values in the Gender column
2. Handling Missing Values
Dropped columns with excessive missing values
Filled remaining missing values using the mode
3. Feature Engineering
Converted categorical variables into numerical format using Label Encoding
4. Data Splitting
Split the dataset into training and testing sets (80:20 ratio)
5. Feature Scaling
Applied StandardScaler to normalize feature values
6. Model Building
Trained a Logistic Regression model
7. Model Evaluation
Evaluated performance using:
Accuracy Score
Confusion Matrix
Classification Report
📊 Model Performance

Update this section after running your model

Accuracy: 70%

🚀 How to Run the Project
Open the notebook in Google Colab
Upload the dataset
Run all cells step-by-step
View the model results
📁 Project Structure
mental-health-prediction/
│── mental_health_prediction.ipynb
│── README.md
🔮 Future Improvements
Implement advanced models (Random Forest, XGBoost)
Perform hyperparameter tuning
Add data visualizations
Deploy the model as a web application
📌 Conclusion

This project demonstrates how machine learning can be applied to analyze mental health-related data and predict treatment needs, helping organizations better understand employee well-being.

👨‍💻 Author

Vansh
