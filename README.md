# Prediction-
Crop yield prediction using different types of algorithms and finding the optimal.
Built a machine learning model to predict crop yield using historical agricultural data (crop, season, state, rainfall, fertilizer, pesticide, etc.).
Preprocessed data with One-Hot Encoding for categorical features and scaling for numeric features.
Compared Linear Regression, Decision Tree, Random Forest, and Gradient Boosting; Gradient Boosting gave the best performance.
Implemented prediction for new data with automatic High/Low yield classification using median threshold.
tools:Python 3.x,Pandas,NumPy,scikit-learn (LinearRegression, DecisionTreeRegressor, RandomForestRegressor, GradientBoostingRegressor)
NOTE:Median is preferred over mean for thresholding because yield data may contain outliers (extremely high or low yields).One-Hot Encoding ensures categorical data does not imply any order.Scaling is only applied to numeric columns, while encoded columns remain 0/1.
