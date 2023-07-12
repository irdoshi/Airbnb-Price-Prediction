# Airbnb-Price-Prediction

In this project, I am doing the following tasks:

- Loaded the data and performed sanity checks. Observed null values in the bedrooms column.
- Cleaned the data by converting the price column to numeric format.
- Removed entries with missing or invalid price, bedrooms, and other variables.
- Analyzed the distribution of price and decided to perform a log transformation due to its lower bound.
- Converted the number of bedrooms into categories (0, 1, 2, 3+) and created a new variable.
- Estimated a linear regression model to predict price based on the number of bedrooms. Compared models based on different categories of bedrooms.
- Included additional variables, such as room type and accommodates, into the model.
- Converted the room type into three categories: "Entire home/apt," "Private room," and "Other," and recoded accommodates into three categories: "1," "2," and "3 or more."
- Amended the previous model with these two variables and assessed their statistical significance. Baseline categories were selected for each variable.
- Used the updated model to predict the log price for each listing in the data.
- Computed the root-mean-squared-error (RMSE) of the predictions.
- Utilized the model to predict the log price for a 2-bedroom apartment that accommodates 4, resulting in an estimated price of 171 dollars.
