# Car Rental Price on Demand
This project presents a general framework for building a model to predict the impact of changes to car rental prices on demand. The main steps involved in the project are:

## Data Collection and Cleaning
Data was collected from <a href="https://www.kaggle.com/datasets/theriley106/turo-rental-car-pricing-info">Kaggle</a>, specifically Turo Rental Car Pricing Information in the United States. The data was cleaned and formatted to ensure its suitability for analysis.

### Exploratory Data Analysis (Part 1)
-	Insights into the relationship between rental prices and demand were gained through visualizing the data, calculating summary statistics, and identifying trends and patterns.

### Feature Engineering (Part 2)
-	New features were engineered based on the insights gained from the exploratory data analysis. These features capture the relationships between rental prices and demand, including seasonality features, location-specific features, car-specific features, and other factors that affect demand.

### Model Selection and Training (Part 3)
-	A model was selected and trained to predict demand based on rental prices, using the engineered features. XGBoost was chosen as the machine learning algorithm due to its lower RMSE compared to other methods.

### Model Evaluation and Refinement
-	The performance of the trained model was evaluated using metrics such as mean squared error or R-squared. Based on the evaluation, the model was refined by adjusting hyper-parameters. Cross-validation techniques were used to ensure model robustness.

### Optimization
-	With a trained and refined model, pricing strategies for different types of cars and locations could be optimized. The model can be used to identify optimal rental prices for different times of the year or different locations and simulate the impact of different pricing strategies for adjustments. A simple risk assessment method has been enabled.

This repository serves as a framework for building and optimizing car rental pricing strategies based on demand, using data analysis, feature engineering, and machine learning techniques.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

