❤️ Heart Disease Prediction & Healthcare Data Analysis
📌 Project Objective

      The objective of this project is to analyze healthcare data and build a machine learning model to predict the presence of heart disease. The project focuses on data preprocessing, visualization, correlation analysis, and classification using Logistic Regression.

📊 Dataset Used

    Dataset: heart.csv
    
    Contains patient medical attributes such as:
    
    Age
    
    Sex
    
    Chest Pain Type (cp)
    
    Cholesterol (chol)
    
    Blood Pressure
    
    Maximum Heart Rate
    
    Target (1 = Heart Disease, 0 = No Disease)
    
    🛠 Technologies & Libraries Used
    
    Python
    
    Pandas
    
    NumPy
    
    Matplotlib
    
    Seaborn
    
    Scikit-learn

🧹 Data Preprocessing

    The following preprocessing steps were performed:
    
    Checked data types and null values (info(), isnull())
    
    Generated summary statistics (describe())
    
    Filled missing values using mean imputation
    
    Applied One-Hot Encoding (get_dummies)
    
    Feature Scaling using StandardScaler
    
    Split dataset into training and testing sets (80/20 split)

📈 Exploratory Data Analysis (EDA)
    🔹 Target Distribution
    
    A count plot was used to visualize the distribution of heart disease cases (1 = Yes, 0 = No).
    
    🔹 Correlation Heatmap
    
    A heatmap was generated to analyze relationships between features and identify strong predictors of heart disease.
    
    🔹 Age vs Heart Disease
    
    A boxplot showed that heart disease is more common in higher age groups.
    
    🔹 Chest Pain Type vs Target
    
    A count plot revealed that certain chest pain types are more associated with heart disease.
    
    🔹 Cholesterol Analysis
    
    Average cholesterol levels were compared between patients with and without heart disease using groupby analysis.

🤖 Machine Learning Model
      Model Used:
      
      Logistic Regression
      
      Steps:
      
      Data split using train_test_split
      
      Model training using LogisticRegression
      
      Predictions made on test data

📊 Model Evaluation

    The model was evaluated using:
    
    Accuracy Score
    
    Classification Report (Precision, Recall, F1-Score)
    
    Confusion Matrix (visualized using heatmap)
    
    These metrics help measure the performance of the classification model in predicting heart disease.

📁 Output

    Cleaned dataset exported as:
    cleaned_healthcare.csv

📌 Key Insights

    Age is positively correlated with heart disease risk.
    
    Certain chest pain types strongly indicate heart disease.
    
    Cholesterol levels vary between diseased and non-diseased patients.
    
    Logistic Regression can effectively classify heart disease presence with good accuracy.

🚀 Conclusion

    This project demonstrates how healthcare data can be cleaned, analyzed, and used to build a predictive machine learning model. Early prediction of heart disease can assist healthcare professionals in preventive treatment and better decision-making.
