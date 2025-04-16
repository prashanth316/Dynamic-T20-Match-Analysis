
# Dynamic T20 Match Analysis
### predicting winning probability and match score




## overview
Dynamic T20 Match Analysis is a project aimed at predicting the winning probability and match score for T20 cricket matches. This system leverages machine learning models to provide accurate forecasts and offers an interactive demo for users to test predictions.

Dataset: https://www.kaggle.com/veeralakrishna/cricsheet-a-retrosheet-for-cricket?select=t20s

## Features
1. ### Winning Probability Prediction
  - **Description:** Uses logistic regression and XGBoost models to predict the winning probability of a T20 match.
  - **Accuracy:** Achieved a 93% accuracy rate.
  - **Enhancements:** Improved model precision by 20% through advanced feature engineering and data cleansing.
2. ### Match Score Prediction
  - **Description:** Predicts the likely match score based on current game conditions.
## Technologies Used
  - **Libraries:** NumPy, pandas, scikit-learn, Streamlit
  -  **Machine Learning Models:** Logistic Regression, XGBoost
  - **Data Processing:** Advanced feature engineering and data cleansing using Python libraries
## Demo

- [**Demo Link**](https://t20-score-win-predictor-karthikeya.streamlit.app/)

### Interact with the Demo:

- **Select Batting Team:** Choose the batting team from the dropdown (e.g., Afghanistan).
- **Select Bowling Team:** Choose the bowling team from the dropdown (e.g., Afghanistan).
- **Select City:** Choose the city where the match is being played (e.g., Abu Dhabi).
- **Enter Target:** Set the target score (e.g., 150).
- **Enter Current Score:** Input the current score (e.g., 75).
- **Overs Done:** Input the number of overs completed (works for over > 5, e.g., 10).
- **Wickets Out:** Input the number of wickets fallen (e.g., 3).
Runs Scored in Last 5 Overs: Input the runs scored in the last 5 overs (e.g., 30).
- **View Output:** The system will display the predicted score and winning probability.




