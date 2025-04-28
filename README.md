Overview
This project is about building a simple linear regression model to predict the median house value based on the median income from a housing dataset. I first cleaned the data, explored it through visualizations, trained the model, and then evaluated its performance.

Dataset
The dataset contains information about houses in California. Some of the important columns include longitude, latitude, housing median age, total rooms, total bedrooms, population, households, median income, median house value, and ocean proximity. The target we want to predict is the median house value.

Steps
First, I handled missing data by filling missing values in the total_bedrooms column with the median. I also converted the ocean_proximity column, which is categorical, into numbers using one-hot encoding. After preprocessing, I performed exploratory data analysis (EDA) by plotting a heatmap to see feature correlations and creating scatter plots between important features and the house value.

For the model, I chose median income as the only input feature and built a simple linear regression model. After training, I evaluated the model by calculating metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score. I also created a scatter plot showing actual vs predicted house values along with the regression line.
