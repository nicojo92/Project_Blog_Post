Job Satisfaction Prediction - Machine Learning Project

Motivation
This project aims to understand and predict job satisfaction among professionals using survey data. By analyzing factors like work arrangement, education level, country of residence, and compensation, we explore what influences satisfaction the most. The project also compares the predictive performance of several machine learning models to identify the most accurate approach.

Libraries Used
	•	pandas: Data manipulation and cleaning
	•	numpy: Numerical operations
	•	matplotlib & seaborn: Data visualization
	•	scikit-learn: Model training, evaluation, and preprocessing
	•	xgboost: Gradient boosting regression

Files in the Repository
	•	job_satisfaction_analysis.ipynb: The main notebook with all code for data 			processing, modeling, and visualization.
	•	job_satisfaction_utils.py: Optional script containing helper functions (if 			applicable).
	•	README.txt: This file, explaining the project and its components.
	•	requirements.txt: A list of required Python libraries.
	•	data/: Directory to store cleaned or raw dataset files (not included due to size 		or privacy).
	•	output/: Directory where generated plots and models are saved.

Summary of Results
The target variable, JobSat, was predicted using four models: Linear Regression, Decision Tree, Random Forest, and XGBoost. All models were evaluated using Mean Absolute Error (MAE) and R² score. Random Forest achieved the lowest MAE (~1.53), indicating it was the most accurate.

Visual analysis revealed that:
	•	Developers by profession report the highest satisfaction.
	•	Job satisfaction tends to increase with age and advanced education.
	•	Remote workers are generally more satisfied.
	•	Compensation has a positive but not perfectly linear correlation with 				satisfaction.

Acknowledgments
	•	The dataset used in this project is based on developer survey data (https://			survey.stackoverflow.co/2024/).
	•	scikit-learn, xgboost, and pandas libraries form the backbone of the machine 			learning workflow.
