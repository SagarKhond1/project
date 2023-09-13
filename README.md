  The Recession Prediction of USA project aims to develop a robust model for predicting recessions in the USA by analyzing key economic
indicators, including the Debt-to-GDP ratio, Federal Funds rate, Inflation CPI, Manufacturing Output,
Unemployment Rate along with five other indicators. After data cleaning and Exploratory Data Analysis (EDA), we
constructed three distinct ML models: Logistic Regression, Random Forest, and Gradient Boost. Utilizing
GridSearchCV, we determined the optimal hyperparameters for these models, subsequently conducting training
with these parameters. Finally, we saved the model built by the Gradient Boost Algorithm. To enhance accessibility
and user-friendliness, we created a local server using Flask in Python. Later, we deployed the model on an Amazon
EC2 instance, ensuring continuous server operation. Technologies used in this project include pandas, matplotlib,
seaborn, Amazon EC2 and Flask.
