# Seattle-Weather-Prediction

This project analyzes the Seattle weather dataset to predict whether it will rain based on precipitation, maximum temperature, and minimum temperature.

Data Loading and Preparation:

The dataset seattleWeather.csv was loaded into a pandas DataFrame. Null values were checked and removed from the dataset.

Exploratory Data Analysis:

The distribution of rainy days vs non-rainy days was analyzed.
Pair plots and distribution plots were generated to visualize the relationships between the features and the target variable (RAIN).
Model Training and Evaluation:

The dataset was split into training and testing sets. The following models were trained and evaluated for their accuracy in predicting rain:

Logistic Regression: Achieved an accuracy of 0.93.

Decision Tree: Achieved an accuracy of 1.00.

Random Forest: Achieved an accuracy of 1.00.

Artificial Neural Network (ANN): Achieved an accuracy of 1.00.

Convolutional Neural Network (CNN): Achieved an accuracy of 1.00.

Results:

The Decision Tree, Random Forest, ANN, and CNN models all achieved perfect accuracy (1.00) on the test set, indicating that they are highly effective in predicting rain based on the given features. The Logistic Regression model also performed well with an accuracy of 0.93.

Conclusion:

Based on the analysis, all the models except for Logistic Regression are highly accurate in predicting rain based on the provided weather features.

