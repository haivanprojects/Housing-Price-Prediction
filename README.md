# Housing Price Prediction

Objective

Build a regression model to predict property prices based on physical attributes and amenities.

Dataset

The project uses the uk_housing_dataset.csv containing 545 property records.
Key Features:

- Price: Target variable (Property value).

- Area: Total square footage.

- Rooms: Number of bedrooms and bathrooms.

- Amenities: Air conditioning, parking, guestroom, and furnishing status.

Technical Workflow

1. Exploratory Data Analysis (EDA): Visualized price distributions and correlations between variables using Seaborn and Matplotlib.

2. Preprocessing: Handled outliers in the area feature and applied label encoding to categorical variables (Yes/No, Furnishing status).

3. Modeling: Implemented and compared:

- Multiple Linear Regression

- Random Forest Regressor

4. Evaluation: Assessed models using R-squared and Mean Squared Error (MSE) to determine prediction accuracy.

Key Findings

- Area and Bathrooms are the strongest predictors of housing prices.

- The Random Forest model provided better results for non-linear relationships compared to simple Linear Regression.

Repository Contents

`housing_price_prediction.ipynb`: End-to-end Python source code.

`Housing_Analysis_Report.pdf`: Final report detailing methodology and insights.

`uk_housing_dataset.csv`: Cleaned dataset used for training.
