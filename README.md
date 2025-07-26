This project focuses on predicting the employee attrition using machine learning model. This project will predict whether the  employee attrition is Yes or No.

**🛠️Imported Libraries.**
      1. Python-Core programming language
      2. Pandas-Data manipulation and preprocessing
      3. NumPy-Numerical operations
      4. Matplotlib/Seaborn-	Data visualization
      5. Scikit-learn	Machine learning algorithms and evaluation
      6. Streamlit-Web app framework for model deployment
      7. Pickle	Save/load machine learning models

**🎯 Objectives:**

      * Analyze employee data to discover key factors contributing to attrition.
      * Build a machine learning model that can predict whether an employee is likely to leave.
      * Deploy the model using Streamlit to create an interactive web application.
      * Allow HR professionals to input employee data and receive real-time attrition risk predictions.

**🧠 Machine Learning :**** 
     * Model Used: Logestic regression
     * Encoding: One-hot encoding was used for categorical variables.
     * Scaling: StandardScaler for numerical feature scaling.
     * Class Imbalance-SMOTE (Synthetic Minority Over-sampling Technique) Creates synthetic samples for the minority class to balance the dataset.

**⚙️ Streamlit Application**
      *  The Streamlit app provides an intuitive UI where HR users can:
      *  Input employee attributes (age, income, job role, etc.)
      *  Click a “Predict Attrition” button
      *  View prediction results with probability and alert messages
