# Flight-Price-Prediction
- This project builds a machine learning model to predict flight ticket prices using various flight-related features.
- Analyzed and preprocessed flight dataset including features like journey date, departure/arrival time, airline, source, destination, and duration.
- Converted and encoded categorical features using label encoding and one-hot encoding.
- Performed feature selection using `ExtraTreesRegressor` to identify top contributing variables.
- Built and tuned a `RandomForestRegressor` using `RandomizedSearchCV` for hyperparameter optimization.
- Evaluated the model using R² score, residual plots, and prediction visualization.
- Saved the trained model using `pickle` for future deployment.
