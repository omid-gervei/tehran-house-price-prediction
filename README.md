<h1 id= "top doc"> Description </h1>

---




1. General info

In this project we have a database containing the price of houses in Tehran.
The goal of the project is to forecast the price of houses having the information like AREA, NO. of ROOMS, PARKING, WAREHOUSE, ... .
We used state-of-the-art algorithms for data cleaning and visualization.
As the data is a real one obtaining from divar.com-a welknown website for buying and selling houses in Iran- we encountered so many challenges to overcome. We also used Gridsearch for finding and tuning the parameters of the methods we used. Finally we used Gradio for creating a webapp.  

2. Used methods

we used ***Grid search*** to find the best parameters of the most famous **machine learninig** algorithms:

- Linear Regression

- Decision Tree Regressor

- Random Forest

- XGBoost Regressor


# Highlights



 ```python

regressor = XGBRegressor(colsample_bytree= 1, gamma= 0, learning_rate= 0.05, max_depth= 5, n_estimators= 100, subsample= 0.75)
regressor.fit(X_train,y_train)

 ```
And a the end we took advantage of ***Gradio*** for building a web app.




- link to some where <a href= "#top doc"> go to up </a>
