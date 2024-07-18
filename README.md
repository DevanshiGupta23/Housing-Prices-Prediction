Dataset
The dataset used in this project is the California Housing Prices dataset. The dataset includes the following features:

longitude: A measure of how far west a house is; a higher value is farther west.
latitude: A measure of how far north a house is; a higher value is farther north.
housingMedianAge: Median age of a house within a block; a lower number indicates a newer building.
totalRooms: Total number of rooms within a block.
totalBedrooms: Total number of bedrooms within a block.
population: Total number of people residing within a block.
households: Total number of households, a group of people residing within a home unit, for a block.
medianIncome: Median income for households within a block of houses (measured in tens of thousands of US Dollars).
medianHouseValue: Median house value for households within a block (measured in US Dollars).
oceanProximity: Location of the house w.r.t ocean/sea.
Project Workflow
1. Data Loading and Exploration
Load the dataset and explore its structure and content.
Check for and handle missing values.
2. Data Preprocessing
Apply log transformation to reduce skewness in the distribution of certain features.
Handle the categorical variable 'ocean_proximity' using one-hot encoding.
Create new features, such as 'bedroom_ratio' (ratio of total bedrooms to total rooms).
3. Model Training
Split the data into training and testing sets.
Train a Linear Regression model on the training data.
4. Model Evaluation
Evaluate the model using metrics such as Mean Squared Error (MSE) and R-squared (R²).
5. Visualization
Plot the actual vs. predicted house values to visualize the model's performance.
Enhance the plot with a regression line and a reference line for better interpretability.
Visualizations
Predictions vs Actual Values
This visualization includes:

A scatter plot of the actual vs. predicted median house values.
A red regression line to indicate the fit of the predictions.
A blue reference line (y = x) to indicate perfect predictions.
