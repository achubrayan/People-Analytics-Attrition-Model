# Predictive Employee Attrition Model

## Project Overview

This project implements a **Predictive Employee Attrition Model** using the IBM HR Analytics Employee Attrition dataset. The model predicts which employees are at high risk of leaving the company, helping HR teams design targeted retention strategies.

The project demonstrates the full **Data Science lifecycle**, including:

* Data loading and cleaning
* Feature engineering
* Handling categorical variables
* Model training and hyperparameter tuning
* Evaluation using performance metrics
* Feature importance analysis and visualization


## Dataset

* **Source:** IBM HR Analytics Employee Attrition dataset
* **Filename:** WA_Fn-UseC_-HR-Employee-Attrition.csv
* **Description:** Contains employee demographics, job details, performance metrics, and attrition status

> ⚠️ **Note:** The dataset is not included due to licensing. Please download it separately.


## Project Workflow

1. **Data Loading** – Load and verify dataset
2. **Data Cleaning & Feature Engineering** – Remove irrelevant columns, convert target to binary, create new predictive features
3. **Handling Categorical Variables** – One-hot encoding
4. **Feature & Target Definition** – Separate features (X) and target (y)
5. **Train-Test Split** – Split dataset with stratification to maintain class balance
6. **Model Training** – Random Forest Classifier with hyperparameter tuning
7. **Model Evaluation** – Assess accuracy, ROC-AUC, confusion matrix, and F1-score
8. **Feature Importance** – Identify top features influencing attrition predictions
9. **Save Model** – Export trained model for future use
10. **Conclusion & Insights** – Summarize key findings and HR recommendations


## Key Findings

* Employees working overtime are more likely to leave
* Low **JobSatisfaction** and poor stock/salary ratio are strong predictors of attrition
* Top predictive features include `OverTime`, `Stock_Sal_Ratio`, and `JobSatisfaction`
* Model performance metrics (example): Accuracy ≈ 86%, ROC-AUC ≈ 91%, F1-score ≈ 78% for attrition cases


## Results & Visualizations

* **Top Feature Importance:** Highlights the factors most influencing attrition risk
* **Confusion Matrix & Metrics:** Provides insight into model performance for identifying employees likely to leave

> Include screenshots of model outputs and feature importance plots in the repository for better visualization


## Usage

* Open the Jupyter Notebook to explore the predictive model
* Ensure the dataset is available in the repository root
* Run the notebook sequentially to reproduce the analysis and visualizations


## Author

**Fabrice Achu Ngando**
[LinkedIn Profile](https://www.linkedin.com/in/fabrice-achu-ngando/?trk=opento_sprofile_topcard)

* Data Science | HR Analytics | Predictive Modeling
* Passionate about leveraging data to improve workplace insights and retention strategies


## License

Educational / Portfolio Use. Dataset must be downloaded separately due to IBM licensing
