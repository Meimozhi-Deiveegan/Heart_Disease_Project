# Heart Disease Prediction Project Report

## 1. Introduction

This report details a project focused on predicting heart disease based on various patient attributes. The project utilizes Python, Pandas, Scikit-learn, and other relevant libraries for data preprocessing, model training, and evaluation. We explore several classification models, including Logistic Regression, Decision Tree, and Random Forest, to predict the presence of heart disease.

## 2. Objectives

The primary objectives were:

* To load and preprocess the heart disease dataset.
* To perform exploratory data analysis and visualize key relationships.
* To train and evaluate multiple classification models.
* To identify the most effective model for heart disease prediction.

## 3. Methodology

The project followed these steps:

1.  **Data Loading and Initial Inspection:**
    * Imported necessary Python libraries: Pandas, NumPy, Matplotlib, and Seaborn.
    * Loaded the "dataset.csv" dataset into a Pandas DataFrame.
    * Displayed the first few rows of the DataFrame to understand the data's structure.
    * Checked for missing values and duplicates.
    * Removed duplicate rows.
    * Described the data using describe() and found the correlation using corr().

2.  **Data Visualization:**
    * Visualized the distribution of patients with and without heart disease.
    * Visualized the relationship between age and heart disease.
    * Generated a heatmap to visualize the correlation between all features.

3.  **Data Preprocessing:**
    * Split the data into independent features (X) and the dependent variable (y).
    * Split the data into training and testing sets.
    * Scaled the data using StandardScaler.

4.  **Model Training and Evaluation:**
    * Trained and evaluated Logistic Regression, Decision Tree, and Random Forest models.
    * Evaluated model performance using confusion matrices, accuracy scores, classification reports, F1-scores, recall scores, and precision scores.
    * Compared the performance of the different models.

## 4. Dataset Description

The "dataset.csv" dataset contains the following columns:

* **age:** Age of the patient.
* **sex:** Sex of the patient (1 = male; 0 = female).
* **cp:** Chest pain type.
* **trestbps:** Resting blood pressure.
* **chol:** Serum cholesterol in mg/dl.
* **fbs:** Fasting blood sugar > 120 mg/dl.
* **restecg:** Resting electrocardiographic results.
* **thalach:** Maximum heart rate achieved.
* **exang:** Exercise induced angina.
* **oldpeak:** ST depression induced by exercise relative to rest.
* **slope:** The slope of the peak exercise ST segment.
* **ca:** Number of major vessels (0-3) colored by fluoroscopy.
* **thal:** Thalassemia.
* **target:** Presence of heart disease (1 = yes; 0 = no).

## 5. Results and Observations

* The dataset contained 303 entries, with 1 duplicate removed.
* The target variable showed a relatively balanced distribution of patients with and without heart disease.
* Correlation analysis and visualizations revealed relationships between various features and the target variable.
* Logistic Regression, Decision Tree, and Random Forest models were trained and evaluated.
* The Random Forest model demonstrated the highest accuracy and overall performance.

## 6. Conclusion

This project successfully trained and evaluated multiple classification models for heart disease prediction. The Random Forest model emerged as the most effective, providing accurate predictions based on the given patient attributes. This model can be valuable for early detection and preventative measures related to heart disease.

## 7. Future Work

Future work on this project could include:

* Exploring other advanced classification models, such as Gradient Boosting or Support Vector Machines.
* Performing hyperparameter tuning to optimize the models' performance.
* Incorporating additional features or external data sources to enhance the model's predictive capabilities.
* Evaluating the model's performance on a larger and more diverse dataset.
* Developing a user-friendly interface for the model to facilitate its use in clinical settings.
* Adding more visualizations to gain deeper insights into the data.
* Performing feature engineering to create more relevant features.
