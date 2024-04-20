# DSAI-Project-Group1: Airline Satisfaction Analysis

## About
This SC1015 project delves into understanding factors that drive customer satisfaction in the airline industry. Utilizing a dataset containing detailed passenger satisfaction surveys, our team aims to identify key features influencing satisfaction. This analysis could aid airlines in enhancing service quality.

## Contributors
- **Malcolm Fong Cheng Hong** - Involved in all aspects of the project including sample collection, exploratory analysis, analytical visualization, machine learning, and conclusion drawing.
- **Dallas Ng Zhi Hao** - Contributed similarly across all stages of the project.
- **S Ramaneesen** - Contributed similarly across all stages of the project.

## Problem Definition
- Predict customer satisfaction scores from various features within the airline experience.
- Explore the data to identify and analyze primary factors contributing to airline passenger satisfaction.

## Models Used
- **Linear Regression**
- **Random Forest**
- **Gradient Boosting**

## Conclusion
Our initial goal was to uncover which features most significantly affect customer satisfaction in the airline industry. As we delved deeper, however, we realized that the satisfaction scores we were analyzing were directly derived from these very features.

Hence, we redirected our attention to predicting arrival and departure delays, a pressing issue for airlines. Here’s what we discovered:
### Key Insights:
- **Model Performance**: Gradient Boosting emerged as the best model for predicting total time delays with high accuracy.
- **Observations on Delay Duration**: The performance of the Gradient Boosting model decreases as the duration of delays increases, highlighting the complexity and unpredictability of factors that lead to longer delays.

These insights have important implications for airlines, suggesting that while some aspects of delays can be predicted, the factors leading to more extended delays remain challenging to model accurately. This project has provided valuable insights into the dynamics of airline delays and the potential for predictive modeling to improve operational decisions.

## What Did We Learn from This Project?
- **ML Techniques**: Utilized various machine learning models including Linear Regression, Random Forest and Gradient Boosting.
- **Data Handling**: Mastered complex data cleaning and preprocessing tasks to prepare the dataset for analysis.
- **Collaboration**: Developed project management and collaboration skills using GitHub.
- **Model Insights**: Recognized Gradient Boosting as the most effective model in terms of predictive accuracy.

## References
https://www.kaggle.com/code/sayedgamal99/airline-passenger-satisfaction-xgboost#6--Data-Preparation-for-ML
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
