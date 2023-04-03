## California Housing Prices Prediction 

This project aims to build a machine learning model that predicts the median housing price for each block group in California.

#### Dataset

kaggle datasets download -d camnugent/california-housing-prices

The dataset used in this project is available in the file housing.csv.  It contains the following columns:

longitude: longitude of the block group
latitude: latitude of the block group
housing_median_age: median age of the houses in the block group
total_rooms: total number of rooms in the block group
total_bedrooms: total number of bedrooms in the block group
population: total population in the block group
households: total number of households in the block group
median_income: median income of the block group
median_house_value: median house value in the block group
ocean_proximity: proximity of the block group to the ocean
Installation
Clone the repository: git clone https://github.com/your-username/california-housing-prices.git
Navigate to the project directory: cd california-housing-prices
Install the required packages: pip install -r requirements.txt
Run the Jupyter notebook: jupyter notebook
### Exploratory Data Analysis
In the Jupyter notebook, california_housing.ipynb, we perform exploratory data analysis on the dataset. This includes:

Checking for missing values
Visualizing the distribution of each feature
Visualizing the correlation between features and the target variable
Visualizing the geographical distribution of the block groups
Data Preprocessing
After performing exploratory data analysis, we preprocess the data to prepare it for machine learning. This includes:

Dropping missing values
Removing the ocean_proximity feature, as it is a categorical variable
Log-transforming the numerical features to reduce the impact of outliers
Splitting the data into training and testing sets
### Models
#### We train and evaluate the performance of the following machine learning models:

##### Linear Regression
##### Random Forest Regressor
##### Gradient Boosting Regressor
##### XGBoost Regressor

I also use GridSearchCV to find the best hyperparameters for the Random Forest Regressor model.

##### Conclusion
Gradient Boosting Regressor model with the best hyperparameters has the highest accuracy, with an R2 score of 82%.

##### Credits 
-- will be updated


```python

```
