# House Prices - Advanced Regression Techniques

## About the repository
This project is a kaggle community competition [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview). The objective is to predict the final price of each house.

Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.

### Project content:

- Exploratory Data Analysis
  - Checking for constant variables
  - Missing Values
    - Concat both datasets
    - Impute values
  - Target variable
    - Log Transformation
  - Categorical variables
    - Univariate Analysis
  - Numerical variables
    - Histogram
    - Scatterplot

- Data preprocessing
  - Log Transformation
    - Applying a logarithmic transformation on high skewness variables
	- Feature encoding
		- Ordinal Variables(LabelEncoder)
    - Nominal Variables(OneHotEncoder)
	- Correlation
	- Optimize Memory

- Modelling
	- Split Imput and Target Variable
  - Scaling Data
	- Cross Validation with XGBClassifier

- Hyperparameter tuning

- Predict and Submission

**Private Score:  Public Score: **
