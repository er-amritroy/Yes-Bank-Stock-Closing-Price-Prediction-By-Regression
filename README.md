# Yes Bank Stock Closing Price Prediction
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.
# Business Objective
The ultimate business objective is to leverage the regression model to provide accurate predictions of the closing price of Yes Bank stock, enabling stakeholders to make well-informed investment decisions, manage risks effectively, optimize portfolios, Early warning systems to alert any fraud cases like Rana Kapoor and align investment strategies with financial goals
# Main Libraries to be Used:
* Pandas for data manipulation, aggregation
* Matplotlib and Seaborn for visualisation and behaviour with respect to the target variable
* NumPy for computationally efficient operations
* Scikit Learn for model training, model optimization, and metrics calculation
* SHAP Python package for understanding and debugging your models. It can tell us how each model feature has contributed to an individual
# Project Objective?
* Efficient EDA
* Understanding of how to prep the data and make it ready for training.
* Understanding the target feature and its distribution
* Assessing target features for class imbalance.
* Modeling - which algorithm to use?
* Evaluation while keeping class imbalance in mind.
* Feature Importance and Conclusion
* Understanding how your project is useful to stakeholders
# Prediction Models:
To predict the stock's closing price, I developed five models: Liner Regression, Ridge Regression, Lasso Regression ,ElasticNet Regression and XGBoost Regressor With GridsearchCV. These models were trained using historical stock price data and various features, including the Open, High, and Low prices.The XGBoost Regressor model performed exceptionally well both on training and test datasets
# Evaluation Metrics:
1. RMSE (Root Mean Squared Error):
* Explanation: RMSE quantifies the average magnitude of prediction errors by taking the square root of the mean of squared differences between predicted and actual values. Lower RMSE indicates better prediction accuracy, with 0 being a perfect fit.
Usage: RMSE helps assess how closely a regression model's predictions align with actual data points, making it a widely used measure of prediction quality.
2. Adjusted R2 (Adjusted R-squared):
* Explanation: Adjusted R2 adjusts the traditional R-squared metric for the number of predictors in a model. It penalizes excessive predictors and provides a more realistic measure of model fit. Higher values signify better model fit.
Usage: Adjusted R2 helps evaluate whether adding more features to a model improves its explanatory power or merely adds noise, aiding in the selection of relevant predictors.
3. R2 Score (Coefficient of Determination):
* Explanation: R2 score quantifies the proportion of variance in the dependent variable explained by the model's independent variables. It ranges from 0 to 1, with higher values indicating a better fit. A score of 1 implies perfect fit.
Usage: R2 score provides an overall measure of how well a regression model captures the relationships between predictors and the target variable, aiding in model assessment and comparison.
# Conclusion & Future Considerations:
The main goal of the project is to create a machine learning model capable of predicting the closing price of Yes Bank stock, taking into account the impact of the fraud case involving Rana Kapoor. The XGBoost Regressor model performed exceptionally well, achieving a high R2 score.

Future considerations for enhancing this project include:

* Exploring daily-level stock price data for finer predictions.
* Incorporating additional features such as holidays, political decisions, events, and volume data.
* Evaluating time series models like ARIMA and LSTM for more precise stock price predictions.
* With the current dataset and features, the model performs well on all data points.

I believe that this detailed README provides you with all the necessary insights to delve into the world of "Yes Bank Stock Closing Price Prediction." If you have any questions or need further assistance, please don't hesitate to reach out to me LinkedIn

May your predictions be accurate, and your financial decisions be informed! 📈💰

## Happy Learning
