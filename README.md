** KC Housing Prediction 

- Objective

The main objective of this project is to predict house prices in King County, USA using machine learning models. By analyzing historical housing data, the project aims to identify the most influential factors that determine property prices and build an accurate prediction model.

This project also helps in:
Understanding housing market trends.
Performing exploratory data analysis (EDA) to gain insights from the dataset.
Comparing different regression algorithms for performance.

🔍 Data Exploration
The dataset contains information about 21,613 house sales from May 2014 to May 2015 in King County (Seattle region).

Key Features
Numerical Features: bedrooms, bathrooms, sqft_living, sqft_lot, floors, yr_built, etc.
Categorical Features: waterfront, view, condition, grade, zipcode.
Target Variable: price (the selling price of houses).

Insights from EDA
Houses with larger living areas (sqft_living) tend to have higher prices.
Location (lat, long, zipcode) plays a major role in house pricing.
Houses with a waterfront view are significantly more expensive.
Number of bedrooms alone is not a strong predictor, but when combined with other features it improves results.
Grade and condition strongly influence the price (better grade → higher value).
Visualizations such as heatmaps, scatter plots, histograms, and boxplots were used to analyze the distribution and relationships among variables.

⚙️ Methodology
Data Preprocessing
Handled missing values.
Scaled/normalized numerical features.
Encoded categorical variables.
Exploratory Data Analysis (EDA)
Checked correlations between variables.
Visualized feature importance.
Detected outliers and distribution patterns.

Modeling

Neural Network - Squential() with relu

Evaluation Metrics
Varirance
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)




🚀 Future Scope

Deploy the prediction model as a web app using Streamlit or Flask.
Integrate geospatial visualization to show pricing patterns on a map.
Extend the dataset with recent housing records for improved predictions.