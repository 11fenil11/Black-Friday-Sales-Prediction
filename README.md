# Black-Friday-Sales-Prediction

# Abstract
This project is focused on predicting the sales of different products during the Black Friday event using machine learning algorithms. We have used the XGBoost, Decision Tree Regressor, Random Forest Regressor, and Linear Regression algorithms for the prediction.

# Dataset
The dataset used for this project is the Black Friday dataset available on Kaggle. The dataset contains various features such as user demographics, product details, and purchase details.Kaggle dataset link: https://www.kaggle.com/datasets/sdolezel/black-friday

# Methodology
The project includes the following steps:

- Data preprocessing and cleaning
- Exploratory data analysis to understand the dataset
- Feature engineering to extract meaningful features from the dataset
- Splitting the dataset into training and testing sets
- Training the machine learning algorithms using the training set
- Evaluating the performance of the algorithms on the testing set
- Selecting the best algorithm for the prediction

# Results

![image](https://user-images.githubusercontent.com/47125158/226377364-c45b176d-a72a-46fc-8ab9-fabe29ae62f0.png)
From the table we again come to the conclusion that XGBoost Performs the best for our problem. If we 
compare the R2 scores and Root Mean Squared errors of all the models used , XgBoost gives us the 
least RMSE and highest R2 score .
This also matches our conclusion from the learning curves as XGBoost showed the best learning curve 
out of all the models.


# Repository Structure
The repository includes the following files:
- notebook: file containing the Jupyter notebook for data preprocessing, exploratory data analysis, feature engineering, and model training
- project report: file containes the thorough report of the project with all methodologies and details
- README.md: file containing the project description and instructions for running the project

# Conclusion
This project demonstrates how machine learning algorithms can be used for predicting sales during Black Friday. The XGBoost algorithm has shown the best performance among all the algorithms used in this project. The project can be further improved by using more advanced machine learning techniques and incorporating more features into the model.
