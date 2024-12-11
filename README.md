# Machine Learning Improving F1 Score

## Project Description
Hyperparameter Tuning and Handling Class Imbalance.

This notebook performs an EDA on a churn dataset.

Then tests three types of classification models (DecisionTree, RandomForest, LogisticRegression) with different hyperparameters to choose the best one to solve the churn problem.

To handle with the classes imbalance, uses the oversmapling method, and the parameter class weight in the model. 

To finish, tune more hyperparameters in the model, to improve performance on the test set and increase the F1_Score.

## Objectives
- Perform exploratory data analysis.
- Test three types of classification models with different hyperparameters.
- Handle class imbalance using oversampling and class weights.
- Tune hyperparameters to improve performance on the test set and increase the F1_Score.

## Tools and Libs used
- Python: Main language used for analysis.
- Pandas: Library for data manipulation and analysis.
- NumPy: Library for numerical operations.
- Matplotlib and Seaborn: Libraries for data visualization.
- Scikit-learn: Library for machine learning.

## Methodology
#### EDA
- Import libraries.
- Load the dataframes.
#### Preprocessing
- Identify and treat missing values.
- Identify and treat outliers.
- Scale the data.
#### Model Training and Evaluation
- Train and evaluate the models with different hyperparameters.
- Compare the performance of the models and select the best one.

## Learnings
- Data analysis: interpreting and extracting valuable insights from large volumes of data.
- Data cleaning: identifying and correcting missing, duplicate, and anomalous values.
- Creating graphics: using matplotlib and seaborn to visualize data in an intuitive and informative way.
- Data preprocessing: preparing data for analysis, including cleaning and treat the data.
- Use of libraries and tools: practical application of various libraries and tools from the Python ecosystem, such as Pandas, Numpy, Sklearn, Matplotlib and Seaborn.
- Data visualization: Creating very detailed graphs and other types of visualizations to identify patterns and trends.
- Data-driven decision making: Using insights derived from data analysis to guide strategic decisions.
- Classification Models: Train and evaluate classification models.