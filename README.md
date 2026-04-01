# NCAA_Tournament_Prediction
Margin Based Modeling and Probability Calibration for NCAA Tournament Prediction

Predicting NCAA tournament outcomes is difficult due to small tournament sample sizes, varying team strengths, and limited direct matchups between teams. As a result, predictions must rely on indirect performance data from regular season games.

This research builds a probabilistic prediction framework based on margin prediction and probability calibration. Score margins are first predicted using XGBoost, and then converted into calibrated win probabilities using
Logistic Regression and probability adjustment methods. Resulting predictions are highly aligned with market predictions from ESPN and Kalshi.

This work is partially inspired by previous Kaggle March Machine Learning Mania solutions (Kim, 2025; Odeh, 2025).

Data provided by Kaggle.

Citation:

Jeff Sonas, Martyna Plomecka, Yao Yan, and Addison Howard. March Machine Learning Mania 2026. https://kaggle.com/competitions/march-machine-learning-mania-2026, 2026. Kaggle.

