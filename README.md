# Heart-Disease-Prediction-using-ML
Heart Disease Prediction using Random Forests, Decision Tree, Logistic Regression and XG Boost 

# Introduction:

Heart disease remains one of the leading causes of mortality worldwide, posing significant challenges to healthcare systems. Early detection and accurate prediction of heart disease can greatly enhance the chances of successful treatment and prevention, ultimately saving lives and reducing healthcare costs. Traditional methods of diagnosing heart disease often rely on subjective clinical evaluations and invasive procedures, which can be time-consuming and uncomfortable for patients.



# Methodology:

Our methodology for the project follows a structured pipeline to ensure comprehensive and effective model development. It begins with Data Acquisition, where we gather relevant data from various sources. This is followed by Data Preprocessing, which involves cleaning and preparing the data for analysis. Exploratory Data Analysis (EDA) is then conducted to uncover patterns and insights within the data. Next, we engage in Feature Engineering to create meaningful features that enhance model performance. We utilize several algorithms for modeling, including Logistic Regression, Decision Tree, Random Forest, and XG Boost. Each of these models is evaluated for performance. The final step is Model Evaluation, where we assess the models using metrics such as precision, recall, and F1 score to ensure the best model is selected for deployment.
 


# Data Acquisition: 
The dataset utilized for identifying heart disease within the tests was sourced from the Kaggle platform  and can be gotten to freely at kaggle/input/Heart-disease/new_model.csv [10]. It comprised 1000 tests with 16 highlights, and specialists labeled this two-class dataset based on whether patients had Heart Disease or not. 

# Data Preprocessing: 
Effective data preprocessing is a crucial step in any machine learning project, as the quality of the input data significantly impacts the performance of the predictive models. In this project on heart disease prediction, several preprocessing tasks were undertaken to ensure the data was clean, consistent, and suitable for analysis:
1.	Handling Imbalance Data:
o	Balancing: By balancing the dataset, you ensure that your model does not become biased towards the majority class and performs well across all classes. This leads to more reliable and fair predictions, especially in critical applications where the minority class is of particular interest.
2.	Removing Duplicates and Outliers:
o	Duplicates: Duplicate records, which can distort the model's learning process, were identified and removed to ensure each data point was unique.
3.	Standardizing and Normalizing Data:
o	Standardization: Numerical features were standardized to have a mean of zero and a standard deviation of one. This process ensured that the data was on a similar scale, which is particularly important for algorithms that rely on distance measurements.
o	Normalization: Alternatively, normalization was applied to scale the numerical data within a specific range, typically between 0 and 1. This helped in speeding up the convergence of gradient-based algorithms.
 

# Exploratory Data Analysis (EDA):
Exploratory Data Analysis (EDA) is a critical step in understanding the underlying patterns, relationships, and distributions within the dataset. For the heart disease prediction project, several EDA techniques were employed:
1.	Descriptive Statistics:
o	Mean, Median, Mode: The central tendency of numerical features was summarized using mean, median, and mode. These statistics provided a quick overview of the data’s central values.
o	Standard Deviation: The variability of the data was assessed using standard deviation, highlighting how spread out the data points were from the mean.

 


2.	Distribution Analysis:
o	Histograms: Histograms were plotted for numerical variables to visualize their distributions. This helped in identifying skewness, kurtosis, and the presence of any outliers.
o	Box Plots: Box plots were used to depict the spread and central tendency of the data, as well as to identify potential outliers within different features.
 

3.	Correlation Analysis:
o	Heatmaps: Correlation heatmaps were generated to examine the relationships between various features. This visual representation helped in identifying strongly correlated variables, which could influence the predictive modeling process.

 

4.	Group Comparisons:
o	Demographic Analysis: The incidence of heart disease was analyzed across different demographic groups such as age, gender, and ethnicity. This analysis provided insights into which demographic factors were associated with higher risks of heart disease.

Through these EDA techniques, we were able to uncover significant patterns and relationships within the data, guiding the feature selection and engineering processes. The insights gained from EDA also provided a solid foundation for the development and refinement of the machine learning models aimed at predicting heart disease.
 
# Feature Engineering:
 Feature engineering plays a pivotal role in enhancing the performance of machine learning models by creating new features that better represent the underlying patterns in the data. In this project on heart disease prediction, several feature engineering techniques were employed to improve the predictive power of the models:

1.	Creating New Features:
o	Log Blood Pressure: A logarithmic transformation of blood pressure was performed to normalize the distribution and reduce the impact of extreme values.
o	Cholesterol_BloodPressure: A composite feature combining cholesterol and blood pressure levels to capture their combined effect on heart health.
o	Exercise_Stress: A measure of stress induced by exercise, which is a significant indicator of heart disease risk.
o	Cholesterol_Ratio: The ratio of HDL (good) cholesterol to LDL (bad) cholesterol, a well-known indicator of heart health.
o	Mean Arterial Pressure: A calculated feature representing the average arterial pressure, providing insight into the overall blood pressure condition.
o	Risk Score: A composite risk score derived from multiple factors such as age, cholesterol levels, and blood pressure, which are known to influence heart disease risk.

# 	Machine Learning Models:
# 	Logistic Regression: 
Logistic Regression is a linear model widely used for binary classification tasks, such as predicting the presence or absence of heart disease. It works by estimating the probability that a given input belongs to a particular class using a logistic function. The model outputs probabilities, which are then thresholded to make a final classification decision. Logistic Regression is appreciated for its simplicity, ease of implementation, and interpretability, making it a strong baseline model for many classification problems.
 
# Decision Trees: 

Decision Trees are non-linear models that recursively split the data into subsets based on feature values, forming a tree-like structure. Each node in the tree represents a feature, each branch represents a decision rule, and each leaf node represents an outcome. Decision Trees are intuitive and easy to visualize, making them useful for understanding the decision-making process. They handle both numerical and categorical data and are capable of capturing non-linear relationships in the data.

# 	Random Forests: 
Random Forests are an ensemble learning method that constructs multiple decision trees during training and merges their outputs to improve accuracy and control overfitting. Each tree in the forest is trained on a random subset of the data and features, and the final prediction is made by averaging the predictions (for regression) or majority voting (for classification). Random Forests are robust, handle large datasets well, and provide insights into feature importance.

# 	Gradient Boosting: 
Gradient Boosting is another powerful ensemble technique that builds models sequentially, with each new model focusing on correcting the errors of the previous ones. Typically using decision trees as base learners, Gradient Boosting optimizes the model by minimizing a loss function in a stage-wise manner. This method is known for its high predictive accuracy and ability to handle a variety of data types, capturing complex relationships in the process.




 





