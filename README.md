# Early Detection of Parkinson's Disease Using Voice Data 

📌 **Project Overview**

This project involves the analysis of the UCI Parkinson's Dataset, focusing on classification and regression tasks using machine learning techniques. The dataset consists of two main files:

parkinsons.data – Used for classification to distinguish individuals with and without Parkinson’s disease.

parkinsons_updrs.data – Used for regression to predict Unified Parkinson’s Disease Rating Scale (UPDRS) scores, which assess disease severity based on biomedical voice measurements.

The goal of this project is to enhance early diagnosis and severity assessment of Parkinson’s disease using machine learning models.

📂 **Dataset Information**

The dataset is obtained from the UCI Machine Learning Repository and contains biomedical voice measurements from individuals with and without Parkinson’s disease. The Telemonitoring Parkinson’s Disease Dataset (found in the Telemonitoring folder) extends the original dataset by including additional biomedical voice measurements and UPDRS scores.

Machine Learning Approaches

Classification (parkinsons.data)

The following models were used to classify individuals as having Parkinson’s disease or not:

Random Forest Classifier

Support Vector Classifier (SVC)

XGBoost Classifier

Regression (parkinsons_updrs.data)

The following models were applied to predict UPDRS scores:

Linear Regression

Random Forest Regressor

Support Vector Regressor (SVR)

📂 **Implementation Steps**

1️⃣ Data Preprocessing:

Handled missing values (if any) and checked for data inconsistencies.

2️⃣ Feature Engineering:

Standardized numerical features using MinMaxScaler and StandardScaler.

3️⃣ Feature Selection:

Identified the most important features using model-based feature selection.

4️⃣ Model Training & Evaluation:

Split data into training and test sets (80% training, 20% testing).

Applied machine learning models for classification and regression.

Evaluated models using appropriate metrics:

Classification: Accuracy, Precision, Recall, F1-score

Regression: Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score

📂 **Installation & Usage**

Requirements

Ensure you have Python installed along with the following dependencies:

pip install numpy pandas scikit-learn xgboost matplotlib seaborn

Run the Project

Clone the repository and navigate to the project directory:

git clone git@github.com:dlwub/Early-Detection-of-Parkinson-s-Diseases-Using-Voice-Data.git

📂 **Results**

The Random Forest Classifier and XGBoost Classifier achieved high accuracy in distinguishing Parkinson’s patients from healthy individuals.

The Random Forest Regressor Regressor outperformed other models in predicting UPDRS scores.

🔥 **Future Improvements**

Implement deep learning models for improved performance.

Use hyperparameter tuning (GridSearchCV, RandomizedSearchCV) on the regression models for further optimization.

Integrate additional patient data for better generalization.

👨‍💻 **Author**

Desta Legesse Wubishet

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

_NOTE: we recommend using the [MIT license](https://choosealicense.com/licenses/mit/) - you can set it up quickly by [using templates available on GitHub](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository). You can also use [any other license](https://choosealicense.com/licenses/) if you wish._

<p align="right">(<a href="#readme-top">back to top</a>)</p>
