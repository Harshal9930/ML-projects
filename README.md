# Project-Predicting-the-term-deposit-subscription

Data set description: The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

Data set domain: Banking  

Context: Leveraging customer information is paramount for most businesses. In the case of a bank, attributes of customers like the ones mentioned below can be crucial in strategizing a marketing campaign when launching a new product. 

Business Objective : The main aim of the project is to predict if the client will subscribe (yes/no) a term deposit (variable y)

Following are the steps followed during any data science projects:(Project Flow):

1)Define Goal (Business Objective) : Understanding the business objective.What exactly we are going to predict here.We should know all feature details either from domain knowledge from your experience.In this project the main aim of the project is to predict if the client will subscribe (yes/no) a term deposit (variable y) of a Portuguese banking institution

2)Data collection and getting Data set details: Once we get any data set during the project ,we should know the meaning of each and every single feature in it.Following are the steps involved in getting the data set details: a)Find the number columns ,number of rows. b)What is training and testing data set ratio? c)Find the dimension of the data. d)Know what all different data types in the data set.

3)EDA :(Exploratory Data Analysis)

Here we are exploring and vizualizing data.Try to understand the pattern in your data.Here we try to understand relationship of features with the outcome.EDA step is very important part in any type of project.EDA is noting but Exploratory data analysis also a statistical analysis of data.Here we are getting insights from the data.Exploratory Data Analysis (EDA) helps in understanding the data sets by summarizing their main characteristics and plotting them visually.This step is very important before we apply and Machine learning algorithm.Following are the steps involved: a)We should know about Business moments such as Measure of Central tendency(Mean,Median.Mode),Measure of dispersion(Variance,Standatd deviation,Range),Skewness,Kurtosis. b)Check whether the data is normally disrtibuted or not.If it is not Normally distributed apply scaling technique. c)Graphical representation :Represent the data set with the help of Graphs such as Line plot,Bar plot,Histogram plot,Pie chart,Box plot and try to get inferences/insights from it. d)we should find the correlation in the data set.All the features should be independent to each other.All these steps are clearly mentioned in the report.We are applying scaling on data here since the features are not normalized(in same range of values).

4)Data Preprocessing:

Data preprocessing is noting but cleaning the data and removing unwanted material out of your data like noise,duplicate records,inconsistancy,missing values.Following are the steps involved a)Data Cleaning step plays a very important role here.In this project we have both categorical and numeric data .While building ML models we have to give numeric inputs so categorical values should be converted to mathematical form before model building.So we use dummy method for creating those values.Dummy values are created for categorical features in the dat set .They are as follows 'job','marital','education','default','housing','loan','contact','month','poutcome.

5)Model Building step: First step in Model building is partitioning the data.Here we alredy have train and test data set seprately. In our project we are dealing with classification probelm i.e to to predict if the client will subscribe (yes/no) a term deposit (variable y).Following are the models used for Model building in this project: 1)Logistic regression. 2)Decision tree classifier. 3) Random forest classifier.

6)Evalute and Compare Performance :

In this step we finalised the models based on accuracy ,precison,recall and f1 score values.We get all these values from Confusion Matrix.We are checking here the performance of the classification models.And also we check for the errors in the different models.We are comparing the actual value versus predicted values.Also we are checking cochens kappa score.



These are the above steps are followed during this Project
