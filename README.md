# Construct-a-loan-credit-risk-assessment-model
## 1. Data exploration 
(1) Data exploration and deletion of missing value samples 
(2) Data feature statistics and the drawing of box plots and frequency distribution tables to show data features 
(3) Explore the correlation between overdue and scores and other data, and draw scatter bubble charts, scatter charts, heat maps, etc. 
## 2. Data preprocessing | Feature engineering 
(1) Compile gender, marriage and other texts in the user table into data by means of serial number coding and unique thermal coding
(2) Construct data feature table and construct new features as much as possible, which can be divided into status features and trend features. The status characteristics include average wage income, average non-wage income, maximum wage income and minimum wage income, maximum non-wage income and minimum non-wage income, maximum debt amount and average debt proportion in bill.csv(credit card statement); The trend characteristics include the growth trends of annual wage, non-wage, total wage and total non-wage in bank.csv(bank statement), and monthly expenditure fluctuations in bill.csv(credit card statement), and finally form the characteristic table 3 of the structure. 
## 3. Model Training & Model Evaluation 
(1) Univariate feature prediction: 
Marriage status characteristics were selected to predict the scores and expectations in the two ways of serial number coding and unique heat coding, respectively. MSE results under ordinary linear regression model, gradient descent linear regression model and ridge regression model were observed for the scores, and logistic regression results and AUC curve
(2) Multivariate feature prediction: 
The average wage, average non-wage, maximum wage, minimum wage, maximum non-wage, minimum non-wage, maximum arrears and average repayment characteristics were selected to predict the score and expectation, and the prediction results were observed. The MSE results under the ordinary linear regression model, gradient descent linear regression model and Ridge regression model were respectively observed for the score. Observation of logistic regression results and prediction of trend characteristics of AUC curve 
(3) Trend characteristics prediction: 
Select the annual wage growth trend, annual non-wage growth trend, total wage growth trend in 2157, total non-wage growth trend in 2157 + maximum arrears amount, and average wage income as the characteristics, make predictions on scores and expectations, and observe the predicted results. MSE results were observed under the normal linear regression model, gradient descent linear regression model and ridge regression model respectively for the fraction, and logistic regression results and AUC curves were observed for the prediction
(4) Statistical characteristics Prediction: 
Monthly expenditure fluctuation in 2156, monthly income fluctuation in 2156, monthly income fluctuation in 2157, monthly expenditure fluctuation in 2157 + occupation, average wage income and average non-wage income are selected as the characteristics, and the scores and expectations are predicted, and the prediction results are observed. MSE results were observed under the normal linear regression model, gradient descent linear regression model and ridge regression model respectively for the fraction, and logistic regression results and AUC curves were observed for the prediction

