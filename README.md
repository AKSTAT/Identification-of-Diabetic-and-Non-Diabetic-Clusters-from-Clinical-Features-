## Project Summary: Identification of Diabetic and Non-Diabetic Clusters from Clinical Features

This project explores the **Identification of diabetic and non-diabetic clusters** using a comprehensive dataset of clinical features. We delve into a real-world diabetes dataset, encompassing attributes like pregnancies, glucose levels, blood pressure, insulin, BMI, and age, alongside the patient's outcome (diabetic or non-diabetic).

The repository details a complete machine learning workflow:

* **Data Import & Exploration:** Loading the dataset and conducting initial observations, noting its **768 records** and **9 features**. Key findings include the presence of **zero values representing missing data** in features like Glucose and Insulin, and a highly **imbalanced outcome variable**.
* **Data Visualization:** Visual analysis reveals a **high correlation between Outcome and Glucose, BMI, Age, and Insulin**, highlighting their significance as potential predictors.
* **Data Preprocessing:** Steps taken to prepare the raw data for modeling, addressing issues like missing values.
* **Data Modeling & Evaluation:** While the project title suggests unsupervised learning, the provided analysis focuses on a **Random Forest classifier**. This supervised model achieved an **overall accuracy of approximately 76%**.
* **Performance Metrics:** The model demonstrated a **precision of 67.35%** and a **recall of 61.11%** for the positive (diabetic) class, with an **F1 score of 0.6408**. A strong **ROC AUC score of 0.81** indicates good discriminative power.

This project serves as a practical example of applying machine learning to healthcare data, showcasing the process from data understanding to model evaluation. It also identifies areas for future improvement, such as hyperparameter tuning and feature engineering, to enhance predictive performance, especially in reducing false negatives.
