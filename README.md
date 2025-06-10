# IPL_PREDICTION_ML

🏏 IPL First Innings Score Prediction using Machine Learning
This project focuses on predicting the final first innings total score in Indian Premier League (IPL) matches using machine learning models. Accurate prediction of the first innings total can help in real-time match analysis, strategy formulation, and fantasy sports applications.

📌 Problem Statement
In T20 cricket, especially in IPL, the first innings total often decides the course of the game. However, predicting this score mid-innings is challenging due to multiple influencing factors such as the teams involved, the venue, overs played, wickets lost, and recent scoring momentum.

✅ Proposed Solution
We use historical IPL data to train machine learning models that take in current match statistics and predict the likely total score at the end of the first innings. The key input features include:

Batting and bowling teams

City/venue

Current score and number of wickets

Overs completed

Runs and wickets in the last 5 overs

🧠 Technology Stack
Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Models Tried: Linear Regression, Random Forest, Ridge Regression

📊 Results
Among the models tested, Ridge Regression performed the best with:

R² Score: 0.96

Mean Absolute Error: ~9.5

Root Mean Squared Error: ~12.7

These results show that the model is highly effective in predicting first innings scores, especially when used after at least 6–10 overs.

🚀 Future Enhancements
Add live data integration using match APIs

Include player-level performance stats

Develop a web app for public use

Extend to second innings prediction and win probability

📚 References
IPL Dataset: Kaggle

Scikit-learn Documentation

ML Blogs & Research Articles
