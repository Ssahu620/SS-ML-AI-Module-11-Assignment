# SS-ML-AI-Module-11-Assignment
SS-ML-AI-Module 11 Assignment
OVERVIEW
In this application, you will explore a dataset from Kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing. Your goal is to understand what factors make a car more or less expensive. As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car.

Sonal's Comments - 
Main task is to find dimensions (columns of vehicles spreadsheet) that impact the price most.
To get the most important dimensions, steps will be as follows:
1.	Import all libraries.
2.	Load data, clean data, drop unnecessary columns.
3.	Replace NA values appropriately.
4.	Use one-hot algorithm to convert values to numerical values.
5.	Run PCA model to figure out the most important dimensions.
6.	Use multiple regression to get the coeffecients of features/dimensions.
7.	Use error metrics - find MSE
8.	Run a new model with polynomial features.
9.	Use Validations - CV- Gridsearch.
10.	If polynomial model is not appropriate then run simple multiple regression with degree = 1.
11.	Keep plotting plots to visually show results.
12.	Summarize final results

Findings and Assumptions:
1)	Due to so many economic and social changes in society since 1900 buying habits of consumers have changed. I felt it was best to only consider data from year 2000 onwards. 
2)	Used Label encoding and one-hot encoding to convert all features to integers, floats, or bools.
3)	Used PCA to figure out the most important features.
4)	Ran regression with polynomial features however as per GridsearchCV  best parameter was degree 1.
5)	Finally used linear regression to come out with the results.

Final Results
1)	Prices are inversely dependent on the year car was made. Newer the car more expensive it will be.
2)	Prices are inversely dependent on odometer value . less miles on the car more expensive it will be.
3)	Impact of year is much higher than impact of odometer.
4)	majority of cars will use gas fuel, will have clean title and automatic transmission.
5)	Most old cars sold since year 2000 are from California.



