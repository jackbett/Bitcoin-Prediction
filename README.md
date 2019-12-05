# Bitcoin-Preduction
Use Jupyter Notebook and Python to predict monthly Bitcoin prices using linear regression.
Using yearly bitcoin data stored in a csv, I extracted monthly data for October, November, and December 2018 and plotted it on a graph.  I then used 3 types of linear regression (RBF, Linear, and Polynomial) to use the monthly data and see how linear progression predicts the final day price in the month.  This was coded using Python in Jupyter notebook.  

October 2018 findings:
The actual price for Bitcoin on the last day of October was $6342.61
Using Linear Regression models:

Radial Basis Function was: $6342.51 -[$.10] 
Linear Regression was: $6429.31 +[$86.7]
Polynomial Regression was: $6369.51 +[$26.9]


November 2018 findings:
The actual price for Bitcoin on the last day of October was $4009.67
Using Linear Regression models:

Radial Basis Function was: $4412.84 +[$403.17] 
Linear Regression was: $4009.57 -[$.10]
Polynomial Regression was: $3188.7 -[$820.97]

December 2018 findings:
The actual price for Bitcoin on the last day of October was $3747.39
Using Linear Regression models:

Radial Basis Function was: $3747.49 +[$.10] 
Linear Regression was: $3910.63 +[$163.24]
Polynomial Regression was: $3971.27 +[$221.88]

Findings:

From what I observed, there is really no coorelation as there should not be in applying daily prices to mathematical equations.  There are many outside variables that are used in terms of stock price predicting such as trading rates, ups, downs, and pure luck.  We can't guess how many people are going to trade or sell or what new technologies or findings may increase or decrease the prices.  I found the findings interesting to apply regression to prices and soon intend to try take a machine learning stance towards this to see if the findings are closer.  I also want to implement in the future more than a one day analysis prediction.
