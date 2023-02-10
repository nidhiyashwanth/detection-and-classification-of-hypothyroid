# Thyroid Disease Detection

Thyroid disease is a very common problem in India, more than one crore people are suffering with the disease every year. Thyroid disorder can speed up or slow down the metabolism of the body.

The main objective of this project is to predict if a person is having compensated hypothyroid, primary hypothyroid, secondary hypothyroid or negative (no thyroid) with the help of Machine Learning. Classification algorithms such as Random Forest, XGBoost and KNN Model have been trained on the thyroid dataset, UCI Machine Learning repository. After hyperparameter tuning on KNN model has performed well with better accuracy. Application has deployed on Heroku with the help of flask framework.

## For Deployment link Prediction
Heroku: https://thyroid-disease.herokuapp.com/

# Demo

https://youtu.be/PJeebeO13v0

# Technical Aspects

- Python 3.7 and more
- Important Libraries: sklearn, pandas, numpy, matplotlib & seaborn
- Front-end: HTML, CSS 
- Back-end: Flask framework
- IDE: Jupyter Notebook, Pycharm & VSCode
- Database: Cassandra 
- Deployment: Heroku

# How to run this app 

Code is written in Python 3.7 and more. If you don't have python installed on your system, click here https://www.python.org/downloads/ to install.

- Create virtual environment - conda create -n myenv python=3.7
- Activate the environment - conda activate myenv
- Install the packages - pip install -r requirements.txt
- Run the app - python run app.py

# Workflow

## Data Collection

Thyroid Disease Data Set from UCI Machine Learning Repository.

Link:https://archive.ics.uci.edu/ml/datasets/thyroid+disease

## Data Pre-processing

- Missing values handling by Simple imputation (KNN Imputer)
- Outliers detection and removal by boxplot and percentile methods
- Categorical features handling by ordinal encoding and label encoding
- Feature scaling done by Standard Scalar method
- Imbalanced dataset handled by SMOTE
- Drop unnecessary columns

## Model Creation and Evaluation

- Various classification algorithms like Random Forest, XGBoost, KNN etc tested.
- Random Forest, XGBoost and KNN were all performed well. 
- Hyper parameter tuning was performed using RandomizedSearchCV
- Model performance evaluated based on accuracy, confusion matrix, classification report.


## Database Connection
Cassandra database used for this project.

## Model Deployment
The final model is deployed on Heroku using Flask framework.



### Batch File Prediction User Interface

#### Homepage: A very simple UI with single page
![Screenshot (127)](https://user-images.githubusercontent.com/72783418/151911749-effe207a-228a-414d-97bc-74a3c83c5aff.png)



#### User need to upload CSV file and click predict button for prediction to start.
![Screenshot (129)](https://user-images.githubusercontent.com/72783418/151911814-1896b89e-d3a7-4669-9ac5-48d98b74962e.png)



#### User can download their result by clicking download button below.
![Screenshot (130)](https://user-images.githubusercontent.com/72783418/151911864-0295fae4-8c32-49af-afee-915f8e341998.png)



#### Downloaded CSV file will contain index numer with type of thyroid disease patient is suffering from.
![Screenshot (133)](https://user-images.githubusercontent.com/72783418/151912091-526182af-fb6c-41b6-bcc8-60de678e2914.png)



#### User can also download sample csv file for reference.
![Screenshot (131)](https://user-images.githubusercontent.com/72783418/151911904-65a610ad-9ca3-4b12-a338-d30f4350acc9.png)






## Project Documents

- HLD:  https://github.com/Sana-Khan94/Thyroid-Disease-Detection/blob/main/Docs/TDD_HLD_V1.0.pdf

- LLD: https://github.com/Sana-Khan94/Thyroid-Disease-Detection/blob/main/Docs/TDD_LLD_V1.0.pdf

- Architecture: https://github.com/Sana-Khan94/Thyroid-Disease-Detection/blob/main/Docs/TDD_Architecture_V1.0.pdf

- Wireframe: https://github.com/Sana-Khan94/Thyroid-Disease-Detection/blob/main/Docs/TDD_Wireframe_V1.0.pdf

- Detailed Project Report: https://github.com/Sana-Khan94/Thyroid-Disease-Detection/blob/main/Docs/TDD_DPR.pdf


# Author

Sana Khan: https://www.linkedin.com/in/sana-khan-03809b127/


# Help Me Improve

Hello Reader if you find any bug please consider raising issue.
