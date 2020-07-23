House Prices - Kaggle

Its not my own project, it is just an example used to compare the performance of different models.
Models used:
	1. DecisionTreeRegressor()
     	2. RandomForestRegressor()
     	3. XGBRegressor()
     	4. LinearRegression()
     	5. Lasso()
     	6. Ridge()
     	7. ElasticNet()
     	8. KNeighborsRegressor()
     	9. GradientBoostingRegressor()
     	10. AdaBoostRegressor()
     	11. SVR()     // 	suppor vector regressor

First we analyze and clean the data. Then, we calculate the error for each model. We choose one of them based on the minimum error. It was Lasso(). Finally, we train the model and generate a .csv file that contains the predictions (SalePrice $$)