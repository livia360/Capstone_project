
Predict customers' response to the marketing champaign
======================================================
  
![customers](./images/shopping.jpg)
# 1. Introduction


Customer personality analysis is an interesting topic for companies. The dataset is from a competition on Kaggle. To 
practice and solve the binary classification problems, I have trained 5 machine learning models to this dataset to 
predict the customers’ response to the marketing campaign, accepting the offer or not, and identified the important 
influential features behind it.



The capstone project contains four parts: data cleaning, exploratory data analysis, preprocessing, final model selection
 and prediction.The data cleaning includes filling in null values, removing less useful features, and organizing the 
categories within the features. EDA is using visualization tools, like bar plots and histograms to look at the 
distribution of independent features and their relations to the dependent feature. The preprocessing and training 
session split data into train/test datasets, trained and tuned 5 different machine learning models. In the last session,
 select the best model based on the metric ‘roc_auc” score, refit the model using all available data and predict the 
customers’ response.
# 2. Data Cleaning and Wrangling
  
![Expenses per Products](./images/expenses.jpg)  
![Expenses per Age](./images/expenses2.jpg)
# 3. Exploratory Data Analysis
  
![Six marketing champaign](./images/campaign.jpg)  
![Total expenses](./images/total_expenses1.jpg)  
![PCA](./images/pca.jpg)

The first two components account for about 60% of the variance, and the first five for over 95%.  
![PCA colored by Total expenses](./images/pca2.jpg)
# 4. Preporcessing and Training
  

|Models|ROC_AUC|
| :---: | :---: |
|LogisticRegression|0.8531198640887856|
|RandomForestClassifier|0.8528982697172824|
|KNeighborsClassifier|0.8089764186656325|
|GradientBoostingClassifier|0.821228740789984|
|XGBClassifier|0.827285653611065|

# 5. Modeling
  
![top 5 important features](./images/important_features.jpg)