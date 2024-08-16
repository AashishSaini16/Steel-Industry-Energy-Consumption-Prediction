# Steel-Industry-Energy-Consumption-Prediction
This repository contains Jupyter notebooks and Python scripts for analyzing and predicting energy consumption in a small-scale steel industry using machine learning techniques. The project focuses on understanding and forecasting electricity usage based on various factors, helping optimize energy management in the steel production process.  

### Dataset Source:  
The dataset is sourced from DAEWOO Steel Co. Ltd in Gwangyang, South Korea. Detailed information about the dataset can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/851/steel+industry+energy+consumption). This dataset includes comprehensive energy consumption metrics, which are essential for training and evaluating the predictive model.

### Key Features:  
Data Loading and Preprocessing: Loaded and preprocessed a large-scale dataset, including numerical and categorical features, for training and evaluation.  
Correlation Analysis: Computed and visualized the correlation between features and energy consumption to understand the most influential factors.  
Machine Learning Model: Developed and trained a Random Forest Regressor model to predict energy consumption.  
Feature Importance: Analyzed and visualized the importance of different features in the prediction model.  
Prediction Function: Implemented a function to make real-time energy consumption predictions based on user input.  
Interactive Widgets: Created interactive widgets in Jupyter Notebook for user input to facilitate easy predictions.  

### Technologies Used:  
Python: Core language used for data manipulation, model training, and prediction.  
Pandas & NumPy: Used for data manipulation and numerical operations.  
Scikit-Learn: Employed for building and evaluating machine learning models, including preprocessing and regression.  
Matplotlib & Seaborn: Utilized for visualizing data and model performance.  
Joblib: Used for saving and loading the trained machine learning model.  
ipywidgets: Created interactive widgets for user input in Jupyter Notebook.  

### Implementation Details:  
Data Loading: The dataset is loaded from a CSV file, containing various features related to energy consumption.  
Preprocessing: Applied scaling and encoding techniques to prepare data for model training.  
Model Training: Implemented a machine learning pipeline combining preprocessing and a Random Forest Regressor to predict energy consumption.  
Evaluation: Assessed model performance using metrics such as RMSE, MAE, and R^2.  
Visualization: Generated plots to visualize feature importances and compare predicted versus actual consumption values.  
Prediction Function: Defined a function to predict energy consumption based on user inputs via interactive widgets.  

This project provides valuable insights into energy consumption patterns and offers a tool for predicting future usage, aiding in more efficient energy management and planning for steel production facilities.
