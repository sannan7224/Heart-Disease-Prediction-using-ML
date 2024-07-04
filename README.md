# Heart-Disease-Prediction-using-ML
Heart Disease Prediction using Random Forests, Decision Tree, Logistic Regression and XG Boost 

# Introduction:

Heart disease remains one of the leading causes of mortality worldwide, posing significant challenges to healthcare systems. Early detection and accurate prediction of heart disease can greatly enhance the chances of successful treatment and prevention, ultimately saving lives and reducing healthcare costs. Traditional methods of diagnosing heart disease often rely on subjective clinical evaluations and invasive procedures, which can be time-consuming and uncomfortable for patients.



# Methodology:

Our methodology for the project follows a structured pipeline to ensure comprehensive and effective model development. It begins with Data Acquisition, where we gather relevant data from various sources. This is followed by Data Preprocessing, which involves cleaning and preparing the data for analysis. Exploratory Data Analysis (EDA) is then conducted to uncover patterns and insights within the data. Next, we engage in Feature Engineering to create meaningful features that enhance model performance. We utilize several algorithms for modeling, including Logistic Regression, Decision Tree, Random Forest, and XG Boost. Each of these models is evaluated for performance. The final step is Model Evaluation, where we assess the models using metrics such as precision, recall, and F1 score to ensure the best model is selected for deployment.
 


# Data Acquisition: 
The dataset utilized for identifying heart disease within the tests was sourced from the Kaggle platform  and can be gotten to freely at kaggle/input/Heart-disease/new_model.csv [10]. It comprised 1000 tests with 16 highlights, and specialists labeled this two-class dataset based on whether patients had Heart Disease or not. 

# Data Preprocessing: 
Data preprocessing is a crucial step in the data analysis and machine learning pipeline, aimed at transforming raw data into a clean and usable format. This process involves several key tasks: data cleaning, where inconsistencies and missing values are addressed; data transformation, which includes normalization, scaling, and encoding categorical variables; and data reduction, such as dimensionality reduction and feature selection to remove irrelevant or redundant information. Preprocessing ensures that the dataset is accurate, consistent, and formatted correctly, which improves the performance and reliability of machine learning models. Effective preprocessing can significantly enhance model accuracy, reduce training time, and prevent issues like overfitting or underfitting.

# Exploratory Data Analysis (EDA):
Exploratory Data Analysis (EDA) is a critical phase in the data analysis process where analysts use statistical and graphical techniques to investigate datasets, summarize their main characteristics, and uncover patterns, anomalies, or relationships. The goal of EDA is to gain insights and understanding of the data before applying any machine learning models or advanced analytics. This involves visualizing data through histograms, scatter plots, box plots, and other charts to identify trends, distributions, and outliers. EDA also includes calculating summary statistics, such as mean, median, and standard deviation, to describe the central tendency and variability of the data. By thoroughly exploring the data, EDA helps in making informed decisions about data cleaning, feature selection, and the appropriate analytical methods to use, ultimately leading to more accurate and robust results.
 
 
# Feature Engineering:
 Feature engineering plays a pivotal role in enhancing the performance of machine learning models by creating new features that better represent the underlying patterns in the data. In this project on heart disease prediction, several feature engineering techniques were employed to improve the predictive power of the models:

1.	Creating New Features:
Several features were engineered to enhance the analysis of heart health data. A logarithmic transformation of blood pressure was performed to normalize its distribution and mitigate the impact of extreme values. The composite feature Cholesterol_BloodPressure was created to capture the combined effect of cholesterol and blood pressure levels on heart health. Exercise_Stress, a measure of stress induced by exercise, was included as it significantly indicates heart disease risk. Cholesterol_Ratio, the ratio of HDL (good) cholesterol to LDL (bad) cholesterol, was calculated due to its established relevance in assessing heart health. Mean Arterial Pressure was computed to provide insight into the overall blood pressure condition. Lastly, a Risk Score was derived from multiple factors, including age, cholesterol levels, and blood pressure, to quantify the overall risk of heart disease.

# 	Machine Learning Models:
# 	Logistic Regression: 
Logistic Regression is a linear model widely used for binary classification tasks, such as predicting the presence or absence of heart disease. It works by estimating the probability that a given input belongs to a particular class using a logistic function. The model outputs probabilities, which are then thresholded to make a final classification decision. Logistic Regression is appreciated for its simplicity, ease of implementation, and interpretability, making it a strong baseline model for many classification problems.
 
# Decision Trees: 

Decision Trees are non-linear models that recursively split the data into subsets based on feature values, forming a tree-like structure. Each node in the tree represents a feature, each branch represents a decision rule, and each leaf node represents an outcome. Decision Trees are intuitive and easy to visualize, making them useful for understanding the decision-making process. They handle both numerical and categorical data and are capable of capturing non-linear relationships in the data.

# 	Random Forests: 
Random Forests are an ensemble learning method that constructs multiple decision trees during training and merges their outputs to improve accuracy and control overfitting. Each tree in the forest is trained on a random subset of the data and features, and the final prediction is made by averaging the predictions (for regression) or majority voting (for classification). Random Forests are robust, handle large datasets well, and provide insights into feature importance.

# 	Gradient Boosting: 
Gradient Boosting is another powerful ensemble technique that builds models sequentially, with each new model focusing on correcting the errors of the previous ones. Typically using decision trees as base learners, Gradient Boosting optimizes the model by minimizing a loss function in a stage-wise manner. This method is known for its high predictive accuracy and ability to handle a variety of data types, capturing complex relationships in the process.

# Conclusion and Future Work:
Random Forest and Decision Tree models outperformed others, achieving 99% accuracy in predicting heart disease. Random Forest was chosen for its ability to mitigate overfitting and its effectiveness with large datasets compared to Decision Tree. To further enhance the accuracy and robustness of the heart disease prediction model, expanding the dataset and employing advanced modeling techniques are highly beneficial. This can be achieved by integrating additional data from public health databases and electronic health records, and using data augmentation methods like SMOTE and GANs. Additionally, employing ensemble techniques such as stacking can further increase the model's accuracy.

 





