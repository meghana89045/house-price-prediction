# house-price-prediction
This project was completed as part of the AI & ML Internship program and focuses on building predictive models for housing prices using both simple and multiple linear regression techniques. The aim is to understand how various factors influence house prices and to develop a model capable of accurately estimating prices based on these factors.

Project Overview
In this project, I worked with a comprehensive housing dataset sourced from Kaggle, which contains key features such as house area, number of bedrooms, furnishing status, location, and ultimately, the price. The goal was to apply linear regression—a fundamental machine learning technique—to predict house prices reliably.

Tools & Libraries
Python for programming
Pandas and NumPy for data manipulation and analysis
Scikit-learn for building and evaluating the regression models
Matplotlib and Seaborn for data visualization and plotting
Workflow
1. Data Exploration
I began by importing the dataset and exploring it for missing values and overall structure. This initial inspection helped ensure the data was clean and ready for analysis. I also performed exploratory data analysis (EDA) to understand distributions and relationships in the data.

2. Data Preprocessing
Since the dataset contained categorical features like furnishing status and location, I encoded these variables using one-hot encoding to convert them into a format suitable for modeling. Then, I separated the features (inputs) and the target variable (house prices).

3. Model Training
Next, the dataset was split into training and testing sets to objectively evaluate model performance. Using scikit-learn's LinearRegression, I trained the model on the training set to learn relationships between the features and the house price.

4. Model Evaluation
To assess the model's accuracy, I evaluated it against the test data using three important metrics:

Mean Absolute Error (MAE): Average absolute difference between predicted and actual prices.
Mean Squared Error (MSE): Average of squared differences, penalizing larger errors more.
R² Score: Proportion of variance in house prices explained by the model.
I also visualized the relationship between actual and predicted prices to better understand model performance.

5. Insights & Interpretation
Finally, I analyzed the regression coefficients to interpret how each feature influences the price. This helped in understanding which factors have the most significant impact on housing prices.

Results
The linear regression model performed reasonably well, offering valuable predictions for housing prices based on the available features. The evaluation metrics confirmed that the model generalizes well on unseen data.

Conclusion
This project successfully demonstrates the power of linear regression in predicting house prices and sheds light on the important factors affecting price determination. Going forward, this foundation can be expanded with feature engineering, advanced algorithms, and hyperparameter tuning to boost accuracy further.
