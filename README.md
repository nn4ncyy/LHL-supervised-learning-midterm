# Data Science Midterm Project

## Project/Goals
The objective of this project is to explore the steps it takes to take data, transform it, and build a machine learning pipeline from it. We will be using historical housing data. We will go through the steps of preproccessing, performing exploratory data analysis, selecting three models to compare and contrast, and finally, complete some hyperparameter tuning. 

## Process
### Step 1: Loading the Data
- Iterate through the data/ directory to load all JSON files into a single Pandas DataFrame.
### Step 2: Clean and Preprocess
- Handle missing values, duplicates, and inconsistent data types.
- Convert relevant columns (e.g., dates, prices) to appropriate formats.
### Step 3: Explore the Data
- Generate descriptive statistics, visualize distributions, and identify relationships (e.g., heatmaps, scatterplots).
### Step 4: Prepare Final Datasets
- Split data into X_train, y_train, X_test, and y_test.
- Save these as CSVs in the data/processed/ directory.
### Step 5: Try Multiple Models
- Train different supervised learning models (e.g., Linear Regression, Random Forest, SVM).
- Use metrics like MAE, RMSE, and R² to assess model performance.
### Step 6: Selecting the Best Models
- Choose the best-performing model based on your defined evaluation criteria.
### Step 7: HyperParameter Tuning
- Apply RandomizedSearchCV to optimize model parameters.
### Step 8: Model Saving
- Save the best-performing model in the models/ directory for later use.


## Results
- Apply RandomizedSearchCV to optimize model parameters; it resulted in the lowest errors and the highest explanatory power. 99.4% of the data points were able to be correctly classified by the Random Forest classifier.
- After completing feature important analysis, features relating to location (i.e city, county, state) as well as square footage proved to be the most significant indicators in predicting property prices.
- After hyperparameter tuning, the model improved its performance even moreso.
## Challenges 
- Data preprocessing is always daunting and an ambiguous process.
- Feature selection, which columns were deemed as irrelevant or not.

## Future Goals
- Complete the stretch activities. This would round out the results of our analysis and give a greater picture on how we can interpret the predicability power of our model on house pricing.
