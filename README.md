<h1 align="left">Hey! Nice to see you.</h1>
<h1 align="center">I'm Dushyant Kumar</h1>
<h3 align="center">I'm passinate for Machine Learning Engineer & Data Scientist</h3>

- 🔭 I’m currently working on **Generative AI  & LLMs**
<h3>I have technical experience and interest in:</h3>

- Machine Learning
- Deep Learning
- Computer Vision
- Natural Langauge Processing
- MLOps
- Generative AI
  
- 📫 How to reach me **dushyank51001@gmail.com**

- 📄 Know about my experiences https://drive.google.com/file/d/1BWjFEvSr4pdFwJRjbCqgtTLPMPyy8JsF/view?usp=drivesdk

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/dushyant-kumar-89685a24a/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="dushyant kumar" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://opencv.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>

<h1 align="left">Projects</h1>

## [Project 1: Credit Card Fraud Detection](https://github.com/Dushyantkumar6395/Data-Science-and-ML-Projects/blob/main/Credit_card_Fraud_Detection_Git.ipynb)
---
### Overview - 
- A supervised classification problem with the underlying objectives were to find patterns about time of fraud during a day (if any) and making a prediction on that basis to identify first-hand whether the transaction belongs to fraud or legit category. The dataset was obtained from Kaggle.
- The dataset has majority of variables unavailable to us due to prior PCA compression, only 3 variables were directly available for our purpose.
- Target variable was highly imbalanced (**0: 99.82%** and **1: 0.18%**), so the application of **re-sampling techniques** (Random Undersampler, Random Oversampler and SMOTE) appeared to be highly prudent.
- Predictive Modeling pipeline of the project used the following: 

    - Algorithms:
        - **Logistic Regression**
        - **Decision Tree Classifier**
        - **Random Forest Classifier**
        - **K-Nearest Neighbors**
        - **Support Vector Classifier**
        
     
     - Metrics (for evaluation):
        - **Accuracy Score**
        - **ROC - AUC Score**
        - **Confusion Matrix**

- Best model:
    - **Random Oversampling with Random Forest Classifier**, reasons:
        - Accuracy Score = **99.993527%**
        - ROC - AUC Score = **99.993508%**
        - Confusion matrix = **False Negatives - 0** and **False Positives - 11**


## [Project 2: House Price prediction (Region - Ames, Iowa, USA)](https://github.com/Dushyantkumar6395/Data-Science-and-ML-Projects/blob/main/House_Price_prediction_Git.ipynb)
---
### Overview -
- This **regression model** was downloaded from the Kaggle competition with the main objective being, prediction of housing sales prices of Ames city in Iowa state of USA.
- The dataset contains **81** columns to deal with.
- With higher independent variables, comes great responsibility of dealing with missing values, outliers, skewness (since it's regression) and other feature processing complexities. 
- Applied **Principal Component Analysis** for feature selection.
- Predictive Modeling pipeline of the project used the following:

    - Algorithms:
        - **Linear Regression**
        - **Ridge Regression**
        - **Lasso Regression**
        - **Elastic Net Regression**
        - **Kernal Regression**
        - **Gradient Boosting**
        - **XGBoost**
        - **Light GBM**
        
     
     - Metrics (for evaluation):
        - **MAPE**
        - **RMSLE**
        
     
     - Optimization:
        - **Grid Search CV**, for tuning Hyper-parameters.
        - used a basic **Ensemble modeling** method. (RMSLE - 0.0724)
