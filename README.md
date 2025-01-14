# Predicting Diabetes Outcomes using Machine Learning

## Project Overview
This project focuses on leveraging machine learning techniques to predict diabetes in individuals using the Pima Indians Diabetes Database. The goal is to improve early detection and support healthcare professionals in intervention planning.

### Key Objectives:
- Develop accurate predictive models for diabetes outcomes.
- Perform comprehensive data analysis and preprocessing.
- Evaluate models using standard performance metrics.

---

## Dataset
- **Name:** Pima Indians Diabetes Database
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/diabetes)
- **Size:** 768 records, 8 features + 1 target variable

### Features:
| Feature                 | Type    | Description                                  |
|-------------------------|---------|----------------------------------------------|
| Pregnancies            | Integer | Number of times pregnant                    |
| Glucose                | Integer | Plasma glucose concentration after 2 hours  |
| Blood Pressure         | Integer | Diastolic blood pressure (mm Hg)            |
| Skin Thickness         | Integer | Triceps skinfold thickness (mm)             |
| Insulin                | Integer | 2-Hour serum insulin (mu U/ml)              |
| BMI                    | Float   | Body Mass Index                              |
| Diabetes Pedigree Func | Float   | Diabetes pedigree function                  |
| Age                    | Integer | Age (years)                                  |
| Outcome                | Integer | 1: Positive for diabetes, 0: Negative       |

---

## Methodology

### 1. Data Preprocessing
- **Outlier Detection:** Identified and handled outliers in key features.
- **Standardization:** Scaled features to normalize data.
- **Train-Test Split:** 80% training, 20% testing.

### 2. Machine Learning Models
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Support Vector Machine (SVM)**

### 3. Evaluation Metrics
- Accuracy
- Precision, Recall, F1-Score
- ROC-AUC Score

---

## Results

| Model                  | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|------------------------|----------|-----------|--------|----------|---------|
| Logistic Regression    | 75%      | 73%       | 75%    | 73.7%    | 0.815   |
| Decision Tree          | 76%      | 75%       | 72%    | 73.5%    | 0.757   |
| Random Forest          | **78.5%**| **82.5%** | 80%    | **81.2%**| **0.814**|
| Support Vector Machine | 73%      | 80%       | 78.5%  | 79.2%    | 0.805   |

**Top Performer:** Random Forest achieved the highest balance of accuracy, precision, and recall.

---

## Future Work
- Implement advanced models like Gradient Boosting (XGBoost, LightGBM).
- Explore feature engineering to improve predictive performance.
- Deploy the model as a web application using Flask or Streamlit.

---

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---

## Acknowledgments
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/diabetes) for the dataset.
- Scikit-learn and Matplotlib libraries for model development and visualization.

---

## Contact
- **Author:** Adithya Vardhan Reddy
- **Email:** [Gmail](adithyavardhanreddy2003@gmail.com)
- **LinkedIn:** [LinkedIn](https://www.linkedin.com/in/yravr)
- **GitHub:** [GitHub]((https://github.com/Y-R-A-V-R-5))
