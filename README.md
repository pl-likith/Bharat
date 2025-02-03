#HOUSE PRICE PREDICTION USING LINEAR REGRESSION

Project Description:

This project aims to predict house prices based on various features such as average area income, house age, number of rooms, number of bedrooms, and area population using Linear Regression. The dataset used contains information about housing prices in the USA and is analyzed using Python and its data science libraries. The model helps understand how different factors influence house prices and provides a predictive framework for real estate pricing.

Python Libraries Used:

pandas – For data manipulation and analysis.

numpy – For numerical operations and array handling.

seaborn – For data visualization and exploring relationships between variables.

matplotlib.pyplot – For generating plots and visualizing data trends.

scikit-learn – For machine learning operations, including data splitting, model training, and evaluation.

Dataset Description:

The dataset, USA_Housing.csv, consists of 5000 rows and 7 columns, providing information about various factors affecting house prices. 

Analysis Summary and Insights:

Data Exploration & Visualization:

A pairplot revealed correlations between features and house prices.

The price distribution showed a roughly normal distribution with some skewness.

Feature Selection & Model Training:

Selected five numerical features as independent variables (X).

Split the data into training (60%) and testing (40%) sets.

Trained a Linear Regression model to predict house prices.

Model Performance & Evaluation:

Intercept: -2,640,159.79 (base price when all features are zero).

Feature Coefficients:

Avg. Area Income: 21.53 (higher income → higher house price).

Avg. Area House Age: 164,883.28 (older houses tend to be more expensive).

Avg. Area Number of Rooms: 122,368.68 (more rooms → higher price).

Avg. Area Number of Bedrooms: 2,233.80 (minor impact on price).

Area Population: 15.15 (less significant impact).

Error Metrics:

MAE (Mean Absolute Error): 82,288

MSE (Mean Squared Error): 10.46 billion

RMSE (Root Mean Squared Error): 102,278

Insights from Residual Analysis:

The residual plot showed normally distributed errors, indicating a good model fit.

Some variance in predictions suggests that additional factors could improve accuracy.

Conclusion:

The Linear Regression model effectively predicts house prices based on available features.

Avg. Area Income and Number of Rooms are the most influential factors in determining house prices.

The model's RMSE of 102,278 suggests that while predictions are reasonably accurate, incorporating more features (like location specifics, crime rates, or proximity to amenities) could further improve predictions.
